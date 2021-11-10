# aws-ethnus
The main architecture of building a face detection app on AWS:
* Connecting EC2, S3 and enabling face rekognition services.
* In EC2-In order to create an instance * Select OS
          * Configure RAM and Processor.
          * Configure Storage 
          * Configure Security
  Download the key pair and convert it to the key pair. ppk extension file to ppk file using puttygen server.
  login to putty server specifying the IP address and SSH protocol. After logging in, login as ec2-user. 
  Install Apache and Httpd
  create a PHP file in which the code is been inserted .(attached to this repository)
  create a bucket in S3
  specify the bucket name and website address in Php file.
  Create a IAM role enabling fullAccessRekogntion.
  So that When  a picture is uploaded in the server, it returns the number of faces recognised in the picture.
