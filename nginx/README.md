### nginx

[![](https://badge.imagelayers.io/matthewgall/nginx:latest.svg)](https://imagelayers.io/?images=matthewgall/nginx:latest 'Get your own badge on imagelayers.io')

#### What is this image?
This image provides a [nginx](https://www.nginx.org) instance, perfect for setting up static file hosting (or more complex environments using PHP). Only 7MB (6 layers) compared to the official image, coming in at a whopping 133MB (12 layers)

#### How do I use this image?
Starting an nginx container is easy, use the following command to start a nginx environment (substitute 49160 for your chosen port)

    docker run -d -p 49160:80 matthewgall/nginx

 Want to mount your own directory for static delivery?

    docker run -d -v /yourfolder:/usr/share/nginx/html -p 49160:80 matthewgall/nginx
