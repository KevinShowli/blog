# Note
##### 自己的笔记库，记录一些日常开发中的小技巧、小知识。
>[面试题：写出满足下列要求的代码](https://github.com/KevinShowli/blog/blob/master/articles/1.md)
```javascript
LazyMan('Tony');
// Hi I am Tony

LazyMan('Tony').sleep(10).eat('lunch');
// Hi I am Tony
// 等待了10秒...
// I am eating lunch

LazyMan('Tony').eat('lunch').sleep(10).eat('dinner');
// Hi I am Tony
// I am eating lunch
// 等待了10秒...
// I am eating diner

LazyMan('Tony').eat('lunch').eat('dinner').sleepFirst(5).sleep(10).eat('junk food');
// Hi I am Tony
// 等待了5秒...
// I am eating lunch
// I am eating dinner
// 等待了10秒...
// I am eating junk food
```
#
>[利用::after/::before伪类实现图片在不定高宽的块元素中的自适应居中](https://github.com/KevinShowli/blog/blob/master/articles/2.md)

![](https://github.com/KevinShowli/blog/blob/master/images/inline-block1.png)
[查看这个例子](https://github.com/KevinShowli/blog/blob/master/demos/inline-block.html)

#
>[安装Java环境](https://github.com/KevinShowli/blog/blob/master/articles/3.md)

![](https://github.com/KevinShowli/blog/blob/master/images/java环境变量.png)
 