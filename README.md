# Kanna-index
### 介绍
> 完全自用，根据[拉屎爱哀嚎][1]的主页写的
>
>想用的话就下载拿去用吧,留个DANGO PROJECT的版权即可

### 功能
介绍自己的特长啊，什么什么的

用JavaScript写了一个随机背景图，但是没有启用。
想用的话记得注释掉页面的css
> 示例

```html
<style>
	.bg{
		height: 100%;
       	width: 100%;
		/** background-image: url(./default.jpg); **/
		background-repeat: no-repeat;
		background-size: auto;
		z-index:1;
		position: absolute;
	}
</style>
```
然后在将位于*<footer>*标签下的 *<script>*标签内注释删除
>删除后的亚子

```JavaScript
	<script>
	 var randomBgIndex =  parseInt(6*Math.random());
	 document.write('<style>.bg{background: rgba(255, 255, 255, 0.0) url("./bgs/bg'+ randomBgIndex +'.jpg"); background-size:100% 100%; background-repeat:no-repeat;}</style>');
	</script>
```
 反之相反

### DEMO LINK
[狱杰的主页][2]


### 引用开源项目
> MDUI
> 
> 阿里巴巴矢量图标库

### 2020狱杰1Jnver
[1]:https://i.lsaiah.cn/
[2]:https://i.obent.cn/