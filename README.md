# College Information System

A small Go command-line application for maintaining university records. It supports adding, viewing, and searching student, teacher, and staff information, with records persisted in a local JSON file.

## Features

- Add student, teacher, and staff records
- View the saved university directory
- Search students by name, teachers by subject, and staff by city
- Store data in `university.json`

## Requirements

- Go installed and available on your `PATH`

## Run

From the repository root:

```bash
go run main.go
```

Use the numbered menu to add, view, or search records. The program reads and writes `university.json` in the current working directory; keep a backup if the data matters.

## Files

```text
.
├── main.go           # CLI menu, records, and JSON persistence
├── university.json   # Local data store
└── README.md
```

This project is a learning-oriented CLI example and stores data locally rather than in a database.
