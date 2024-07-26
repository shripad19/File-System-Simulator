# File System Simulator

This project is a File System Simulator that simulates the working of several common file system commands. It is implemented in C and allows you to perform various operations on files and directories within a simulated environment.

## Features

The following commands are supported:

- **man**: Displays information about all available commands.
- **cd**: Changes the current directory.
- **ls**: Lists all files and folders in the current directory.
- **mkdir**: Creates a new folder.
- **cp**: Copies the content of a file to another file.
- **touch**: Creates a new file.
- **rm**: Deletes a file or folder.
- **cat**: Displays the content of a file.
- **rename**: Renames a file.
- **mv**: Moves a file or folder.
- **pwd**: Displays the path of the present working directory.
- **find**: Checks if a file exists.
- **exit**: Exits the system.

## Usage

1. **Clone the repository**:
    ```sh
    git clone https://github.com/shripad19/File-System-Simulator.git
    cd File-System-Simulator
    ```

2. **Compile the program**:
    ```sh
    gcc -o file_system_simulator main.c
    ```

3. **Run the program**:
    ```sh
    ./file_system_simulator
    ```

4. **Use the commands**: Type any of the supported commands listed above to interact with the file system simulator.

## Example

Here's an example session demonstrating some of the commands:

```sh
United2004@DESKTOP-Ubuntu:~$ touch file1
United2004@DESKTOP-Ubuntu:~$ ls
file1
United2004@DESKTOP-Ubuntu:~$ mkdir folder1
United2004@DESKTOP-Ubuntu:~$ ls
file1
folder1
United2004@DESKTOP-Ubuntu:~$ cd folder1
United2004@DESKTOP-Ubuntu:~/folder1$ pwd
c:/folder1/
United2004@DESKTOP-Ubuntu:~/folder1$ touch file2
United2004@DESKTOP-Ubuntu:~/folder1$ ls
file2
United2004@DESKTOP-Ubuntu:~/folder1$ cd ..
United2004@DESKTOP-Ubuntu:~$ find file1
c:/file1/
United2004@DESKTOP-Ubuntu:~$ rm file1
United2004@DESKTOP-Ubuntu:~$ ls
folder1
United2004@DESKTOP-Ubuntu:~$ exit
