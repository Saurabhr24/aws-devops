# aws-devops - What is done with this project - explaination is followed . 

IAM - Created a User with credentials and assigned the required roles.
KMS - Used to keep the data safe and encrypted.
CodeCommit - Used this services as a git , to store the code in the repository and to
push-pull the changes/commits.
CodeBuild - This is same as a Jenkins, build environment to compile and test the code
Artifacts - Used to managed and shared application dependencies securely
S3 - Used to store artifacts and enable the data storage.
CodeDeploy - Used for deploying the applicaton to staging environment.
Ec2 – An instances created to managed virtual servers for hosting the application.


The project involved creating an end-to-end CI/CD pipeline firstly manually and then
automated where code changes pushed to CodeCommit automatically and then
triggered the build process in CodeBuild. Upon successful builds, the artifacts get stored
in the S3 bucket and then the CodeDeploy automated the deployment of the
application to an EC2 instance.
