# Intel i586 Boards Arduino IDE Package Index

The official <https://downloads.arduino.cc/packages/package_index.json> sadly points to now dead URLs, which makes it non-installable anymore.

This repository has a fixed package index that you can point to, to successfully install Intel Galileo ("Intel i586 Boards") board support.

Just add this URL to File -> Preferences -> Additional board manager URLs:
```
https://raw.githubusercontent.com/maxgerhardt/arduino-Intel-i586-revive/refs/heads/main/package_index.json
```

Then search for "[REVIVED] Intel i586 Boards" in your board manager.