# COMM-LINE 💬

COMM-LINE is a peer-to-peer terminal-based chat application written in Python. It allows multiple users to connect over a local network and chat in real-time, all through the command line. Built with simplicity and minimal dependencies, it’s perfect for LAN-based messaging or experimenting with socket programming.

---

## 🚀 Features

- 🧵 **Multi-threaded Server**: Handles multiple incoming connections concurrently using threads.
- 🔌 **Peer-to-Peer Communication**: Uses TCP sockets for direct messaging between peers.
- 🧭 **Built-in Commands**:
  - `connect <ip> [port]`: Connect to another peer.
  - `peers`: View currently connected peers.
  - `quit`: Gracefully exit the application.
- 🌐 **Auto IP Detection**: Automatically shows your local IP when launching the app.

---

## 🛠️ Requirements

- Python 3.6 or higher

### Python Libraries

Install required dependencies using:

```bash
pip install -r requirements.txt
```

## USAGE

# Start the chat server

```bash
    python chat.py --name YourName
```

# Connect to peer (Found after entering the program above)

```bash
    connect <ip>
```

# Also Autoconnect via 

```bash 
    python chat.py --name Name --peer <ip>
```
