# netscope
NetScope is a simple and useful tool for viewing network information on Linux (Ubuntu).
<img width="480" height="270" alt="splashscreen from NetScope" src="https://github.com/user-attachments/assets/57843324-f2ab-424c-9dff-e10808fdaf68" />

How to run:
Download or clone the repository.
Open a terminal in the project folder.
Make the executable file runnable (if needed):
```bash
chmod +x NetScope
```

Run the program:
```bash
./NetScope
```

Viewing the application icon:
The program sets a window icon when running.
To see an icon in the file manager or desktop, create a ``.desktop`` file:
```bash
[Desktop Entry]
Name=NetScope
Comment=Network Information Tool
Exec=/full/path/to/NetScope
Icon=/full/path/to/images/icon.png
Terminal=false
Type=Application
Categories=Utility;
```

Make it executable:
```bash
chmod +x NetScope.desktop
```

Now the program will show the icon when launched from the file manager or menu.
