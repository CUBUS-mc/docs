
CUBUS is a collection of interacting projects about Minecraft.
It gathers and analyses data from Mc servers and players. It also controls headless clients to do things on servers.  CUBUS also offers a watch list to get notified about updates about a server or player 

### __Structure__: 
[[CUBUS Structure.canvas|CUBUS Structure]] (This is a simplified diagram without middle managers)

The most important components are:
- The [[Queen.md|Queen]] that acts like a C2 server
- [[Security.md|Security]] that is responsible for authenticating everything and convey messages between the [[Queen.md|Queen]] and the [[API]]
- The [[Database.canvas|Database]] that stores everything
- The [[API]] that can be contacted directly or by other components
- The [[CubusMod]] that can be installed into Minecraft
- The [[Discord Bot]]
- The [[Website.md|Website]]
- And the [[Drones.canvas|Drones]]
All components except the drones are hosted by @virus-rpi. Drones are hosted by users.

The drones are specialized for specific tasks:
- The [[Minecraft Proxy]] drones are responsible for allowing players to join on Mc Servers through CUBUS while keeping clients secure, offering some features and enforcing the anti-greef-policy
- The [[SpaceInvader]] drones
-  The [[MPI]] drones are headless MC clients that can be uses by other drones or components

### __Out-lawed servers:__
Servers that are offensive and/or illegal can be reported at CUBUS. Than  drone will visit it and take screenshots of the reported area as well as download the chunks. A human moderator will than look at the recorded data and can declare the server as out-law. Out-lawed servers are not greef protected anymore in the problematic areas.


[[Terms of Service|Terms of Service]]