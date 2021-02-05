# GetAllIssuesPj

This program get all issues from a project and store fields in a Excel file

![alt text](https://github.com/guihen01/GetAllIssuesPj/blob/main/Doc/Capture-Excel.PNG "Logo Title Text 1")

# Publication

Package Will be distributed as a nuget package. 

# How it was developed

1. Coded in C#
2. application portable  (Target Runtime : portable) Will run in Windows  or in Linux 
2. Developed with Visual Studio 2019
3. Exist also as a method , routine : GetAllIssuesPj() included in a C# library ( form : .DLL) JiraLib 
   See ( https://www.nuget.org/packages/RestAPI-JIRA-Lib/) 

# How to use (Method 1)

1. Dowwnload in github  the latest version of the exec ( : https://github.com/guihen01/GetAllIssuesPj/releases/download/JIRAIssues/GetAllIssuesPj.zip
2. Unpack (unzip) the latest version file : GetAllIssuesPj.zip in the directory you want , on your computer.
3. in the directory unpacked, execute the application (execute the below file :  ) 

https://github.com/guihen01/GetAllIssuesPj/blob/main/Doc/Capture-How-To-Run.PNG
![alt text](https://github.com/guihen01/GetAllIssuesPj/blob/main/Doc/Capture-How-To-Run.PNG "Logo Title Text 1")

4. PAy attention to your antivirus and/or firewall ,it could block the execution on the exec. So if it occurs 
change config of firewall or antivirus to allow execution

# How to use (Method 2)

1. Download the nuget package at : https://www.nuget.org/packages/JIRA.GetAll.IssuesInPj/
2. USe Visual Studio or tool that use Nuget 
2. in your c# code use the method GetAllIssuesPj()

# Console output (What is displayed on your console screen) : 

https://github.com/guihen01/GetAllIssuesPj/blob/main/Doc/Capture-console-output.PNG
![alt text]( https://github.com/guihen01/GetAllIssuesPj/blob/main/Doc/Capture-console-output.PNG "Logo Title Text 1")
