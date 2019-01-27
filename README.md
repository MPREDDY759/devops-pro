# Links for the DEVOPS Pro Exam

In addition to the DEVOPs exam blueprint https://d1.awsstatic.com/training-and-certification/docs-devops-pro/AWS%20Certified%20DevOps%20Engineer%20Professional_Exam%20Guide_v1.5_FINAL%20(2).pdf 


https://aws.amazon.com/blogs/devops/use-a-creationpolicy-to-wait-for-on-instance-configurations/
## Blue Green 
https://d0.awsstatic.com/whitepapers/AWS_Blue_Green_Deployments.pdf
## CICD
https://d0.awsstatic.com/whitepapers/DevOps/practicing-continuous-integration-continuous-delivery-on-AWS.pdf

## Opsworks 
https://aws.amazon.com/opsworks/stacks/faqs/
https://docs.aws.amazon.com/opsworks/latest/userguide/welcome_classic.html
https://docs.aws.amazon.com/opsworks/latest/userguide/workingcookbook-installingcustom-enable.html
https://docs.aws.amazon.com/opsworks/latest/userguide/workingcookbook-assigningcustom.html
https://docs.aws.amazon.com/opsworks/latest/userguide/workingcookbook-events.html
https://aws.amazon.com/blogs/devops/running-docker-on-aws-opsworks
https://docs.aws.amazon.com/opsworks/latest/userguide/workinginstances-os.html
https://docs.aws.amazon.com/opsworks/latest/userguide/welcome.html
https://docs.aws.amazon.com/opsworks/latest/userguide/troubleshoot-debug-login.html
https://docs.aws.amazon.com/opsworks/latest/APIReference/API_DeploymentCommand.html
https://docs.aws.amazon.com/opsworks/latest/userguide/workingapps-deploying.html
https://docs.aws.amazon.com/opsworks/latest/userguide/workingapps-connectdb.html
https://docs.aws.amazon.com/opsworks/latest/userguide/workingstacks-commands.html
AWS OpsWorks Stacks provides a set of stack commands, which you can use to perform a variety of operations on a stack's instances. To run a stack command, click Run Command on the Stack page. You then choose the appropriate command, specify any options, and press the button at the lower right, which will be labeled with the command's name.
https://docs.aws.amazon.com/opsworks/latest/userguide/workingsecurity-updates.html
https://docs.aws.amazon.com/opsworks/latest/userguide/other-services-redis.html

## Code Deploy
https://docs.aws.amazon.com/codedeploy/latest/userguide/reference-appspec-file.html
https://docs.aws.amazon.com/codedeploy/latest/userguide/application-specification-files.html
An application specification file (AppSpec file), which is unique to AWS CodeDeploy, is a YAML-formatted or JSON-formatted file. The AppSpec file is used to manage each deployment as a series of lifecycle event hooks, which are defined in the file.
https://docs.aws.amazon.com/codedeploy/latest/userguide/primary-components.html
https://docs.aws.amazon.com/codedeploy/latest/userguide/deployment-steps.html

## Code Build 
https://docs.aws.amazon.com/codebuild/latest/userguide/planning.html

## Cloud Formation 
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/parameters-section-structure.html
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/troubleshooting.html

### Use cloud formation console 
EC2 go to the cloud-init and can logs.    
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-waitcondition.html
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-changesets.html
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-attribute-updatepolicy.html
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/best-practices.html

### aws cloudformation list-stacks 
https://docs.aws.amazon.com/cli/latest/reference/cloudformation/list-stacks.html
https://docs.aws.amazon.com/cli/latest/reference/cloudformation/list-stack-resources.html

## Kinesis 
https://docs.aws.amazon.com/streams/latest/dev/introduction.html

## Cloud Watch 
https://docs.aws.amazon.com/AmazonCloudWatch/latest/events/WhatIsCloudWatchEvents.html
https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/StartTheCWLAgent.html
https://docs.aws.amazon.com/AmazonCloudWatch/latest/events/LogASGroupState.html
https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/UsingAlarmActions.html
https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/publishingMetrics.html
https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/aws-services-cloudwatch-metrics.html
https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/cloudwatch_concepts.html

## CloudTrail
https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-log-file-validation-intro.html

## Elastic Bean Stalk 
Elastic Beanstalk default deployments is rolling: 
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features.rolling-version-deploy.html
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/environments-create-wizard.html
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/customize-containers-ec2.html
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features.CNAMESwap.html
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/applications-lifecycle.html
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features.deploy-existing-version.html
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/AWSHowTo.RDS.html
AWS Elastic Beanstalk provides support for running Amazon Relational Database Service (Amazon RDS) instances in your Elastic Beanstalk environment. This works great for development and testing environments. However, it isn't ideal for a production environment because it ties the lifecycle of the database instance to the lifecycle of your application's environment.
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features.rollingupdates.html
Rolling updates occur when you change settings that require new EC2 instances to be provisioned for your environment. 
Rolling deployments occur whenever you deploy your application and can typically be performed without replacing instances in your environment.  
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features-managing-env-types.html 
Elastic Beanstalk can have either Single Instance or Load-Balanced (autoscaling) 
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_docker_ecs.html

https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/environment-configuration-savedconfig.html

### Hosted non-standard application on ElasticBeanStalk 
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_docker.html
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-getting-started.html
https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb3-cli-git.html

## EBS
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/snapshot-lifecycle.html

## EC2 
Run Command - provides access to each EC2 instance without logging in 
https://docs.aws.amazon.com/systems-manager/latest/userguide/rc-console.html
https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-scale-based-on-demand.html

### ReplaceUnHealthy 
https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-suspend-resume-processes.html
https://docs.aws.amazon.com/autoscaling/ec2/userguide/healthcheck.html
https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-instance-termination.html#instance-protection-instance 
https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-instance-termination.html

### Auto Scaling
https://docs.aws.amazon.com/autoscaling/ec2/userguide/lifecycle-hooks.htm

![alt text](https://docs.aws.amazon.com/autoscaling/ec2/userguide/images/lifecycle_hooks.png)

https://docs.aws.amazon.com/autoscaling/ec2/userguide/Cooldown.html
The cooldown period is a configurable setting for your Auto Scaling group that helps to ensure that it doesn't launch or terminate additional instances before the previous scaling activity takes effect. After the Auto Scaling group dynamically scales using a simple scaling policy, it waits for the cooldown period to complete before resuming scaling activities.
Important Amazon EC2 Auto Scaling supports cooldown periods when using simple scaling policies, but not when using target tracking policies, step scaling policies, or scheduled scaling.
https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-enter-exit-standby.html
https://docs.aws.amazon.com/autoscaling/ec2/userguide/AutoScalingGroupLifecycle.html

## ELB
https://docs.aws.amazon.com/elasticloadbalancing/latest/classic/access-log-collection.html

## DynamoDB
https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/best-practices.html
https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/best-practices.html

## Lambda
https://docs.aws.amazon.com/lambda/latest/dg/with-s3.html
Amazon S3 can publish events (for example, when an object is created in a bucket) to AWS Lambda and invoke your Lambda function by passing the event data as a parameter. This integration enables you to write Lambda functions that process Amazon S3 events. In Amazon S3, you add bucket notification configuration that identifies the type of event that you want Amazon S3 to publish and the Lambda function that you want to invoke.

## Concurrent Lambda 
https://docs.aws.amazon.com/lambda/latest/dg/concurrent-executions.html


## Datapipeline
https://docs.aws.amazon.com/datapipeline/latest/DeveloperGuide/what-is-datapipeline.html
* A pipeline definition specifies the business logic of your data management. For more information, see Pipeline Definition File Syntax.
* A pipeline schedules and runs tasks by creating Amazon EC2 instances to perform the defined work activities. You upload your pipeline definition to the pipeline, and then activate the pipeline. You can edit the pipeline definition for a running pipeline and activate the pipeline again for it to take effect. You can deactivate the pipeline, modify a data source, and then activate the pipeline again. When you are finished with your pipeline, you can delete it.
* Task Runner polls for tasks and then performs those tasks. For example, Task Runner could copy log files to Amazon S3 and launch Amazon EMR clusters.Task Runner is installed and runs automatically on resources created by your pipeline definitions. You can write a custom task runner application, or you can use the Task Runner application that is provided by AWS Data Pipeline. For more information, see Task Runners.

## RDS
https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Concepts.MultiAZ.html

AWS CLI describe-db-instances command, or the Amazon RDS API DescribeDBInstances action to find the secondary AZ.

## Route 53 
https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/dns-failover.html
