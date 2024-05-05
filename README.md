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
mkdir %userprofile%\Desktop\MyLab

![image](https://github.com/blessingjeffrey/Windows-basic-commands-batchscript/assets/149134943/32c920a7-7544-4309-8bca-bc923b599573)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
![image](https://github.com/blessingjeffrey/Windows-basic-commands-batchscript/assets/149134943/576abe6b-bacb-4654-b04d-4c09ab7328f9)
![image](https://github.com/blessingjeffrey/Windows-basic-commands-batchscript/assets/149134943/af683e0c-6dd0-49b9-aa83-0c873f8fcbdf)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
![image](https://github.com/blessingjeffrey/Windows-basic-commands-batchscript/assets/149134943/aa5fe7ab-4017-41c2-80d6-4bebcdc623a8)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![image](https://github.com/blessingjeffrey/Windows-basic-commands-batchscript/assets/149134943/a951cd38-1347-4db0-a58d-e40b25f548b0)
![image](https://github.com/blessingjeffrey/Windows-basic-commands-batchscript/assets/149134943/8ba8abac-350b-4813-be85-683556d205fc)


## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents
![image](https://github.com/blessingjeffrey/Windows-basic-commands-batchscript/assets/149134943/22dc9633-728c-4a4d-9c42-45b6fcbd8878)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!




## OUTPUT
![image](https://github.com/blessingjeffrey/Windows-basic-commands-batchscript/assets/149134943/6e89bcb4-b5a5-491a-adbf-0394b1327256)

## RESULT:

The commands/batch files are executed successfully.









