# PyRedis
Based on the project by Charles Leifer. As of right now, all the credit goes to Charles. 

A "snippet" version of Redis.




Things that I need to do (some based on Leifer's reconmendations):
1. Refactor, clean intial code, and add comments
2. Add test functionality ( to test connection to server and speed of "transfer")
3. Add better error handling
4. Allow Client to close connection and re-connect
5. Logging

Things I might add:
1. Add more commands
2. Use the protocol handler to implement an append only command log
3. Re-write to use the standard library's SocketServer and ThreadingMixin
