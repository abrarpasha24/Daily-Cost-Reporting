# EC2-Reporting
Simple architecture to generate a daily report of the usage of EC2, EBS &amp; EIPs.

<h3>This AWS architecture focuses on generating a daily report which showcases the usage of three AWS services namely <b>EC2, EBS, EIP(Elastic IPs)</b></h3>

<h4>This is achived through a Cloudformation template which generates the following:</h4>
<h5>-AWS Lambda Function: To compute the costs for the aforementioned resources</h5>
<h5>-AWS EventBridge: To trigger the Lambda function at 7:00 PM everyday.</h5>
<h5>-AWS Simple Email Service(SES): To send an email to the designated email account at the mentioned time everyday.</h5>


![image](https://github.com/abrarpasha24/EC2-Reporting/assets/30976576/b47474dc-14f8-4116-bdd0-a4a329bb08b7)
