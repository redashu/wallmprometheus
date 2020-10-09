# To monitor containers or containerized app 

## prometheus need to connect with Service Discovery 

### CAdvisor 

## ITs a Google production written in GO 

<img src="cad.png">

## Docker GCR image for 

```
 docker  pull gcr.io/google-containers/cadvisor
 
```

## starting Cadvisor as container 

```
docker run -d --name cad650 --restart always -p 8080:8080  -v /var/lib/docker:/var/lib/docker:ro -v /cgroup:/cgroup:
ro   -v  /var/run:/var/run:rw  -v  /:/rootfs:ro   gcr.io/google-containers/cadvisor
```


# Black Box 

[githublink] ('https://github.com/prometheus/blackbox_exporter')


