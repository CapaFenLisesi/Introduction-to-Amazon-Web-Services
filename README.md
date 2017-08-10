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
> Amazon Web Services (AWS) describes both a **technology** and **a company**. The company AWS is a subsidiary of **Amazon.com** and provides **on-demand cloud computing platforms to individuals, companies and governments, on a paid subscription basis with a free-tier option available for 12 months**. The technology allows subscribers to have at their disposal **a full-fledged virtual cluster of computers, available all the time, through the internet**. AWS's version of virtual computers have most of the attributes of a real computer including hardware (CPU(s) & GPU(s) for processing, local/RAM memory, hard-disk/SSD storage); a choice of operating systems; networking; and pre-loaded application software such as web servers, databases, CRM, etc. Each AWS system also virtualizes its console I/O (keyboard, display, and mouse), allowing AWS subscribers to connect to their AWS system using a modern browser. The browser acts as a window into the virtual computer, letting subscribers log-in, configure and use their virtual systems just as they would a real physical computer. They can choose to deploy their AWS systems to provide internet-based services for their own and their customers' benefit.  

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
- provide API
- process data on servers (computations)
- host a small application
- host a high traffic service
- host WordPress website
- you name it

### Jobs with AWS
How big is the market and what type of [jobs](http://uk.dice.com/index.php?SearchMode=StandardSearch&SearchFilter=SearchFilter&Mode=AdvertSearch&lang=en&AdvertShortlistLimit=50&SearchTerms=AWS&ClientTypeFilter_1=1&ClientTypeFilter_2=2&) can you get? 
- developer 
- deployment
- architecture design
- startup

### Who uses AWS? 
We don't have enough time here. Some of the services that you use on a daily basis use AWS, like:
- [Airbnb](https://aws.amazon.com/solutions/case-studies/airbnb/)
- [Spotify](https://aws.amazon.com/solutions/case-studies/spotify/)
- [Netflix](https://aws.amazon.com/solutions/case-studies/netflix/)

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

<p>[Back to top](#contents)</p>

# Pricing and Free Tier 

How much can you get for [free](https://aws.amazon.com/free/?nc2=h_l2_cc)? A lot!

What if you have to [pay](https://aws.amazon.com/pricing/services/)? 

Learn to use [Total Cost of Ownership (TCO) Calculators](https://aws.amazon.com/tco-calculator/) 

<p>[Back to top](#contents)</p>

# Certification

What if you decide to become an AWS expert? You may want to become [certified](https://aws.amazon.com/certification/our-certifications/).

But where to start? [AWS Certified Developer - Associate](https://aws.amazon.com/certification/certified-developer-associate/)

<p>[Back to top](#contents)</p>

# Documentation

Where to start? Look at the full [documentation](https://aws.amazon.com/documentation/?nc2=h_ql_ny_livestream_blu_t5) for every service. 

The AWS Glossary is [here](http://docs.aws.amazon.com/general/latest/gr/glos-chap.html)  

<p>[Back to top](#contents)</p>

# Console

Ok, it's time to log into the AWS account. Point your browser to the following address:   

https://cyf-scotland.signin.aws.amazon.com/console   
 
Use the username and password that was given to you. 

<p>[Back to top](#contents)</p>

# S3

> **Amazon Simple Storage Service (Amazon S3)** makes it simple and practical to collect, store, and analyze data - regardless of format – all at massive scale. S3 is **object storage** built to store and retrieve any amount of data from anywhere – web sites and mobile apps, corporate applications, and data from IoT sensors or devices.   

It is designed to deliver **99.999999999% durability**. S3 guarantees **99.9% monthly uptime**.

What does it mean?  
**Durability** - if you store 10,000 objects with Amazon S3, you can on average expect to incur a loss of a single object once every 10,000,000 years.  
**Availability** - that is, not more than 43 minutes of downtime per month.  
**Size of objects** - up to 5 terabytes in size, each accompanied by up to 2 kilobytes of metadata. What is metadata? 

**Bucket** - a container for stored objects. Every object is contained in a bucket. For example, if the object named **photos/puppy.jpg** is stored in the **johnsmith** bucket, then authorized users can access the object with the URL http://johnsmith.s3.amazonaws.com/photos/puppy.jpg.  

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

<p>[Back to top](#contents)</p>

# EC2
Now, try to go to **EC2** service.

<p>[Back to top](#contents)</p>

# IAM 
Go to **IAM** service.

# Exercises
1. Node.js app
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

<p>[Back to top](#contents)</p>

### Others
[5 Numbers That Illustrate the Mind-Bending Size of Amazon's Cloud](https://www.bloomberg.com/news/2014-11-14/5-numbers-that-illustrate-the-mind-bending-size-of-amazon-s-cloud.html)  
[Magic Quadrant for Cloud Infrastructure as a Service, Worldwide](https://www.gartner.com/doc/reprints?id=1-2G2O5FC&ct=150519&st=sb)
