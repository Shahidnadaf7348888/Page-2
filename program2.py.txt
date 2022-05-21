#Drawing color filled hexagon

import turtle 
t=turtle.Turtle()
s=int(input("Enter the lenght of the sidee of the hexagin :"))
col=input("Enter the color name or hexa value of color :"))

t.fillcolor(col)
for _ in range(6):
    t.forword(s)
    t.right(-60)
t.end_fill()
