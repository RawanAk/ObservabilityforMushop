# Observability for Mushop
 # Introduction

![](./images/Intro.png)

## About 

In this Project I'm showing a step by step tutorial to configure the **[Monitoring Solution for Kubernetes](https://github.com/oracle-quickstart/oci-kubernetes-monitoring)**

The purpose behind the project is deploy a monitoring solution for MuShop Application which is deployed on Kubernetes, showcasing Oracle Cloud Native technologies and backing services. 

MuShop is a showcase of several Oracle Cloud Infrastructure services in a unified reference application. The sample application implements an e-commerce platform built as a set of micro-services. The accompanying content can be used to get started with cloud native application development on Oracle Cloud Infrastructure.

You can find the main project for deploying the Mushop at this **[link](https://github.com/oracle-quickstart/oci-cloudnative)**!
Also, you can find the source project of this tutorial at this **[link](https://github.com/oracle-quickstart/oci-kubernetes-monitoring)**!
### Objectives



### Prerequisites

-  This tutorial requires an Oracle Cloud account with available credits, you may check out this **[video](https://www.youtube.com/watch?v=4U-0SumNz6w)** to help you signing up. You also can use a paid cloud account or a trial cloud account as well.
  



## **[Task 1: Infrastructure Configuration](infrastructure/infrastructure.md)**

 First, we will build the infrastructure that we will use to run the rest of the workshop.  The sample application is a showcase of several Oracle Cloud Infrastructure services in a unified reference application. It implements an e-commerce platform built as a set of micro-services. The accompanying content can be used to get started with cloud native application development on Oracle Cloud Infrastructure.

 Let's start by obtaining the Mushop source code, the application code as well as the Terraform code, that creates all the required resources and configures the application on the created resources.

- After you sign in into you tenant, open up the Cloud Shell and clone the github repo.

```
git clone https://github.com/oracle-quickstart/oci-cloudnative.git mushop
```
![](images/tenant.png)
![](images/gitclone.png)

```
cd mushop/deploy/complete/terraform/
terraform init
```
![](images/init.png)
![](images/init2.png)
## **[Lab 2: Logging Analytics & Logging](logana/logana.md)**

 In this lab we will unleash the capabilites of Logging Analytics and review aggregated data in a dashboard and explore the available logs in the Log Explorer. 
 Oracle Cloud Logging Analytics is a cloud solution in Oracle Cloud Infrastructure that lets you index, enrich, aggregate, explore, search, analyze, correlate, visualize and monitor all log data from your applications and system infrastructure.

## **[Lab 3: Database Management & Operation Insights](dbmngt/dbmngt.md)**

 Database Management Cloud Service, DBAs get a unified console for on-premises and cloud databases with lifecycle database management capabilities for monitoring, performance management, tuning, and administration. Use advanced database fleet diagnostics and tuning to troubleshoot issues and optimize performance. 
 While Operations Insights is an OCI native service that provides holistic insight into database and host resource utilization and capacity.
 It also provides direct access to the Oracle Cloud Infrastructure Database Management service, which lets you take advantage of its real-time database performance and management capability with a single click.
 
## **[Lab 4: Monitoring](monitor/monitor.md)**

The Oracle Cloud Infrastructure Monitoring service uses metrics  to monitor resources and alarms  to notify you when these metrics meet alarm-specified triggers. 

## **[Lab 5: Outage Simulation](simulation/simulation.md)**

This step showcases the a load file deployed to the application which will create a sudden increase in the API server request and we will see how the alarms firing works and we will notice the change in the dashboards.

Ready? let's start learning!



