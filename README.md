# dockerfiles

## images
### build-base

[![](https://badge.imagelayers.io/matthewgall/build-base:latest.svg)](https://imagelayers.io/?images=matthewgall/build-base:latest 'Get your own badge on imagelayers.io')

#### What is this image?
This image provides a base Alpine linux installation (provided by gliderlabs/alpine:latest) and installs a base set of packages used by child images, such as build-base, git and many more (as required)

### golang

[![](https://badge.imagelayers.io/matthewgall/golang:latest.svg)](https://imagelayers.io/?images=matthewgall/golang:latest 'Get your own badge on imagelayers.io')

#### What is this image?
This image provides a [Go](https://www.golang.org) environment for all your Docker needs!

### maltrail-client

[![](https://badge.imagelayers.io/matthewgall/maltrail-client:latest.svg)](https://imagelayers.io/?images=matthewgall/maltrail-client:latest 'Get your own badge on imagelayers.io')

#### What is this image?
This image provides a [maltrail](https://github.com/stamparm/maltrail) client, part of a larger maltrail system. Maltrail is a malicious traffic detection system, utilizing publicly available (black)lists containing malicious and/or generally suspicious trails, along with static trails compiled from various AV reports and custom user defined lists, where trail can be anything from domain name.

### nginx

[![](https://badge.imagelayers.io/matthewgall/nginx:latest.svg)](https://imagelayers.io/?images=matthewgall/nginx:latest 'Get your own badge on imagelayers.io')

#### What is this image?
This image provides a [nginx](https://www.nginx.org) instance, perfect for setting up static file hosting (or more complex environments using PHP). Only 7MB (6 layers) compared to the official image, coming in at a whopping 133MB (12 layers)

#### How do I use this image?
Starting an nginx container is easy, use the following command to start a nginx environment (substitute 49160 for your chosen port)

    docker run -d -p 49160:80 matthewgall/nginx

 Want to mount your own directory for static delivery?

    docker run -d -v /yourfolder:/usr/share/nginx/html -p 49160:80 matthewgall/nginx

### nodejs-dev

[![](https://badge.imagelayers.io/matthewgall/nodejs-dev:latest.svg)](https://imagelayers.io/?images=matthewgall/nodejs-dev:latest 'Get your own badge on imagelayers.io')

#### What is this image?
This image provides a [nodejs](https://www.nodejs.org) environment, including [npm](https://www.npmjs.com) for all your Docker needs!

### python-dev

[![](https://badge.imagelayers.io/matthewgall/python-dev:latest.svg)](https://imagelayers.io/?images=matthewgall/python-dev:latest 'Get your own badge on imagelayers.io')

#### What is this image?
This image provides a [Python](https://www.python.org) environment, including [pip](https://pypi.python.org/pypi/pip) and [virtualenv](https://virtualenv.pypa.io/en/latest) for all your Docker needs!

### build-base

[![](https://badge.imagelayers.io/matthewgall/build-base:latest.svg)](https://imagelayers.io/?images=matthewgall/build-base:latest 'Get your own badge on imagelayers.io')

#### What is this image?
This image provides a base Alpine linux installation (provided by gliderlabs/alpine:latest) and installs a base set of packages used by child images, such as build-base, git and many more (as required)

### golang

[![](https://badge.imagelayers.io/matthewgall/golang:latest.svg)](https://imagelayers.io/?images=matthewgall/golang:latest 'Get your own badge on imagelayers.io')

#### What is this image?
This image provides a [Go](https://www.golang.org) environment for all your Docker needs!

### maltrail-client

[![](https://badge.imagelayers.io/matthewgall/maltrail-client:latest.svg)](https://imagelayers.io/?images=matthewgall/maltrail-client:latest 'Get your own badge on imagelayers.io')

#### What is this image?
This image provides a [maltrail](https://github.com/stamparm/maltrail) client, part of a larger maltrail system. Maltrail is a malicious traffic detection system, utilizing publicly available (black)lists containing malicious and/or generally suspicious trails, along with static trails compiled from various AV reports and custom user defined lists, where trail can be anything from domain name.
### nginx

[![](https://badge.imagelayers.io/matthewgall/nginx:latest.svg)](https://imagelayers.io/?images=matthewgall/nginx:latest 'Get your own badge on imagelayers.io')

#### What is this image?
This image provides a [nginx](https://www.nginx.org) instance, perfect for setting up static file hosting (or more complex environments using PHP). Only 7MB (6 layers) compared to the official image, coming in at a whopping 133MB (12 layers)

#### How do I use this image?
Starting an nginx container is easy, use the following command to start a nginx environment (substitute 49160 for your chosen port)

    docker run -d -p 49160:80 matthewgall/nginx

 Want to mount your own directory for static delivery?

    docker run -d -v /yourfolder:/usr/share/nginx/html -p 49160:80 matthewgall/nginx

### nodejs-dev

[![](https://badge.imagelayers.io/matthewgall/nodejs-dev:latest.svg)](https://imagelayers.io/?images=matthewgall/nodejs-dev:latest 'Get your own badge on imagelayers.io')

#### What is this image?
This image provides a [nodejs](https://www.nodejs.org) environment, including [npm](https://www.npmjs.com) for all your Docker needs!

### openjdk

#### What is this image?
This image provides a base Alpine linux installation (provided by gliderlabs/alpine:latest) and installs a base set of packages to provide Java support.

#### Versions
##### 7
    docker pull matthewgall/openjdk7

##### 8
    docker pull matthewgall/openjdk8
### python-dev

[![](https://badge.imagelayers.io/matthewgall/python-dev:latest.svg)](https://imagelayers.io/?images=matthewgall/python-dev:latest 'Get your own badge on imagelayers.io')

#### What is this image?
This image provides a [Python](https://www.python.org) environment, including [pip](https://pypi.python.org/pypi/pip) and [virtualenv](https://virtualenv.pypa.io/en/latest) for all your Docker needs!
