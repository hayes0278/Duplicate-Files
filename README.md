# Duplicate-Files
A lightweight Windows desktop utility written in C# that will help detect and handle duplicate files.

Features

- Detect duplicate files on criteria such as same name or file size.
- User can choose to log, move or delete the duplicate files found.
- User can add custom criteria to run in addition to the built in criteria. 
- Does not store or transmit any path, file or folder information.
- Safe to run against very large directories such as pictures with many files.

Screenshots 



To Run

Download the package and double click on the DuplicateFiles.exe file.

How It Works

- Verifies directory path and custom criteria.
- Indexes the folder and files within.
- Runs default criteria against index list.
- Runs any custom criteria (if provided)
- A list of suspected duplicates is displayed.
- The user can then act on each of the duplicates.

Limitations

- Only will run on Windows, no Linux or Macintosh support.
- 