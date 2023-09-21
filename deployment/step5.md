# Setup edgecore(on Edge Node)
<br>

Get token from cloud side (on Master Node)
`sudo keadm gettoken` {{execute}}

# On Edge 
<br>
<br>
Next, run keadm join to join edge node.

`sudo keadm join --cloudcore-ipport="CloudCore-IP:10000" --token=${token} --kubeedge-version=v1.14.2` {{execute}}

keadm join will install edgecore and mqtt, and --cloudcore-ipport flag is a mandatory flag.   
<br> 
<br>
**Now you can see KubeEdge edgecore is running.**