aws_big_data_demo
=================

Goal
=====
To demostrate multiple big data technologies quickly via a simple log analysis use case.  Note this is heavily based on a presentation at AWS Re:Invent.

This will ingest apache logs in Kinesis, tranform them via EMR and store in S3, finally reading from S3 in parallel into Redshift for analysis.

Steps
=====

1.  In AWS console create new IAM user account with PowerUserAccess.
  
  Note the following
    * User name
    * Access Key
    * Secret Key

2.  In the AWS console create a new t2.micro instance.  This will be used to launch all other services.
