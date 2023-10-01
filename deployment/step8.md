### Get token from cloud side (on Master Node)
```
sudo keadm gettoken
```
{{execute}}

# On Edge 
<br>
<br>
Next, run keadm join to join edge node.

```
sudo keadm join --cloudcore-ipport="52.205.239.229:10000" --token=afa163b12dbc8a324f86c22546f1899a3edb1cf918861c305ee1175e5c379403.eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE2OTYyNTI0OTh9.UN7gYnWlKC4lg2eWsNrDwBPSCJ7UIe-ti8qkkmaWuQk --kubeedge-version=v1.14.2 --runtimetype=remote --remote-runtime-endpoint=unix:///var/run/cri-dockerd.sock

``` 
{{execute}}

keadm join will install edgecore and mqtt, and --cloudcore-ipport flag is a mandatory flag.   
<br> 
<br>
**Now you can see KubeEdge edgecore is running.**