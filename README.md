# Mini-Cloud-Service-V2

###### To Install this you have to type the following comand

docker compose -f dockerization.yaml up -d

install nodejs(v20)(not from docker)

install node-red(not from docker)

install on node red these libraries:
1) node-red-contrib-minio-all
2) node-red-contrib-ui-upload
3) node-red-dashboard
4) node-red-contrib-graphs
5) node-red-contrib-amqp2

Open localhost:1880
upload the file flows json
Type the node of minio
Set username and password the credentials(You can find them on file dockerization.yaml)

Then open localhost:1880/ui and you are ready
