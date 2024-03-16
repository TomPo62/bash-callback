# Navigation 🗺️

Welcome to the "Navigation" section of the **Bash Callback** repository. This guide is intended to help users master the art of moving between folders and accessing files within a **Linux** system using the **Bash** terminal. Efficient navigation is a foundational skill for anyone working in a **Unix-like** environment, enabling users to quickly and effectively manage their file system.

## Basic Commands for Navigation

### pwd - Print Working Directory

Before you start moving around, it's important to know where you are. The `pwd` command displays your current directory (the directory you're currently in).
```
pwd
```

### cd - Change Directory

The `cd` (change directory) command is used to move between directories.

  - **To go to your home directory:**
    ```
    cd
    ```

  - **To navigate into a specific directory:**
    ```
    cd /path/to/directory
    ```

  - **To move up one directory (to the parent directory):**
    ```
    cd ..
    ```

  - **To go back to the previous directory:**
    ```
    cd -
    ```

### ls - List Directory Contents

The `ls` command lists the contents of directories. By default, it lists the contents of the current directory.

  - **To list files in the current directory:**
    ```
    ls
    ```

  - **To list files in a specific directory:**
    ```
    ls /path/to/directory
    ```

  - For more details on `ls` and its options, refer to the [Listing section](../Listing/README.md) of this repository.

## Advanced Navigation Techniques

### Tab Completion

Tab completion is a powerful feature of the **Bash** terminal that saves time and reduces typos. By pressing the Tab key while typing a command, **Bash** automatically completes file names, commands, and directory names.

### Wildcards

Wildcards are characters that enable you to select file names based on patterns. The most common wildcards are `*` (matches any number of characters) and `?` (matches any single character).

  - **To list all .txt files in the current directory:**
    ```
    ls *.txt
    ```

### pushd and popd - Stacking Directories

The `pushd` and `popd` commands allow you to work with a stack of directories for easy navigation.

  - **Use `pushd` to change the directory and save the current one:**
    ```
    pushd /path/to/new/directory
    ```

  - **Use popd to return to the last directory saved:**
    ```
    popd
    ```

## Tips for Efficient Navigation

  - **Remember your home:** Your home directory (`~`) is your base of operations. Knowing how to quickly return to it (`cd ~` or simply `cd`) can save time.
  - **Use absolute and relative paths wisely:** Understand the difference between absolute paths (which start from the root directory, `/`) and relative paths (which are relative to the current directory).
  - `Organize your files:` Keeping your files and directories organized in a logical structure makes navigation much easier.

## Conclusion

Mastering navigation commands in **Bash** is crucial for anyone who uses **Linux** or **Unix-like** systems. These commands and techniques provide the foundation for efficient file system management, allowing you to move seamlessly between directories, access files quickly, and work more productively in the terminal.

Remember, practice is key to becoming proficient in navigating your system's file structure. Happy navigating!
