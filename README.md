# JavaPrograms
# Various Java program solutions for the following graduate courses at Eastern Kentucky University
# Other programming languages may be included, e.g., c, C++, Python, HTML, Shell Script, Batch Scripts, ..., et cetera.
# Course Listings:
# Computer Science 730 Data Structures and Algorithms
# Computer Science 815 Computer Admin and Security
# Computer Science 736 Incident Response I
# Computer Science 737 Incident Response II
# More courses may be inlcuded in the future.
# Personal Java projects for various programming problems.

# How to compile Java in Unix / Linux
```
javac -d classes/ -cp lib/sample-1.jar src/project/Example.java -verbose -Xlint:unchecked

jar --create --file lib/sample-2.jar -C classes/ .
```
# How to run Java Unix / Linux
```
java -cp lib/sample-2.jar:lib/sample-1.jar project.Example > output.txt
```

# How to run Java in Windows
```
java -cp lib/sample-2.jar;lib/sample-1.jar project.Example > output.txt
```

# Requirements
```
JDK 17+
JRE 17+
```

# install Java in Windows visit
```
https://docs.oracle.com/en/java/javase/18/install/installation-jdk-microsoft-windows-platforms.html#GUID-DAF345BA-B3E7-4CF2-B87A-B6662D691840
```

# Update Path Variable in Windows (Access javac, jar, and java commands)
```
Option 1. 
Open the System Properties and add the paths with the javac, jar, and java executables to your PATH environment variable.
Go to Settings >> System >> About >>  Advanced system settings >> Environment Variables >> System Variables >> Path >> Edit >> New 
copy the paths, e.g., C:\Program Files\Java\jdk-18.0.2.1\bin, into here. Also, consider adding the JAVA_HOME variable to your System Variables while you are in this menu.
Under System Variables select New. In the variable name, type JAVA_HOME (or JRE_HOME for JRE installations). In Variable Value, copy and paste the filepath of your Java installation as shown above,
e.g., "C:\Program Files\Java\jdk-18.0.2.1" or "C:\Program Files\Java\jdk-20". 


Option 2. Excute PATH command. Copy the return string (should have a list of paths semi-colon delimited). Append path to JDK binary and library directors separated by a semi-colon, e.g., 

user> PATH
PATH=C:\Program Files\Common Files\Oracle\Java\javapath;C:\cygwin64\bin

user> PATH C:\Program Files\Common Files\Oracle\Java\javapath;C:\cygwin64\bin;C:\Program Files\Java\jdk-18.0.2.1\lib;C:\Program Files\Java\jdk-18.0.2.1\bin

user> PATH
PATH=C:\Program Files\Common Files\Oracle\Java\javapath;C:\cygwin64\bin;C:\Program Files\Java\jdk-18.0.2.1\lib;C:\Program Files\Java\jdk-18.0.2.1\bin
```

# Maven JUnit (Third Party Package) Repository
```
https://mvnrepository.com/artifact/junit/junit/4.13.2
```

# Adding Maven JUnit 4.13.2 (Third Party Package) Repo to your environment (Example API Call to Download Repo File(s))
```
curl -s https://repo1.maven.org/maven2/junit/junit/4.13.2/junit-4.13.2.jar -o C:/JUnit/Junit-4.12.jar
```

# Add JUnit unit testing framework to your Windows Java Development Environment
```
To add the JUNIT_HOME variable to your System Variables while you are in this menu.
Under System Variables select New. In the variable name, type JUNIT_HOME. In Variable Value, copy and paste the filepath of your Java installation as shown above,
e.g., "C:\JUnit". 
```

# How to compile in Windows (back slash)
```
javac -d classes/ -cp lib\sample-1.jar src\project\Example.java -verbose -Xlint:unchecked
jar --create --file lib\sample-2.jar -C classes/ .
```

# How to run in Windows (semi-colon)
```
java -cp lib\sample-2.jar;lib\sample-1.jar project.Example > output.txt
```

# Maven JSON Simple 1.1.1 (Third Party Package) Repo Example
```
https://repo1.maven.org/maven2/com/googlecode/json-simple/json-simple/1.1.1/json-simple-1.1.1.jar
```

# Adding Maven JSON Simple 1.1.1 (Third Party Package) Repo to your lib directory (Example API Call to Download Repo File(s))
```
curl -s https://repo1.maven.org/maven2/com/googlecode/json-simple/json-simple/1.1.1/json-simple-1.1.1.jar -o lib\json-simple.jar
```

# Coindesk BTC API endpoint (Example API Call to retrieve JSON payload)
```
https://api.coindesk.com/v1/bpi/currentprice.json
```

# Sending a Request to Coindesk BTC API endpoint and saving the returned payload
```
curl -# -o api_payload.json https://api.coindesk.com/v1/bpi/currentprice.json
```

# Maven JSON Simple (Third Party Package) Repo
```
https://mvnrepository.com/artifact/com.googlecode.json-simple/json-simple/1.1.1
```

# Oracle JDK 18.0.2 Installer
```
https://www.oracle.com/java/technologies/downloads/#jdk18-windows
```

# Oracle JDK 18.0.2 Installer Tutorial
```
https://docs.oracle.com/en/java/javase/18/install/installation-jdk-microsoft-windows-platforms.html#GUID-DAF345BA-B3E7-4CF2-B87A-B6662D691840
```

# Cygwin Get that Linux feeling - on Windows
```
https://www.cygwin.com/
```

# Check if you have Linux commands on your Windows machine
```
Open CMD and type the command, e.g., ls or vim
If it exists, use where to see where it lives, e.g., where ls or where nano
If it does not exist, you will need to install something like Gitbash or CygWin
```

# Install Java (Linux, Ubuntu 20.04)
```
sudo apt update
sudo apt upgrade
sudo apt install openjdk-17-jdk openjdk-17-jre
```

# How to compile in Ubuntu (forward slash)
```
javac -d classes/ -cp lib/sample-1.jar src/project/Example.java -verbose -Xlint:unchecked
jar --create --file lib/sample-2.jar -C classes/ .
```

# How to run in Ubuntu (colon)
```
java -cp lib/sample-2.jar:lib/sample-1.jar project.Example > output.txt
```

