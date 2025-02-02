# Ghost Terminal - Web Terminal Interface

## Educational & Research Purpose Only
This tool is developed strictly for educational purposes, proof-of-concept testing, and research. Users must ensure they have explicit permission to use this tool on any system.

## Overview
Ghost Terminal is a PHP-based web terminal interface that provides a safe, controlled environment for testing and understanding web application behavior.

## Features

### Core Functionality
- Secure session handling
- Command throttling (0.5s delay between commands)
- Command history management (up to 50 commands)
- Directory traversal
- Detailed error handling and feedback

### Command Set
- `help` - Display available commands
- `ls/dir` - List directory contents
- `pwd` - Print working directory
- `cd` - Change directory
- `mkdir` - Create new directory
- `rmdir` - Remove directory
- `rm` - Remove files
- `cp` - Copy files
- `cat` - View file contents
- `echo` - Print text
- `clear` - Clear terminal screen
- `history` - Show command history
- `whoami` - Display current user
- `date` - Show current date/time
- `status` - Show terminal status

### Special Features
- Ghost Mode activation for extended functionality
- File upload capabilities (Ghost Mode only)
- Real-time command feedback
- Path validation and sanitization
- Base64 encoded communications
- Session-based working directory persistence

### Security Features
- Command whitelisting
- Directory boundary enforcement
- Input sanitization
- Session-based access control
- Request throttling
- Error suppression
