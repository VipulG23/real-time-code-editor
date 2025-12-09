🚀 Real-Time Collaborative Code Editor

React • Node.js • Socket.IO • Monaco Editor • WebSockets

A full-stack, real-time collaborative coding platform that allows multiple users to edit, share, and execute code together inside live rooms. Built with a modern tech stack and optimized for low-latency performance.

✨ Features
🔥 Real-Time Collaboration

Multiple users can edit the same file simultaneously.

Bi-directional sync powered by Socket.IO + WebSockets.

Low latency updates with conflict-free merging.

🧑‍💻 VS Code–Like Editor (Monaco)

Syntax highlighting

Autocompletion

Multi-language support

Error markers & IntelliSense-like experience

🏠 Live Rooms

Create or join live coding rooms

Session-based collaboration

Each room maintains its own code state dynamically

⚙️ In-Browser Code Execution

Run code instantly

View output without leaving the editor

Supports multiple languages (based on implemented backend executors)

🌐 Modern UI/UX

Fast, responsive, minimal design

Optimized for both solo coding and collaborative work

🛠 Tech Stack
Frontend

React.js

Monaco Editor

Socket.IO Client

WebSockets

Backend

Node.js

Express

Socket.IO Server

📦 Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/collaborative-code-editor.git
cd collaborative-code-editor

2️⃣ Install dependencies

Frontend

cd client
npm install


Backend

cd server
npm install

3️⃣ Start development servers

Backend

npm run dev


Frontend

npm start

🧩 How It Works (High-Level Architecture)

Monaco Editor captures user code changes.

Socket.IO sends changes to the server using WebSockets.

Server broadcasts updates to all users in the same room.

Each client's editor updates instantly, maintaining real-time sync.

Code execution requests are sent to the backend for safe processing.

Output is returned and displayed inside the editor.

📸 Screenshots (Optional)

Add your UI screenshots here if available.

🌍 Live Demo

🔗 Hosted Link: https://real-time-code-editor-2-0n6h.onrender.com/
🔗 GitHub Repo: https://github.com/VipulG23/real-time-code-editor

🤝 Contributing

Contributions are welcome!
Feel free to open issues and submit pull requests.

📄 License

This project is licensed under the MIT License.
