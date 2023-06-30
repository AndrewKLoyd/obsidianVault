Is mechanism for serializing data but faster and smaller than XML.
That's a good way to serialize data for future sharing it via different types of  [[Connection]].

Simple method to make a Google proto buffer into a byte[] message in C#

![[Pasted image 20221123134621.png]]
Where grp - is a builded [[.proto message]] into C#
stream - is a buildin type into Google proto [[Nuget]]
pubSock - [[NetMQ(ZeroMQ)]] [[Connection]]

Use "dotnet add package Google.Protobuf --version 3.21.9" to download or https://www.nuget.org/packages/Google.Protobuf/