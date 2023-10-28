# DevOps-Capstone-2
# Capstone II - Analytics Pvt Ltd

## Description
As a DevOps Engineer for Analytics Pvt Ltd, the goal is to implement a DevOps lifecycle to automate deployment, scaling, and operations of application containers across clusters of hosts, ensuring no changes to Docker containers in the testing environment.

## Project Details
- **Product:** [GitHub Repository](https://github.com/hshar/website.git)
- **Organization Type:** Product-based

## Specifications
1. **Git Workflow**:
   - Implement version control for the monolithic architecture. Releases scheduled on the 25th of every month.
2. **CodeBuild Automation**:
   - Trigger CodeBuild upon commits to the master branch.
3. **Docker Containerization**:
   - Build a custom Docker image using a Dockerfile for every push to GitHub.
4. **Kubernetes Deployment**:
   - Deploy containerized code from Docker Hub on a Kubernetes cluster with 2 replicas.
   - Create a NodePort service and configure it for port 30008 on the production server.
5. **Jenkins Pipeline**:
   - Develop a Jenkins Pipeline script to accomplish the above tasks.
6. **Infrastructure Configuration Management**:
   - Use Terraform to deploy necessary software and configurations on the servers.

## Execution Steps
1. Clone the product repository: `git clone https://github.com/hshar/website.git`
2. Establish a Git workflow with scheduled releases on the 25th of every month.
3. Configure CodeBuild to trigger upon commits to the master branch.
4. Develop a Dockerfile and build a custom Docker image for the code.
5. Deploy code on a Kubernetes cluster with 2 replicas and configure the NodePort service.
6. Create a Jenkins Pipeline script to automate the deployment and scaling tasks.
7. Use Terraform to handle infrastructure configuration management in the AWS cloud.

## Contact
For inquiries, contact [Nikhil Sharma](mailto:nickyeee1210@gmail.com).

