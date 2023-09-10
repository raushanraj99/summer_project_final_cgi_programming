# summer_project_final_cgi_programming

enter commad for s3 and ec2 because they are our own command:
ec2 : 
ec2 ls : to check the list of ec2 instance launched
ec2 -c 2 : to create the number of instance launc ie 2 here
ec2 -d Instance_id : delete the running instance id 

for S3 :
Note: befor using this you have to crate the IAM role
to first create the IAM role ie the service in AWS. Now Create secret_access_id and Secret_access_key.

commands :
s3 ls : to check the list of bucket created
s3 -n bucket_name : to crate the new bucket with unique bucket_name
s3 -d bucket_name: to delete the s3 bucket 

docker : 
run all the docker command
eg. docker images
docker ps
docker ps -a
docker pull ubuntu:14.04
docker run -dit imagesname eg : docker run -dit ubuntu:14.04

email: 
send email from gmail account 
create the gmail security app key of your gmail/ sender gmail account
we will user the secret key instead of original password here
sender_email : enter sender email
sender_password : enter sender app key

sms
create account on your twilio account
paste all the data in double quotation
creata account id : ie account_sid
auth_token : create authorized tocken and paste
verified_number: paster the number which have you used to create the twilio account or any twilio verified number
