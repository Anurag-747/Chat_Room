
# Chat Room 

This Python-based chat application enables real-time communication between users through a central server. It features user authentication, admin privileges (kick/ban commands), and a system to manage banned users, ensuring secure and controlled interactions.



## Features of the Chat Room:

- Real-time Communication: Users can send and receive messages instantly.
- Admin Privileges: Admin can kick or ban users from the chat room.
- User Authentication: Admin login requires a password for verification.
- Ban List: Permanently ban users by adding their nickname to a ban list.
- Dynamic User Interaction: Displays join/leave messages for all users.
- Kick Users: Admin can remove disruptive users from the chat room.
- Simple Interface: Easy-to-use for both admins and regular users.




## Requirements

- Python 3.x (with socket and threading modules, both included in standard Python libraries)
- A text editor or IDE (e.g., VS Code, PyCharm, Sublime Text)





    
## Run Locally

1. Clone the project

```bash
  git clone https://github.com/Anurag-747/Chat_Room.git
```

2. Go to the project directory

```bash
  cd Chat_Room
```

3. Run the Server:

```bash
  python server.py
```
4. Run the Client:

```bash
  python client.py
```
5. You can open additional terminals and run the client script (client.py) in each to simulate multiple users joining the chat.



