# data-cleaning-script
“This script cleans a dataset by handling null values and duplicates. Future updates will include column cleaning and visual analysis.”
Data Cleaning Script (v1.0)
📘 Description

This Python script is designed to perform basic data cleaning operations on a CSV dataset using Pandas.
It focuses on identifying and handling missing and duplicate data through user input, making it easy to clean datasets even for beginners.

⚙️ Current Features

CSV Input:

The script takes a CSV file link from the user and loads it into a pandas DataFrame.

Null Value Detection:

Checks for missing (NaN) values and displays their count.

Duplicate Detection & Removal:

Detects duplicate rows and removes them automatically.

User-Controlled Null Handling:

The user can choose how to handle null values:

Drop rows containing nulls

Fill missing values with mean, median, or mode

Interactive Command-Line Input:

The script guides users step-by-step with input prompts.

🧾 Upcoming Updates (Planned for v1.1)

🔹 Fixes & Improvements

Ensure the script handles numeric-only columns while using mean/median/mode.

Add exception handling (try-except) for invalid file links or non-numeric columns.

Clean columns containing special characters or unwanted symbols (using regex or .str.replace()).

Add summary statistics (e.g., total rows before and after cleaning).

Save the cleaned data to a new file (cleaned_data.csv).



# 📦 Update: Data Cleaning Script (v1.1)
🆕 What's New in v1.1
This version introduces several enhancements to make your data cleaning workflow smoother and more powerful:
🔹 Column Cleaning with Regex
- Automatically removes special characters from numeric columns.
- Converts cleaned values to float for statistical analysis.
🔹 Summary Statistics
- Displays total rows before and after cleaning.
- Shows column data types and memory usage using df.info() and df.shape.
🔹 Safe File Saving
- Prompts the user for a filename.
- Warns before overwriting an existing file (without using os).
🔹 Improved Exception Handling
- Handles non-numeric columns gracefully during fill operations.
- Catches errors from invalid file paths or malformed data.
💾 How to Use
- Run the script and input your CSV file path.
- Follow the interactive prompts to handle missing and duplicate data.
- Let the script clean numeric columns automatically.
- Save the cleaned dataset with your chosen filename.


📌 Tip
For best results, ensure your numeric columns are stored as strings if they contain symbols (e.g., ₹, %, etc.) so the regex cleaning can process them correctly.

# 💬 Feedback Welcome: If you encounter any errors, issues, or have suggestions for improvement, feel free to open an issue or start a discussion — contributions and feedback are always appreciated!



