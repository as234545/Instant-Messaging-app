# Java Instant Messaging application

Introduction: 
------------------
This project is designed and implemented based on instant messaging system, including both the client and the server.
The server is responsible fir managing the state of both clients and conversations.
A conversation is an interactive text-exchange session between some number of clinets and is the ultimate purpose of the IM system.

Key features:
------------------
- Each client can be able to join the Group Messenger chat, create a private chat, and leave any chat.  
-	Each client can see which users currently logged in.  
-	Incoming messages are displayed immediately.  
-	Server can be able to maintain an unlimited number of open client connections.   
-	One client can send a private chat to another client  
-	One client can have multiple private chat with each user  

How to use:
------------------
1- After downloading and unzipping the file, open the java files in NetBeans.  
2- In line 18 in the TcpClient.java file put the server ip address.  
3- first run the TcpServer.java file then the TcpClient.java file.  
4- new you should have a IM application runing.  

contain:
------------------
ChatDialog.java  
TcpServer.java  
TcpClient.java  
