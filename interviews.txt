#Daily activities : i login check the build tickets as per give the build  and also look into the any build fails check and reslove the issues and inform to the seniors if relsoved.

############################################################################
we using jenkins  for Declaretive pipeline , when the developer pushes code to the github repo automatically it trigger the job in jenkins with help of the webhook. it will go to the stages like build,test and deploy. in the build we use docker file  to build the image and store that image we use the
repository like nexus and for the deployment we are using the kubernetes(container orchestration tool) 

#In my organisation multiple builds are going on for that i need to create the release branch as well and merge it as well. 
#whenever any merge confilts arises i need to fix that with help of the developer

#I have exposure in the aws services like loadblancer,autoscaling, ebs,s3...
#for configuration side we are using ansible
#for the terrafom build infrasture in aws 
# I need to check the jenkins dashboard becasue multiple builds going on it.
#if any build fail issue i need to check with in console, if its a realtime issue(complaition issue) i need to inform to the developer.
#if its a build environmental type of issue i need to take care of it
#if any manulle task i need to automate it by using a shellscript.
#

#Merge confilt :
we have a three types fo environments like nonprod(dev,qa,uat) preprod(its for customer requirement wheather requirement met with quality critia) ,prod 
# if problem occures in the relesase branch,  we again create the bug(or)hot fix branch. once issue is fixed  then merge code to dev branch at that time any merge conflict arises i relsove the merge conflicts with help of the development team.

#how many developers in the project ? 
 we deployment with respect of thorugh differnet kinds  microservices like 
 for each microservices some developer using the python and some developer usign the node.js basicaaly.

# how is your  pipeline is written ?
declarative way , there is a  four stages in a pipeline (10 minutes)

#how the jenkins step ?
