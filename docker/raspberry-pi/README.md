# BedrockConnect on Docker on Raspberry Pi

- Put the `Dockerfile` and the `BedrockConnect-1.0-SNAPSHOT.jar` in one directory
- Configure the `CMD` line in the `Dockerfile` to fit your needs
- run `docker build -t bedrock-connect .`
- run `docker run --name "bedrock-c" -d --restart always -p 19132:19132/udp bedrock-connect`
