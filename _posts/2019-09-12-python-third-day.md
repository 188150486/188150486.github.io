---
title: Third Day For python
categories: python
tags: python
---

# 变量不需要声明     
# 输入函数input    
变量 = input("提示字符")      

**注意：这种情况下 变量得到的东西的类型为字符**    
当变量需要得到数值的时候，可以用函数eval：   

⑴ 变量 = eval(input("提示字符"))    
⑵ print("m和n的差为：",eval(m)-eval(n))    

# 输出函数print   

print在输出后会自动换行      

若想print输出后不换行，可以这样：      
```python 
print("the answer is ",end="") #使用end=""，输出字符串后不换行
print(3+4)
>>> the answer is 7
```

# 字符串处理函数   
find():查找一个字符串在另一个字符串中第一次出现的位置   
rfind()：查找一个字符串在另一个字符串中最后一次出现的位置   
如果不存在返回-1   

index():查找一个字符串在另一个字符串中第一次出现的位置   
rindex()：查找一个字符串在另一个字符串中最后一次出现的位置   
如果不存在抛出异常   

count():计算一个字符串在另一个字符串中出现的次数   

split():指定字符串为分隔字符，从左到右   
rsplit():指定字符串为分隔字符，从右到左   
s.split(maxsplit = 2) maxsplit为指定最大分隔次数，即分隔两次后，后面的字符串不分隔   

partition():指定一个字符串为分隔符，从左到右分为3部分   
rpartition():指定一个字符串为分隔符，从右到左分为3部分   
s.partition('fish') 以左端第一个fish为界限 将s字符串分为3部分   

replace():替换指定字符或子串，一次只能替换一个   

strip(),rstrip(),lstrip()：删除字符串两端、右端、左端连续字符(默认时删除空白字符)   

starswith(),endswith():判断字符串是否以指定字符开始或结束，返回true和false   

判断字符串类型：   
isupper():是否是否全为大写   
islower():是否全为小写   
isdigit():是否全为数字   
isalnum():是否全为数字   
isalpha():是否全为字母   

字符串排序：   
center(30，"="):居中对齐，输出宽度为30，不足以=补齐   
ljust(20,"*"):居左对齐，输出宽度为30，不足以*补齐   
rjust():居右对齐，同理上面   
zflii(20)：输出宽度为20，左侧以0填充。   


