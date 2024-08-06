# Rust Projects Practice Repository

### Welcome to my Rust Projects Practice Repository! This repository is dedicated to housing various Rust projects that I will be working on to enhance my skills and understanding of the Rust programming language.

**About**

This repository will serve as a collection of different Rust projects, ranging from beginner to advanced levels. Each project will be a standalone application focusing on different aspects of Rust development, including systems programming, web development, concurrency, and more.

**Purpose**

The main goals of this repository are:

1. To provide a centralized location for all my Rust practice projects
2. To track my progress and growth in Rust development
3. To showcase my skills and understanding of Rust concepts
4. To serve as a reference for future projects and learning

**Project Structure**

Each project will be contained in its own directory within this repository. The directory name will reflect the project's main focus or functionality. Inside each project directory, you'll find:

- A complete Rust application
- A README file with project-specific details, including setup instructions and key features
- Any additional resources or documentation relevant to the project

**Technologies**

The projects in this repository will primarily use:

- Rust
- Cargo (Rust's package manager and build system)
- Various Rust libraries and crates as needed for specific project requirements

**Projects**

Project 1 : [Compression](https://github.com/vasanthgx/compress_project)

Description : This Rust project demonstrates file compression using the `flate2` crate for Gzip compression. The application reads a source file, compresses it, and writes the compressed data to a target file, measuring and displaying the elapsed time for the compression process.

Key Features:

- Uses the `flate2` crate to perform Gzip compression.
- Reads input from a source file specified by the user.
- Writes the compressed data to a target file specified by the user.
- Displays the sizes of the source and target files.
- Measures and displays the time taken for the compression process.



Project 2 : [Decompression](https://github.com/vasanthgx/decompress_project)

Description : This Rust program is a command-line ZIP file extractor. It takes a ZIP file as input and extracts all its contents to the current directory, preserving the internal folder structure. The program handles both files and directories within the ZIP archive, and on Unix systems, it maintains the original file permissions. It also displays any comments associated with files in the archive. The extractor provides informative console output, showing the progress of each file being extracted along with its size. This tool is useful for quickly unpacking ZIP archives while maintaining their original structure and metadata.

Key features:
1. Extracts all files from a ZIP archive
2. Preserves directory structure
3. Maintains file permissions on Unix systems
4. Displays file comments
5. Provides progress information during extraction


Project 3 : [CLI-Calculator](https://github.com/vasanthgx/cli-calculator-rust)

Description : This project is a simple command-line calculator written in Rust. It accepts three arguments: two numbers and an operator. The calculator performs basic arithmetic operations—addition, subtraction, multiplication, and division—based on the provided operator and prints the result.



