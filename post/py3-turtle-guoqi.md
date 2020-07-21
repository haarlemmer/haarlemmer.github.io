## Python3海龟绘图 画国旗

今天学了Python的turtle模块，就想着去画一个国旗，于是就写了个程序

<div id="readmore">
import turtle # 导入turtle库
<br>
input("Press Enter To Start...")  # 等待用户按下Enter键
<br>
turtle.setup(600, 350)  # 设置窗口大小
<br>
turtle.title("")  # 清空标题
<br>
turtle.speed(1.5)  # 设置速度
<br>
turtle.hideturtle()  # 隐藏海龟
<br>
turtle.up()  # 画笔上抬
<br>
turtle.goto(-225, 150)  # 移动位置到开始处
<br>
turtle.down()  # 放下画笔
<br>
turtle.begin_fill()  # 准备填充
<br>
turtle.fillcolor("red")  # 设置填充颜色为红色
<br>
turtle.pencolor("red")  # 设置笔的颜色为红色
<br>
for i in range(2):  # 开始循环,循环2次
<br>
    turtle.forward(438)  # 向前移动438个像素
<br>
    turtle.right(90)  # 向右转90度
<br>
    turtle.forward(292)  # 向前移动292个像素
<br>
    turtle.right(90)  # 向右转90度
<br>
turtle.end_fill()  # 填充
<br>
turtle.fillcolor("yellow")  # 设置填充颜色为黄色
<br>
turtle.pencolor("yellow")  # 设置画笔颜色为黄色
<br>
turtle.up()  # 画笔上抬
<br>
turtle.goto(-195, 95)  # 移动位置到开始处
<br>
turtle.down()  # 放下画笔
<br>
turtle.begin_fill()  # 准备填充
<br>
for x in range(5):  # 开始循环，循环5次
<br>
    turtle.fd(25)  # 向前移动25个像素
<br>
    turtle.left(72)  # 左转72度
<br>
    turtle.fd(25)  # 向前移动25个像素
<br>
    turtle.right(144)  # 右转144度
<br>
turtle.end_fill()  # 填充
<br>
turtle.up()  # 画笔上抬
<br>
turtle.goto(-125, 130)  # 移动位置到开始处
<br>
turtle.setheading(305)  # 面向305度的方向
<br>
turtle.down()  # 放下画笔
<br>
turtle.begin_fill()  # 准备填充
<br>
for x in range(5):  # 开始循环，循环5次
<br>
    turtle.fd(10)  # 向前移动10个像素
<br>
    turtle.left(72)  # 左转72度
<br>
    turtle.fd(10)  # 向前移动10个像素
<br>
    turtle.right(144)  # 右转144度
<br>
turtle.end_fill()  # 填充
<br>
turtle.up()  # 画笔上抬
<br>
turtle.goto(-110, 100)  # 移动位置到开始处
<br>
turtle.setheading(30)  # 面向30度的方向
<br>
turtle.down()  # 放下画笔
<br>
turtle.begin_fill()  # 准备填充
<br>
for x in range(5):  # 开始循环，循环5次
<br>
    turtle.fd(10)  # 向前移动10个像素
<br>
    turtle.left(72)  # 左转72度
<br>
    turtle.fd(10)  # 向前移动10个像素
<br>
    turtle.right(144)  # 右转144度
<br>
turtle.end_fill()  # 填充
<br>
turtle.up()  # 画笔上抬
<br>
turtle.goto(-110, 70)  # 移动位置到开始处
<br>
turtle.setheading(3)  # 面向3度的方向
<br>
turtle.down()  # 放下画笔
<br>
turtle.begin_fill()  # 准备填充
<br>
for x in range(5):  # 开始循环，循环5次
<br>
    turtle.fd(10)  # 向前移动10个像素
<br>
    turtle.left(72)  # 左转72度
<br>
    turtle.fd(10)  # 向前移动10个像素
<br>
    turtle.right(144)  # 右转144度
<br>
turtle.end_fill()  # 填充
<br>
turtle.up()  # 画笔上抬
<br>
turtle.goto(-110, 45)  # 移动位置到开始处
<br>
turtle.setheading(200)  # 面向200度的方向
<br>
turtle.down()  # 放下画笔
<br>
turtle.begin_fill()  # 准备填充
<br>
for x in range(5):  # 开始循环，循环5次
<br>
    turtle.fd(10)  # 向前移动10个像素
<br>
    turtle.left(72)  # 左转72度
<br>
    turtle.fd(10)  # 向前移动10个像素
<br>
    turtle.right(144)  # 右转144度
<br>
turtle.end_fill()  # 填充
<br>
turtle.done()  # 结束,保持窗口显示
</div>
<script src="https://my.openwrite.cn/js/readmore.js" type="text/javascript"></script>
<script>
    const btw = new BTWPlugin();
    btw.init({
        id: 'readmore',
        blogId: '23200-1595322128196-534',
        name: 'None',
        qrcode: 'http://bpic.588ku.com/element_origin_min_pic/01/56/32/045747b48740dc7.jpg',
        keyword: 'None',
    });
</script>
