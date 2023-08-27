# test_gb_1
test
<<<<<<< HEAD
 fghnhf 
 
=======
asdfadfad
>>>>>>> b21fa44bdd3b81f8cf532d226158782a2bde41b8

# Test_txt

import time
from turtle import *

pen = Turtle()
pen.color('red')
bgcolor('black')

def curve():
    for i in range(200):
        pen.right(1)
        pen.forward(1)

def draw_heart():
    pen.fillcolor('red')
    pen.begin_fill()
    pen.left(140)
    pen.forward(113)
    curve()
    pen.left(120)
    curve()
    pen.forward(112)
    pen.end_fill()

def draw_txt():
    pen.up()
    pen.setpos(-50, 90)
    pen.down()
    pen.color('white')
    pen.write("Люблю реки", font=("Montserrat", 16, "bold"))
    pen.up()
    pen.setpos(-70, 70)
    pen.down()
    time.sleep(1)
    pen.write("И немножно Python", font=("Montserrat", 14, "bold"))

draw_heart()
draw_txt()
pen.ht()
done()