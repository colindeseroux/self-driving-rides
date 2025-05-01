# Self-driving-rides

Hashcode 2018

## Description

This is a Python application using the `tkinter` library to provide a graphical interface for visualizing trips taken by autonomous vehicles in a simulated environment. Input data is read from a file (`*.txt`), and completed trips are read from an output file (`ends_*.txt`).

## Features

- Visualize vehicle routes as colored lines on a canvas.
- Zoom in and out for detailed or broader views.
- Scroll horizontally and vertically to navigate the entire map.
- Display a color legend to interpret route statuses.
- Console output highlights unassigned trips.

## Usage

1. Ensure that both the input (`*.txt`) and output (`ends_*.txt`) files are in the same directory as this script.
2. Run the Python script to launch the visualizer.
3. Use the following keyboard controls:

   - `+` : Zoom in
   - `-` : Zoom out
   - Left arrow: Scroll left
   - Right arrow: Scroll right
   - Up arrow: Scroll up
   - Down arrow: Scroll down

## Example Route Color Legend

- Unreachable routes: Yellow
- Bonus unreachable: Blue
- Bonus reachable: Green

## Warning

This tool is intended for visualization and demonstration purposes only. It does not guarantee the accuracy or correctness of the trip data. Unassigned trips will be detected and shown in the console, but further analysis is recommended.

## Notes

This program requires the `tkinter` library. Ensure it's installed and available in your Python environment.

## Over 300 trips? Be patient.

If you have ideas for optimization...
