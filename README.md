# TransAudit

## Description
TransAudit is a Python application designed to help users audit financial transactions by comparing data entries from CSV files against records stored in a SQLite database. The tool identifies discrepancies in transaction amounts and provides a detailed report of any mismatches found. It features a simple GUI powered by tkinter, allowing users to easily interact with the application to start comparisons, view discrepancy reports, and exit the program.

## Key Features
- **Database Integration**: Uses SQLite to store transaction records.
- **CSV Comparison**: Compares transactions listed in CSV files with the database to find discrepancies.
- **Report Generation**: Outputs a report listing any discrepancies found during the comparison.
- **User Interface**: Simple graphical user interface for easy interaction with the application.

## Installation

### Prerequisites
Ensure Python 3 is installed along with the `tkinter` and `sqlite3` libraries, which are included in most standard Python installations. If not present, they can be installed via Python's standard library.

### Setup
1. Clone the repository:
```bash
git clone [your-repository-url]
