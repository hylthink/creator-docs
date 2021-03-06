# Mask（遮罩）组件参考

Mask 用于规定子节点可渲染的范围，带有 Mask 的组件的节点会使用该节点的约束框（也就是`size`规定的范围）创建一个渲染遮罩，该节点的所有子节点都会依据这个遮罩进行裁剪，遮罩范围外的将不会渲染。

![add-mask](./mask/add-mask.png)

点击 **属性检查器** 下面的 `添加组件` 按钮，然后从 `添加渲染组件` 中选择 `Mask`，即可添加 Mask 组件到节点上。注意该组件不能添加到有其他渲染组件的节点上，如 `Sprite`、`Label` 等。

遮罩的脚本接口请参考[Mask API](../api/classes/Mask.html)。


## Mask 属性

| 属性 |   功能说明
| -------------- | ----------- |
| NA |NA

## 详细说明

给节点添加 Mask 组件之后，所有在该节点下的子节点在渲染的时候都会受 Mask 影响。

---

继续前往 [MotionStreak 组件参考](motion-streak.md)。