# Desktop File Sorter

This script organizes files in a specified folder into subfolders based on their file types. It's useful for cleaning up cluttered directories by grouping similar files together.

## Features

- Automatically creates subfolders for each file type.
- Moves files into their respective subfolders based on file extensions.

## Requirements

- Python 3.x
- `os` module (standard library)
- `shutil` module (standard library)

## Installation

1. Clone the repository:

```sh
git clone https://github.com/Arighna2003/Desktop-File-Sorter.git
```

2. Navigate to the project directory:

```sh
cd Desktop-File-Sorter
```

## Usage

1. Run the script:

```sh
python file-sorter.py
```

2. When prompted, enter the path to the folder you want to clean:

```sh
Please enter the folder path: /path/to/your/folder
```

The script will then organize the files in the specified folder into subfolders based on their file types.

## Example

If your directory contains the following files:

```
report.docx
image.png
presentation.pptx
```

After running the script, the directory will be organized as:

```
DOCX Files/
    report.docx
PNG Files/
    image.png
PPTX Files/
    presentation.pptx
```

## License

This project is licensed under the [MIT License](LICENSE).
