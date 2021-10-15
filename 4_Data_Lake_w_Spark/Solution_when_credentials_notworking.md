# Backgroud
One of problems I met is the credential doesn't work. The only information I received is that I need to create a new user. Here is the note to explain how to create a new account. 
Appreciate Vivian's help to figure out how to proceed. She is also the person who reminded me that I should try to document this and share.

# The error msg
<img src="https://github.com/ClaireChiang91/Work_from_DataEngineering_Udacity/blob/main/4_Data_Lake_w_Spark/1_error_msg_credential_notworking.png" width="1000">

# How to solve this:
## Step1: You need to go to AWS following the below steps:
Click "Launch AWS Gateway"
<img src="https://github.com/ClaireChiang91/Work_from_DataEngineering_Udacity/blob/main/4_Data_Lake_w_Spark/2_Launch%20AWS%20Gateway.png" width="1000">
Click "Open AWS Console"
<img src="https://github.com/ClaireChiang91/Work_from_DataEngineering_Udacity/blob/main/4_Data_Lake_w_Spark/3_Open_AWS_Console.png" width="1000">

## Step2: Once you're transferred to AWS webpage, fine IAM webpage:
Click "Services" at the left top 
Then Click "IAM" under "Security, Identity, & Compliance"
<img src="https://github.com/ClaireChiang91/Work_from_DataEngineering_Udacity/blob/main/4_Data_Lake_w_Spark/4_Services_IAM.png" width="1000">

## Step3: Create new user acct
Click "Users" at the left side 
Then click "Add users" at the right side 
<img src="https://github.com/ClaireChiang91/Work_from_DataEngineering_Udacity/blob/main/4_Data_Lake_w_Spark/5_IAM_users.png" width="1000">

Then you will move to the next page to input the user name.
Input "username"
Click both: <br/>
  (1)Access key - Programmatic access<br/>
  (2)Password - AWS management Console access<br/>
<img src="https://github.com/ClaireChiang91/Work_from_DataEngineering_Udacity/blob/main/4_Data_Lake_w_Spark/6_Add_User_name.png" width="1000">

Once you fill in all required fields, click "Next: Permissions"

Further, you will need to set up permission. The webpage will move to the below:
<img src="https://github.com/ClaireChiang91/Work_from_DataEngineering_Udacity/blob/main/4_Data_Lake_w_Spark/7_Attached_existing_policy.png" width="1000">

Choose "Attach existing policies directly" 
Choose "AmazonS3FullAccess"

Once you fill in all fields, click "Next: Tags"
Then you will see the below webpage for review. 
<img src="https://github.com/ClaireChiang91/Work_from_DataEngineering_Udacity/blob/main/4_Data_Lake_w_Spark/8_click_create.png" width="1000">

Once the content is fine with you, click "Create user"
Finally, you will see the below success confirmation.
<img src="https://github.com/ClaireChiang91/Work_from_DataEngineering_Udacity/blob/main/4_Data_Lake_w_Spark/AWS_Final_create_new_user_confirmation.png" width="1000">


