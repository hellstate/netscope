# netscope
NetScope is a simple and useful tool for viewing network information on Linux (Ubuntu).

How to run:
Download or clone the repository.
Open a terminal in the project folder.
Make the executable file runnable (if needed):
```chmod +x NetScope```

Run the program:
```./NetScope```

Viewing the application icon:
The program sets a window icon when running.
To see an icon in the file manager or desktop, create a ``.desktop`` file:
```[Desktop Entry]
Name=NetScope
Comment=Network Information Tool
Exec=/full/path/to/NetScope
Icon=/full/path/to/images/icon.png
Terminal=false
Type=Application
Categories=Utility;```

Make it executable:
```chmod +x NetScope.desktop```

Now the program will show the icon when launched from the file manager or menu.
