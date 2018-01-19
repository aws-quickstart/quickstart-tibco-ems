# quickstart-tibco-ems
## TIBCO Enterprise Message Service (EMS)  on the AWS Cloud


This new Quick Start automatically deploys TIBCO Enterprise Message Service (EMS) into a customizable environment on the Amazon Web Services (AWS) Cloud, using Amazon Elastic File System (Amazon EFS) for shared storage.

TIBCO EMS implements the Java Message Service (JMS) framework to provide a uniform messaging interface for enterprise applications. It connects other messaging services, such as TIBCO Rendezvous and TIBCO FTL, directly, and integrates with other application types and services by using TIBCO BusinessWorks.

AWS extends the capabilities of TIBCO EMS by enabling applications running on different Amazon Elastic Compute Cloud (Amazon EC2) instances to communicate easily. With Amazon EFS, AWS also removes the need to have dedicated hardware or expensive disk arrays (SAN or NAS) for shared storage, while providing a complete fault-tolerant environment for all messages.

The Quick Start offers two deployment options:

- Deploying TIBCO EMS into a new virtual private cloud (VPC) on AWS
- Deploying TIBCO EMS into an existing VPC on AWS

You can also use the AWS CloudFormation templates as a starting point for your own implementation.

![Quick Start architecture for TIBCO EMS on AWS](https://d0.awsstatic.com/partner-network/QuickStart/datasheets/tibco-ems-on-aws-architecture.png) 

For architectural details, best practices, step-by-step instructions, and customization options, see the 
[deployment guide](https://s3.amazonaws.com/quickstart-reference/tibco/ems/latest/doc/tibco-ems-on-the-aws-cloud.pdf).

To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo.
If you'd like to submit code for this Quick Start, please review the [AWS Quick Start Contributor's Kit](https://aws-quickstart.github.io/). 
