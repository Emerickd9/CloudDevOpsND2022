### Project Title - Deploy a high-availability web app using CloudFormation
This folder contains the CloudFormation codes for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. The folder contains the following files:

#### [Udacity Project 2 Infrastructure Diagram](Udacity%20Project%202%20Infrastructure%20Diagram.jpeg)
Infrastructure diagram

#### [projectinfra.yml](projectinfra.yml)
Deploys the network infrastructure.

#### [projectinfra-params.json](projectinfra-params.json)
Parameters for the network infrastructure

In YAML code, the `${EnvironmentName}` would be substituted with `UdacityUdagramProject` accordingly.

#### [projectservers.yml](projectservers.yml)
Deploys the web servers

#### [projectservers-params.json](projectservers-params.json)
Parameters for the web servers

#### [create.sh](create.sh)
Helper script to create the CloudFormation stack

#### [update.sh](update.sh)
Helper script to update the CloudFormation stack


#### [delete.sh](delete.sh)
Helper script to delete the CloudFormation stack
