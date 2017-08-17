# vm-address-json


城市数据库，包括：省/市/区县/乡(街道)四级数据，该数据一般用于**城市选择**或者**地址选择**。

## DATA STRUCTURE

1. 请求原始JSON数据返回数组，参数详情：

params       | name         | description
-------------|--------------|----------------------
divisionCode | 区域编码     | 例如：110101001
post         | 邮编         | 例如：100010
divisionName | 区域名称     | 例如："东华门街道"
isLeaf       | 是否是子节点 | 可以是：0(不是)，1(是)

2. JSON文件的文件名是当前文件的父节点的`divisionCode`

3. 请求地址示例：https://raw.githubusercontent.com/vm-component/vm-address-json/master/data/1.json

## LICENSE

MIT