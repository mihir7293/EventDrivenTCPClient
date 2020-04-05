# EventDrivenTcpClient
This repo contains EventDrivenTCPClient.cs which was taken from https://www.daniweb.com/programming/software-development/code/422291/user-friendly-asynchronous-event-driven-tcp-client
Due to updates in later versions of .Net, Framework 4.x onwards, if BeginConnect is called asynchronously more than once it will generate exception. I have patched the issue by closing the socket for which object is going to and creating new object and then connect again.
Please feel free to report any issue along with exception details and steps to reproduce the same.
