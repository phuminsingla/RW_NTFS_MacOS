# NTFS Re Write for MacOS

## Install brew on terminal

How to Install Homebrew on Mac by EasyOSX
https://www.youtube.com/watch?v=IWJKRmFLn-g

### Step 1

![Screenshot 2566-10-09 at 07 17 47](https://github.com/phuminsingla/RW_NTFS_MacOS/assets/5608098/2c37f66f-846e-4a56-94cb-1fc2057dcc3f)


/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"



### Step 2

brew tap gromgit/homebrew-fuse

brew install --cask macfuse

brew install ntfs-3g-mac 


### Step 3

chmod +x rwntfs

chmod +x install

-----------------------------------------

### Usage.

./rwntfs


-----------------------------------------

## Run script as startup.

./install

Enable terminal 
-> System Settings
  -> Privacy & Security
     -> Developer Tools
     -> Allow Terminal

Reboot System.

![Screenshot 2566-10-09 at 07 17 01](https://github.com/phuminsingla/RW_NTFS_MacOS/assets/5608098/3c8d62bb-a498-4a65-82a3-a8b72b7e1b9d)


## Credits
<ul>
	<li>[EasyOSX](https://www.youtube.com/@EasyOSX)</li>
	<li>[Homebrew](https://brew.sh/)</li>
	<li>[Tuxera ntfs-3g](https://www.tuxera.com/company/open-source/)</li>
</ul>
