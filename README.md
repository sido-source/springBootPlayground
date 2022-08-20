# springBootPlayground

List of all subjects:
1) how to consume rest services
2) how to consume soap services
3) how to build api gateway
4) how to build load balancing
5) Queues
6) Annotation




#1How to start:
Install Java. In order to fully install and configure local environment follow these steps:
  - download and install jdk (Java SE Development Kit )
  - add global path for java


setting java path: 
  windowds: 
    1) Search in the searching box "advanced system settings"
    2) click"environment variables"
    3) set in "System variables" section new record:
        {
          variableName: JAVA_HOME,
          variableValue: C:\Program Files\Java\jdk17.0 // path where the JDK folder is saved 
        }
    4) Click "Path" in system variables section and add create new record %JAVA_HOME%\bin 
    Test:  echo $JAVA_HOME in cmd
    
  linux:
    1) In terminal paste this command: sudo nano /etc/environment
    2) Replace the value (JAVA_HOME = path where JDK bin is installed)
    TEst:  echo $JAVA_HOME in terminal
    
        
 
