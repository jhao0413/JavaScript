## 创建添加节点
```
//创建元素节点
var child = document.createElement("div");
//添加节点
node.appendChild(child);
```
node.appendChild()方法将一个节点添加到指定的父节点的子节点列表的末尾

```
//创建元素节点
var child = document.createElement("div");
//添加节点
node.insertBefore(child,指定元素);
```

node.insertBefore(child,指定元素)方法将一个节点添加到父节点的指定子节点前面

## 删除节点
```
node.removeChild(child);
```

node.removeChild()方法从DOM中删除一个子节点，返回删除的节点