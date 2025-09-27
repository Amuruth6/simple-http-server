# simple-http-server (Python)

This project implements a **basic HTTP/1.0 web server** using Python’s built-in `socket` module.  
It can serve static HTML files from the `htdocs` folder and respond with a simple **404 Not Found** if the file is missing.

## 📂 Project Structure
simple-http-server/
├── htdocs/
│ └── index.html # Sample homepage
├── server.py # Main server code
└── README.md

## ⚡ Features

- Serves static files (e.g., `index.html`)  
- Returns a **404 Not Found** for missing files  
- Built using **Python sockets** (no external dependencies)  
- Minimal and lightweight (great for learning how HTTP works)


## ▶️ How to Run

1. Clone this repository:
   git clone https://github.com/YOUR_GITHUB_USERNAME/simple-http-server.git
   cd simple-http-server
2. Run the server:
   python server.py
3. Open your browser and go to:
   http://127.0.0.1:8000


📜 Example Output

When you visit http://localhost:8000, you’ll see:

🚀 Simple HTTP Server
This page is served using my Python Socket HTTP Server project.

📘 Learning Outcome

By building this project, you’ll learn:

How HTTP requests and responses work

Basics of TCP sockets in Python

Serving files over the web

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss your idea.

⭐ Show Support

If you like this project, please star the repo on GitHub 🌟

Made with ❤️ using Python


👉 Replace `YOUR_GITHUB_USERNAME` with your GitHub username.  
👉 You can add a real screenshot by running your server, opening in a browser, and uploading the screenshot into your repo.  

Would you like me to also suggest a **couple of extra beginner-friendly features** you can add before publishing (like serving CSS/JS, logging requests, etc.) so it looks even stronger on GitHub?
   ub.com/YOUR_GITHUB_USERNAME/simple-http-server.git
   cd simple-http-server
