# Commands

- `/nm <name>` - get a name, else, anonymous user
- `/join <room-name>` - join a room, if room doesn't exitst, a new room is created. User can only be in one room at a time
- `/rooms` - get the list of rooms
- `/msg <msg>` - send message to everyone in the room
- `/quit` - exit the room/chat server

# Starting the server
- run the build file: ./tcp-chat
- open two new terminals and run: telnet localhost port where port is the port which the server started running on e.g. telnet localhost 8000

Credit to Alex Pliutau for the video which inspired this project