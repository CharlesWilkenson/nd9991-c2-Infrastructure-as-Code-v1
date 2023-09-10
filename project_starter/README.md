### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the starter code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:


#### final-project-starter.yml
Students have to write the CloudFormation code using this YAML template for building the cloud infrastructure, as required for the project. 

#### server-parameters.json
Students may use a JSON file for increasing the generic nature of the YAML code. For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "UdacityProject". 

In YAML code, the `${EnvironmentName}` would be substituted with `UdacityProject` accordingly.

### How to run the project?
You can run the project in two easy steps:
```bash

./create.sh network network.yml network-parameters.json 
./create.sh server servers.yml servers-parameters.json


The web app is served at: 
http://serve-webap-d5hzoq8qk2a7-415030427.us-west-2.elb.amazonaws.com/