
## Server DB

This is a SQL DB that stores active servers. Every entry contains:
- UID
- IP
- Port
- Online Players (Name + UUID)
- Max Players
- Version
- Description
- Plugins
- Mods
- Type (e.g. SMP)
- Whitelist (enabled or not)
- Ping
- Last time it was scanned
- Country
- RCom port usable
- RCom password
- Other open ports
- CVEs on Server
- Hostname
- ID to world save
- ID to screen shots
- Chat history
- A list of out-lawed areas 

## Player DB

This is a NoSQL DB that stores players. Every entry contains
- UUID
- CUBUS UUID
- Server history
- Activity chart
- Chat history
- ID to Skin
- Username
- Username history


## Cache

This is a DB for temporary data.


## Messenger

This is a RabbitMQ and/or Redis DB for messaging between components and drones