# Task 1: Basic Network Scanning with Nmap

## 🎯 Objective
To perform a basic network scan on my own system (localhost) using Nmap, and identify open ports and the services running on them.

## 🛠 Tools Used
- Nmap version 7.97
- Windows 10

## 💻 Command Used
  nmap -sV localhost


## 📊 Scan Results

- **Port 135** – Open – Microsoft RPC  
  (Used by Windows for Remote Procedure Calls)

- **Port 445** – Open – Microsoft-DS  
  (Used for file sharing and network access in Windows)

- **Port 3306** – Open – MySQL 8.0.40  
  (Used by the MySQL database server)

## ✅ Conclusion
The scan was successful. I identified 3 open ports with services running. These findings show how Nmap helps in detecting potential entry points in a system.

## 🖼 Screenshot
I have attached a screenshot of the Nmap scan output in my submission.
