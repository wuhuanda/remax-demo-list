# 微信小程序 Remax demo 集合

## Examples

### 选择区域列表（Region）

用原生组件 `Picker` 中 `mode="multiSelector"` 写的一个选择区域列表组件。与 `mode="region"`的区别就是支持自定义传入区域数据。

### 图表（Charts）

引用字节跳动的[开源项目](https://github.com/xiaolin3303/wx-charts)，目前 demo 中只引入了其中一种图标类型—— `Line`，其他的可以去开源项目看，用啥取啥，按需引入。

### Click event callback of stopPropagation (Remax > v1.5.0)

点击操作阻止冒泡回调事件, 点击事件会回调一个对象，使用对象中的 `stopPropagation` 即可阻止事件冒泡。

## TODO

- [x] 选择区域列表
- [x] Charts
- [x] 测试点击操作阻止冒泡回调事件
