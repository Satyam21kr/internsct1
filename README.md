# internsct1 - Simple Command Line Utility

## Overview

internsct1 is a simple command-line utility designed for basic system-related tasks. It provides information about the CPU, memory, users, and files. The utility is extensible and allows users to perform various actions with different options.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Options](#options)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Features

### CPU Information

Run internsct1 cpu getinfo to display information about the CPU.

### Memory Information

Run internsct1 memory getinfo to display information about the system memory.

### User Management

- *Create User:* Run internsct1 user create <username> to create a new user.

- *List Users:* Run internsct1 user list to list all regular users. Add --sudo-only to list users with sudo permissions.

### File Information

Run internsct1 file getinfo [options] <file-name> to get information about a file. Options include --size, --permissions, --owner, and --last-modified.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/internsct1.git

2. Move into the repository: 

    ```bash
    cd internsct1

3. Copy the script into a directory in your PATH(e.gl, **'/usr/local/bin/'**):

    ```bash
    sudo cp internsct1 /usr/local/bin/

4. Update the man database:

    ```bash
    sudo mandb

# Usage

Run the '**internsc1**' command followed by the desired action and options. Use '**--help**' for additional information.

    ```bash
    internsct1 --help
    internsct1 cpu getinfo
    internsct1 memory getinfo
    internsct1 user create <username>
    internsct1 user list
    internsct1 user list --sudo-only
    internsct1 file getinfo [options] <file-name>

# Options
- '--version' : Display the version information
- '--help' : Display the help information.
- 'get cpu info': Display the CPU information
- 'memory get info': Display the memory information
- 'user create <username>':  Create a new user with the given username
- 'user list --sub-only': List users with sudo permissions
- 'file getinfo [options] <file-name>: Get information about a file.
