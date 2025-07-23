
# A basic FIM
FIM (short for File Integrity Monitor) is a tool that monitors a host’s local system for changes to specified files, directories, and registry settings to detect illicit modifications. In this basic FIM, it accomplishes its task by calculating file hashes and storing them in a baseline, then the monitoring starts by verifying that the current file state hash is equal to the one stored in our trusted baseline.


### Python


### Executing the script : 

#### Python
Open terminal 
```shell
python3 path/to/script.py
```

#### Powershell
##### On Windows
open powershell and type
```shell
cd path/to/script
./script.ps1
```
##### On linux and MacOS
```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
```shell
brew install --cask powershell
```
```shell
$ pwsh
cd  path/to/script
./script.ps1
```

#### Bash
##### On linux or MacOS
```shell
$ sh /path/to/script
```
or
```shell 
$ cd /directory/with/script
$ ./executable
#----------------
$ chmod +x script     # only required if your file is not already executable
```
##### On Windows 10
Execute Shell Script file same as on a linux based system using WSL (Windows Subsystem for Linux) or by installing a linux virtual machine.





## Contributing
Pull requests are welcome. Feel free to take the code and make it your own, expand on it and put it in your portfolio, while mentioning the original authors.

