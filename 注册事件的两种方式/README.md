## 获取对象

### 传统方法
```
document.getElementById('name');

document.getElementByClassName('name');

document.getElementByTagName('name');
```
### H5新方法
```
document.querySelector('name');

document.querySelectorAll('name');
```
## 注册事件
### 传统方式
```
oBtn.onclick = function(){

    alert('Hello World');

}
```

```
oBtn.addEventListener('click',function{

    alert('Hello World');
    
})
```