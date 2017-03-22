# iOSDylib

yololib 可执行文件 要被注入的.dylib

optool install -c load -p "@executable_path/要被注入的.dylib" -t 可执行文件

Thanks To
------
[KJCracks / yololib](https://github.com/KJCracks/yololib): dylib injector for mach-o binaries.

[alexzielenski / optool](https://github.com/alexzielenski/optool): optool is a tool which interfaces with MachO binaries in order to insert/remove load commands, strip code signatures, resign, and remove aslr. Below is its help.
