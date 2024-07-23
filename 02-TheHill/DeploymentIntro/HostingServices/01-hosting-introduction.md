# Hosting services: the basics

1. [What's a Web App?](#Introduction)
2. [Render](#Render)
3. [Other solutions](#others)

## Introduction

When it comes to deploying your API (also called, web-server), a lot of solutions exists.

Each with the set of services, facilities and prices.

## Big cloud providers

A first possibility, and what will mostly be used in big companies is cloud providers. The 3 mains ones are:
- Amazon Web Services (AWS)
- Microsoft Azure (AZ)
- Google Cloud Platform (GCP) 

Each of those gives you the possibility to manager your own Linux machine and expose it to the internet.

So you can run API, ML models, ...

But this kind of service is expensive and not easy to manage. You have to update the OS regularly, configure a firewall, set-up the security, ...

To make the process of deploying all the "common" services (API, web app, website,...) they have specific services that you can use with less configuration more ease.

In this course, we won't use cloud providers that much because a lot of free alternative exists, but for bigger projects it's good to be aware of what is out there.

**For APIs, here are some interesting solutions:**

- [AWS API gateway](https://docs.aws.amazon.com/apigateway/latest/developerguide/how-to-deploy-api.html)
- [AWS Lambda](https://aws.amazon.com/lambda/)
- [Azure API](https://azure.microsoft.com/en-gb/services/api-management/#overview)
- [Azure functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview)
- [Googe API](https://cloud.google.com/endpoints/docs/openapi/deploy-api-backend)
- [Google Cloud functions](https://developers.google.com/learn/topics/functions#:~:text=Google%20Cloud%20Functions%20is%20a,your%20cloud%20infrastructure%20and%20services.)

**For raw servers:**

### AWS EC2

[Amazon Elastic Compute Cloud](https://aws.amazon.com/ec2/) (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers. Amazon EC2’s simple web service interface allows you to obtain and configure capacity with minimal friction. It provides you with complete control of your computing resources and lets you run on Amazon’s proven computing environment.

AWS has been around for quite some time now and allows you do to pretty much everything, like the [AWS S3 servers](https://aws.amazon.com/s3/?nc1=h_ls) that provides storage and fast computing capabilities and thus very useful to train Neural Networks. AWS certifications are also really valuables by a lot of companies.

The huge challenge is learning how all those services works. You can take a look at [Amazon Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/?nc1=h_ls) .

**Please be careful because the pricing can escalate pretty quickly.**

[Deploy Flask app on AWS EC2 tutorial](https://www.codementor.io/@dushyantbgs/deploying-a-flask-application-to-aws-gnva38cf0)

### Azure

[Microsoft Azure Container Instances](https://azure.microsoft.com/en-us/services/container-instances/) also allows you to run containers on their platform.

Microsoft Azure is one of the most used Wep Application Service, like Amazon's AWS and the certifications are also highly valuable for companies.

[Deploy Flask app on Azure tutorial](https://medium.com/@alexjsanchez/creating-and-deploying-a-flask-app-with-docker-on-azure-in-5-easy-9f7aa7a12145)

**Please be careful because the pricing can escalate pretty quickly.**

## Render

If you want to easily deploy an API for free, [Render](https://render.com/) is what you are looking for...
