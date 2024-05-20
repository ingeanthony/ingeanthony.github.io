import turtle

def draw_triangle(vertices, color, turtle_obj):
    """
    Dibuja un triángulo usando los vértices y el color proporcionados.
    """
    turtle_obj.fillcolor(color)
    turtle_obj.penup()
    turtle_obj.goto(vertices[0][0], vertices[0][1])
    turtle_obj.pendown()
    turtle_obj.begin_fill()
    turtle_obj.goto(vertices[1][0], vertices[1][1])
    turtle_obj.goto(vertices[2][0], vertices[2][1])
    turtle_obj.goto(vertices[0][0], vertices[0][1])
    turtle_obj.end_fill()

def get_midpoint(point1, point2):
    """
    Calcula el punto medio entre dos puntos.
    """
    return [(point1[0] + point2[0]) / 2, (point1[1] + point2[1]) / 2]

def sierpinski(vertices, level, turtle_obj):
    """
    Dibuja el fractal del triángulo de Sierpinski.
    """
    colormap = ['blue', 'red', 'green', 'white', 'yellow', 'violet', 'orange']
    draw_triangle(vertices, colormap[level], turtle_obj)
    if level > 0:
        sierpinski([vertices[0],
                    get_midpoint(vertices[0], vertices[1]),
                    get_midpoint(vertices[0], vertices[2])],
                   level-1, turtle_obj)
        sierpinski([vertices[1],
                    get_midpoint(vertices[0], vertices[1]),
                    get_midpoint(vertices[1], vertices[2])],
                   level-1, turtle_obj)
        sierpinski([vertices[2],
                    get_midpoint(vertices[2], vertices[1]),
                    get_midpoint(vertices[0], vertices[2])],
                   level-1, turtle_obj)

def main():
    screen = turtle.Screen()
    screen.bgcolor("white")

    my_turtle = turtle.Turtle()
    my_turtle.speed(0)  # Establece la velocidad de dibujo al máximo

    vertices = [[-200, -100], [0, 200], [200, -100]]
    level = 4  # Nivel de profundidad del fractal
    sierpinski(vertices, level, my_turtle)

    screen.exitonclick()

if __name__ == "__main__":
    main()



