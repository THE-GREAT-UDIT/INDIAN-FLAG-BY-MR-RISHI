# INDIAN-FLAG-BY-MR-RISHI
import turtle
from turtle import*

#screen for output
screen = turtle.Screen()

# Defining a turtle Instance
t = turtle.Turtle()
speed(0)

# initially penup()
t.penup()
t.goto(-400, 250)
t.pendown()

# Orange Rectangle
#white rectangle
t.color("orange")
t.begin_fill()
t.forward(800)
t.right(90)
t.forward(167)
t.right(90)
t.forward(800)
t.end_fill()
t.left(90)
t.forward(167)

# Green Rectangle
t.color("green")
t.begin_fill()
t.forward(167)
t.left(90)
t.forward(800)
t.left(90)
t.forward(167)
t.end_fill()

# Big Blue Circle
t.penup()
t.goto(70, 0)
t.pendown()
t.color("navy")
t.begin_fill()
t.circle(70)
t.end_fill()

# Big White Circle
t.penup()
t.goto(60, 0)
t.pendown()
t.color("white")
t.begin_fill()
t.circle(60)
t.end_fill()

# Mini Blue Circles
t.penup()
t.goto(-57, -8)
t.pendown()
t.color("navy")
for i in range(24):
	t.begin_fill()
	t.circle(3)
	t.end_fill()
	t.penup()
	t.forward(15)
	t.right(15)
	t.pendown()
	
# Small Blue Circle
t.penup()
t.goto(20, 0)
t.pendown()
t.begin_fill()
t.circle(20)
t.end_fill()
# Spokes
t.penup()
t.goto(0, 0)
t.pendown()
t.pensize(2)
for i in range(24):
	t.forward(60)
	t.backward(60)
	t.left(15)
# writing text
text = turtle.Turtle()
text.hideturtle()
text.speed(2)

#for stick of the flag
t.color("Brown")
t.pensize(10)
t.penup()
t.goto(-400,240)
t.right(180)
t.pendown()
t.forward(800)
def write(message,pos,color):
    x,y = pos
    text.color(color)
    text.penup()
    text.goto(x,y)
    text.pendown()
    style = ('Courier',40,'italic')
    text.write(message,font=style)

write('HAPPY',(60,-100),'orange')
write('INDEPENDENCE',(10,-160),'white')
write('DAY 2022 ',(1,-220),'pink')
write('AZADI KA AMRIT MAHOTSAV',(2,-300),'green')
#to hold the
#output window
turtle.done()

#CODE WRITTEN BY @ MR UDIT JAIN..!
#INSTAGRAM IG @THE_GREAT_UDIT..!
