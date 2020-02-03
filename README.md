# JavaScript

## JavaScript学习中的小知识

### 自定义属性
H5规定自定义属性data-开头作为属性名并复制，例如：
```
<div data-index="1"></div>
```
新建自定义属性
```
setAttributes("data-index",10)
```
获取一个自定义属性
```
getAttributes("data-index")
```
获取多个自定义属性(dataset是一个集合，里面存放了所有以data开头的自定义属性)
```
div.dataset
div.dataset.index
div.dataset["index"]
//特殊情况
//dataset兼容不兼容ie11以下版本
data-list-name
div.dataset.listName
div.dataset["listName"]
```
移除自定义属性
```
removeAttributes()
```