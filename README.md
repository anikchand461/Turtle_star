# Turtle_star

from turtle import Turtle, Screen

s=Screen()
t=Turtle()
t.hideturtle()
t.speed('fast')
t.color('red','yellow')
t.pensize(2)
t.begin_fill()
for i in range(18):
    if i==0:
        t.fd(200)
        t.lt(170)
        t.fd(400)
        t.left(170)
    else:
        t.fd(400)
        t.lt(170)
        t.fd(400)
        t.left(170)

t.end_fill()
t.fd(200)
s.mainloop()
