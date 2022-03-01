from turtle import Turtle, Screen

josh = Turtle()
screen = Screen()

def move_forwards():
    josh.forward(10)

def move_backwards():
    josh.back(10)

def move_counter_clockwise():
    josh.left(10)

def move_clockwise():
    josh.right(10)

def clear_screen():
    josh.clear()
    josh.penup()
    josh.home()
    josh.pendown()

screen.listen()
screen.onkey(move_forwards, "w")
screen.onkey(move_backwards, "s")
screen.onkey(move_counter_clockwise, "a")
screen.onkey(move_clockwise, "d")
screen.onkey(clear_screen, "c")
screen.exitonclick()
