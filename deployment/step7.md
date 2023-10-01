### Install Kubectl

```
curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
```
{{execute}}

### Setup keadm

```
wget https://github.com/kubeedge/kubeedge/releases/download/v1.14.2/keadm-v1.14.2-linux-amd64.tar.gz

tar -zxvf keadm-v1.14.2-linux-amd64.tar.gz

cp keadm-v1.14.2-linux-amd64/keadm/keadm /usr/local/bin/

```
{{execute}}

