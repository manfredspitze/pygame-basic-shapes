## Pygame: Practice Drawing Rectangles & Circles

### Overview

In this Pygame project, you'll write two different functions, one that lets you draw a rectangle, and the other that lets you draw circles.

Name the functions:

- `draw_circle()`
- `draw_rectangle()`

Each function will take different parameters.  **Remember to call these functions from your `main( )` function.**

---

### Example 1: Function to draw a rectangle

Note the parameters this function takes.
```python
def draw_rectangle(screen, rect, color, thickness):
    """Draws a rectangle on the Pygame window."""
    pygame.draw.rect(screen, color, rect, thickness)

# Call the rectangle function from your main ( ) function like so:
```python
my_rect1 = [100, 100, 200, 150]
thickness1 = 8

draw_rectangle(screen, my_rect1, config.GREEN, thickness1)
```
---

### Example 2: Function to draw a circle

Note which parameters this function takes.
```python
def draw_circle(screen, center, radius, color, thickness):
    """Draws a circle on the Pygame window."""
    pygame.draw.circle(screen, color, center, radius, thickness)

# Call the circle function from your main ( ) function like so:
```python
 # Define circle arguments for the function call
 circle_center = (300, 200)  # Center point of the circle (x, y)
 circle_radius = 50           # Radius of the circle
 circle_color = config.GREEN   # Color of the circle
 circle_thickness = 0         # 0 pixels creates a filled in circle

 # Draw the circle
 draw_circle(screen, circle_center, circle_radius, circle_color, circle_thickness)
```
