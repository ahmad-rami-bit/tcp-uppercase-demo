# 🔌 TCP Uppercase Demo

A concise TCP socket programming demo in Python featuring a client-server architecture. The client captures lowercase input from the user and sends it to the server, which responds with the uppercase version. This simple interaction showcases core networking principles using Python's built-in `socket` module.

---

## 📄 Overview

This project demonstrates:
- TCP stream-based communication in Python
- Basic client-server interaction using sockets
- Real-time text transformation over a network

---

## ⚙️ Technologies Used

- **Python 3.x**
- **socket module (standard library)**

No third-party dependencies required.

---

## 🚀 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/ahmad-rami-bit/tcp-uppercase-demo.git
cd tcp-uppercase-demo
```

2. **Start the server**

```bash
python server.py
```

- You'll be prompted to enter the number of clients to support.

3. **Run the client**

```bash
python client.py
```

- Enter any lowercase string when prompted.

---

## 🗂 File Structure

```text
tcp-uppercase-demo/
├── client.py       # TCP client code
├── server.py       # TCP server code
└── README.md       # Project documentation
```

---
