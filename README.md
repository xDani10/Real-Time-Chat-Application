# 🧠 Go WebSocket Chat Server

A simple real-time chat server implemented in Go using the Gorilla WebSocket package. This project demonstrates how to manage multiple WebSocket clients and broadcast messages between them.

## 🚀 Features

- Real-time messaging using WebSockets
- Multiple clients support
- Simple message broadcasting
- Clean and minimal server logic
- Fully concurrent with goroutines and mutex locking

## 📦 Requirements

- [Go](https://golang.org/dl/) 1.18+
- [Gorilla WebSocket](https://github.com/gorilla/websocket)

Install the Gorilla WebSocket package if not already:

```bash
go get github.com/gorilla/websocket
