

# v-collapse-transition
> vue折叠动画组件, 参照element-ui


## Install

```bash
npm i -S v-collapse-transition
```

## Usage

Plugin install:

```js
import Vue from 'vue'
import VCollapseTransitionfrom 'v-collapse-transition'

Vue.use(VCollapseTransitionfrom)
```

Or work on a Vue instance:

```
<template>
	<div>
		<button  @click='show=!show'></button>
		<v-collapse-transition>
			<ul  v-show="show">
				<li>需折叠切换的内容</li>
				<li>需折叠切换的内容</li>
				<li>需折叠切换的内容</li>
				<li>需折叠切换的内容</li>
				<li>需折叠切换的内容</li>
				<li>需折叠切换的内容</li>
			</ul>
		</v-collapse-transition>
	</div>
</template>

<script>
import VCollapseTransitionfrom 'v-collapse-transition'
export  default {
	data() {
		return {
			show:  false
		};
	},
	components: {
		VCollapseTransitionfrom 
	}
};
</script>

<style>

</style>
```


## Demo

[地址待更新](/)

## Browsers support

Modern browsers and Internet Explorer 10+.

| IE10, IE11, Edge| last 2 versions| last 2 versions| last 2 versions

## 参考文档


[Vue.js](https://cn.vuejs.org/v2/guide/)

[element-ui](http://element-cn.eleme.io/2.4/#/zh-CN)


## 问题回馈

chen_zhaoyang (951369696@qq.com)
