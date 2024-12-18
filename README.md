# Jenkins-CI-CD-for-Docker
Project scope: create a Declarative Jenkinsfile for a CI pipeline.

Overview of Jenkinsfile:
1. Fetch code from Github.
2. Perform 'Unit Test' with Maven.
3. perform 'Code Analysis' with Checkstyle.
4. perform another 'Code Analysis' with SonarQube.
5. Build Docker image with the Artifact.
6. Publish the Docker Image to Amazon ECR.
7. Deploy the Docker Image on Amazon ECS.

Steps:
   AWS
1. Install AWS CLI.
2. Create an IAM USER with Access Keys.
3. Create an Amazon ECR Registry for the Docker image.
4. Deploy the image on ECS.

   Jenkins:
1. Install Docker and Docker pipeline plugins.
2. Install plugin pipeline:AWS steps
3. Install ECR plugin.
4. Install AWS SDK.
5. Add Docker user to docker group & reboot.
6. Store  AWS access keys(credentials).
7. Install Docker Engine in Jenkins.

8. Run the pipeline.
