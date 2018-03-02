# Media Server stack running on Kubernetes

Work in Progress

## HTPCManager

## Plex

* Plex is running on NodePort with port 32400 mapped locally
* Forward port 32400 on external router to the NodePort of your cluster (Any node IP of the cluster)
* Open Plex on browser: http://plex.internal.yourdomain.com/web/index.html
* Go to Settings -> Server -> Network and add `192.168.0.0/255.255.0.0,10.0.0.0/255.0.0.0` to "List of IP addresses and networks that are allowed without auth" parameter.

## Transmission

## SickRage

## CouchPotato
