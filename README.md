# cf-info
The Cloud Foundry platform is abstracted as a set of large-scale distributed services.
It uses Cloud Foundry Bosh to operate the underlying infrastructure from IaaS providers 
(e.g., VMware, Amazon AWS, OpenStack).

cf login --skip-ssl-validation -a https://api.run.pivotal.io -u <USER>
  
cf push <appname> -b <buildPack> -m 2G -t 240 -p <appPath>
  
cf restage <appname>
  
cf apps

cf orgs

cf spaces

cf logs <appName>
  
cf logs <appName> --instance INSTANCE
  
cf scale <appName> -i <NoOfInstances>
  
cf scale <appName> -m <memoryInGig>
  
cf start <appName>
  
cf stop <appName>
  
docs.cloudfoundry.org/deploying/ec2/aws_steps.html


“BOSH is a project for release engineering, deployment, and lifecycle management of large-scale cloud software”
Sometimes referred to a “Datacenter OS”
Provisions/deploys/monitors/updates/recovers with zero-to-minimal downtime
Supports many IaaS providers via Cloud Provider Interfaces (CPI)
BOSH, an open source tool for release engineering, deployment, lifecycle management, and distributed systems monitoring

Deploying Cloud Foundry with cf-deployment
