# CNA Tutorial
VirtualBox => Preferences => Network => Host-only Networks
![VBox network settings 1](https://github.com/EslamElHusseiny/CNA_tutorial/blob/master/vbox1.png "VBox Network Settings 1")

Create a new Network with IP => 192.168.58.1 and Network Mask => 255.255.255.0
![VBox network settings 2](https://github.com/EslamElHusseiny/CNA_tutorial/blob/master/vobx2.png "VBox Network Settings 2")

| Component     | IP           | Port  |
| ------------- |------------  | ----- |
| Docker Host   | 192.168.58.2 |       |
| Portainer     | 192.168.58.3 | 9000  |
| registry-srv  | 192.168.58.4 | 5000  |
| registry-gui  | 192.168.58.5 | 8080  |
| minio-target  | 192.168.58.6 | 9000  |
| gitlab        | 192.168.58.7 | 30080 |
| concourse-web | 192.168.58.8 | 9004  |
