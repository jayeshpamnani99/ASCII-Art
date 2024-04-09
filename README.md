# ASCII Art 

This Rust program converts an image into an ASCII art representation.

## Prerequisites

- Ensure you have Rust installed on your system. You can download it from the official Rust website: [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install)

## Installation

1. Clone the repository or download the source code (https://github.com/jayeshpamnani99/ASCII-Art.git)
2. Navigate to the project directory in your terminal.

## Adding Dependencies

The program uses the `image` crate, which needs to be added as a dependency. Follow these steps to add the dependency:

**Method - I**
1. Open the `Cargo.toml` file in the project directory.
2. In the `[dependencies]` section, add the following line:

   ```toml
   image = "0.25.1"
   ```

   This will add the `image` crate version `0.25.1` as a dependency (or the latest version available at the time).

3. Save the `Cargo.toml` file.

**Method -II**

Run the below command in the terminal:
   ```
   cargo add image
   ```
This will add the `image` crate version `0.25.1` as a dependency (or the latest version available at the time).

## Running the Code

1. In the terminal, navigate to the project directory.
2. Run the following command to build and execute the program:

   ```
   cargo run
   ```

   This will convert the image in the project directory into an ASCII art representation and display it in the terminal.

