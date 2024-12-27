# 2.12_FaaS_Assignment

Given a Lambda function that is triggered upon the creation of files in an S3 bucket, answer the following:

1.  What is the purpose of the execution role on the Lambda function?
    # Execution Role is used by Lambda to access other AWS Services.
      
2.  What is the purpose of the resource-based policy on the Lambda function?
    # Resource based policies is used to grant access for other AWS services to access Lambda.
      
3. If the function is needed to upload a file into an S3 bucket, describe (i.e no need for the actual policies)
     - What is the needed update on the execution role?
       # Allow Lambda to upload file into S3 Bucket.
     
     - What is the new resource-based policy that needs to be added (if any)?
       # Allow S3 bucket to access and invoke Lambda Function.
      
Create a public github repository that has a README.md file, containing the above answers.

Submission is the url to your public github repository.



