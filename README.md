![logo](./assets/flysorter-logo.png)
# Welcome
The following documentation is specifically for the ***BACK END*** repository. If you are looking for the ***FRONT END*** respository click [HERE](https://github.com/EmeryP/flySorter-front-end-v2).

# Description
FlySorter is an inventory management application for the Seattle-based company: [FlySorter](https://flysorter.com/). FlySorter builds machines to sort fruit flies so they can be used for scientific research. This application keeps track of those machine assemblies, sub-assemblies, and the parts that belong to those sub assemblies. These components are displayed on the page and allows the user to click on a sub-assembly to reveal the parts that makeup that sub-assembly. The table also allows the user to filter parts and search for a part in order to make finding particular parts faster and easier for the user.

# Why It Matters
_"In 1908, looking to test Mendel’s theories on heredity, Thomas Hunt Morgan began studying Drosophila melanogaster (also known as the fruit fly or vinegar fly) in his “Fly Room” at Columbia University. Dr. Morgan and his students studied flies, looking for mutations, and found that some individuals had white eyes instead of the usual red eyes. Experimentation on the prevalence and propagation of the mutation led to the first proof that the chromosomal theory of inheritance was correct, and established drosophila as the first model research organism. The use of drosophila has been extremely fruitful in the past 100 years. Since Dr. Morgan’s experiments, drosophila research has been featured in over 100,000 scientific papers. This includes being involved in Nobel prize-winning research five times (in 1933, 1946, 1995, 2004, and 2011)."_ — [The Research Value of Drosophila Melangoaster](http://powersscientific.com/the-research-value-of-drosophila-melanogaster/)

# Languages, Technologies, Frameworks, & Libraries Used
The following technologies were used to develop the backend:

1. AWS [Lambda](https://aws.amazon.com/lambda/) running NodeJS 6.10
2. AWS [Aurora](https://aws.amazon.com/rds/aurora/) running Serverless MySQL
3. AWS [Cognito](https://aws.amazon.com/cognito/) for authentication
4. AWS [API Gateway](https://aws.amazon.com/api-gateway/) with CORS
5. AWS [CloudWatch](https://aws.amazon.com/cloudwatch/) for logging

# Running the application
The original backend for the FlySorter application was developed using Node, Express, and MongoDB. This original version could be deployed locally. However, this release of the application is being hosted exclusively from Amazon Web Services, and the code stored on this repository now consists of fragments and snippets that were ultimately deployed to AWS.

If you would like to view the latest deployement of this application please click [HERE](http://flyorterfrontendv2-20181221115532-hostingbucket.s3-website-us-west-2.amazonaws.com).

# Testing
Backend testing for this application was performed exclusively from within AWS using the [API Gateway](https://aws.amazon.com/api-gateway/) testing tools and test suites run via [AWS Cloud9](https://aws.amazon.com/cloud9/).

# Models
![ERD](assets/ERD.png)


# Project Team
### Original Team 
* [Benjamin West](https://github.com/bgwest) | | 
[Daniel Frey](https://github.com/fncreative) | | 
[Tom North](https://github.com/tnorth93) | | 
[Wyatt Pefley](https://github.com/peffles)
____

### AWS Serverless Migration Team
* [Ben Harris](https://github.com/harrishills) | |
[David Chambers, Jr.](https://github.com/dlchambersjr) | |
[Emery Parks](https://github.com/emeryP) | |
[Timothy Li](https://github.com/timinis) | |
[Trevor Stam](https://github.com/trevorstam)

____
