#$hape o

import pgzrun
import random

WIDTH = 500
HEIGHT = 500

def draw():
    W = WIDTH
    H = HEIGHT-300
    R = 0
    G = 0
    B = 0
    screen.fill("Black")
    for i in range(25):
        r1 = Rect((0,0),(W,H))
        r1.center = WIDTH/2,HEIGHT/2
        screen.draw.rect(r1,(R,G,B))
        W -=10
        H +=10
        G +=10
        B +=10
pgzrun.go()     

CIRCLEOE TEXT
import pgzrun
HEIGHT = 500
WIDTH= 500
def draw():
    screen.fill("Black")
    screen.draw.text("Wsp World",(250,250),color = "Cyan")
    screen.draw.circle((200,200),100,color="Blue")
    screen.draw.filled_circle((175,175),100,color="Blue")


pgzrun.go()
