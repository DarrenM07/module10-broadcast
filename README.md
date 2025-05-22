# Advanced Programming Module 10 - Broadcast Chat
### Darren Marcello Sidabutar - 2306256293

> How it runs

![Run](images/ss1.png)
![Run](images/ss2.png)
![Run](images/ss3.png)
![Run](images/ss4.png)
Whenever a client sends a message, it first reaches the server. The server then forwards that message to every connected client, including the one who sent it. This is made possible by the server maintaining a list of current connections and actively listening for new messages to relay.