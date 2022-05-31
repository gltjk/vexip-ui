### Progress 属性

| 名称         | 类型                        | 说明                                                                                            | 默认值    |
| ------------ | --------------------------- | ----------------------------------------------------------------------------------------------- | --------- |
| percentage   | Number                      | 当前的进度百分比，取值为 0 ~ 100                                                                | 0         |
| stroke-width | Number                      | 进度条的填充宽度                                                                                | 8         |
| info-type    | String                      | 进度条信息的类型，可选值为 `outside`、`inside`、`bubble`、`bubble-top`、`bubble-bottom`、`none` | 'outside' |
| stroke-color | String \| Array \| Function | 进度条的填充颜色，传入数组时会使用线性渐变                                                      | null      |

### Progress 插槽

| 名称    | 说明                     |
| ------- | ------------------------ |
| default | 进度信息的自定义内容插槽 |