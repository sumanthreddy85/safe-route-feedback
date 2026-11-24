# Safe Route Feedback Log
## Project #76 — Python for Good

A beginner-friendly, menu-driven Python application for collecting and reviewing route-safety observations.

### Features
- Add safety feedback with input validation
- Save and reload records using local JSON storage
- View, search, and filter reports
- Update report status
- Executive summary with severity and overdue warnings
- Export CSV, text, and Markdown reports
- Import validated CSV records
- Includes 30 sample records for demonstration

### Requirements
- Python 3.10 or later
- No third-party packages required

### Run the project
Open a terminal in this folder and run:

```bash
python safe_route_feedback.py
```

### Menu walkthrough
1. Choose `2` to view the included sample records.
2. Choose `5` to display the executive summary.
3. Choose `3` to search for a route, location, or safety concern.
4. Choose `1` to add a new report.
5. Choose `4` to update a report's status.
6. Choose `6`, `7`, or `8` to export reports in CSV, text, or Markdown format.

### Data files
- `safe_route_feedback.json` — starter data loaded by the application.
- `sample_feedback.csv` — same 30 sample records for import/testing.
- The application creates exported reports in the current working directory.

### Severity scale
1 = Low, 2 = Moderate, 3 = High, 4 = Critical, 5 = Emergency.

### Status values
- Open
- In Progress
- Resolved

### Notes
The JSON file is the application's primary data store. Keep a backup before manually editing it.
