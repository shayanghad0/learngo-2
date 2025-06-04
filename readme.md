# 📄 Go JSON Parser

A beginner-friendly CLI tool in Go that reads and parses a .json file, then prints structured data to the terminal.

- 🎯 Part of the die <= learn Go => master journey.
 
- 🧠 What It Does

- 📥 Loads a JSON file

- 🧩 Parses the data into a Go struct

- 🖨️ Prints out each field

📁 Example Input (data.json)
```
{
  "name": "Shayan",
  "age": 23,
  "skills": ["Go", "Python", "JS"],
  "active": true
}
```
## 🚀 Getting Started

1. Clone the Repo
```
git clone https://github.com/shayanghad0/go-task2
cd go-json-parser
```
2. Add a data.json file

Create a JSON file like the one above.

3. Run the app
```
go run main.go
```
💻 Output
```
✅ Parsed JSON Data:
Name: Shayan
Age: 23
Skills: [Go Python JS]
Active: true
```
## 🛠️ Technologies Used

- Go (encoding/json)

- Structs with JSON tags

- Basic file I/O

## 🧰 Learning Goals

- Read files from disk

- Map JSON to Go structs

- Handle errors cleanly

- Practice idiomatic Go

## 🧠 Part of...
>📘 die <= learn Go => master

## 📜 License
> MIT — free to use, learn, remix.