---
nav: zh-CN
---


### PopupRadio_COM

<img width="100" src="http://qr.topscan.com/api.php?text=https%3A%2F%2Fvux.li%2Fdemos%2Fv2%2F%23%2Fcomponent%2Fpopup-radio"/>

<a href="https://vux.li/demos/v2/#/component/popup-radio" target="_blank" style="font-size:12px;color:#888;">demo 原始链接：https://vux.li/demos/v2/#/component/popup-radio</a>



---

#### 演示

 <div style="width:377px;height:667px;display:inline-block;border:1px dashed #ececec;border-radius:5px;overflow:hidden;">
   <iframe src="https://vux.li/demos/v2/#/component/popup-radio" width="375" height="667" border="0" frameborder="0"></iframe>
 </div>

#### demo 代码

<p class="tip">下面的$t是Demo的i18n使用的翻译函数，一般情况下可以直接使用字符串。另外，下面代码隐藏了i18n标签部分的代码。</p>

``` html
<template>
  <div>
    <group>
      <popup-radio title="options" :options="options1"></popup-radio>
    </group>
  </div>
</template>

<script>
import { Group, PopupRadio } from 'vux'

export default {
  components: {
    Group,
    PopupRadio
  },
  data () {
    return {
      options1: ['A', 'B', 'C']
    }
  }
}
</script>

```


#### Github Issue