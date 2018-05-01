# quadrature
a=int(input("1.求三角形面积(已知底和高)   2.求三角形面积(已知三边)     3.求矩形面积    4.求圆的面积   请输入序号：  "))
if a < 2:
         h=int(input("请输入三角形的高 :"))
         c=int(input("请输入三角形的底 :"))
         print("三角形的面积为 :")
         print(h*c*0.5)
if  3< a <5:
         r=int(input("请输入圆的半径 :"))
         print("圆的面积为 :")
         print(3.1415926*r*r)
if 2< a <4:
         s=int(input("请输入矩形的底 :"))
         d=int(input("请输入矩形的高 :"))
         print("矩形的面积为 : ")
         print(s*d)
if 1< a <3:
         x=int(input("请输入第一条边"))
         y=int(input("请输入第二条边"))
         z=int(input("请输入第三条边"))
         q=1/2*(x+y+z)
         print("三角形的面积为")
         print((q*(q-x)*(q-y)*(q-z))**0.5)
