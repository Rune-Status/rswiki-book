\[\[Category Packet\]\] \[\[Category Packet 377\]\]
{{packet\|name=Initialize Player\|description=Sends the player's
membership status and their current index on the server's player
list.\|opcode=249\|type=Fixed\|length=3\|revision=377}} == Initialize
Player ==

=== Description === Sends the player's membership status and their
current index on the server's player list.

=== Packet Structure ===

{\| border=2 ! Data type ! Description \|- \| Unsigned \[\[Data
Types\#Standard data types\|Byte\]\] \| Membership flag (1 = member, 0 =
free). \|- \| Unsigned \[\[Data Types\#Little Endian\|Little Endian\]\]
\[\[Data Types\#Standard data types\|Short\]\] \| Player list index. \|-
\|}
