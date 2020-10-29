
To check if you have Java installed on a Windows PC, search in the start bar for Java or type the following in Command Prompt (cmd.exe):

***`C:\Users\_Your Name_>java -version`***

***If Java is installed, you will see something like this (depending on version):***

    java version "11.0.1" 2018-10-16 LTS   Java(TM) SE Runtime Environment
    18.9 (build 11.0.1+13-LTS)   Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.1+13-LTS, mixed mode)

If you do not have Java installed on your computer, you can download it for free at [oracle.com](https://www.oracle.com/technetwork/java/javase/overview/index.html).

## Setup for Windows

To install Java on Windows:

1.  Go to "System Properties" (Can be found on Control Panel > System and Security > System > Advanced System Settings)

2.  Click on the "Environment variables" button under the "Advanced" tab

3.  Then, select the "Path" variable in System variables and click on the "Edit" button

4.  Click on the "New" button and add the path where Java is installed, followed by  **\bin**. By default, Java is installed in C:\Program Files\Java\jdk-11.0.1 (If nothing else was specified when you installed it). In that case, You will have to add a new path with:  **C:\Program Files\Java\jdk-11.0.1\bin**  

  

>   ***Then, click "OK", and save the settings***

    
6.  At last, open Command Prompt (cmd.exe) and type  **java -version**  to see if Java is running on your machine
