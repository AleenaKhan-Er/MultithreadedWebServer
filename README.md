# 🌐 Multithreaded Java Webserver

This project demonstrates a **basic web server** built using Java, supporting multiple client connections through different threading models:

- 🔁 **Single-Threaded**
- 🧵 **Multi-Threaded**
- 🧶 **Thread Pool-Based**

> Ideal for learning how socket programming and multithreading work in Java.

---

## 📁 Project Structure

Webserver/
├── SingleThreaded/ # Server handling one client at a time
├── MultiThreaded/ # Server creates a new thread for each client
├── ThreadPool/ # Server uses a thread pool for managing clients
├── Client.java # Java client to connect to any server
└── .gitignore

---

## 🚀 Features

✅ Basic HTTP-style server-client communication  
✅ Multithreaded architecture using Java's threading APIs  
✅ Demonstrates `Socket`, `ServerSocket`, `Thread`, `ExecutorService`  
✅ Modular structure for easy learning and experimentation

---

## 🧪 How to Run

### 1. Compile and Run the Server

````bash
cd Webserver/SingleThreaded  # or MultiThreaded, ThreadPool
javac Server.java
java Server
cd Webserver
javac Client.java
java Client

🔧 Requirements
Java 8 or higher

Terminal or VS Code

📚 Topics Covered
Java Sockets (Socket, ServerSocket)

Multithreading

Thread Pools (ExecutorService)

I/O Streams (BufferedReader, PrintWriter)


✍️ Author
Aleena Khan
📫 GitHub

---

## ✅ How to Add This to Your GitHub

### Option 1: VS Code

1. Create a new file: `README.md` inside your repo folder.
2. Paste the content above.
3. Save the file.
4. Push changes:

```bash
git add README.md
git commit -m "Add README file"
git push

Option 2: Use GitHub Web Editor
Click "Add a README" on GitHub (where your screenshot shows).

Paste the content above.

Click Commit changes.
````
