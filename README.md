# Python Digital Clock with Tkinter

This repository contains a Python script that creates a digital clock using the Tkinter GUI library. It displays the current time in a large, easy-to-read format with a customizable font and colors.

## Features

* Clear and user-friendly digital clock display
* Customizable font and background/foreground colors 
* Runs continuously, updating the time every second

## Customization

* To change the font, edit the `font` parameter in the `label` creation line:

   ```python
   label = Label(root, font=("your_font_name", 80), background="black", foreground="cyan")

## To adjust background and foreground colors, modify the corresponding parameters:

* label = Label(root, font=("ds-digital", 80), background="your_background_color", foreground="your_foreground_color")

