# Spring Boot Application Deployment on AWS EC2

This repository contains a step-by-step guide titled **"AWS EC2"** authored by Mahmoud Najmeh in May 2024. The document explains how to deploy a Spring Boot application on an Amazon EC2 instance.

## Contents

The document covers the following topics:

1. **Spring Boot Application on AWS EC2**
   - A brief introduction to deploying a Spring Boot application on AWS EC2.

2. **Create a Spring Boot Application**
   - Instructions on how to create a Spring Boot application using [Spring Initializr](https://start.spring.io/).
   - Dependency setup and project generation.
   - Commands to package the application using Maven in IntelliJ.

3. **Create a Repository**
   - Guidance on setting up a repository, which will be cloned later onto the EC2 instance.

4. **Set Up an Amazon EC2 Instance**
   - Detailed steps to launch a new EC2 instance, including:
     - Choosing an Amazon Machine Image (Ubuntu).
     - Selecting the Free Tier eligible instance type.
     - Creating a new key pair and security group.
     - Configuring storage and launching the instance.

5. **Connect to Your EC2 Instance**
   - Commands to connect to the EC2 instance, install Git, clone your repository, and install Amazon Corretto (Java Development Kit).
   - Instructions to verify the Java installation and run your Spring Boot application.

6. **Configure Security Groups**
   - Steps to edit inbound rules in the security group to allow traffic on port 8080, necessary for accessing your Spring Boot application.

7. **How to Run**
   - Instructions on accessing your deployed application by using the Public IPv4 address of your EC2 instance followed by `:8080/your-endpoint`.

## How to Use this Repository

- **Follow the Steps**: Use the detailed instructions provided in the PDF to set up an EC2 instance and deploy a Spring Boot application.
- **Access the Application**: After deployment, access your application through the public IP of your EC2 instance.

## Conclusion

This guide is a comprehensive resource for deploying a Spring Boot application on AWS EC2. It covers everything from setting up the application and EC2 instance to configuring security groups and running your application.

---

Feel free to contribute to this repository by submitting issues or pull requests if you have improvements or additional content to share.
