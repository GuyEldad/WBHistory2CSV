<p align="center">
  <img src="WBHistory2CSV.jpg" alt="WBHistory2CSV Banner" width="850">
</p>

# WBHistory2CSV

**WBHistory2CSV** is a tool designed to parse browsing and download history from multiple browsers, convert timestamps to UTC, and export data to CSV format for easy analysis.

## Features
- Parses browsing and download history and converts timestamps (Epoch, Unix, WebKit) to UTC.
- Exports data to CSV format for easy analysis.
- Supports multiple browsers, including **Chrome, Firefox, Edge, Brave, and Opera**.
- Provides an easy-to-use **graphical user interface (GUI)** for navigation and data export.
- Available as an **executable file for Windows (EXE)** and an **ELF file for Linux**, ensuring a standalone experience with no additional dependencies required.

## Download

Get the pre-built executable files for your operating system from the links below:

- **Windows**: [WBHistory2CSV.zip](WBHistory2CSV.zip)

- **Linux**: [WBHistory2CSV.tar.gz](WBHistory2CSV.tar.gz)


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
