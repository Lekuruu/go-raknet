# go-raknet

> [!NOTE]
> This is a fork of sandertv's raknet implementation, with some small modifications
> to fit our needs. Please don't use this, unless you know what you are doing!

go-raknet is a library that implements a basic version of the RakNet protocol, which is used for
Minecraft (Bedrock Edition). It implements Unreliable, Reliable and 
ReliableOrdered packets and sends user packets as ReliableOrdered.

go-raknet attempts to abstract away direct interaction with RakNet, and provides simple to use, idiomatic Go
API used to listen for connections or connect to servers.
