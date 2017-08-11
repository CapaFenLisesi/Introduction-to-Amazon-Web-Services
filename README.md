# Introduction to Amazon Web Services

## Contents
1. [Overview](#overview)
1. [Pricing and Free Tier](#pricing-and-free-tier)
1. [Certification](#certification)
1. [Documentation](#documentation)
1. [Console](#console)
1. [S3](#s3)
1. [IAM](#iam)
1. [EC2](#ec2)
1. SDK

5. DynamoDB
6. Lambda? Elastic Beanstalk? 
1. [Resources](#resources)
1. [Links](#links)

## Overview

### What is Cloud Computing? 

Let's watch the [video](https://aws.amazon.com/what-is-cloud-computing/) on AWS and another one on [Youtube](https://www.youtube.com/watch?v=ae_DKNwK_ms)  

![alt text](https://github.com/Michael-Antczak/Introduction-to-Amazon-Web-Services/blob/master/resources/iaas-paas-saas.png "IAAS vs PAAS vs SAAS")  

Watch the course in the [Resources](#resources) section.  

### So what is Amazon Web Services? 

According to [Wikipedia](https://en.wikipedia.org/wiki/Amazon_Web_Services):  
> Amazon Web Services (AWS) describes both a **technology** and **a company**. The company AWS is a subsidiary of **Amazon.com** and provides **on-demand cloud computing platforms to individuals, companies and governments, on a paid subscription basis with a free-tier option available for 12 months**. The technology allows subscribers to have at their disposal **a full-fledged virtual cluster of computers, available all the time, through the internet**.   

Ok, but in plain English please:  
> It's very much analogous to **a huge, general-purpose computer** said Josh Stella...

The key points: 
- technology
- on demand
- cloud
- for everybody
- 12 months free tier
- access through the browser, console or code  

Watch the [AWS Tech Essentials](#resources) course later on. 

### What can YOU do with AWS? 
- host your own website
- create API
- process data on servers (computations)
- host a small application
- host a high traffic service
- host WordPress, Drupal, etc. website
- endless possibilities

### Jobs with AWS
How big is the market and what type of [jobs](http://uk.dice.com/index.php?SearchMode=StandardSearch&SearchFilter=SearchFilter&Mode=AdvertSearch&lang=en&AdvertShortlistLimit=50&SearchTerms=AWS&ClientTypeFilter_1=1&ClientTypeFilter_2=2&) can you get? 
- developer 
- deployment
- system maintenance 
- architecture design
- startup

### Who uses AWS? 
We don't have enough time here. Some of the services that you use on a daily basis use AWS, like:
- [Airbnb](https://aws.amazon.com/solutions/case-studies/airbnb/)
- [Spotify](https://aws.amazon.com/solutions/case-studies/spotify/)
- [Netflix](https://aws.amazon.com/solutions/case-studies/netflix/)
- [Koffer](www.koffer.io)

If it's good for them, it can also be good for you. Just be careful. 

### How big is AWS? 

![alt text](https://github.com/Michael-Antczak/Introduction-to-Amazon-Web-Services/blob/master/resources/gartner_iaas_mq_june_2017.png "Gartner AWS")  

It is [massive](https://aws.amazon.com/products/?nc2=h_ql_ny_livestream_blu_t2). Over 70 services grouped into:
- Compute
- Storage
- Database
- Migration
- Networking
- etc.

The very basic services to start with are in my opinion: **IAM**, **S3** and **EC2**. 

In terms of the physical [infrastructure](https://aws.amazon.com/about-aws/global-infrastructure/) we talk about **Regions** and **Availability Zones**    

A **Region** is a physical location in the world where we have multiple Availability Zones.   
An **Availability Zone** consist of one or more discrete data centers, each with redundant power, networking and connectivity, housed in separate facilities.  

![alt text](https://github.com/Michael-Antczak/Introduction-to-Amazon-Web-Services/blob/master/resources/aws_regions.png "AWS Regions") 

Take as an example **EU Ireland Region**  

![alt text](https://github.com/Michael-Antczak/Introduction-to-Amazon-Web-Services/blob/master/resources/AZlinks.png "EU Ireland Region") 


### Exercise
Open a [new account](https://www.amazon.com/ap/signin?openid.assoc_handle=aws&openid.return_to=https%3A%2F%2Fsignin.aws.amazon.com%2Foauth%3Fresponse_type%3Dcode%26client_id%3Darn%253Aaws%253Aiam%253A%253A015428540659%253Auser%252Fawssignupportal%26redirect_uri%3Dhttps%253A%252F%252Fportal.aws.amazon.com%252Fbilling%252Fsignup%253Fredirect_url%253Dhttps%25253A%25252F%25252Faws.amazon.com%25252Fregistration-confirmation%2526state%253DhashArgs%252523%2526isauthcode%253Dtrue%26noAuthCookie%3Dtrue&openid.mode=checkid_setup&openid.ns=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0&openid.identity=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0%2Fidentifier_select&openid.claimed_id=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0%2Fidentifier_select&action=&disableCorpSignUp=&clientContext=&marketPlaceId=&poolName=&authCookies=&pageId=aws.ssop&siteState=pre-register%2Cen_US&accountStatusPolicy=P1&sso=&openid.pape.preferred_auth_policies=MultifactorPhysical&openid.pape.max_auth_age=120&openid.ns.pape=http%3A%2F%2Fspecs.openid.net%2Fextensions%2Fpape%2F1.0&server=%2Fap%2Fsignin%3Fie%3DUTF8&accountPoolAlias=&forceMobileApp=0&language=en_US&forceMobileLayout=0). 

[Back to top](#contents)

# Pricing and Free Tier    

How much can you get for [free](https://aws.amazon.com/free/?nc2=h_l2_cc)? A lot!

What if you have to [pay](https://aws.amazon.com/pricing/services/)? 

Learn to use [Total Cost of Ownership (TCO) Calculators](https://aws.amazon.com/tco-calculator/) 

[Back to top](#contents)  

# Certification

What if you decide to become an AWS expert? You may want to become [certified](https://aws.amazon.com/certification/our-certifications/).

But where to start? [AWS Certified Developer - Associate](https://aws.amazon.com/certification/certified-developer-associate/)

[Back to top](#contents)  

# Documentation 

Where to start? Look at the full [documentation](https://aws.amazon.com/documentation/?nc2=h_ql_ny_livestream_blu_t5) for every service. 

The AWS Glossary is [here](http://docs.aws.amazon.com/general/latest/gr/glos-chap.html)  

[Back to top](#contents)  

# Console

Ok, it's time to log into the AWS account. Point your browser to the following address:   

https://cyf-scotland.signin.aws.amazon.com/console   
 
Use the username and password that was given to you. 

[Back to top](#contents)  


# S3

> **Amazon Simple Storage Service (Amazon S3)** makes it simple and practical to collect, store, and analyze data - regardless of format – all at massive scale. S3 is **object storage** built to store and retrieve any amount of data from anywhere – web sites and mobile apps, corporate applications, and data from IoT sensors or devices.   

### Key terms   
#### 99.999999999% durability
If you store 10,000 objects with Amazon S3, you can on average expect to lose a single object once every 10,000,000 years.  
#### 99.9% monthly uptime - availability
Not more than 43 minutes of downtime per month.  
#### Size of objects
Up to 5 terabytes in size, each accompanied by up to 2 kilobytes of metadata. What is metadata? 
#### Bucket 
A container for stored objects. Every object is contained in a bucket. For example, if the object named **photos/puppy.jpg** is stored in the **johnsmith** bucket, then authorized users can access the object with the URL http://johnsmith.s3.amazonaws.com/photos/puppy.jpg.  

### Exercise - basics of S3
1. go to S3 service
1. click **Create bucket**
1. type a letter **t**. What happened? 
1. type **test** and hit create. What happened? 
1. type **test%^$**. What happened? 
1. use the following format for the bucket name **cyf-{YOUR_NAME}-{TODAYS_DATE}** or anything that works
1. create a new file inside any folder and call it **index.html**. Add a simple h1 tag with **Hello World!** inside.
1. upload to S3
1. now try to access the file in the browser. Did it work?
1. go to the file, the Permissions -> Public access -> Read object
1. now create another file called **home.html** and add another h1 **Hi, I am home**
1. try to access the file. Did it work? 
1. repeat the steps
1. delete the bucket

How much does it cost? [Pricing](https://aws.amazon.com/s3/pricing/)

### Exercise - Setting up a Static Website
Go to http://docs.aws.amazon.com/AmazonS3/latest/dev/HostingWebsiteOnS3Setup.html and follow the steps.
1. create a new bucket
1. open bucket Properties -> Static Website Hosting -> Enable
1. copy the endpoint. Can we access it in the browser? 
1. create bucket policy
1. upload a new index.html file. Does it work now? 

### Exercise
Now get one of your existing websites and make it live in a new bucket. 

[Back to top](#contents)


# IAM 
Now, try to go to **EC2** service. Can you make it? 

Watch [Introduction to AWS IAM](https://www.youtube.com/watch?v=Ul6FW4UANGc)

So what it does? Check the Introduction in the [docs](http://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)

Let's go to **IAM** service now.

### Key terms   
#### Root user 
Never use it for everyday work in AWS. Always create an admin account for yourself.    
#### IAM users 
Just users within your AWS account (doesn't have to be a human!).  
#### Federated identity 
Passwords and logins from other company can work with AWS. 
#### Group 
A collection of IAM users. Groups let you specify permissions for multiple users, which can make it easier to manage the permissions for those users. Here is more info how to [manage a group](http://docs.aws.amazon.com/IAM/latest/UserGuide/id_groups_manage.html)    
#### Policy
By default, users can't access anything in your account. You grant permissions to a user by creating a policy, which is a document that defines the effect, actions, resources, and optional conditions.  
The following example shows a policy that grants permission to perform Amazon DynamoDB actions (dynamodb:*) on the Books table in the account 123456789012 within the us-east-2 region. 

```json
{
  "Version": "2012-10-17",
  "Statement": {
    "Effect": "Allow",
    "Action": "dynamodb:*",
    "Resource": "arn:aws:dynamodb:us-east-2:123456789012:table/Books"
  }
}
```

![alt-text](http://docs.aws.amazon.com/IAM/latest/UserGuide/images/Relationship_Between_Entities_Example.diagram.png)

### Exercise
Create two new groups called **junior-devs** and **db-access**. Give **junior-devs** access to S3 and EC2, and give **db-access** group access to DynamoDB and EC2.  
Can you access and a create table in DynamoDB? If no, why not? 

Finish off with deleting the groups that you created. 

# EC2

> Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable **compute capacity** in the cloud. Amazon EC2 reduces the time required to obtain and boot **new server instances to minutes**, allowing you to **quickly scale capacity, both up and down**, as your computing requirements change. 

### Key terms   
#### Instance Types
[Instance types](https://aws.amazon.com/ec2/instance-types/) comprise varying combinations of CPU, memory, storage, and networking capacity and give you the flexibility to choose the appropriate mix of resources for your applications.
#### EC2 Pricing
* [On-Demand](https://aws.amazon.com/ec2/pricing/on-demand/) - you pay for compute capacity **by the hour** with no long-term commitments or upfront payments
* [Reserved Instances](https://aws.amazon.com/ec2/pricing/reserved-instances/pricing/) - provide you with a significant discount (up to 75%) compared to On-Demand instance pricing
* [Spot Instances](https://aws.amazon.com/ec2/spot/pricing/) - allow you to bid on spare Amazon EC2 computing capacity for up to 90% off the On-Demand price

### Exercise - [Launch Instance](https://aws.amazon.com/getting-started/tutorials/launch-a-virtual-machine/)
 
1. go to EC2 in the console and click **Launch Instance**
1. choose an Amazon Machine Image (AMI): In step 1 of the wizard, we recommend the Amazon Linux AMI (free-tier eligible).
1. choose an instance type: we recommend the t2.micro (free-tier eligible).
1. security group: In step 6, configure your virtual firewall. Choose existing SG. 
1. launch instance: In step 7, review your instance configuration and choose "Launch".
1. create a key pair: Select "Create a new key pair" and assign a name. The key pair file (.pem) will download automatically - save this in a safe place as we will later use this file to log in to the instance. Finally, choose "Launch Instances" to complete the set up.

### Exercise - Connect to your instance
Not sure how file permissions work on Linux? Check [here](https://www.pluralsight.com/blog/it-ops/linux-file-permissions)
Follow step 3 from the [tutorial](https://aws.amazon.com/getting-started/tutorials/launch-a-virtual-machine/)

When you finished, go ahead and terminate the server. 

### Exercise - [Install LAMP stack](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/install-LAMP.html)
1. create another server and use the same set of keys
1. run `sudo yum update -y`
1. `sudo yum install -y httpd24 php56 mysql56-server php56-mysqlnd` and check the IP address in the browser
1. start Apache server `sudo service httpd start` and check the IP address in the browser
1. configure the Apache web server to start at each system boot `sudo chkconfig httpd on`
1. `chkconfig --list httpd`
1. go to `/var/www/html`, create file `index.html` and add some HTML content
1. go back to the browser and check the IP address
1. create a simple PHP file in the Apache document root `<?php phpinfo(); ?>`
1. go to the browser and add `/phpinfo.php`

### Excercise - Setup Node.js
Plan A is to use [this](https://nodejs.org/en/download/package-manager/#enterprise-linux-and-fedora)
1. start a new server
1. run `node` what do you see? 
1. run `curl --silent --location https://rpm.nodesource.com/setup_8.x | sudo bash -`
1. then `sudo yum -y install nodejs`
1. run `node` now

Plan B is to use [this](http://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/setting-up-node-on-ec2-instance.html)

### Exercise - Setup Express app
1. `sudo npm install -g express-generator@4`
1. `sudo express foo`
1. `cd foo`
1. `sudo npm install` 
1. `sudo PORT=80 npm start`


[Back to top](#contents)  

# Exercises
1. Wordpress on EC2

# Resources
[Introduction to Cloud Computing](https://acloud.guru/learn/intro-cloud-computing)  
[AWS Tech Essentials](https://acloud.guru/learn/aws-technical-essentials)  

# Links

### AWS
[What is Cloud Computing?](https://aws.amazon.com/what-is-cloud-computing/)
[Regions and Availability Zones](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html)  
[Getting Started](https://aws.amazon.com/getting-started/resource-center/?nc2=h_ql_ny_livestream_blu_b_t2)  
[Build a Serverless Web Application](https://aws.amazon.com/getting-started/serverless-web-app/)  
[Deploy a Node.js Web App](https://aws.amazon.com/getting-started/projects/deploy-nodejs-web-app/)  
[Cloud Services Pricing](https://aws.amazon.com/pricing/services/)  
[Startups](https://aws.amazon.com/startups/)  
[All Customer Success Stories](https://aws.amazon.com/solutions/case-studies/all/)
[AWS Certifications](https://aws.amazon.com/certification/our-certifications/)

[Back to top](#contents)

### Others
[5 Numbers That Illustrate the Mind-Bending Size of Amazon's Cloud](https://www.bloomberg.com/news/2014-11-14/5-numbers-that-illustrate-the-mind-bending-size-of-amazon-s-cloud.html)  
[Magic Quadrant for Cloud Infrastructure as a Service, Worldwide](https://www.gartner.com/doc/reprints?id=1-2G2O5FC&ct=150519&st=sb)
