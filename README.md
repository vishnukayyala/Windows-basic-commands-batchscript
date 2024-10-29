# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

## Name: VISHNU KM
## Reg.NO.: 212223240185

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
```
mkdir %userprofile%\Desktop\MyLab
```

![OS9](https://github.com/user-attachments/assets/31698066-eee1-4d09-bec7-cd0a77b5d580)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

```
cd %userprofile%\Desktop\MyLab
```

![OS10](https://github.com/user-attachments/assets/836d3d12-c77b-4554-8a56-4df08e3755fb)
![OS11](https://github.com/user-attachments/assets/8e121b0a-58ff-4b7e-b114-0001cdc7bf89)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

```
dir %userprofile%\Desktop\MyLab
```

![OS12](https://github.com/user-attachments/assets/43a04033-1393-4b8a-adf2-0a37948ceb10)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

```
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup
```

![OS13](https://github.com/user-attachments/assets/97089ff1-4fd8-4665-8411-5d4b27ff9705)
![OS14](https://github.com/user-attachments/assets/9a2f1db7-c4e7-4bbf-835a-f1bedad1c14b)


## COMMAND AND OUTPUT

```
mv Myfile.txt %userprofile%\Documents
```

![OS15](https://github.com/user-attachments/assets/e103f131-3864-43ca-b883-7298a3c3a21f)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
```

echo Backup completed successfully!



## OUTPUT
![OS16](https://github.com/user-attachments/assets/9f08c7c6-8952-40b2-9382-992cdb85650e)

## RESULT:

The commands/batch files are executed successfully.









