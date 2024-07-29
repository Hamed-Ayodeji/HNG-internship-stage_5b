# Automated Deployment and Configuration with Ansible for Boiler plates

## Overview

This project showcases automated deployment and configuration using Ansible for a FastAPI boilerplate application. The objective is to streamline the setup of a development environment by automating the installation of dependencies, database configuration, application setup, and logging.

## Project Requirements

- Clone the repository from the `devops` branch.
- Install necessary dependencies, including databases and messaging queues if required.
- Build and deploy the FastAPI boilerplate application.
- Configure PostgreSQL and securely store admin credentials.
- Set up Nginx as a reverse proxy to forward requests to the application.
- Ensure proper logging of application outputs and errors.

## Prerequisites

- Ansible installed on the deployment server.
- Access to a remote Linux server (Ubuntu 22.04).
- Necessary SSH keys and permissions.

## Ansible Playbook Structure

### Playbook (`main.yaml`)

The playbook orchestrates the entire deployment process and includes:

- System updates and user setup.
- Directory creation and permission settings.
- Package installations and dependency management.
- Repository cloning and virtual environment setup.
- PostgreSQL configuration.
- Application deployment and startup.
- Nginx configuration.

### Configuration File (`ansible.cfg`)

The configuration file defines settings for Ansible, including temporary file locations and SSH key checking behavior.

### Template File (`nginx.conf.j2`)

The template file configures Nginx to proxy requests from port 80 to the application running on port 3000.

## Setting Up the Ansible Server

1. **Create and Set Up Server:**
   - Launch a new Ubuntu 22.04 server on DigitalOcean or any other provider.
   - SSH into the server and install Ansible.
   - Configure the `ansible.cfg` file according to project requirements.

2. **Clone Repository and Prepare Files:**
   - Clone this repository to your Ansible server.
   - Ensure all necessary files (`main.yaml`, `ansible.cfg`, `nginx.conf.j2`) are in place.

3. **Add an Inventory File:**
   - Add all servers to the `hng` group in the inventory file, with the host set to `hng`.

## Running the Deployment

Execute the playbook using the following command:

```bash
ansible-playbook main.yaml -b
```

This command automates the deployment and configuration process as defined in the playbook.

## Post-Deployment Verification

After running the deployment, verify the following:

1. **User and Directory Setup:**
   - Confirm the creation of the `hng` user with sudo privileges.
   - Verify that the `devops` branch of your repository is cloned into `/opt/stage_5b`.
   - Ensure `/opt/stage_5b` is owned by the `hng` user.

2. **Application Availability:**
   - Confirm the application is running on `127.0.0.1:3000`.
   - Ensure port 3000 is not exposed externally.

3. **Nginx Configuration:**
   - Verify that Nginx 1.26 is installed.
   - Check that Nginx is correctly reverse proxying requests from port 80 to `127.0.0.1:3000`.

4. **PostgreSQL Setup:**
   - Confirm PostgreSQL is installed and running.
   - Ensure admin credentials are saved in `/var/secrets/pg_pw.txt`.
   - Test PostgreSQL accessibility using the stored credentials.

5. **Logging Configuration:**
   - Ensure stderr logs are written to `/var/log/stage_5b/error.log`.
   - Ensure stdout logs are written to `/var/log/stage_5b/out.log`.
   - Verify that both log files are owned by the `hng` user.

6. **Dependency Installation:**
   - Check that all application dependencies, including databases and messaging queues, are installed.
   - Confirm that environment variables, application properties, or application settings are configured correctly.

## Security Considerations

- Manage SSH keys securely.
- Ensure the deployment user has appropriate permissions.
- Store sensitive data, such as database credentials, securely.

## References

- [Ansible Documentation](https://docs.ansible.com/)
- [FastAPI Documentation](https://fastapi.tiangolo.com/)
- [DigitalOcean](https://www.digitalocean.com/)
- [AWS EC2](https://aws.amazon.com/ec2/)

## Summary

This project provides a comprehensive approach to automating the deployment and configuration of a FastAPI application using Ansible. Following this guide ensures a consistent and reliable setup process for your development environment.
