# iOS Runtime device log capture in windows
This package includes a BAT file and associated libraries that enable you to extract and view iOS device runtime logs on a Windows computer. With this tool, you can access and analyze logs for debugging purposes directly on your Windows machine, eliminating the need for third-party applications.

# Pre-Conditions 
Install iTunes latest version

# Steps to be followed
1. Extract the Zip file to a folder and go to iOS_Live_Log_Capture folder
2. Create a shortcut for Apple (windows batch file) and move it to desktop
3. Create a shortcut for iOS_Logs folder and move it to desktop
4. Connect iPhone to PC 
5. Go to desktop and double click on Apple shortcut file from step 2 to run it
6. Press enter to capture iOS logs and reproduce the issue
7. close the command window to stop capturing the log
8. The log file will be saved in iOS_Logs folder from step 3

Disclaimer: This script was not created or owned by me. I found it to be an efficient tool for saving time and space during my testing process. I believe many others will find it equally beneficial and helpful in their work.
