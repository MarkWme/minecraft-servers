# Minecraft Servers

Deploy Minecraft servers to a Kubernetes cluster with persistent storage attached. 

## Minecraft

Deploys a "vanilla" Minecraft server

## Pixelmon

Deploys a forge enabled Minecraft server. Once deployed, you will need to use a tool such as kubectl cp to copy the pixelmon mod file to the pod's persistent storage. Then delete and redeploy the pod to initiate a Minecraft server with Pixelmon.



