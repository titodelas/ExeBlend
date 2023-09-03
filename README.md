# ExeBlend

ExeBlend is a command-line tool for injecting one executable file into another. It allows you to blend the functionality of two executable files into a single executable, optionally preserving the properties of the original file.

## Table of Contents

- [ExeBlend](#exeblend)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
    - [Inject](#inject)
    - [Clear](#clear)
  - [Contributing](#contributing)
  - [License](#license)

## Features

- Inject one executable file into another.
- Option to clone all original file properties.
- Simple command-line interface for ease of use.

## Getting Started

### Prerequisites

Before you can use ExeBlend, ensure you have the following prerequisites:

- Python 3.x installed on your system.
- Required Python modules installed (listed in `requirements.txt`).

### Installation

1. Clone the ExeBlend repository to your local machine:

```bash
git clone https://github.com/yourusername/ExeBlend.git
```

2. Navigate to the project directory:

```bash
cd ExeBlend
```

3. Install the required Python modules using pip:

```bash
pip install -r requirements.txt
```

## Usage

To use ExeBlend, open a command prompt or terminal and navigate to the project directory. Then, you can run the following commands:

### Inject

The `inject` command is used to inject one executable file into another.

```bash
python main.py inject [injected_file] ? [target_file] ?
```

- `[injected_file]`: The path to the file you want to inject.
- `[target_file]`: The path to the target file where the injection will occur.
- Use `?` to interactively provide file paths if not specified.

Example:

```bash
python main.py inject myapp.exe ? target.exe
```

### Clear

The `clear` command clears the console.

```bash
python main.py clear
```

## Contributing

Contributions to ExeBlend are welcome! If you want to contribute to this project, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and test them.
4.  Commit your changes with a descriptive commit message.
5.  Push your changes to your fork.
6.  Create a pull request to the main repository.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/titodelas/ExeBlend/LICENSE) file for details.
