Demonstrate your ability to run a Jenkins build and manually deploy to Elastic Beanstalk.

- Create a separate GitHub repository for this application

- Download the files from this repository and upload them to your newly created repository

- Be sure to follow the deployment instructions from this Repository

- Document your progress in a .md file in your repository. Also, document any issues you may run into and what you did to fix them.
- Make sure your documentation includes these sections:

  - Purpose
  - Issues
  - Steps
  - System Diagram
  - Optimization (How would make this deployment more efficient)

- Lastly, save your documentation and diagram into your repository. Submit your repository link to the LMS

## Deployment instructions Link:

- [Link to instructions: https://github.com/kura-labs-org/C4_deployment-2/blob/main/Deployment-instructions.md

<p align="center">
<img src="https://github.com/kura-labs-org/kuralabs_deployment_1/blob/main/Kuralogo.png">
</p>

## Deployment Instructions:

1. Create your own Jenkins Server and install the following on the server:
   - Install "python3.10-venv"
   - Download and install the Jenkins plugin "Pipeline Utility Steps"
2. Create and run a Jenkins build for the application
3. Observe the pipeline stages via the console output and document what occurred
4. Jenkins will zip the application file. Figure out how to extract the zip from Jenkins
5. **IF** the pipeline is successful, download the application files from your repository and proceed to the next step: https://scribehow.com/shared/How_to_Create_and_Deploy_a_Python_URL_Shortener_on_AWS_Elastic_Beanstalk__MS9pB8lfRaGFiKAq2FU-cw
