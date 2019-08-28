Clipboard Image Auto Saver is a Python script which monitors the Windows' clipboard and automatically saves images from there.

## Usage
1. Install required packages using package manager [pip](https://pip.pypa.io/en/stable/)
```bash
pip install pillow pywin32 win10toast
```
2. Run the clipboard_img_auto_saver.bat file. The batch file is provided to launch the python script in background.
3. Add shortcut to clipboard_img_auto_saver.bat in C:\Users\\<your user>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup. Windows will start script automatically on Windows load.

## Contributing
Please open an issue first to discuss what you would like to change.
