# upload files
 scp -i "config-server_key.pem" /c/workspace/upwork/genc_tech/novizit/novizit/config-server/target/config-server-0.0.1-SNAPSHOT.jar azureuser@config-server.eastus.cloudapp.azure.com:/home/azureuser

# upload service file
scp -i "config-server_key.pem" /c/workspace/upwork/genc_tech/novizit/novizit/novizit.service azureuser@config-server.eastus.cloudapp.azure.com:/etc/systemd/system