# 🔥 Go REST API with Firebase Auth

This project is a RESTful API built in Go (Golang) that integrates with Firebase using its REST API. It handles user authentication (sign-up/sign-in) and basic protected endpoints.

## 🚀 Features

- User Sign Up with Firebase
- User Sign In and Token Retrieval
- Protected Route using Firebase ID Token Verification
- Written in Go using native net/http
- Firebase Integration via REST API (not Admin SDK)

## 🧰 Tech Stack

- Go 1.21+
- Firebase Authentication (via REST API)
- Gorilla Mux (or native `net/http`)
- HTTP client (`net/http`)

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/your-username/go-firebase-api.git
cd go-firebase-api

# Initialize go module
go mod init github.com/your-username/go-firebase-api
go mod tidy
