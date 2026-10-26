# DevPulse Pro — Coding Practice Tracker

A beginner-friendly coding practice tracker built with:
- Java 17 + Spring Boot
- Spring Data JPA
- H2 SQL database (persistent file database)
- HTML, CSS, and vanilla JavaScript
- CSV export that opens in Microsoft Excel

## Features
- Add, view, and delete coding practice records
- Track problem title, platform, topic, difficulty, status, and date
- Dashboard totals for problems solved, attempted, and pending
- Search/filter records
- Export records as CSV for Excel
- Light responsive interface

## Requirements
- Java 17 or later
- Maven 3.6+ (or use an IDE that supports Maven)

## Run the project
1. Extract the ZIP.
2. Open a terminal in this folder.
3. Run:
   ```bash
   mvn spring-boot:run
   ```
4. Open http://localhost:8080

If you use IntelliJ IDEA or Eclipse, import this folder as an existing Maven project and run `DevPulseProApplication.java`.

## Database
The H2 database is saved under `./data/devpulse` and survives app restarts.
The database is SQL, not an Excel file. Click **Export CSV** in the website to download a spreadsheet-compatible file that can be opened in Excel.

## Important
This is a recreated starter project based on the description, not a recovered copy of the original Google AI Studio source code. Do not upload passwords, API keys, or private data to GitHub.
