# 什么是表达式和语句
* 语句是为了进行某种操作，一般情况下不需要返回值；而表达式都是为了得到返回值。
* 例：var a=1+3; 这句代码是条语句，而里面的“1+3”是表达式。

# 标识符的规则
* 代码中为了标识变量、函数或属性的字符序列
* 在JS中，标识符只能字母、数字、下划线或美元符号，且不能以数字开头

# if else语句
1. if else语句：如果满足表达式，执行语句，不满足跳过，执行else后面的语句。
``` Javascript
var a=5;
if(a>6&&a=6){
    console.log("a大于等于6");
}else{
    console.log("a小于6");
}
```
2. else if语句：如果满足表达式，执行语句，不满足执行else if后面的语句，还不满足执行else后面的语句。
``` Javascript
var x;
if (x > 5) {
 /* do the right thing */
} else if (x > 50) {
 /* do the right thing */
} else {
 /* do the right thing */
}
```

# while for语句
1. while语句
     * while(表达式){语句}
     * 表达式真，执行语句，执行完再判断表达式的真假；表达式假，执行后面的语句
     * while(true){}是死循环
2. for语句
     * for(语句1;表达式2;语句3){循环体}
     * 先执行语句1，然后判断表达式2。如果为真，执行循环体，然后执行语句3；如果为假，直接退出循环，执行后面的语句。
     * 举例：下面代码结果是5个5.
``` Javascript
for(var i=0;i<5;i++){
    SetTimeout(()=>(console.log(i)))
}
```
# break continue
* break：退出所有循环
* continue：退出当前循环

# lable 标签
* {foo:1} 这不是一个对象，foo是一个lable。
* var a={foo:1} 这是一个对象。

