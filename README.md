About this folder

this folder contains AWS Cloudformation yaml template files

1. s3-bucket-exercise - creates an S3 bucket
2. s3-bucket - creates another S3 bucket

    Type: AWS::S3::Bucket
    Properties used:  BucketName
    Properties available: https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/aws-resource-s3-bucket.html

3. vpc - VPC template

4. iam - IAM template creates and IAM User, IAM Group, group membership, IAM Role, and IAM Policy

    Type: AWS::IAM::User
    Properties used: UserName, ManagedPolicyArns
    Properties available: https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/aws-resource-iam-user.html
    
    Type: AWS::IAM::Group
    Properties used: GroupName
    Properties available: https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/aws-resource-iam-group.html

    Type: AWS::IAM::UserToGroupAddition
    Properties used: GroupName, Users
    Properties available: https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/aws-resource-iam-usertogroupaddition.html

    Type: AWS::IAM::Role
    Properties used: AssumeRolePolicyDocument, ManagedPolicyArns
    Properties available: https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/aws-resource-iam-role.html

    Type: AWS::IAM::Policy
    Properties used: PolicyDocument, PolicyName, Roles
    Properties available: https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/aws-resource-iam-policy.html

5. ec2 - Application load balancer template

6. asg - Auto scaling group template



