#Python 3 的学习
'''
    `天都要有Get的感觉`
'''
## basic 基础部分
***
    能调用方法的一定是对象
***
## advs  高级部分
## algo  算法部分
## func  函数部分
### 装饰器(函数)
    作用域: LEGB
    高阶函数: 函数名可以作为参数输入、函数名也可以作为返回值
    闭包: 如果在一个内部函数里,对在外部作用域(但不是在全局作用域)的变量进行引用，那么内部函数就被认为是闭包(closure)
    闭包 = 函数块 + 定义函数时的环境

### Importance
```
什么是迭代器?
生成器都是迭代器, 迭代器不一定是生成器
满足两个条件: 
1 - 有iter方法
2 - 有next方法

for循环内部实现的三件事(即for内部实现机制):
1 - 调用可迭代对象的iter方法返回一个迭代器对象
2 - 不断调用迭代器对象的next方法
3 - 处理StopIteration

列表生成式
>>> [x*2 for x in range(10)]
[0, 2, 4, 6, 8, 10, 12, 14, 16, 18]

# 生成器(generator)
生成器有两种生成方式:
    1、(x for x in range(n))
    2、yield关键字
    
什么式迭代器?
满足迭代器协议:内部有next方法和内部有iter方法
    



Day18-3 sys模块

Day18-4 hashlib模块
主要用于加密



```
    
# todo
   
    
# Python
```text
1、查看版本
   python -V

2、在Python中可以使用pip与conda工具安装第三方库
pip install 库的名称
conda install 库的名称

```    
    
