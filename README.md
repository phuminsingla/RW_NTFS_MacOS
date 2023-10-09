# NTFS Re Write for MacOS

<h2 data-sourcepos="1:1-1:25" id="user-content-ntfs-re-write-for-macos" dir="auto" class="vicinity rich-diff-level-zero"><a class="heading-link rich-diff-level-one" href="/phuminsingla/RW_NTFS_MacOS/blob/main/README.md#ntfs-re-write-for-macos">Install brew on shell commands<svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></h2>

How to Install Homebrew on Mac
https://www.youtube.com/watch?v=IWJKRmFLn-g

##Step 1

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"



##Step 2

brew tap gromgit/homebrew-fuse

brew install --cask macfuse

brew install ntfs-3g-mac 


##Step 3

chmod +x rwntfs

chmod +x install

-----------------------------------------

##Usage.

./rwntfs


-----------------------------------------

##Automation on Status.

./install

Enable terminal 
-> System Settings
  -> Privacy & Security
     -> Developer Tools
     -> Allow Terminal

Reboot System.

![Screenshot 2566-10-09 at 06 41 00](https://github.com/phuminsingla/RW_NTFS_MacOS/assets/5608098/ad8260f7-64fc-468b-93f1-b2c2b3a160a2)
