# Kaplumba-a
import turtle

uzunluk = int(input("Kenar uzunluğunu giriniz :"))
kenar_say = int(input("Kenar sayısını giriniz :"))
kenar_s = int(360 / kenar_say)

celol = turtle.Turtle()

def polygon():
    for i in range(0,kenar_say):
        celol.forward(uzunluk)
        celol.left(kenar_s)

polygon()

print(celol)

turtle.done()
