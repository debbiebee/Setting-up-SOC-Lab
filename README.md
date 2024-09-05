# Setting-up-SOC-Lab
<p><img src="https://miro.medium.com/v2/resize:fit:828/format:webp/1*QNZJefs6QrE4lm7TdFofYQ.jpeg" alt="SOC Architecture" width="300px" /></p>
I started with setting up a home lab environment for SOC operations.


# My SOC Architecture with Integrated C2 Server
My first task is creating a Logical Diagram for My SOC Lab. To get started, I’m working on setting up my home SOC lab with the following key components:

Here are the elements that makes up the architecture:

📍 Fleet Servers: These are a set of servers that allow for the centralized management of endpoint agents across the network. They collect logs and other data from endpoints and send them back to a central location, enabling continuous monitoring of security events and potential threats.

📍Ubuntu Server (SSH Enabled): This is a Linux-based server that I’ll connect to securely using SSH (Secure Shell). It will act as a crucial part of the lab, allowing me to run commands remotely, manage logs, and simulate various attack scenarios in a safe environment.

📍Windows Server (RDP Enabled): A Windows-based server that I’ll access via RDP (Remote Desktop Protocol). This server will allow me to simulate environments that are often targeted by attackers. RDP will help me securely manage and monitor the server, mimicking real-world IT infrastructures.

📍Elastic & Kibana: For log analysis and visualization, these tools will help me track and analyze security events in real-time, offering valuable insights to respond quickly to incidents.

📍Ticket Server: A system for managing incidents, it will help in keeping track of alerts, tasks, and resolution steps during the SOC workflow.

📍C2 Server: A Command and Control (C2) server to simulate adversary actions, which helps to mimic how attackers manage compromised machines remotely, allowing me to practice defense strategies.

# For more contents:
You can check out MYDFIR video on creating logical diagram here <https://www.youtube.com/watch?v=VAE3aVZi0Go>
