# Hello-world
小白一枚
#用于注释
=（单等号）和==（双等号）的区别，前者把等号右边的值赋给等号右边，后者判断等号两边是否相等。
操作符两边加上空格会让代码更容易阅读，如x=100和 x = 100 显然后者更容易阅读
如何创建嵌入变量内容的字符串，首先（“”）当然是必须的，然后字符串还必须用f开头如（f“”）,最重要的是使用{}符号把变量放在里面如my_name = 'zhangpeng' print(f"Let's talk about {my_name}.")
变量名要以字母开头，故a1可行而1不可行。
my_name = 'zhangpeng'
my_age = 18 # not a lie
my_height = 65 # inches
my_weight = 180 # 1bs
my_eyes = 'black'
my_teech = 'white'
my_hair = 'black'

print(f"Let's talk about {my_name}.")
print(f"He's {my_height} inches tall.")
print(f"He's {my_weight} pounds heavy.")
print("Actually that's not too heavy.")
print(f"he's got {my_eyes} eyes and {my_hair} hair.")
print(f"He's teech are usually {my_teech} depending on the coffee.")

# this line is tricky,try to get it exactly right
total = my_age + my_height + my_weight
print(f"If I add {my_age}, {my_height}, and {my_weight} I get {total}.")
