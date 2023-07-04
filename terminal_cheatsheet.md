# **Terminal Cheatsheet**
## **Overview**

Terminal is a shell in which we can run UNIX commands. Below are various commands that can be used for example; to view, access and create directories/files.

---
> ### **List**

|          |     |
| -------- | :-------|
|Code |Description|
|`ls`| This lists out the contents of the folder. ***Bold** text indicates a folder.*|
|`ls -l`| Gives a detailed list. *Note, this addition of `-l` is an example of adding a flag.*|
|`ls -a`    | Lists all folders. *A "`.`" before a name indicates it is a hidden file/folder*|
|`ls -al`| Gives a detailed list of all folders and files.|
---

>### **Change Directory**

|      |     |
| ---- | :----|
|Code | Description|
| `cd` | Used to change directory/folder. *Note, can hit tab key to see possibly folders tab until desired folder.*|
|`cd -`| Takes you back to the directory that you were previously using.|
|`cd ..` | To change to the directory one up in the tree. *Can use `cd ...` to move two up in a tree etc.*|
|`cd folder_1/folder_1a/folder_1aa`|To change directory to the one at the end of that path.|
---
>### **Create**
|      |     |
| ---- | :---- |
|Code | Description|
|`mkdir folder_name`|Make directory/folder.| 
|`touch`|To create a new file. *Eg,`touch my_file.txt` creates a text file.*|
---
>### **Open**
|      |     |
| ---- | :---- |
|`open file_name` | Opens file or can also open folder. *Ensure to add file extension.*|
|`open .`| Opens the current directory we are using.|
|`code file_name`| Opens the file is VSCode editor.|
|`code .`| Opens the current directory and its files in VSCode editor.|
---
>### **Move and Rename**
|      |     |
| ---- | ----|
|Code | Description|
|`mv file_name new_file_name `| Can use to rename or move a file into a different folder.|
|`mv file_name ..`|Moves file to parent directory/folder.|
|`mv file_name ~/`| Moves file to directory. *Hit tab key for possible folders.*|
---
>### **Remove**
|      |     |
| ---- | ----|
|Code | Description|
|`rm file_name`| Removes file.|
|`rm -r folder_name`| Deletes every thing in folder.||
|`rm -rf`| Force deletes.|
---
>### **Other**
- `pwd` - *print working directory*. Allows us to see the current folder in use by displaying the folder path.
- `cp file_name folder_name` - *Copying*. Can make a copy of the file (*provide path if file is not in current directory that is in use.*) then put the directory/folder name, i.e then location we want to copy it into. 
    - `cp -r` - If wanting to copy an entire directory, use `-r` flag.

---
## ***Shortcuts***

**Clear screen** - CTRL + L or type `clear`.

**Quit** - To exit to 'main' terminal page press the q character on keyboard. *May occur when using git log and the page indicates* (END).

---