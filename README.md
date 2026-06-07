# Drawing Pad 🎨

A simple and interactive drawing application built with Python Tkinter. This project allows users to draw freely on a canvas using different colors, adjust brush size, and erase or clear their artwork.

It’s a great beginner-friendly project that demonstrates GUI design, event handling, and real-time drawing in Python.

## Features

- 🖌️ Freehand drawing with mouse
- 🎨 Multiple color options (black, red, blue, green, yellow)
- 🧽 Eraser tool
- 📏 Adjustable pen size slider
- 🧼 Clear canvas button
- 🖥️ Responsive window layout

## Requirements

- Python 3.x

## Installation

```bash
git clone https://github.com/your-username/Drawing-Pad.git
cd Drawing-Pad
```

## Usage

```bash
python3 PY3drawpad.py
```

## How It Works

* A Tkinter window is created with a canvas for drawing
* Mouse events (click, drag, release) control drawing behavior
* Lines are drawn between mouse positions to simulate smooth strokes
* Buttons update the current drawing color
* A slider dynamically adjusts brush thickness
* The eraser works by drawing in the background color (white)

## Controls

* Click + Drag → Draw
* Color Buttons → Change pen color
* Eraser → Switch to erase mode
* Slider → Adjust brush size
* Clear → Reset the canvas

## Technical Details

* Built using tkinter for GUI
* Uses Canvas.create_line() for drawing strokes
* Event bindings:
    * <Button-1> → Start drawing
    * <B1-Motion> → Draw while dragging
    * <ButtonRelease-1> → Stop drawing
* Grid layout system for responsive UI
* Global state used for tracking pen color and size

## Future Enhancements

* Save drawings as image files
* Add more colors or a color picker
* Add undo/redo functionality
* Add shapes (circle, rectangle tools)
* Keyboard shortcuts for tools

## License

Open source - Feel free to take inspiration!

