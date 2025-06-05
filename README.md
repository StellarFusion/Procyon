<p align="center">
  <img src="Procyon.svg" width="200" alt="Procyon Logo"/>
</p>

# Procyon  
###### v1.0.0  

Procyon is a lightweight programming language developed specifically for the Raspberry Pi Pico. It is designed for both beginners and advanced users, offering a simple and intuitive syntax for rapid development.
---

### 🌟 Features:

✅ Syntax highlighting  
✅ Supports all Raspberry Pi Pico Models  
✅ File icon support in the Explorer  
✅ Lightweight and easy to use  
✅ File extension: `.pcy`

---

### 🟠 Requirements:

- Download the firmware files (`procyon_core.mpy`, `config.txt`, and `main.py`) from the GitHub repository (link below).  
- Install the **MicroPico** extension by Paulober in VS Code.  
- Open the Command Palette (`Cmd+Shift+P` on macOS or `Ctrl+Shift+P` on Windows).  
- Run the command:

~~~
MicroPico: Initialize MicroPico Project
~~~

- Connect your Raspberry Pi Pico; its status will appear in the VS Code status bar.  
- Click **Toggle Mpy FS** in the status bar to open the Pico's file system (Mpy Remote Workspace).  
- Upload the downloaded firmware files (`procyon_core.mpy`, `config.txt`, and `main.py`) by dragging and dropping them into the Pico file system.

---

### 🟡 Usage:

1️⃣ In the Pico's Mpy Remote Workspace, create a new file with the `.pcy` extension (e.g., `test.pcy`).  
2️⃣ Write your Procyon code inside the `.pcy` file and save it.  
3️⃣ Open `config.txt` in the Pico's file system and enter the filename of the `.pcy` script you want to run (e.g., `test.pcy`).  
4️⃣ Save and close `config.txt`.  
5️⃣ Open main.py and click Run in the VS Code window to start executing your .pcy script.
6️⃣ You can have multiple `.pcy` files on the Pico. Update `config.txt` with the desired filename to switch scripts.

---

### 📌 Known Issues

- No known issues at this time.

---

### 📝 Release Notes

#### v1.0.0
- Initial release.  
- Added language grammar and icon support for `.pcy` files.  
- Integrated with MicroPico VS Code extension for seamless file system access.  
- Included core firmware files to simplify setup.  
- Supports multiple `.pcy` files with easy script switching through `config.txt`.
---
### Download Contents
- Package for download of the .zip files contains:
~~~
   3x Firmware files:
   procyon_core.mpy
   main.py
   config.txt
~~~
~~~
   3x Example Files:
   E01-Blink.pcy
   E02-Brightness.pcy
   E03-AnalogBlinkWithMath.pcy
~~~
- Package for download of the .rtf files contains:
~~~
  1x Procyon Language Contents.rtf
  -This file has the function of each code block.
~~~
---
### 🛠️ Developed by Santosh Andiappa Thaneermalai  
   © 2025 StellarFusion. All rights reserved.

-----
Feel free to contribute or report issues via GitHub Issues.  
Happy coding with Procyon! 🚀

**Full Changelog**: https://github.com/StellarFusion/Procyon/commits/V1.0.0
