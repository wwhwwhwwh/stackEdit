
> Written with [StackEdit](https://stackedit.io/).

# 这是一级标题

## 这是二级标题

### 这是三级标题

> stackEdit真的很方便，上手很容易，好用请star


直接写正文。。。
换行一次还是追加内容，如果内容很多很多的很多很多的很多很多的很多很多的很多很多的很多很多的很多很多的很多很多的很多很多的很多很多的很多很多的很多很多的很多很多的很多很多的话

另起一段则需要**回车两次两次两次**（重要的操作重复两次）


> 右括折号表示引用说明

**双星代表加粗**

*单星表示斜体* 

~~双波浪表示删除线~~


- 列表1
- 列表2

1.  列表3
2.  列表4
3.  列表5

+  列表6
*  列表7


这是一个链接，[我的博客](https://xinmingzhou.github.io)

这里是图片（怎么插入）
![这是图片描述](这是图片的绝对存放位置)

这里是单行代码
` NSString *str = @"This is a String"; `


``` Objective-C（多行代码）

NSString *str = @"This is a String";
NSLog(@"low1 = %@", [str lowercaseString]);
NSLog(@"up1 = %@", [str uppercaseString]);
//交换两个方法
Method originalMethod = class_getInstanceMethod([NSString class], @selector(lowercaseString));
Method swappedMethod = class_getInstanceMethod([NSString class], @selector(uppercaseString));
method_exchangeImplementations(originalMethod, swappedMethod);
NSString *str2 = @"This is B String";
NSLog(@"low2 = %@", [str2 lowercaseString]);
NSLog(@"up2 = %@", [str2 uppercaseString]);

```



这里是文章内的快速跳转[^1]












[^1]: 角标大大大大说
 



<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0ODA5OTk2OTNdfQ==
-->