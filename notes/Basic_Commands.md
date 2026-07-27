# Basic Shell Scripting Commands

1. **list command (ls)**:

**Purpose**: Lists the files and directories in the current working directory.

**Syntax**:`ls [options] [directory]`

### Common Options

|Command|Description|
|-------|-----------|
|`ls`|List Files|
|`ls -a`| Show hidden files|
|`ls -l`| Long Format |
|`ls -t`| Sort by Time |
|`ls -r`| Reverse Order |
|`ls -R`| Show ALL files (even in subdirectories)|

2. **pwd**:

**Purpose**: Prints the current working directory.

**Syntax**:`pwd`

3. **mv**:

**Purpose**: To change the name of a folder or file.

**Syntax**: `mv [fileName / folderName]`


4. **cd**

**Purpose**: To change the working directory.

**Syntax**: `cd [file path]`

### Common options
| Command | Description |
|---------|-------------|
|`cd ..` | Go back |

5. **touch**:

**Purpose**: To create a new file

**Syntax**:`touch [filename]`

6. **nano**:

**Purpose**: To append into a file (if no file exists, it will create one)

**Syntax**:`nano [filename]`


7. **cat**:

**Purpose**: To view and print the contents of a file in terminal.

**Syntax**:`cat [file name]`

### Common Options
|Command|Description|
|-------|-----------|
|`cat >> [filename]`| appends into the file |

8. **cp**:

**Purpose**: To copy the contents of one file to another

**Syntax**: `cp [SOURCE] [DESTINATION]`

9. **history**:

**Purpose**: To see all the history of all commands written till now.

**Syntax**: `history`

10.  **clear**:

**Purpose**: Clears the terminal screen.

**Syntax**: `clear`

11. **rm**:

**Purpose**: Removes file from system without confirmation

**Syntax**:`rm [filename]`

12. **mkdir**:

**Purpose**: To make Directories

**Syntax**: `mkdir [options][directorynames]`

13. **rmdir**:

**Purpose**: To remove directories.

**Syntax**: `rmdir [-p][-v|verboase] [-ignore-fail-on-non-empty] [directories]

> Note: This ONLY removes empty directories.

14. **cmp**:

**Purpose**: Compares 2 file byte by byte to check wether the files are identical or not

**Syntax**: `cmp [file1] [file2]`

15. **grep**:

**Purpose**: to find and locate sting inside a given file

**Syntax**: `grep [string (in "" if there are whitespaces)] [files to search from]`

