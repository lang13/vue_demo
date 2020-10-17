# 1.HTML
```html
<!--label标签的使用
    必选属性for,值为需要绑定的标签的id
-->
<input type="checkbox" id="runoob">
<label for="runoob">Runoob</label>
```

# 2.css
```
1.font-szie: 0px: 用于消除子元素的间隙
```
# 3.vue
## vue网络编程部分
 ```html
<!--    引入axios的代码-->
<script src="https://unpkg.com/axios/dist/axios.min.js"></script>
```
* vue的生命周期
![vue生命周期](../image/vue生命周期.png)

beforeCreate
> 在实例初始化之后，数据观测(data observe)和event/watcher配置之前调用

created
> 实例已经创建完成后被调用。在这一步，实例已完成一下配置：数据观测(data observe)，
属性和方法的运算，watcher/event事件的回调。但是挂载阶段还没开始，$el属性目前不可见

beforeMount
> 在挂载开始前被调用：相关的render函数被调用

Mounted
> el被新创建的vm.$el替代，并挂载到实例上去之后调用该钩子

beforeUpdate
> 数据更新前调用，发生在虚拟Dom重新渲染和打补丁之前。你可以在这个钩子中进一步的更改状态，这不会触发附件的重渲染效果

updated
> 由于数据更改导致的虚拟DOM重新渲染和打补丁，在这之后会调用此钩子函数
>> 当这个钩子被调用时，组件DOM已经更新，所以现在可以执行依赖于新的DOM的操作。然而大多数情况下，应该避免在此期间更改状态
因为可能导致更新无限循环。

beforeDestroy
> 实例销毁之前调用。在这一步，实例仍然完全可以调用

destroyed
> Vue实例销毁后调用。调用后，Vue实例指示的所有东西都会解绑，所有的事件监听器都会被移除，所有的子实例也会销毁。改钩子在服务器渲染期间不被调用

![vue钩子函数](../image/vue钩子函数.png)
* v-show和v-if控制的标签的显示与否，而v-bind则是控制标签的class属性

####**项目中使用到的链接说明**
![avatar](接口.png)

