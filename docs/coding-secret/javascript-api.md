
使用JavaScript常用的api（待排版）


**数组**：

遍历方法

- foreach按顺序传入每个值，不返回内容
- reduce，将每个值从第二个参数中获取，在第一个参数中保存，返回最终结果
- filter过滤器，筛选符合条件的值，返回新数组
- map按顺序传入每个值，return的值改变当前值，返回新数组


- concat(数/数组)----连接数组，返回一个副本
- sort()----按照字符编码排序

- splice(start,deleteCount,...['items'])----从start开始删除deleteCount个元素，并添加items

**字符串**：

- split(正则)----以表达式拆分字符串，返回数组
- slice(0,length)----按照长度裁剪字符串
- replace(正则/字符串,替换成什么)----替换字符串
- search(正则)----匹配正则的第一个index

**节点**

添加、删除、替换、插入子节点：

```javascript
//向末尾添加子元素
Node.appendChild(newNode)
// 方法从DOM中删除子节点。返回删除的节点。
Node.removeChild(oldNode)
//方法用指定的节点替换子节点，并返回被替换掉的节点。
Node.replaceChild(newNode) 
//parentDiv中的sp2之前插入节点
parentDiv.insertBefore(sp1, sp2);
```

**object**：

Object.hasOwnProperty()//判断是否有某个属性
Object.getPrototypeOf(1)//获取对象原型
