# Unix-like-commands-list
Work in progress  
A collection of counterpart commands for Linux and macOS.

|**Description**|**Linux**|**macOS**|
-----------|------|-----|
|Launch daemons and services|systemctl|launchctl|
|Print shared objects (shared libraries)|ldd |otool -L|
|Spotlight search|find / -iname|mdfind -name|
|List hardware information|lshw|system_profiler|
|List USB interface info|lsusb -v|ioreg -p IOUSB -l -w 0|
|Show local IPs|ip addr show|ifconfig \| grep inet|
|Show external IP|curl ifconfig.me|curl ifconfig.me|
|Open file or URL|xdg-open|open|
|List Access Control List (ACL) for a folder/file|getfacl|ls -le|
|Set ACL for a folder/file|setfacl|chmod +a|
