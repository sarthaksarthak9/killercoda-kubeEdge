# Deploy cloudcore (on Master Node)
## Note: You need to get public IP of cloud node, make sure edge node can connect cloud node using this IP, and 10000 and 10002 in your cloudcore needs to be accessible for your edge nodes

`sudo keadm deprecated init --advertise-address="CloudCore-IP" --kubeedge-version=1.14.2 --kube-config=/root/.kube/config` {{execute}} 

## check if cloudcore running successfully:
`sudo kubectl get all -nkubeedge`{{execute}}


**Now you can see KubeEdge cloudcore is running.**