## Container Webhook Demonstration


#### Description
Very simple webpage to demo the use of containers. Presentation given internally to section.


#### How to use

```
git clone https://github.com/pyratebeard/container-webhook-demo.git
cd container-webhook-demo
docker build -t webhookdemo .
docker run -d -p 80:80 webhookdemo
```
Navigate to `localhost:80` in your browser.


#### Docker
This repo is linked to a [Docker Hub image](https://hub.docker.com/r/pyratebeard/container-webhook-demo) which then uses a webhook to an Azure Service webapp.

You can pull the image directly by incanting
```
docker pull pyratebeard/container-webhook-demo
```


#### Bugs
Don't care, it's only a demo. If you use this code then it's your own fault.

