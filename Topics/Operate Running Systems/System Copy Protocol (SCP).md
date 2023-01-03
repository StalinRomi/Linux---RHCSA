SCP is used to securely **transfer files between 2 systems**

## Transfer files between 2 AWS EC2 instances

1. If **Instance - A** wants to send a file to **Instance - B**, then instance - A will need instance B's pem file.

Before Sending Instance B's pem file to Instance A, change the file permission to **r-r-r(444)**

### scp instance-A.pem instance-B.pem ubuntu@Public-IP of instance - A:Path

(Path - Where you want the file to be placed)

Now instance-A has B's pem file, again change B's pem file permission to **r-- (400)**

Suppose, we need to transfer a file called **contents from instance A to instance B** ->

### scp -i instance-B.pem contents ubuntu@Public-IP of instance - B:Path

(Path - Where do you want the contents file to be placed)

To get **Public IP** of this instances ->

### curl ifconfig.me
