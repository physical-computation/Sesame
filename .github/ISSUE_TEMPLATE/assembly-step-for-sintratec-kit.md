---
name: Assembly Step for Sintratec Kit
about: Use this issue template to create a git issue to describe an assembly step
  for the Sintratec Kit SLS printer
title: Assembly Step NNNN
labels: Mechanical Assembly, Sintratec Kit
assignees: ''

---

^--- Set the title to a descriptive phrase of the form "Assembly Step XNNN", then delete this line up until the header "Step Number XNNN" below.

# Step Number XNNN
(Where XNNN is something like **D001**). Delete this text and then add a brief description (e.g., "Door assembly.")

# Build Diagram from Assembly Manual
Export the assembly diagrams from the assembly guide as a PNG and drag and drop them here. GitHub will automatically upload them and insert a link when you do so. On macOS you can use SHIFT+COMMAND+4 followed by SPACE to capture a picture of a window to a file. If your default screen capture format is PDF on macOS, you can do `defaults write com.apple.screencapture type png; killall SystemUIServer` from the shell to set it to PNG. When done, delete these instructions.

# Tags
Tag / label this issue with labels #Mechanical Assembly and #Sintratec Kit. When done, delete this block. You can find the **labels** pull down to the right of the text box of this page.

# Sensors
If the build step is a candidate for locating a sensor to monitor in-chamber conditions, also tag the issue with label #In-Chamber Sensor and write a few notes explaining why, here. If not applicable or if you are not sure, simply replace this block with "N/A".

# Build Picture
Pictures from the assembly go here or to be attached as comments below.

# Notes
Any additional notes go here.
