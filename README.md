# College Information System

A command-line Go program for storing and browsing a university's student, teacher, and staff records. The application persists its data in the local `university.json` file.

## Features

- Add student records with course, branch, age, and CGPA
- Add teacher records with subject, position, and home city
- Add staff records with salary and home city
- Display stored university records
- Search students by name, teachers by subject, and staff by city

## Requirements

- Go

## Run

From the repository root:

```bash
go run main.go
```

The program displays a numbered menu. Choose an option to add, view, or search records, or choose `6` to exit.

## Data File

The application reads and writes `university.json` relative to the current working directory. Keep a backup of this file if its contents are important. The checked-in JSON file is the initial dataset.

## Project Structure

```text
.
├── main.go
├── university.json
└── README.md
```

## Limitations

This is a local, single-process command-line application. It does not provide a network API, user accounts, or multi-user data storage.
