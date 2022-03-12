# dfsagfsgdfgsdf# print("5 Dan")
# print("5 * 2",5*2)

# a = int(input())
# b = int(input())
# print(a,"*",b,"=",a*b)
# print(a,"/",b,"=",a/b)

# a = float(input())
# b = a*0.9144*100
# c,d = str(b).split(".")
# if int(d[4]) > 4:
#     d = int(d)+int(1)
#     e = str(d)
#     print(c+"."+e[:3]+"cm")

# a = input()
# b = input()
# print(a,"and",b)
# print(a+"&"+b)

# l = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15]
# l2 = []
# a = int(input())
# for i in range(15):
#     if l[i]%a == 0:
#         l2.append(l[i])
# print(l2)

# l = ["dog", "cat", "chick"]
# a = int(input("Number?"))
# if a == 1:
#     print("dog")
# elif a == 2:
#     print("cat")
# elif a == 3:
#     print("chick")
# else:
#     print('"I don`t know"')

# print("1plus1 = Gwi yo mi")
# print("1 + 1 =",1+1)

# a = float(input())
# b = float(input())
# c = float(a*b)
# print(c)

# a = int(input())
# b = int(input())
# c = int(input())
# l = []
# l.append(a)
# l.append(b)
# l.append(c)
# d = sum(l)
# e = d/len(l)
# print(d)
# if type(e) == float:
#     g,f = str(e).split(".")
#     print(g)
# else:
#     print(e)

# a = input()
# b = input()
# c = int(input())
# print(b*c+a)

# l = [2434,4234,3423]
# l = [1,2]
# a = int(input())
# l.append(a)
# print(l[2])
# print(l[1])
# print(l[0])

# a = float(input())
# if a > 88.45:
#     print("heavyweight")
# elif 88.45 >= a:
#     print("cruiserweight")
# elif 72.57 >= a:
#     print("middleweight")
# elif 61.23 >= a:
#     print("lightweight")
# elif 50.80 >= a:
#     print("flyweight")

# a = int(input())
# l = []
# l2 = []
# l3 = []
# while a != 0:
#     l.append(a)
#     a = int(input())
# for i in range(len(l)):
#     if l[i]%2 == 0:
#         l2.append(l[i])
#     elif l[i]%2 != 0:
#         l3.append(l[i])
# b = len(l2)
# c = len(l3)
# print("odd :",b)
# print("even :",c)

# a = int(input())
# b = int(input())
# c = int(input())
# d = int(input())
# l = []
# l.append(a)
# l.append(b)
# l.append(c)
# l.append(d)
# e = sum(l)
# f = e/len(l)
# if type(f) == float:
#     v,x = str(f).split(".")
#     if len(x) > 1:
#         if x[1] > 4:
#             x[0] = x[0] + 1
# j = v+"."+x[0]
# print(j)
# if float(j) >= 80.0:
#     print("pass")
# else:
#     print("fail")

# a = int(input())
# def ald(x):
#     y = x*x*3.14
#     if type(y) == float:
#         m,n = str(y).split(".")
#         if len(n) > 2:
#             if n[2] > 4:
#                 n[1] = n[1] + 1
#     z = m+"."+n[:1]
#     print(z)
# ald(a)
