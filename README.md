# Deploying Mediawiki app into kubernetes( i deployed over minikube)
This is a deployment of Mediawiki into it using docker and kubernetes. 


### Prerequisites
1. Git, Docker and Minikube should be installed over machine.
2. For better performance, use 2 VCPU and 4GB RAM of VM.


### Running The Automation

1. Clone the current repo to your local machine using 

```
git clone https://github.com/Anurag-30/MediaWiki.git

```
2. Move into Terraform directory

```
cd MediaWiki/Terraform/

```

3. Run the Terraform script

```
terraform apply

```
Need to specify the region at the run time eg:us-east-1.

You can access the application at http://{publicip}:30163/wiki
