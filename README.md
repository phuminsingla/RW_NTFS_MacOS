# Read and Write NTFS for Mac

Compatibility : Big Sur, Monterey, Ventura, Sonoma for CPU x64

## Install brew on terminal

How to Install Homebrew on Mac by EasyOSX
https://www.youtube.com/watch?v=IWJKRmFLn-g

### Step 1

![Screenshot 2566-10-09 at 07 17 47](https://github.com/phuminsingla/RW_NTFS_MacOS/assets/5608098/2c37f66f-846e-4a56-94cb-1fc2057dcc3f)

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```


### Step 2

```
brew tap gromgit/homebrew-fuse
```

```
brew install --cask macfuse
```

```
brew install ntfs-3g-mac 
```

### Step 3

Download NTFS-ReadWrite.dmg

-----------------------------------------

### Usage.

Open NTFS-ReadWrite.dmg and copy to Apptications.

Allow apps downloaded from NTFS-ReadWrite

![Screen Shot 2566-10-09 at 14 03 24](https://github.com/phuminsingla/RW_NTFS_MacOS/assets/5608098/38b3ee8c-4a0f-401f-ab7c-47502a076d40)

<img width="268" alt="Screenshot 2567-01-04 at 19 33 53" src="https://github.com/phuminsingla/RW_NTFS_MacOS/assets/5608098/1b21dce6-70fe-40a1-b0b9-42bedcce02c6">

-----------------------------------------


### Troubleshoot.
Find disk name on terminal

```
diskutil list
```

demo disk name is disk2s1

<img width="1063" alt="Screenshot 2567-01-02 at 16 54 32" src="https://github.com/phuminsingla/RW_NTFS_MacOS/assets/5608098/6308a569-e412-43f4-9262-0d5b750da3a6">


```
sudo ntfsfix /dev/disk2s1
```

![414470440_1521246378655647_5916290364917890632_n](https://github.com/phuminsingla/RW_NTFS_MacOS/assets/5608098/259ecbc1-d581-49d4-beb1-f1d5fc81e5f0)

-----------------------------------------

### Add program on Login Items

<img width="485" alt="Screenshot 2567-01-02 at 18 13 08" src="https://github.com/phuminsingla/RW_NTFS_MacOS/assets/5608098/ce985fe2-ac6d-4b6e-995a-d23fe9702037">

-----------------------------------------

## Credits
<ul>
	<li>[EasyOSX](https://www.youtube.com/@EasyOSX)</li>
	<li>[Homebrew](https://brew.sh/)</li>
	<li>[Tuxera ntfs-3g](https://www.tuxera.com/company/open-source/)</li>
</ul>
