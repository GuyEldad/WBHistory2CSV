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

| Platform | Interface | Download |
|----------|-----------|----------|
| Windows  | GUI       | [WBHistory2CSV_GUI_Windows.7z](./WBHistory2CSV_GUI_Windows.7z) |
| Windows  | CLI       | [WBHistory2CSV_CLI_Windows.7z](./WBHistory2CSV_CLI_Windows.7z) |
| Linux    | CLI       | [WBHistory2CSV_CLI_Linux.7z](./WBHistory2CSV_CLI_Linux.7z) |


## Installation and Usage

### Windows GUI Version
- Extract the .7z archive.
- Run the executable without any additional dependencies.
- Once the tool launches:
  - Select the appropriate browser button: **Chrome**, **Firefox**, **Edge**, **Brave**, or **Opera**.
  - When prompted, choose the corresponding browser history file.
  - You can click the **"Show Browser Paths"** button to view default file locations.
- The tool will parse the data and export it as a `.csv` file for easy analysis.

---

### Windows CLI Version
- Extract the `.7z` archive.
- Open **Command Prompt** in the folder where the executable is located.
- Use the following syntax:

  ```bash
  WBHistory2CSV.exe -f <input_history_file> -o <output_folder> -browser <chrome|firefox|edge|brave|opera>
  ```
- **Example**

  ```bash
  WBHistory2CSV.exe -f "C:\Users\Username\AppData\Local\Google\Chrome\User Data\Default\History" -o "C:\Users\Username\Desktop" -browser chrome
  ```
  
---
  
### Linux CLI Version
- Extract the `.7z` archive using:
  ```bash
  7z x WBHistory2CSV_CLI_Linux.7z
  ```
- Make the binary executable:
  ```bash
  chmod +x WBHistory2CSV
  ```
- Run the tool using the following syntax:

  ```bash
  ./WBHistory2CSV -f <input_history_file> -o <output_folder> -browser <chrome|firefox|edge|brave|opera>
  ```

- **Example**

  ```bash
  ./WBHistory2CSV -f ~/path/to/History -o ~/Desktop -browser chrome
  ```
  
- **Optional Arguments**
  ```
  -h            Show help message  
  -f            Path to browser history SQLite file  
  -o            Output folder for all CSVs  
  -browser      {chrome,firefox,edge,brave,opera} - Type of browser history file
  ```

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
