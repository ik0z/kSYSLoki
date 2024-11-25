# kSYSLoki
kSYSLoki is a secure logging server designed to receive and store logs over a secure TLS connection. This project demonstrates how to establish a secure TCP connection using a TLS certificate, receive log messages 
from clients, and store these logs in organized files. It is developed for cybersecurity and system monitoring purposes.


### Requirements

* .NET Runtime: .NET 6.0 or later.
* TLS Certificate: A .pfx file with a private key for TLS authentication.
* Permissions: Ensure the application has write access to the logs directory.

### Usage 

#### Console based :
- Download the compressed file from the link: [Download](https://github.com/ik0z/kSYSLoki/archive/refs/heads/main.zip)
- To create a new certificate, run ```cert_generation.exe``` with administrator privileges and optionally enter a password to generate the certificate.
- Run the server ```kSYSLoki.exe``` and enter the password you selected for the certificate.
- Copy the ```kSYSAgent.exe``` file to the Loki folder along with its dependencies, and ensure you have added the required information.

#### GUI Based 
- All you need is to download the graphical user interface version provided in ```kSYSLoki GUI.zip```
![alt text](https://github.com/ik0z/kSYSLoki/blob/main/GUI.png?raw=true)


### Author
######   Khaled Alshammri | VAPT 
