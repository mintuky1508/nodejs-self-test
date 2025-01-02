#How to Deploy this nodejs aaplication on ubuntu ec2.

1. create aws ec2.
2. ssh ubuntu@ec2-instance-private-ip -i <xyz.pem>
3. sudo su
4. apt update
5. apt install -y nodejs npm
6. node -v
7. npm -v
8. git clone <github repo link>
9. cd <cloned repo> [go in side of cloned repo]
10. npm install
11. npm start
12. Hit your public ip with port[https://12.32.55.8:3000(Example)] and also enable the port from aws ec2 secuirity group. 



 



    
