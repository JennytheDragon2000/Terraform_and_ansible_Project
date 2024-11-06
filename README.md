# Terraform and Ansible Practice Project

This project was created as a way to practice and learn Terraform and Ansible. It includes various infrastructure components and automation scripts to help reinforce the concepts and skills related to these tools.

## Purpose

The main goal of this project is to provide a hands-on learning environment for:

1. **Terraform**: Exploring Terraform's capabilities in creating and managing cloud infrastructure, including resources such as VPCs, web servers, and remote state storage.
2. **Ansible**: Demonstrating the use of Ansible for provisioning and configuring resources, as a complement to the Terraform-based infrastructure.
3. **Infrastructure as Code**: Practicing the principles of Infrastructure as Code (IaC) by defining the entire infrastructure and its components through code.
4. **Modular Design**: Showcasing the benefits of a modular approach by creating reusable Terraform modules for common infrastructure components.
5. **Automation**: Exploring the use of helper scripts to automate certain tasks, such as installing Docker and waiting for instance creation.

## Directory Structure

The project is organized into several directories, each focusing on a specific aspect of Terraform and Ansible:

- `ansible/`: Contains an Ansible playbook for provisioning and configuring resources.
- `aws-vpc-webserver/`: Terraform configuration for creating a VPC and a web server on AWS.
- `demo/`: A simple Terraform configuration for demonstration purposes.
- `_modules/`: Contains reusable Terraform modules for VPC and web server.
- `remote-state-s3/`: Terraform configuration for creating an S3 bucket for remote state storage.
- `scripts/`: Includes helper scripts for installing Docker and waiting for instance creation.
- `vpc-webserver/`: Terraform configuration for creating a VPC and a web server on AWS.
- `vpc-webserver-via-modules/`: Terraform configuration for creating a VPC and a web server on AWS, using the reusable modules.

## Getting Started

Refer to the instructions in the main [README.md](README.md) file to set up and explore the different components of this project.

## Contributing

If you would like to contribute to this project, please follow the standard GitHub workflow:

1. Fork the repository
2. Create a new branch for your changes
3. Make your changes and test them
4. Submit a pull request

We welcome all contributions, including bug fixes, feature enhancements, and documentation improvements.

## License

This project is licensed under the [MIT License](LICENSE).
