# pkg-merge
A tool to merge parts of a PS4 PKG into one entire PKG file. Useful for installing a full game on your system. Written in C++.

# Usage
## User-friendly
1. Download the lastest release from the [Release Page](https://github.com/Tustin/pkg-merge/releases)
1. Extract pkg-merge.exe
1. Go to where you extracted pkg-merge.exe, and locate/create a folder with all your PKG pieces inside.
1. Drag the folder of PKG files ontop of the pkg-merge.exe program. The merging process should begin.

## Development
1. Clone the repo
1. Open project using Visual Studio (I used VS 2017 Community with the C++ build tools installed)
1. Build and run


## Merge PS4 pkg files in Linux

1.You can merge the pkg files by copying the merge.sh and pkg-merge-x64.exe to the folder containing the pkg files.

2.Then open the terminal then type this command:

```
chmod +x merge.sh
```

3.After that open the terminal in the folder containing the pkg files and the merge.sh and pkg-merge-x64.exe and type the following command:

```
./merge.sh
```

4.When the merging will be complete, the terminal will say the following:

```
Package Merger has completed the task. You can now close the terminal.
```

5.You will see a file named "merged.pkg". This is your final merged file.
