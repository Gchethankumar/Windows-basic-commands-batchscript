# Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:
Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:
Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.

### Step 3:
Execute the necessary commands/batch file for the desired output. 

#### Developed by: G Chethan Kumar
#### Register no.: 212222240022
# WINDOWS COMMANDS:

## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

## COMMAND
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
```
mkdir %userprofile%\Desktop\MyLab
cd %userprofile%\Desktop\MyLab
type nul > MyFile.txt
```
## OUTPUT:
![osimg3](https://github.com/Gchethankumar/Windows-basic-commands-batchscript/assets/118348224/3069e613-fc02-4a55-b8f1-5f6afbcb7289)

## COMMAND
List the contents of the "MyLab" directory.
```
dir %userprofile%\Desktop\MyLab
```
## Output:
![osimg4](https://github.com/Gchethankumar/Windows-basic-commands-batchscript/assets/118348224/714cd7f7-7d18-49c8-9b8a-eec448f7dada)

## COMMAND

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
Move the "MyLab" directory to the "Documents" folder.
```
mkdir %userprofile%\Desktop\Backup
copy MyFile.txt %userprofile%\Desktop\Backup
```
## OUTPUT
![osimg5](https://github.com/Gchethankumar/Windows-basic-commands-batchscript/assets/118348224/c03c7bab-af52-4560-8bb1-c239e6ecb0e0)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup

```
## OUTPUT:
![osimg6](https://github.com/Gchethankumar/Windows-basic-commands-batchscript/assets/118348224/f6941b27-3ab2-4ffc-8265-ddf7c007d2b4)


```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx

```
## OUTPUT:
![osimg7](https://github.com/Gchethankumar/Windows-basic-commands-batchscript/assets/118348224/5dd66088-b7a9-4763-ad55-e00517efe9bf)


# RESULT:
The commands/batch files are executed successfully.

