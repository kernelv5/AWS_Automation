AWS AutoScaling with Ansible ( DevOps / Automation ) 

This script applicable if you already have 
- Auto Scaling Group
- One fixed AMI which used for AMI update
- Existing Security Groups 


This script will turn on the AMI then wait for 5 min then stop and start creating AMI. From that AMI it will create auto-scaling configuration and then that will update as well. 

In my AutoScaling AMI , during startup it complete pull and update the code. 


** This script is tested and installed. 
-- Anyone is allow to use that script at their own risk. 

For help you can comment or email. 
