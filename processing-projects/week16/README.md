# Week 16 – Generative Art and Interactive Graphics

This week focuses on creating visual patterns and interactive graphics using Processing. The exercises explore mathematical shapes, mouse interactions, arcs, and animated circular designs.

## 1. Mathematical Drawing and Heart Shapes

### `week16_1_heart`
- Draws a heart shape using a mathematical equation.
- Uses nested loops to examine individual canvas coordinates.
- Applies a conditional statement to determine which points belong to the heart.

### `week16_2_many_ellipse_mousePressed`
- Draws an initial circle in the center of the canvas.
- Creates additional circles at the mouse position whenever the mouse is clicked.
- Introduces mouse interaction through the `mousePressed()` function.

### `week16_3_smaller_heart`
- Draws a smaller heart using the same mathematical approach.
- Adjusts coordinate scaling and positioning to change the heart's size and location.

### `week16_4_mousePressed_myHeart`
- Defines a custom `myHeart()` function to draw a heart shape.
- Draws a heart at the mouse position when the user clicks the canvas.
- Practices function creation and parameter passing.

## 2. Arcs and Circular Patterns

### `week16_5_arc`
- Draws a 270-degree arc using the `arc()` function.
- Uses `radians()` and the `PIE` drawing mode.

### `week16_6_many_arc`
- Divides a circle into 24 arc sections.
- Uses a loop and angle calculations to generate a circular pattern.

### `week16_7_arc_mouseX`
- Creates an interactive arc controlled by the mouse's horizontal position.
- Updates the arc angle continuously in the `draw()` function.

## 3. Interactive Spinning Wheel

### `week16_8_big_wheel`
- Creates a colorful wheel divided into 24 sections.
- Uses different fill colors to distinguish the sections.
- Rotates the wheel according to the mouse's horizontal position.

### `week16_9_lucky_big_wheel`
- Develops a spinning wheel with mouse interaction.
- Uses mouse events to track dragging and release movement.
- Applies a velocity variable and gradual reduction to simulate rotational deceleration.

## Key Concepts

- **Mathematical Drawing:** Using equations and coordinate transformations to generate shapes.
- **Loops:** Applying nested loops and iteration to create repeated visual patterns.
- **Functions:** Defining reusable drawing functions with parameters.
- **Mouse Interaction:** Using `mousePressed()`, `mouseX`, and mouse-related events.
- **Angles and Radians:** Converting degrees into radians for graphical calculations.
- **Animation:** Updating graphics continuously through the `draw()` function.
- **Motion and Velocity:** Using variables to simulate rotation and gradual deceleration.

## Learning Outcomes

Through these exercises, I practiced generating mathematical shapes, creating interactive graphics, working with angles and arcs, defining reusable functions, and implementing basic animation and mouse-controlled interactions in Processing.
