# spinnaker-gate

github addr [https://github.com/kubernets/spinnaker-gate](https://github.com/kubernets/spinnaker-gate)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/spinnaker-gate/raw/master/get-spinnaker-gate-image.sh

## Arch and Version

- [**all** 0.10.0-20180221133510](https://hub.docker.com/r/kubernets/spinnaker-gate)

    > docker pull kubernets/spinnaker-gate:0.10.0-20180221133510

    > docker tag kubernets/spinnaker-gate:0.10.0-20180221133510 gcr.io/spinnaker-marketplace/gate:0.10.0-20180221133510 

    > docker rmi kubernets/spinnaker-gate:0.10.0-20180221133510

- [**all** 1.1.1-20180829141913](https://hub.docker.com/r/kubernets/spinnaker-gate)

    > docker pull kubernets/spinnaker-gate:1.1.1-20180829141913

    > docker tag kubernets/spinnaker-gate:1.1.1-20180829141913 gcr.io/spinnaker-marketplace/gate:1.1.1-20180829141913 

    > docker rmi kubernets/spinnaker-gate:1.1.1-20180829141913
