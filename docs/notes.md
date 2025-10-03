# **Notes**
This is a section full of tiny notes about different things that come up with frc programming 


## **VS Code Errors**
Often you may get an error where vs code says libraries or classes are missing when the code compiles just fine. To fix this delete the .gradle and build folders and then close and reopen WPILib vscode. This should refresh the gradle cache meaning that when the java language server restarts it will be able to recognize the new classes or libraries.