📡 Static Routing Project

This project demonstrates how to configure static routing on Cisco routers. It’s designed for beginners who want to learn the basics of routing and how devices communicate in a network.
🗂️ Project Contents

    .pkt file — the Cisco Packet Tracer project file.

    README.md — this file.


✅ Requirements

    Cisco Packet Tracer (recommended)
    Download Cisco Packet Tracer — You need a free Cisco Networking Academy account.


🛠️ How to Run the Project
1️⃣ Install Cisco Packet Tracer

    Go to Cisco NetAcad.

    Create a free account if you don’t have one.

    Download and install Packet Tracer for your operating system.

    Open Packet Tracer and sign in.

2️⃣ Open the Project

    Clone or download this repository:

    git clone https://github.com/Fiki1910/static-routing.git

    or download it as a ZIP and extract it.

    Open Cisco Packet Tracer.

    Click File > Open and select the .pkt file from this project.

3️⃣ Run the Simulation

    The network topology will appear.

    Click on any router to open its CLI (Command Line Interface).

    If not pre-configured, follow the instructions in the .pkt file or your instructor’s guide to enter static routes.

🧩 Example Static Route Command

Here’s an example of how you add a static route on a Cisco router:

Router> enable
Router# configure terminal
Router(config)# ip route [destination_network] [subnet_mask] [next_hop_ip]

For example:

ip route 192.168.2.0 255.255.255.0 192.168.1.2

This tells the router how to reach the 192.168.2.0 network via the next hop 192.168.1.2.
🕵️‍♂️ How to Test It

    Use the ping command:

    Router# ping [destination_ip]

    Watch the packets flow using the simulation mode in Packet Tracer.

