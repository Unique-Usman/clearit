# ClearIt - Interactive File Deletion Script

## Description
ClearIt is a Bash script designed as a command-line tool for interactive file removal, allowing users to inspect file contents before deletion. It facilitates a user-friendly approach by enabling content review before deciding whether to delete files.

## Usage
### Installation
1. Download the script to your desired location.
2. Grant execute permissions: `chmod +x clearit`
3. Move it to `/usr/local/bin/` to use it as a command: `sudo mv clearit /usr/local/bin/`

### Running the Script
Execute the script by typing `clearit` followed by the directory path or file name for review and potential deletion.

**Example Usage:**
- Remove a file: `clearit /path/to/file.txt`
- Clean a directory: `clearit /path/to/directory`

## Functionality
- Interactive prompt to check file content before deletion.
- Distinguishes between regular files and directories.
- For ELF executable files, prompts for confirmation before deletion.
- Option to view content before confirming deletion.
- Respond to prompts with "yes," "no," or abbreviations like "y" or "n."

## Usage Syntax

clearit [directory_name or file_name]

## Note
ClearIt is designed to provide an interactive file-handling approach, prompting users before deleting files or directories.
