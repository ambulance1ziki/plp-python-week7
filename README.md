
# Week 7 Assignment: My Notes & The Report Builder

## Description
This assignment demonstrates Python file handling, CSV processing,
exception handling, and report generation.

## Project Files

- my_notes.py - Writes, appends, reads, and counts notes.
- my_notes.txt - Stores the generated notes.
- report_builder.py - Reads CSV data and generates a learner report.
- hubs.csv - Contains learner names, hubs, and scores.
- report.txt - Contains the generated learner performance report.

## What happens if "a" is changed to "w"?

Changing the file mode from "a" (append) to "w" (write)
would erase the existing contents before writing new data.
This means the first three notes would be lost and only
the fourth note would remain in the file.

## Concepts Practiced

- File handling using with open()
- Writing, appending, and reading files
- CSV processing using csv.DictReader
- Exception handling using FileNotFoundError
- Converting strings into integers
- Generating text reports
