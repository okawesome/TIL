[ Steps for installing GO CD Agent ]

1. Install JAVA 8 JDK

    1.1 Install JAVA
  
    1.2 Set system environment variable(JAVA_HOME, Path)
  
2. Connect remote repository

    2.1 Install git
  
    2.2 Set git remote repository, config (user.name, user.email)
  
    2.3 Generate ssh key 
  
        2.3.1 Input instructions on commandline ($ssh-keygen -t rsa -b 4096 -C "test@gmail.com")
      
        2.3.2 Copy public key from id_rsa.pub file 
      
        2.3.3 Paste key to ssh keysettings of user account on remote repository (e.q Git lab)
      
    2.4 Check to work 'git clone' successfully on commandline
  
3. Install Go Agent

    3.1 Start to install Go Agent on default setting
  
    3.2 Input Go Agent Server url (e.q https://[ip]:[port]/go) (port is 8154 or 8153)
  
    3.3 Reboot
  
4. Run job on Go Agent
  
    4.1 Login Go Server
    
    4.2 Open Agent tab
    
    4.3 Find your ip address (If it's not exist, Wait a few minutes.)
    
    4.4 Check go agent and Click Enable button (only admin user can see that button)
    
    4.5 Set running environment by clicking Envrionment button
    
