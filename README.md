#### Logo_on_http
***

##### Overview
Simple docker-container with ruby listener on port 8080. When requesting on this port, it returns the result of the utility Linux_logo

Linuxlogo or linux_logo is a Linux command line utility that generates a color ANSI picture of Distribution logo with a few system information.

***

##### Overview Dockerfile

###### Quickstart run

```
docker run -dit -p 8080:8080 iggysav/logo_on_http

```

###### Ports:
``` 8080 ``` - HTTP 

***


##### Testing out

After run docker-container you'll make a request using ```curl```.

```curl localhost:8080```