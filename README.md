<p align="center">
  <img src="WBHistory2CSV.jpg" alt="WBHistory2CSV Banner" width="850">
</p>

# WBHistory2CSV

**WBHistory2CSV** is a forensic tool designed to parse web browsing and download history, convert timestamps to UTC, and export the data to CSV format for efficient analysis and investigation.

## Features
- Parses browsing and download history and converts timestamps (Epoch, Unix, WebKit) to UTC.
- Exports data to CSV format for easy analysis.
- Supports multiple browsers: **Chrome, Firefox, Edge, Brave, and Opera**.
- Provides both:
  - A **graphical user interface (GUI)** for intuitive navigation and export.
  - A **command-line interface (CLI)** for automation and scripting use.
- Available as an **executable file for Windows (EXE)** and an **ELF file for Linux**, ensuring a standalone experience with no additional dependencies required.

## Download

| Version | Platform | Interface | Download |
|--------|----------|-----------|----------|
| GUI    | Windows  | GUI       | [WBHistory2CSV_GUI_Windows.7z](./WBHistory2CSV_GUI_Windows.7z) |
| CLI    | Windows  | CLI       | [WBHistory2CSV_CLI_Windows.7z](./WBHistory2CSV_CLI_Windows.7z) |
| CLI    | Linux    | CLI       | [WBHistory2CSV_CLI_Linux.7z](./WBHistory2CSV_CLI_Linux.7z) |


## Installation and Usage

### Windows:
- Extract the ZIP file.
- Run the executable without any additional dependencies.

### Linux:
- Extract the archive using:
  ```bash
  tar -xvzf WBHistory2CSV.tar.gz
 
- Run the following command to grant execution permission:
  ```bash
  chmod +x WBHistory2CSV

- Once the tool is running, select the appropriate browser button (Chrome, Firefox, Edge, Brave, Opera).
- Choose the corresponding history file when prompted.
- Click the **"!"** button to view default history file locations if needed.
- The tool will parse the data and export it as a CSV file for easy analysis.

## Important Notice

Some antivirus software may flag the executable version of this tool as a false positive. This is due to the way the tool interacts with system files and browser history databases. The tool is built using **Python** and **PyInstaller**, which can sometimes trigger heuristic detections.

If you encounter warnings, please consider the following:

- Running the tool in a sandbox environment.
- Adding an exclusion rule for the executable in your antivirus software.
- Temporarily disabling your antivirus software.

## Contact

For questions or feedback, please contact me via https://www.linkedin.com/in/guy-eldad/


Copyright
© 2025 Guy Eldad. All rights reserved.
