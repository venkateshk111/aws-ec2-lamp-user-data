# aws-ec2-lamp-user-data
user data script for EC2 LAMP server 

## Method 1
- Copy the code from below file to user-data
  - [ec2-lamp.sh](./ec2-lamp.sh)

## Method 2

- Add below code to user-data (or you can copy the file content from [bootstap.sh](bootstarp.sh))
  ```
  #include
  https://s3.amazonaws.com/immersionday-labs/bootstrap.sh
  ```

## Links
https://catalog.us-east-1.prod.workshops.aws/workshops/f3a3e2bd-e1d5-49de-b8e6-dac361842e76/en-US/basic-modules/10-ec2/ec2-linux/2-ec2
https://uploads-ssl.webflow.com/5f1c97b8a30ead7807491ac2/5f899b980a9e9f40924a2d9a_EC2LinuxLab.pdf
https://github.com/nclouds/immersion-day-basics
