# Xpresso ☕

A coffee shop ordering application written in C with a GTK 3 graphical interface.

## Features
- Menu with item names, prices, and pictures
- Add items to a cart and see a running total
- Generate and save a bill to a text file
- Styled interface using GTK CSS

## Built With
- C
- GTK 3

## Requirements
- GCC
- GTK 3 and pkg-config

On macOS:
brew install gtk+3 pkg-config

## Build and Run
gcc main.c -o coffee `pkg-config --cflags --libs gtk+3.0`
./coffee

## Project Structure
- main.c: GTK setup and screens
- images/: menu item pictures

## Author
Sarah Khan

