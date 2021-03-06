\[\[Category Packet\]\] \[\[Category Packet 718\]\] \[\[Category RS2\]\]

== '''Packet structure''' == ?

== '''Login''' == ?

== '''Game Protocol''' ==

===Server -\> Client Packets===

  {
  ---

! Opcode ! Type ! Length (bytes) ! Name ! Description \|- \| 2 \|
VARIABLE\_SHORT \| -2 \| \[\[718 Friends packet\|Friends packet\]\] \|
Sends a friend to the friend list. \|- \| 5 \| FIXED \| 4 \| \[\[718
Close window\|Close window\]\] \| Closes an interface. \|- \| 6 \| FIXED
\| 1 \| \[\[718 Player under NPC priority\|Player under NPC priority\]\]
\| N/A \|- \| 9 \| FIXED \| 6 \| \[\[718 Music effect\|Music effect\]\]
\| Plays a music effect. \|- \| 10 \| VARIABLE\_BYTE \| -1 \| \[\[718
Set mouse\|Set mouse\]\] \| N/A \|- \| 11 \| FIXED \| -2 \| \[\[718
World list\|World list\]\] \| Sends the world list. \|- \| 14 \| FIXED
\| 23 \| \[\[718 Interface\|Interface\]\] \| Opens an interface. \|- \|
17 \| VARIABLE\_SHORT \| -2 \| \[\[718 Open URL\|Open URL\]\] \| Opens a
hyperlink. \|- \| 20 \| FIXED \| 16 \| \[\[718
Projectile\|Projectile\]\] \| Plays a projectile. \|- \| 23 \| FIXED \|
4 \| \[\[718 Player on IComponent\|Music effect\]\] \| N/A \|- \| 25 \|
FIXED \| 1 \| \[\[718 Run energy\|Run energy\]\] \| Sends the run
energy. \|- \| 30 \| VARIABLE\_BYTE \| -1 \| \[\[718 Send friend quick
chat\|Send friend quick chat\]\] \| Sends a friend a quick chat message.
\|- \| 31 \| FIXED \| 8 \| \[\[718 Model on IComponent\|Model on
IComponent\]\] \| Sends a model to an IComponent (child interface). \|-
\| 32 \| FIXED \| -1 \| \[\[718 Receive friend quick chat\|Receive
friend quick chat\]\] \| Displays a received quick chat message to a
friend. \|- \| 33 \| VARIABLE\_BYTE \| -1 \| \[\[718 Receive personal
message\|Receive personal message\]\] \| Received a private message (PM)
and displays it. \|- \| 39 \| FIXED \| 19 \| \[\[718 Game pane\|Game
pane\]\] \| Sends the game pane. \|- \| 40 \| FIXED \| 12 \| \[\[718
IComponent Settings\|IComponent Settings\]\] \| N/A \|- \| 42 \|
VARIABLE\_SHORT \| -2 \| \[\[718 Load map scene\|Load map scene\]\] \|
Loads a map. \|- \| 44 \| FIXED \| 6 \| \[\[718 Shake camera\|Shake
camera\]\] \| Shakes the camera of the character. \|- \| 45 \| FIXED \|
2 \| \[\[718 Destroy object\|Destroy object\]\] \| Removes an object
from the screen. \|- \| 55 \| VARIABLE\_SHORT \| -2 \| \[\[718
Ignores\|Ignores\]\] \| Sends a player to a player's ignore list. \|-
\|}

===Client -\> Server Packets===

  {
  ---

! Opcode ! Type ! Length (bytes) ! Name ! Description \|- \| 3 \| FIXED
\| 16 \| \[\[718 Item on item\|Item on item\]\] \| Send an item on item
request. \|- \| 4 \| VARIABLE\_BYTE \| -1 \| \[\[718 Add ignore\|Add
ignore\]\] \| Sends a request to add a person to a person's ignore list.
\|- \| 8 \| VARIABLE\_BYTE \| -1 \| \[\[718 Walk\|Walk\]\] \| Sends a
request to walk to specific coordinates. \|- \| 9 \| FIXED \| 3 \|
\[\[718 NPC Examine\|NPC Examine\]\] \| Sends a request to examine an
NPC. \|- \|}
