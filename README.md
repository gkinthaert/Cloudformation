About this folder

this folder contains AWS Cloudformation yaml files

1. s3-bucket-exercise
2. s3-bucket

    Properties used:  BucketName

    Properties available (for full list consult https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/aws-resource-s3-bucket.html)

Type: AWS::S3::Bucket
Properties:
  AbacStatus: String
  AccelerateConfiguration: 
    AccelerateConfiguration
  AccessControl: String
  AnalyticsConfigurations: 
    - AnalyticsConfiguration
  BucketEncryption: 
    BucketEncryption
  BucketName: String
  CorsConfiguration: 
    CorsConfiguration
  IntelligentTieringConfigurations: 
    - IntelligentTieringConfiguration
  InventoryConfigurations: 
    - InventoryConfiguration
  LifecycleConfiguration: 
    LifecycleConfiguration
  LoggingConfiguration: 
    LoggingConfiguration
  MetadataConfiguration: 
    MetadataConfiguration
  MetadataTableConfiguration: 
    MetadataTableConfiguration
  MetricsConfigurations: 
    - MetricsConfiguration
  NotificationConfiguration: 
    NotificationConfiguration
  ObjectLockConfiguration: 
    ObjectLockConfiguration
  ObjectLockEnabled: Boolean
  OwnershipControls: 
    OwnershipControls
  PublicAccessBlockConfiguration: 
    PublicAccessBlockConfiguration
  ReplicationConfiguration: 
    ReplicationConfiguration
  Tags: 
    - Tag
  VersioningConfiguration: 
    VersioningConfiguration
  WebsiteConfiguration: 
    WebsiteConfiguration


3. vpc
4. iam
5. ec2


