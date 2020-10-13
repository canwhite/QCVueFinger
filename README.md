# QCVueFinger
vue的简单手势操作
---
#### main.js中引入 

```
import finger from "../../js/vue-finger"   
Vue.use(finger);
```
warn:注意vue-finger.js文件引入的相对位置

#### 然后再具体使用的地方

```
<div class="list" v-swipeup="(e)=>vueTouch('上滑',e)">

</div>

vueTouch:function(txt,e){
    console.log('-----',txt);
},

```
