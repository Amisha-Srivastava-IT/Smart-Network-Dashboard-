#🚀 Smart Network Dashboard

A visually rich real-time network simulation dashboard that mimics a Network Operations Center (NOC). It dynamically visualizes multiple clients connected to a central server, showing latency, bandwidth, CPU load, and live data flow.


---

📌 Features

🖥️ Real-Time Network Simulation

Simulates multiple clients connected to a server

Dynamic updates every second using randomized metrics

Tracks:

Download speed

Upload speed

Latency

Data usage



🌐 Interactive Network Topology

Canvas-based visualization

Animated data packets flowing between server and clients

Click on any client to view detailed metrics

Hover interactions for better UX


📊 Live Charts (Powered by Chart.js)

Download Speed graph

Upload Speed graph

Average Latency graph

30-second rolling data window


🧠 Smart Alerts System

Real-time alerts for:

High latency

Low bandwidth

Client disconnections

Server overload


Categorized as:

✅ Normal

⚠ Warning

❌ Critical



🖥️ Server Monitoring Panel

CPU Load meter

Bandwidth usage

Memory usage

Dynamic color indicators for overload


👥 Client Management

Add/remove clients dynamically

Max 10 clients supported

Client health indicators (good/warning/bad)

Detailed popup with:

IP Address

MAC Address

Speed stats

Data usage



⚙️ Network Conditions Simulation

Simulate different environments:

🟢 Normal

🟡 Slow Network

🔴 Server Overload



---

🛠️ Tech Stack

HTML5

CSS3 (Custom Dark UI Theme)

Vanilla JavaScript

Canvas API

Chart.js



---

📂 Project Structure

smart-network-dashboard/
│
├── index.html   # Main application (HTML + CSS + JS)
└── README.md    # Project documentation


---

▶️ How to Run

1. Clone the repository:



git clone https://github.com/your-username/smart-network-dashboard.git

2. Open the project folder:git clone https://github.com/your-username/smart-network-dashboard.git



cd smart-network-dashboard

3. Run the 

🎮 How It Works

•Each client is an object with network properties.
•A simulation loop (setInterval)updates data every second.
•Metrics change using arandom walk algorithm for realism.

•Canvas renders:

○Nodes (clients + server)

○Connections

○Animated data packets


•Charts update in real-time using historical buffers.



---

📸 Preview

> (Add screenshots or GIFs here for better GitHub visibility)




---

💡 Use Cases

Learning networking concepts visually

Hackathon MVP demos

UI/UX portfolio projects

Simulation-based dashboards

Educational tools



---

🚧 Future Improvements

Backend integration (real network data)

Authentication system

Dark/Light theme toggle

Export logs & analytics

Mobile responsiveness improvements

WebSocket-based real-time updates



---

🤝 Contributing

Contributions are welcome!

1. Fork the repo


2. Create a new branch


3. Make your changes


4. Submit a pull request




---

📜 License

This project is open-source and available under the MIT License.


---


