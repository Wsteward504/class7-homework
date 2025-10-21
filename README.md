# Homework Week 1
## Readme Instructions on Creating and Tearing down an EC2
Log into AWS, preferably with your IAM user. Use Root user if need be.
Locate the search bar and type in EC2.
Select EC2.
Locate Network & Security on left hand side of screen.
Select Security Groups.
Locate and select create Security Group "Orange button on the top right"
Under Basic details/Security group name give your security group a name.
Copy your Security Group name and paste it the description section next.
Use default VPC.
Go to Inbound rules and select HTTP in the Type section.
Select Anywhere-IPv4 in the Source type.
Type anything you want in the Description section.
# You see Outbound rules--DON'T TOUCH "DA FUC"
Add new tag, which is optional.
Give Key a name.
Give Value a name.
Select Create sercurity group "Orange button on the bottom right."
Select EC2 at top left of screen.
Select Instances next "located directly below."
Select Launch instances "Orange button on the top right."
Go to Name and Tags and name your instance.
Amazon Linux is default Application and OS Images "keep it."
AMI, Description, and Architecture is at default...Don't touch it.
Instance Type will be ethier t3.micro or T2 nano.
Select Proceed without a key pair "for now" in Key pair section.
Network Settings leave as is.
Firewall select existing security group.
Common security group select your security group you just made.
Go to Advanced details and select it.
Go all the way down to User data and paste Theo's repo in it.
Select Launch instance "Orange button at bottom right of screen."
Select the link giving to you in the green area titled Success.
Click the copy button under Public DNS.
Open a new tab and type http:// and paste your public DNS and hit enter.
Preform tear down. 
Select Dashboard under the EC2 title.
Select the check box next to your running instance.
Select Instance state.
Select Terminate (delete) instance.
Refresh screen.
Once showing 0 running instances sign out.
