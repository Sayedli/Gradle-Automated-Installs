# Gradle-Automated-Installs
Automation scripts to silently install common UW applications using Gradle. Includes support for OpenJDK, PyCharm Pro, Eclipse, Firefox ESR, Chrome, Microsoft Office 2021, MATLAB, Notepad++, Git, and more. Simplifies setup with pre-installation checks and error handling. Perfect for UW environments!


=====================
Build Scripts for UW Apps
===================

This repository contains Gradle build scripts to automate the silent installation of common UW applications. These scripts are designed to make setup simple, efficient, and error-free.

-----------------
Pre-requisites
-----------------
1. **Gradle Installed**: Ensure Gradle is installed on your system and is accessible via the command line.
   - Download Gradle: https://gradle.org/install/
   - Verify installation: `gradle -v`

2. **Java JDK Installed**: Gradle requires Java to run.
   - Install a JDK (e.g., OpenJDK): https://openjdk.org/
   - Verify installation: `java -version`

3. **PowerShell**: PowerShell is used for executing installation commands.

4. **Installer Files**: Place the required installer files in the respective directories as specified in the build scripts.

-----------------
Included Apps
-----------------
1. **OpenJDK**
2. **PyCharm Pro**
3. **Cygwin GCC**
4. **Eclipse & Eclipse CDT**
5. **Firefox ESR**
6. **Google Chrome**
7. **Microsoft Office 2021**
8. **Notepad++**
9. **Git**
10. **MATLAB (Network Installation)**

-----------------
Usage Instructions
-----------------
1. Clone or download this repository:

2. Navigate to the folder containing the specific build script for the app you want to install.

3. Place the required installer file(s) in the project directory:
- Example: `Firefox Setup <version>.exe` for Firefox.

4. Open a terminal in the folder and run:
- Replace `<task_name>` with the desired task. For example:
  - `installFirefox` for Mozilla Firefox.
  - `installChrome` for Google Chrome.

5. The script will:
- Check if the app is already installed.
- Perform a silent installation if not installed.
- Provide error messages if anything goes wrong.

-----------------
Example Commands
-----------------
gradle installmsOffice- To install Microsoft Office:

gradle installnpp - To install Notepad++:

gradle installgit- To install Git:


-----------------
Notes
-----------------
- Ensure the installer file names match those specified in the build scripts.
- You can modify the scripts to change default installation directories or settings.
- For troubleshooting, enable debug mode using:


-----------------
Author
-----------------
- **Sayed Ali**
-----------------

===================================
Thank you for using the UW Apps Installer!
===================================


