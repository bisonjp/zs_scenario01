# Zscaler Demo Scenario
## Prequisite
- Prepare Zscaler Private Access license
- Create AWS IAM account who is assigned PowerUserAccess policy
- Subscribe Zscaler Private Access Connector on AWS
- Terrafrom Cloud account
- Github account

## Overview
This scenario is for testing secure access to private application which is deployed on AWS via Zscaler Private Access.
This code will make following AWS environment. Also App Connector will connect to ZPA Serivce Edge automatically.  
![image](https://github.com/bisonjp/scenario01_dev/assets/39214022/b7ce6371-bbc8-476c-bc65-e3bbb16afdff)




## Directory structure
    ├── README.md
    ├── main.tf
    ├── aws_ac.tf
    ├── zpa.tf
    ├── variable.tf
    ├── output.tf
