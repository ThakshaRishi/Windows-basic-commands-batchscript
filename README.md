# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

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




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

![image](https://github.com/user-attachments/assets/f4787abc-2849-43ca-8c7b-3c231d7fc598)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

![image](https://github.com/user-attachments/assets/47c6ff1e-2f78-4b25-8130-cb0cfb1c7663)

![image](https://github.com/user-attachments/assets/c1f09dd7-9c3c-4a70-92b6-2ed7704684c3)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

![image](https://github.com/user-attachments/assets/b0bb0052-7b64-400a-a103-0ee945a6d6e0)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

![image](https://github.com/user-attachments/assets/09930074-e1fe-49dc-b3f0-68706083cdb9)
![image](https://github.com/user-attachments/assets/b8877290-0e3b-4101-a53e-64c47f2628b7)


## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents
![image](https://github.com/user-attachments/assets/a0446cb1-8a32-4c2e-8f4b-019063c8860c)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.



@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!



## OUTPUT

![image](https://github.com/user-attachments/assets/c8076a89-03b3-4531-919d-54b829bfda06)





# RESULT:
The commands/batch files are executed successfully.

