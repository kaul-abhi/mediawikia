# Deploying Mediawiki app into kubernetes( i deployed over minikube)
This is a deployment of Mediawiki app using docker and kubernetes. 


### Prerequisites
1. Git, Docker and Minikube should be installed over machine.
2. For better performance, use 2 VCPU and 4GB RAM of VM.


### Running The Automation

1. Clone the current repo to your local machine using 

```
git clone https://github.com/kaul-abhi/mediawikia.git

```
2. Move into Mediawikiapp folder

```
cd Mediawikiapp/kubernetes/

```

3. Run the kubectl command to deploy application, MariaDB. Running the command will create two replicas of app and 1 for mariadb.
   I have exposed the application over nodeport 30163.

```

You can access the application at http://{publicip}:30163/wiki or at http://localhost:30163/wiki
