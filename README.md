# eks_assignment

## Assignment scenario:

Design a highly available and scalable containerised application on Amazon EKS. Below are the requirements and deliverables:

## Requirements:

1. Create an EKS cluster along with a node-group with t3.small instances using [eksctl](https://eksctl.io/)(using config files).
2. Deploy a simple [Hello World container](https://hub.docker.com/r/amazon/amazon-ecs-sample) on EKS this cluster.
3. Expose this application on internet using Application Load balancer.
4. Configure this application to autoscale based on CPU utilisation(70% CPU)

**Note-** Please use manifest files to create all the resources and avoid using UI.


## Deliverables:

1. Complete setup by showcasing the application accessible from internet.
2. Link of a Github repo hosting the config files used to create the above setup.
3. Provide suggestions on how you would make this application more secure and cost-effective.

## website access url:
a521a751a38c349c4ba7a126a217cd6d-92791127.ap-south-1.elb.amazonaws.com