\# Terraform Docker EC2 Deployment



This project demonstrates a complete DevOps workflow where infrastructure is provisioned using Terraform and a Docker container is automatically deployed on an AWS EC2 instance.



```

\## Project Overview



* Infrastructure as Code using Terraform
* AWS EC2 instance provisioning
* Docker installation via user\_data
* Nginx container deployment
* Public IP-based access



```

\## Tech Stack



* AWS EC2
* Terraform
* Docker
* Nginx
* Linux (Ubuntu)



```

\## How it works



1. Terraform creates EC2 instances
2. Security group allows HTTP (port 80)
3. user\_data install Docker automatically
4. Nginx container runs on port 80
5. Public IP serves the webpage



```

\## Deployment Steps



```

terraform init

terraform plan

terraform apply



```

\## Output



After deployment, open:

http://<ec2-instance-public-ip>



You will see Nginx welcome page



```

\## Key Learnings 



* Infrastructure as code ( IaC)
* EC2 provisioning automation
* Docker container deployment
* Debugging real-world cloud issues
* Security group configuration



```

\## Screenshot

!\[Output](nginx-output.png)



```

\## Author

Bijendra Kumar Deori

