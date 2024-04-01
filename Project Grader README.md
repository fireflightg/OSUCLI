
# OSU Project Grader

OSU Project Grader is a command-line tool designed to facilitate the grading of projects by automating the compilation, testing, and evaluation of Java code. It utilizes various libraries such as `rimraf`, `chalk`, `boxen`, `figlet`, `yargs`, and others to provide a user-friendly interface and efficient grading process.

## Features

- Automatic download of project dependencies.
- Compilation and execution of Java test cases.
- Integration with OpenAI for advanced code analysis and grading.
- Support for both manual and automated test case addition.
- Clear and colored console output for easy result interpretation.
- Progress tracking during file extraction and grading.

## Prerequisites

- Node.js and npm installed on your system.
- Java Development Kit (JDK) for compiling and running Java code.
- Access to the internet for downloading dependencies.

## Installation

1. Clone the repository or download the source code.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install the required Node.js dependencies.

## Usage

```
grad -n <project number> -t <project type>
```

Options:
- `-n`, `--number`: The number of the project being graded.
- `-t`, `--type`: Type of grading (test or main file).
- `-i`, `--install`: Install dependencies.
- `-d`, `--delete`: Clears folders.
- `-l`, `--load`: Sets up zip files for grading.
- `-r`, `--run`: Run the grading process.
- `-a`, `--addtest`: Adds a new test case.

## Examples

To grade a project:

```
grad -n 1 -t main
```

To install dependencies:

```
grad -i
```

To clear the source and test directories:

```
grad -d
```

## Additional Information

For more detailed information, troubleshooting, and custom configurations, visit our [website](https://your-website.com).

## Video Tutorial

For a comprehensive guide on how to use the OSU Project Grader, please refer to our [video tutorial](https://your-video-link.com).

## Contributing

Contributions to the OSU Project Grader are welcome. Please feel free to fork the repository, make changes, and submit pull requests.
