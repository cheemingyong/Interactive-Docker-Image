# Interactive-Docker-Image

## Deployment Of Apache Docker Image To EC2
### Go to http://ec2-54-255-207-175.ap-southeast-1.compute.amazonaws.com/ to access the deployed EC2 instance

### The DockerFile used to generate the Apache Web Server Docker Image can be accessed from
    https://github.com/cheemingyong/Interactive-Docker-Image/blob/main/test.dockerfile

### To access the SSH shell, please download the private key into a folder on your desktop
    Make sure ssh is installed
    https://github.com/cheemingyong/Interactive-Docker-Image/blob/main/AWS_DOCKER.pem
    Go to the folder containing the AWS_DOCKER.pem file 
    Run ssh -i AWS_DOCKER.PEM ec2-user@54.255.207.175

### Instructions can be retrieved from the userguide.docx

## Future Enhancements

### Next release to feature Fargate deployment of Docker Containers

## Roadmap

### Deployment to EC2 Instance will improvised to deploy a LAMP stack in the following order
#### AWS Fargate
#### ECS 
#### EKS

### DockerFile approach to be deprecated and replaced by
#### Terraform 
#### CloudFormation
