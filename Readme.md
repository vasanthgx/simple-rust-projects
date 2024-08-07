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


Project 4 : [Image-Combiner](https://github.com/vasanthgx/combiner)

Description : This Rust project combines two images by alternating their pixel data. The program reads two images, ensures they have the same format, resizes them to the smallest dimensions, and then merges them by alternating pixel blocks from each image. The result is saved as a new image file.

### Features

- **Image Format Verification:** Ensures both images are of the same format.
- **Image Resizing:** Standardizes the size of both images to the smallest dimensions.
- **Pixel Alternation:** Combines the images by alternating 4-byte RGBA pixel blocks.
- **Output Image Creation:** Saves the combined image to a specified file.

### Usage

To run the program, use:

```sh
cargo run -- <path_to_image_1> <path_to_image_2> <output_path>
```

Example:

```sh
cargo run -- image1.png image2.png output.png
```

This will create an `output.png` file with the combined image data from `image1.png` and `image2.png`.

---



Project 5 : [Guess the Number](https://github.com/vasanthgx/guessing_game)

Description: Welcome to the "Guess the Number" game! This simple yet engaging project is a console-based number guessing game implemented in Rust. The game randomly generates a secret number between 1 and 100, and the player's goal is to guess this number. The program provides feedback on whether the guess is too low, too high, or correct. The game continues to prompt the player for guesses until the correct number is guessed.

#### Key Features:
- **Random Number Generation**: Utilizes the `rand` crate to generate a random number between 1 and 100.
- **User Input Handling**: Reads user input from the command line.
- **Input Validation**: Ensures that the user input is a valid number.
- **Feedback Loop**: Provides feedback on whether the guess is too low, too high, or correct.
- **Looping Mechanism**: Continues to prompt the user for guesses until the correct number is guessed.

### Usage

1. **Install Rust**: Ensure you have Rust installed on your machine. If not, you can install it by following the instructions at [rust-lang.org](https://www.rust-lang.org/).

2. **Clone the Repository**: Clone this repository to your local machine using:
   ```sh
   git clone https://github.com/your-username/guess-the-number.git
   ```

3. **Navigate to the Project Directory**:
   ```sh
   cd guess-the-number
   ```

4. **Build the Project**:
   ```sh
   cargo build
   ```

5. **Run the Project**:
   ```sh
   cargo run
   ```

6. **Play the Game**: Follow the on-screen instructions to input your guesses. The game will provide feedback and continue until you guess the correct number.

### Concepts Covered

- **Random Number Generation**: Using the `rand` crate to generate random numbers.
- **Standard Library Modules**: Utilizing `std::io` for input handling and `std::cmp` for comparisons.
- **Pattern Matching**: Using the `match` statement for control flow based on the comparison results.
- **Error Handling**: Utilizing the `expect` method to handle potential errors in reading input.
- **Looping**: Using the `loop` keyword to create an infinite loop until the correct guess is made.

