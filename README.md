# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript
# REGISTER NO:212224230203
# NAME:P.PRAMISHA

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\MyLab
```
![image](https://github.com/user-attachments/assets/3fdf9f2b-5c7b-420f-964f-0527d8057fd7)
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.



## COMMAND AND OUTPUT
```
cd %userprofile%\Desktop\MyLab
```
![image](https://github.com/user-attachments/assets/fcbb2216-07e6-4e16-88ac-ea689a413ab2)

type nul > MyFile.txt
![image](https://github.com/user-attachments/assets/9c8372e4-0d09-4967-a905-da831189b98c)
List the contents of the "MyLab" directory.

## COMMAND AND OUTPUT
```
dir %userprofile%\Desktop\MyLab
```
![image](https://github.com/user-attachments/assets/ff659ad4-b86e-4ea4-8dc1-1fd370791d98)
Copy "MyFile.txt" to a new folder named "Backup" on the desktop

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Backup
```
![image](https://github.com/user-attachments/assets/0d913e0d-9c80-4e49-95e2-6079bf3a229d)
copy MyFile.txt %userprofile%\Desktop\Backup
![image](https://github.com/user-attachments/assets/bac455b5-24f7-474b-9230-96249870e958)
Move the "MyLab" directory to the "Documents" folder.
## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Documents
```
move MyLab Documents
![image](https://github.com/user-attachments/assets/c20f2780-e63e-474b-aa36-dfde7c4f9657)


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
## OUTPUT
![image](https://github.com/user-attachments/assets/96397cb4-c6f3-4143-9e02-361dfc520cfc)
## COMMAND
```
  @echo off
  mkdir %userprofile%\Desktop\DocBackup
  copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
  del %userprofile%\Documents\*.docx
  echo Backup and deletion completed successfully!
  ```

## OUTPUT
![image](https://github.com/user-attachments/assets/10b2ebb3-eb02-4b22-baad-1978425d9a61)



# RESULT:
The commands/batch files are executed successfully.

