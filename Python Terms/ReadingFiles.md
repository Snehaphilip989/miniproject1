# Reading Files

The csv library provides functionality to both read from and write to CSV files. Designed to work out of the box with Excel-generated CSV files, it is easily adapted to work with a variety of CSV formats. The csv library contains objects and other code to read, write, and process data from and to CSV files.

## How to Read a File

Not only you can create .txt file from Python but you can also call .txt file in a "read mode"(r).

* Step 1) Open the file in Read mode
f=open("guru99.txt", "r")

* Step 2) We use the mode function in the code to check that the file is in open mode. If yes, we proceed ahead
if f.mode == 'r':

* Step 3) Use f.read to read file data and store it in variable content
contents =f.read()

* Step 4) print contents
Here is the output

# Source:
https://www.guru99.com/reading-and-writing-files-in-python.html#3
