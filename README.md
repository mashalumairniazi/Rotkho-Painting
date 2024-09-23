# Project 2.1: Rothko Painting - CSS Art

##### This repository contains the completed code for Project 2.1, demonstrating how to recreate an abstract painting in the style of Mark Rothko using HTML and CSS.

This project shows how to use CSS properties like `background-color`, `box-shadow`, and `filter` to create an abstract design using simple div elements, emulating the style of a Rothko painting.

## Project Overview

The **Rothko Painting** project is a minimalist representation of abstract expressionism. The project demonstrates how to manipulate layout and visual effects purely through CSS, without images, to create an artistic piece.

### Key Features

- **CSS-Only Art**: The painting consists of div elements styled entirely with CSS to resemble a Rothko-inspired abstract painting.
- **Layered Elements**: The project uses multiple layers of rectangles with various colors, sizes, and slight rotations to create depth and texture.
- **Blur and Box Shadows**: The painting employs CSS filters like `blur` and shadows for a softer, more abstract effect, similar to the texture seen in Rothko’s work.

## Code Details

### HTML Structure:

- **Container Divs**:
  - The `frame` div acts as a border for the painting.
  - The `canvas` div is the main container for the three colored rectangles.
  - Three inner divs (`one`, `two`, `three`) represent the layers of the abstract painting.

### CSS Styling:

- **Canvas and Frame**:
  - The `.canvas` class defines the size and background color of the painting area.
  - The `.frame` class creates a black border around the painting to resemble a picture frame.
  
- **Color Blocks**:
  - The three divs inside `.canvas` are styled with varying sizes, colors, border radii, and slight rotations to mimic an abstract Rothko painting.
  - **First block**: Pale yellow with a small rotation.
  - **Second block**: Deep red with a slight tilt.
  - **Third block**: A darker red with rounded corners and more subtle adjustments.

- **Blur and Shadows**:
  - Filters such as `blur` and `box-shadow` are used to give the painting a soft, out-of-focus appearance, enhancing the abstract feel.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rothko-painting.git
2. Ensure both the index.html and styles.css files are in the same directory.
3. Open the index.html file in a web browser to view the project.
