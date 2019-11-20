# 基于vue-draggable-resizable组件二次开发

## 新增Prop属性：
1. isConflictCheck: 冲突检测，默认false 可选值： true， false
2. snap: 元素对齐，布尔值，默认false
3. snapTolerance：设置模块与模块之间的对齐距离，以像素为单位，默认值5
4. parentScale：父容器parent缩放值，默认值1，可选范围0-1

## 新增属性解释：
1. isConflictCheck开启后，不允许模块相互重叠
2. snap开启模块对齐，在snapTolerance设置的距离内，有吸附效果
3. snapTolerance: 模块对齐距离触发值
4. parentScale，传递父容器的缩放比率

## 参考链接
1. https://mauricius.github.io/vue-draggable-resizable/?path=/story/basic--basic-component 官方在线示例
2. https://www.npmjs.com/package/vue-draggable-resizable#live-playground npm官方地址
