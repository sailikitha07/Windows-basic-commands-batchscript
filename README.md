# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

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
Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

COMMAND AND OUTPUT
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it. %userprofile%\Desktop\MyLab
<img width="842" height="52" alt="Screenshot 2025-10-19 113801" src="https://github.com/user-attachments/assets/938ffaf1-4793-45a0-86b3-c4e8c508e5b4" />


COMMAND AND OUTPUT
List the contents of the "MyLab" directory.

%userprofile%\Desktop\MyLab 
<img width="835" height="53" alt="Screenshot 2025-10-19 113838" src="https://github.com/user-attachments/assets/e82678a0-418e-46e4-839e-33178292c665" />
<img width="962" height="57" alt="Screenshot 2025-10-19 113844" src="https://github.com/user-attachments/assets/663a8328-cb0f-4cb8-9967-6fbd087ccfa8" />

COMMAND AND OUTPUT
Copy "MyFile.txt" to a new folder named "Backup" on the desktop. %userprofile%\Desktop\MyLab 
<img width="843" height="76" alt="Screenshot 2025-10-19 113931" src="https://github.com/user-attachments/assets/80858a9f-0039-4f63-b77c-1492f39a6275" />


COMMAND AND OUTPUT
Move the "MyLab" directory to the "Documents" folder. mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup 
<img width="1033" height="45" alt="Screenshot 2025-10-19 114001" src="https://github.com/user-attachments/assets/dbb7218a-d388-4545-8faf-fcc584d80e70" />
<img width="1029" height="55" alt="Screenshot 2025-10-19 114014" src="https://github.com/user-attachments/assets/35f68afe-e17b-4c34-a2c0-ecb4a8ad1699" />


COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents 
<img width="1018" height="48" alt="Screenshot 2025-10-19 114102" src="https://github.com/user-attachments/assets/bfad6970-0558-4c20-9c92-7e018ab352f0" />


Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!

OUTPUT
image
<img width="885" height="85" alt="Screenshot 2025-10-19 114109" src="https://github.com/user-attachments/assets/0211a770-b403-48f4-9add-81293dc0cf99" />

# RESULT:
The commands/batch files are executed successfully.

