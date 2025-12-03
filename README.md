File Transfer System using Python Sockets

This project demonstrates a basic yet effective file transfer system built using Python socket programming. It enables a client to send files over a TCP network to a server, which receives and securely stores the transferred data.

🏷️ Badges
| Category | Badge                                                                              |
| -------- | ---------------------------------------------------------------------------------- |
| Language | ![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)                      |
| Platform | ![Socket Programming](https://img.shields.io/badge/Network-TCP%20Socket-green.svg) |
| Status   | ![Working](https://img.shields.io/badge/Status-Active-success.svg)                 |

🚀 Features

Sends filename, file size, and file data using TCP

Server auto-saves received files

Demonstrates core networking, socket communication, and file handling in Python

Lightweight and easy to set up

📌 How It Works

The server script starts listening for connections

The client selects a file

File metadata + file content is transmitted in chunks

Server writes data to a new file locally

📂 File Structure
📁 File-Transfer-System
│── File_server.py   → Server-side script
│── File_client.py   → Client-side script

▶️ Execution Guide
On Server:
python File_server.py

On Client:
python File_client.py


Enter the file name when prompted.
Make sure the server IP in client script is updated before running.

📎 Requirements

Python 3.x installed

Both scripts running in the same network (or publicly reachable server IP)

👩‍💻 Author

Krithika S
