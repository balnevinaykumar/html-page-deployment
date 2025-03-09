# html-page-deployment


Task: Deploying an HTML Web Template on AWS using GitHub Actions and Docker
Objective:
You are required to download an HTML web template from the internet, set up a GitHub Actions workflow, and automate the deployment 
of this template on an AWS EC2 instance 
using Docker. The deployed website should be publicly accessible via the Public DNS of the EC2 instance on a specified port.


Instructions:
1.Download an HTML Web Template:
--Search for and download a free HTML web template from any reliable
--Extract the files and organize them properly inside a repository.

2.Set Up GitHub Actions Workflow:
--Inside the root of your repository, create a hidden directory named .github/workflows (as per industry standards).
--Inside this folder, create a file called deploy.yaml that defines the CI/CD pipeline for deploying the HTML template on AWS.

3.Deploy the HTML Web Template using Docker:
--Create a Dockerfile that serves the HTML template using a lightweight web server (such as nginx).
--Build and run the Docker container.

4.Expose the Application to the Public Internet:
--Ensure that the container runs on a public-accessible port (e.g., 80 or 8080).
--The application should be accessible by visiting http://<PUBLIC_DNS>:<PORT> in a browser.
