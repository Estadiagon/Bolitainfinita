# Bolitainfinita
laboratorio de la bola infinita
from graphics import *

a=1

ventana=GraphWin("Bola infinitamente divertida!!!!",500,500)

circulo=Circle(Point(40,40),40)
circulo.setFill("blue")
circulo.draw(ventana)

for ñ in range(0,10000000000000000000000000000000000000000000000000000):
    if a==1:
        for i in  range(0,80):
            time.sleep(0.001)
            circulo.move(5,5)
        for j in range(0,80):
            time.sleep(0.001)
            circulo.move(0,-5)
        for k in range(0,80):
            time.sleep(0.001)
            circulo.move(-5,5)
        for l in range(0,80):
            time.sleep(0.001)
            circulo.move(0,-5)
time.sleep(5)
