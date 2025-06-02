# Hello Scripts

This repository contains simple "hello world" scripts in different programming languages.

## Scripts

### hello.sh (Bash)
A bash script that prints a greeting message.

**Usage:**
```bash
./hello.sh              # Prints "hello world!"
./hello.sh Alice        # Prints "hello Alice!"
./hello.sh "John Doe"   # Prints "hello John Doe!"
```

### hello.rb (Ruby)
A Ruby script that prints a greeting message.

**Usage:**
```bash
./hello.rb              # Prints "hello world!"
./hello.rb Alice        # Prints "hello Alice!"
./hello.rb "John Doe"   # Prints "hello John Doe!"
```

## Features

- Both scripts accept an optional name argument
- Default to "world" if no argument is provided
- Support multi-word names when quoted
- Executable scripts with proper shebangs

## Requirements

- **Bash script**: Requires bash (available on most Unix-like systems)
- **Ruby script**: Requires Ruby interpreter