Pipe and Filter Pattern in Java
Overview
This project demonstrates the Pipe and Filter design pattern in Java using functional programming concepts. The pattern processes a list of integers through a sequence of filters (operations), where each filter transforms the data before passing it to the next stage in the pipeline.

Features:
Filters even numbers from the input list

Squares the filtered numbers

Cubes the squared numbers

Filters numbers greater than 10

Code Structure
processPipeline: Applies a sequence of filters to the input list.

filterEvenNumbers: Keeps only even numbers.

squareNumbers: Squares each number in the list.

cubeNumbers: Cubes each number in the list.

filterNumbersGreaterThanTen: Keeps only numbers greater than 10.