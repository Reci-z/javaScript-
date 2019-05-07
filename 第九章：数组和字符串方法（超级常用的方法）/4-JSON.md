# JSON

### JSON是什么？

JSON是一种轻量级的数据交换格式。因为语言的种类繁多，且不同的语言对于数据有不同的定义，例如：

php 中的数组，分为两种形式，一种：索引数组，这个与我们 JS 中的数组类似；还有一种：关联数组，它更像是我们 JS 中的对象，但是在php中他们都是数组。

![](4/timg.jpg)



### JSON的数据格式

```javascript
var jsonString = '{"key":value}';
```



- JSON.parse( )
  - 把JSON数据转化为 JS 中对应的数据，方便操作。
- JSON.stringify( )
  - 把JS中的数组或对象，转成JSON字符串进行输出。