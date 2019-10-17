# S3 EC2 VPC RDS Tutorial
The following tutorial explains how to create a web application that connects to an AWS database and how to deploy that application in EC2. Additionally, it explains how to create static resources using S3.

## How to create a bucket S3 in AWS
 1. Push on the add bucket button on AWS dashboard to create a S3 service.
	 ![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/Bucket/cBucket.JPG)
	 
2. Grant access to make the bucket public.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/Bucket/pBucket.JPG)
	
3. Press create button to finish the process.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/Bucket/fBucket.JPG)

4. Verify if the bucket is public to access it no matter who or what.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/Bucket/publicBucket.JPG) 

5. After the bucket is created, is ready to add a file into it, press add files button to do it.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/Bucket/uFileBucket.JPG)
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/Bucket/addFileBucket.JPG)

6.  Once the file is added, verify this one and open it throug the URL provided in the step 4.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/Bucket/fileAddedBucket.JPG)
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/Bucket/bucketOpenned.JPG)

### To more details, watch this video.
[S3 Tutorial](https://www.youtube.com/watch?v=kXvKLuH8mmo)

## How to create a VPC in AWS
1. On the VPC dashboard, press the button Security Group and start with the process.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/VPC/vpcInit.JPG)
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/VPC/createSG.JPG)

2. Add a name to the SG (security group) and a description.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/VPC/createSG1.JPG)

3. Once is created, verify its rules and continue to add a pair of these.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/VPC/inboundRules.JPG)

4. Create an Inbound Rule to garanty a MySQL access that we'll use in a future.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/VPC/cInboundRule.JPG)

### To more details, watch this video.
[VPC Tutorial](https://www.youtube.com/watch?v=QeliabbO3gg&t=4s)


## How to create a RDS connected with a web application in AWS
1. Go to RDS dashboard in AWS and press Create DataBase button.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/RDS/RDS_init.PNG)

2. Follow this settings that will allow you to configure correctly the DataBase
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/RDS/Settings.PNG)
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/RDS/Settings1.PNG)
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/RDS/Settings2.PNG)
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/RDS/Settings3.PNG)
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/RDS/Settings4.PNG)

3. Verify its status on the dashboard, it has to be "Available"
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/RDS/DashboardDB.PNG)

4. Now, keep in mind the endpoint, it will able you to make a connection throug some manager of data bases, in this case will be DBeaver.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/RDS/Endpoint.PNG)

5. From DBeaver, make a connection with it, using the endpoint and credentials that you used in the step 2.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/RDS/DBeaverConnection.PNG)

6. Using scripts into DBeaver, create a table and insert data on it.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/RDS/SQLScript.PNG)
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/RDS/SQLScript1.PNG)

7. Remember that we will use a web application, you can clone [this](https://github.com/Sergyo97/Architectural_Patterns_AREM) one and configure the next files.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/RDS/ApplicationProperties.PNG)
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/RDS/JQueryFromJAVA.PNG)

8. After configure the above files, run the application and prove it locally.
	![](https://github.com/Sergyo97/S3_EC2_VPC_RDS/blob/master/RDS/Proof.PNG)

### To more details, watch this video.
[RDS Tutorial](https://www.youtube.com/watch?v=jAUGhh2ZQxc)


## Author
Sergio Hernando Ruiz Paez - [GitHub](https://github.com/Sergyo97) - Escuela Colombiana de Ingeniería Julio Garavito

## License
This project is under GNU General Public License - see  [LICENSE](https://github.com/Sergyo97/AREM_FirstProject/blob/master/LICENSE) to more info.

	
