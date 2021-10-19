# mypolygon
# Homework for MEG203

import turtle
cho = turtle.Turtle()

def polygon(cho, length, n):
    for i in range(n):
        cho.fd(length)
        cho.lt(360 / n)

    print(cho)

polygon(cho, 23, 46)

turtle.mainloop()

