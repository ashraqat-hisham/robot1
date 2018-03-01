# robot1
from OpenGL.GL import *
from OpenGL.GLU import *
from OpenGL.GLUT import *
import OpenGL.GLUT
import numpy as np
from math import*

def draw():
    #Drawing

    glColor(1,1,1)
    glBegin(GL_POLYGON)
    glVertex2f(-1, 1)
    glVertex2f(1, 1)
    glVertex2f(1, -1)
    glVertex2f(-1, -1)
    glEnd()
    glFlush()


    glColor(0,0,0)
    glBegin(GL_POLYGON)
    r = .5
    for theta in np.arange  ( .1 , 2 * pi  , .02 ):
        y = r * sin(theta)+ 0
        x = r * cos (theta)+0
        glVertex2d(x,y)
    glEnd()
    glFlush()


    glColor(1,1,1)
    glBegin(GL_POLYGON)
    r = .3
    for theta in np.arange  ( .1 , 2 * pi  , .1 ):
        y = r * sin(theta)+ -.07
        x = r * cos (theta)+0
        glVertex2d(x,y)
    glEnd()
    glFlush()


    glColor(0,0,0)
    glBegin(GL_POLYGON)
    r = .33
    for theta in np.arange  ( .1 , 2 * pi  , .1 ):
        y = r * sin(theta)+ -.02
        x = r * cos (theta)+0
        glVertex2d(x,y)
    glEnd()
    glFlush()


    glColor(1,1,1)
    glBegin(GL_POLYGON)
    r = .2
    for theta in np.arange  ( .1 , 2 * pi  , .02 ):
        y = r * sin(theta)+ .2
        x = r * cos (theta)+0
        glVertex2d(x,y)
    glEnd()
    glFlush()

    glColor(0,0,0)
    glBegin(GL_POLYGON)
    r = .1
    for theta in np.arange  ( .1 , 2 * pi  , .02 ):
        y = r * sin(theta)+ .2
        x = r * cos (theta)+0
        glVertex2d(x,y)
    glEnd()
    glFlush()


    glColor(0,0,0)
    glBegin(GL_POLYGON)
    r = .07
    for theta in np.arange  ( .1 , 2 * pi  , .02 ):
        y = r * sin(theta)+ .39
        x = r * cos (theta)+.1
        glVertex2d(x,y)
    glEnd()
    glFlush()

    glColor(0,0,0)
    glBegin(GL_POLYGON)
    r = .07
    for theta in np.arange  ( .1 , 2 * pi  , .02 ):
        y = r * sin(theta)+ .39
        x = r * cos (theta)-.1
        glVertex2d(x,y)
    glEnd()
    glFlush()

    glColor(0,0,0)
    glBegin(GL_POLYGON)
    r = .07
    for theta in np.arange  ( .1 , 2 * pi  , .02 ):
        y = r * sin(theta)+ .39
        x = r * cos (theta)+0
        glVertex2d(x,y)
    glEnd()
    glFlush()

    glColor(0,0,1)
    glBegin(GL_POLYGON)
    r = .025
    for theta in np.arange  ( .1 , 2 * pi  , .2 ):
        y = r * sin(theta)+ .2
        x = r * cos (theta)+0
        glVertex2d(x,y)
    glEnd()
    glFlush()

    glColor(0,0,0)
    glBegin(GL_POLYGON)
    glVertex2f(-0.32, 0.43)
    glVertex2f(.32, .43)
    glVertex2f(.32, .72)
    glVertex2f(-.32, .72)

    glEnd()
    glFlush()

    glColor(0,0,0)
    glBegin(GL_POLYGON)
    r = .1
    for theta in np.arange  ( .1 , 2 * pi  , .02 ):
        y = r * sin(theta)+ .72
        x = r * cos (theta)+0
        glVertex2d(x,y)
    glEnd()
    glFlush()

    glColor(0,0,0)
    glBegin(GL_POLYGON)
    glVertex2f(-0.1,-.45)
    glVertex2f(-.2, -0.45)
    glVertex2f(-.2, -.8)
    glVertex2f(-.1, -.8)
    glEnd()
    glFlush()


    glColor(0,0,0)
    glBegin(GL_POLYGON)
    glVertex2f(0.1,-.45)
    glVertex2f(.2, -0.45)
    glVertex2f(.2, -.8)
    glVertex2f(.1, -.8)
    glEnd()
    glFlush()


    glColor(0,0,0)
    glBegin(GL_POLYGON)
    r = .08
    for theta in np.arange  ( .1 , 2 * pi  , .02 ):
        y = r * sin(theta)+ -.8
        x = r * cos (theta)+0.18
        glVertex2d(x,y)
    glEnd()
    glFlush()


    glColor(0,0,0)
    glBegin(GL_POLYGON)
    r = .08
    for theta in np.arange  ( .1 , 2 * pi  , .02 ):
        y = r * sin(theta)+ -.8
        x = r * cos (theta)+-0.12
        glVertex2d(x,y)
    glEnd()
    glFlush()

    glColor(0,0,0)
    glBegin(GL_POLYGON)
    glVertex2f(0.3,-.2)
    glVertex2f(.3, -.1)
    glVertex2f(.7, 0)
    glVertex2f(0.7,-.1)

    glEnd()
    glFlush()


    glColor(0,0,0)
    glBegin(GL_POLYGON)
    glVertex2f(-0.3,-.2)
    glVertex2f(-.3, -.1)
    glVertex2f(-.7, 0)
    glVertex2f(-0.7,-.1)
    glEnd()
    glFlush()


    glColor(0,0,0)
    glBegin(GL_POLYGON)
    r = .08
    for theta in np.arange  ( .1 , 2 * pi  , .02 ):
        y = r * sin(theta)+ -.06
        x = r * cos (theta)+-0.7
        glVertex2d(x,y)
    glEnd()
    glFlush()

    glColor(0,0,0)
    glBegin(GL_POLYGON)
    r = .08
    for theta in np.arange  ( .1 , 2 * pi  , .02 ):
        y = r * sin(theta)+- .06
        x = r * cos (theta)+0.7
        glVertex2d(x,y)
    glEnd()
    glFlush()

    glColor(1,1,1)
    glBegin(GL_POLYGON)
    glVertex2f(0,-.06)
    glVertex2f(.08, -.15)
    glVertex2f(-.08, -.1)
    glEnd()
    glFlush()



glutInit ()
glutInitDisplayMode(GLUT_SINGLE | GLUT_RGB)
glutInitWindowSize(600,600)
glutCreateWindow(b"First OpenGl Programme")
glutDisplayFunc(draw)
glutMainLoop()



