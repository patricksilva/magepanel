# ![Alt text](http://s23.postimg.org/t7m6upgzb/magepanel.png) MagePanel #

This project is a web-based user interface for [Magallanes Project](http://magephp.com/).

Enjoy!

![Alt text](http://s30.postimg.org/ugokqktlt/Main_Page.png)

*(Requires [Node](http://nodejs.org/) v0.10.2 or newer)*

## Prerequisites ##

- For Debian Based Linux (Ubuntu, ...):
```bash
>> sudo apt-get install php5-cli
```
- For RedHat Based Linux (CentOS, ...):
```bash
>> sudo yum install php-cli
```
Rest of the requirements will be automatically installed with installers provided..

## Installers (Latest - v1.1) ##

- [![alt text](http://s11.postimg.org/w7biouren/windows.png) Windows Installer](https://github.com/erincinci/magepanel/releases/download/v1.1/MagePanelSetup-v1.1.exe)
- [![alt text](http://s11.postimg.org/hzlu07epr/deb.png) Linux DEB Package](https://github.com/erincinci/magepanel/releases/download/v1.1/magepanel-v1.1.deb)
- [![alt text](http://s11.postimg.org/cmwzm2qtb/rpm.png) Linux RPM Package](https://github.com/erincinci/magepanel/releases/download/v1.1/magepanel-v1.1.i386.rpm)
- [![alt text](http://s13.postimg.org/9oskv0dnn/mac.png) Mac OS X Package](https://github.com/erincinci/magepanel/releases/download/v1.1/MagePanel-v1.1.pkg)
 
## Running Magallanes on Cygwin (Windows) ##

* Install **cygwin** *(Will be automatically installed with MagePanel Windows Installer)* → [**Here**](https://cygwin.com/install.html)
* Download & Extract latest **Magallanes** release → [**Here**](https://github.com/andres-montanez/Magallanes/releases/latest)
* Download & Setup your keys in **Putty Pageant** → [**Here**](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html)
* Download & Copy **ssh-pageant** binary in cygwin `/usr/bin/` directory as described → [**Here**](https://github.com/cuviper/ssh-pageant)
* Start **cygwin** and change dir to extracted **Magallanes** `bin/` dir → *ex:* `cd /cygdrive/c/Downloads/magallanes/bin/`
* Run commands →
```bash
>> ./mage compile
>> cp mage.phar /usr/bin/mage
>> chmod +x /usr/bin/mage
```
* Run `mage version` command on **cygwin** to test if **Magallanes** is working correctly

## Starting Application from Source ##

```bash
>> git clone https://github.com/erincinci/magepanel.git MagePanel
>> cd MagePanel

# On Unix
>> ./run.sh

# On Windows
>> run.bat
```
