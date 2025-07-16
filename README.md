# 🔧 Py to EXE Converter (Auto Builder)

This is a simple Python script that helps you convert `.py` files into `.exe` executables using [PyInstaller](https://pyinstaller.org/). It supports optional icon integration and handles interruptions and errors gracefully.

---

## 📦 Features

- Automatically installs PyInstaller if not already installed
- Converts Python files to `.exe`
- Optional `.ico` file support for custom icons
- Works on **Windows**, **Linux**, and **macOS** terminals
- Handles keyboard interruptions and clears the terminal
- Color-coded terminal messages using `colorama`

---

## 🚀 How to Use

### 1. ✅ Requirements

Make sure you have Python installed. This script will install PyInstaller automatically if it's missing.

You can run the script like this:

```bash
python py_to_exe.py

2. 🧾 Script Prompts

You'll be prompted to enter:

    The name of the Python file (e.g., main.py)

    Whether you want to include a logo/icon (Y/N)

        If "Y", it will ask for the .ico file path

The script then runs PyInstaller and creates the .exe in the dist/ folder.
3. ⚙️ Output

Your .exe file will appear in the dist folder, located in the same directory.
❗ Example

Enter File Name: main.py
Is there a logo? (Y/N): Y
Icon Name: icon.ico
Py to Exe completed successfully!

💻 Clean Exit on Ctrl+C

If you hit Ctrl + C, the script will display a countdown and exit cleanly.
📁 File Structure

📂 your-folder/
├── py_to_exe.py
├── your_script.py
├── icon.ico (optional)
└── dist/
    └── your_script.exe

🧠 Notes

    Make sure the .ico file is in the same directory or provide a full path.

    Only .ico files are supported by PyInstaller for icons.

    This script is designed for educational and personal use.

🔓 License

This project is licensed under the MIT License.
🧑‍💻 Author

Made by Semih — follow for more tools and projects!

GitHub: https://github.com/Simit6155
Instagram: @redsimit
