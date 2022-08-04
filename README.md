# Image filter - Udacity Cloud Developer Nanodegree project

## Udagram, my Instagram on AWS

### AIM

* The aim of the project is to deploy an image filter app to AWS using Elastic Beanstalk

### Steps taken

1. Create a github repository for the project
2. Clone the repository to your pc
3. clone the starter code
4. Copy Starter code to the folder of the repository that was created
5. Create a dev branch
6. Edit starter code to create new endpoint
* To test the code run "npm i" to install dependecies
* Run "npm run dev" on terminal to run the server.ts file

7. Configure aws credentials and install elastic beanstalk cli
8. Run "aws configure" to setup credentials
9. Run "eb init" to create a new application and follow the prompt.

* specify the region
* select the application to use
* select "Node.js" for the language
* Setup SSH for EC2 instance using the key-pairs

10. Next build the application by running "npm run build"

* for windows users edit the build command to make sure it fits windows commands

11. Next, create an Elastic Beanstalk (eb) environment using "eb create" 
12. Finally deploy the code using "eb deploy"
13. Go to the AWS console under the EB service to check if the application was deployed. 

14. Copy the endpoint URL: image-filter-dev.us-east-1.elasticbeanstalk.com



