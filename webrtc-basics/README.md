# WebRTC Basics

### STEPS 

1. Open two browsers
2. Open DevTools on both
3. Paste peerA.js content in first browser dev tools
4. Copy the SDP offer generated JSON
5. Go to the second browser and create "offer" object and set it to the SDP you copied (signaled) 
6. Paste peerB.js content in second browser dev tools
7. Copy output of peerB.js and create answer variable in first browser and put it into it.
8. Paste the content of peerA_Final.js in first browser
9. Use sendChannel.send() to send data from peerA
9. use remoteConnection.channel.send() to send data from peerB


