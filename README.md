# vue3的拖拽div组件
## 1. 引入
`import DragablePanel from 'vue3-draggable-div'`
## 2. 使用
```html
<DragablePanel width="810px">
<!--内容-->
</DragablePanel>
```
## 3. 参数
- width,height: 宽高，默认100px

## 4. 事件
- `on-begin-drag`: 开始拖拽
- `on-dragging`：拖拽中
- `on-end-drag`：结束拖拽