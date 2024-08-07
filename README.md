# QuickReplace

QuickReplace is a command-line tool written in Rust that allows you to replace occurrences of a target string with a replacement string in a given input file and output the result to a specified output file.

## Features

- Replace all occurrences of a target string with a replacement string in a text file.
- Handles errors gracefully and provides informative error messages.
- Uses regular expressions for string matching.

## Installation
### Clone the repository
- git clone https://github.com/yourusername/quickreplace.git
### Navigate to the project directory:
- cd quickreplace
### Build the project using Cargo:
- cargo build --release

## Usage

To use QuickReplace, run the following command:

```sh
quickreplace <target> <replacement> <INPUT> <OUTPUT>
