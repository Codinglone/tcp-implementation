# 🔌 sockets.c

A tiny C program that talks directly to Google's servers via raw sockets to fetch HTTP headers like a real hacker. 🧑‍💻

## 🧠 What it does
This little beast:
- Opens a TCP socket 🧵  
- Connects to `www.google.com` via IP 📡  
- Sends a `HEAD /` HTTP request 📝  
- Prints the raw HTTP headers returned by the server 📬

## ⚙️ Compile & Run

```bash
gcc sockets.c -o sockets
./sockets



Let me know if you'd like a version with syntax-highlighted C code snippet, badges, or a longer description!
