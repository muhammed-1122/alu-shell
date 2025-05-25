# alu-shell Basics

This repository contains shell scripts that perform basic Linux command line tasks.

## Scripts

- **0-current_working_directory**  
  Prints the absolute path of the current working directory.

- **1-listit**  
  Lists the contents of the current directory.

- **2-bring_me_home**  
  Changes the working directory to the user’s home directory without using shell variables.

- **3-listfiles**  
  Lists the contents of the current directory in long format.

- **4-listmorefiles**  
  Lists all files including hidden ones in long format.

- **5-listfilesdigitonly**  
  Lists all files including hidden ones in long format with numeric user and group IDs.

- **6-firstdirectory**  
  Creates a directory named `my_first_directory` in `/tmp/`.

- **7-movethatfile**  
  Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory`.

- **8-firstdelete**  
  Deletes the file `betty` from `/tmp/my_first_directory`.

- **9-firstdirdeletion**  
  Deletes the directory `my_first_directory` from `/tmp/`.

- **10-back**  
  Changes the working directory to the previous one.

- **11-lists**  
  Lists all files (including hidden) in the current directory, its parent, and `/boot` in long format.

- **12-file_type**  
  Prints the type of the file named `iamafile` located in `/tmp/`.

- **13-symbolic_link**  
  Creates a symbolic link named `__ls__` to `/bin/ls` in the current directory.

- **14-copy_html**  
  Copies `.html` files from the current directory to its parent, only if they are new or updated.

- **15-lets_move**  
  Moves all files starting with an uppercase letter to `/tmp/u`.

- **16-clean_emacs**  
  Deletes all files in the current directory ending with `~`.

- **17-tree**  
  Creates nested directories: `welcome/`, `welcome/to/`, and `welcome/to/school` in the current directory.

---

All scripts are located in the `basics` directory.


