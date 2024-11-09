Making server : 

New one get from server file: 
https://www.minecraft.net/fr-fr/download/server

insert jar file in a folder, and create another start.bat file :
java -Xmx1024M -Xms1024M -jar minecraft_server.1.21.3.jar nogui

Run server and then use ngrok to host the server : 
run ngrok.Exe and the type : 
ngrok tcp --region eu "insert minecraft server port here"
