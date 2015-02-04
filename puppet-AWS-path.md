Integrating AWS CloudFormation with Puppet
===================

Overview
--------

AWS CloudFormation gives you an easy way to create the set of resources such as Amazon EC2 instance, Amazon RDS database instances and Elastic Load Balancers needed to run your application. The template describes what resources you need and AWS CloudFormation takes care of how: provisioning the resources in an orderly and predictable fashion, handling and recovering from any failures or issues. For more details of using AWS CloudFormation see the [AWS CloudFormation product detail page](http://aws.amazon.com/cloudformation/).

While AWS CloudFormation takes care of provisioning all the resources, it raises the obvious question of how your application software is deployed, configured and executed on the Amazon EC2 instances. There are many options, each of which has implications on how quickly your application is ready and how flexible you need to be in terms of deploying new versions of the software. The remainder of this document shows how to use the AWS CloudFormation bootstrap helper scripts to deploy applications using Puppet. It builds on the features of AWS CloudFormation introduced in the whitepaper [Bootstrapping Applications With AWS CloudFormation](https://s3.amazonaws.com/cloudformation-examples/BoostrappingApplicationsWithAWSCloudFormation.pdf).

For the full whitepaper, please go to: [Integrating AWS CloudFormation with Puppet](https://s3.amazonaws.com/cloudformation-examples/IntegratingAWSCloudFormationWithPuppet.pdf).
 
 



