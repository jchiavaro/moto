Moto Changelog
===================

Latest
------

0.4.25
------

    * ASG tags
    * ContainerInstance handling in ECS
    *

0.4.22
------

    * Add basic lambda endpoints
    * Support placement for EC2
    * Cleanup API versions


0.4.21
------

    * Fix bug with wrong response matches for S3

0.4.20
------

    * mock_s3 and mocks3bucket_path are now the same thing. The server decides
    which interface to is being used based on the request Host header. We will
    evetually deprecate mocks3bucket_path.
    * Basic ECS support
    * More Dynamo querying and indexes
    * Add Kinesis and ELB tags
    * Add JSON responses for EMR
    * Fix root instance volume to show up in other EBS volume calls
