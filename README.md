## End to End MAchine Learning Project

# AWS Deployment

1. Docker Build checked
2. Github Workflow
3. Iam User In AWS

## Docker Setup In EC2 commands to be Executed

#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker

## Configure EC2 as self-hosted runner:

## Setup github secrets:

AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = demo>>  566373416292.dkr.ecr.ap-south-1.amazonaws.com

ECR_REPOSITORY_NAME = simple-app


![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/81e77f95-5542-403c-8238-d5bc3302f198)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/2fb98ba5-78da-47e0-92fd-1fafdf4ee506)

# CI - YAML File

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/7ba347a9-a4ca-4859-a37a-1d117fba6593)

# CD- Yaml.File

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/3359a18f-2a4a-4d83-9de3-64ee375922a2)

# Pull the image

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/86e8b122-12d1-488d-80ec-468153aeee30)


# how to get Workflow- Yaml File= Go to Actions -  Select new Work Flow

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/a37b5a76-af03-4873-be6f-7c2442a75c95)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/8f357a18-b6fc-4030-bad8-ee271e71dd76)

# Click on Deploy to Amazon ECS- Configure – Note its just a sample one

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/4feea869-89c7-4ca4-b9a9-201537996454)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/bfc78222-9c8e-4d29-b6b7-ab7c3d61e9b7)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/f3912150-e1d8-4fb1-999a-3eec133cf139)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/0231a56e-db81-4f5d-891b-8ba1d64c3be8)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/c1ffd243-4b9f-4475-b4ef-6644ebe70245)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/8c8bcb77-429c-46c0-921c-e6f90464f127)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/36067ae3-6111-4e71-b9c8-f0a33d805801)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/2c840936-58a8-4b51-a676-f72a12c42a02)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/cb1065ec-4a1f-4162-a497-fea55f2e87df)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/4bbe9289-aa77-4207-b790-5a2b3613b4d2)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/86dee49a-d5ca-4a82-92e7-b7d09af4f162)

# Go to Security_Credentials -  select Access Key

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/d541655a-6c00-4d59-a4e4-5933fb30b601)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/1557f577-20ae-4425-844c-ae5a3e3a81b4)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/f3370f05-a0e7-4fa6-ba94-8f343dd139c4)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/c00021e5-afa6-475a-a031-0b1b9cb91426)

# Go to ECR

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/0837082f-18ba-4589-9b91-b28b4564aaff)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/39621c83-e429-4c8f-bb6b-2d2fcc664667)

# Create a new Repo

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/83c1da61-6bf4-4d6e-997b-43638f7ab821)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/a1729928-545e-4c38-b24a-3305f2282635)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/565ab1ff-bdc4-4215-9d96-1ce66f0b9c55)

# now Go to EC2 instance  ., with this integrate to ECR .. 

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/4cb7f64e-6735-4330-a879-2afcbc7ce7b9)

# Now Launch Instance

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/fea7ba78-0f95-4645-9ac6-cb07a70c8bef)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/a9752a8e-ecdd-4fe2-a087-da6999ff8c0d)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/a6ca1c2d-5846-41a7-8e5a-e0a7157de414)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/4d39143e-7e9a-479f-a355-50d4e8b51d98)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/2bc5f4d6-b027-4260-8141-29dfd22a9318)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/13551881-bbe7-4100-84ae-13011324d639)

# instance Created + running

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/136c43d4-e917-41e2-b82b-1376fafa2eba)

# Connect to 3rd party SSH – MobaXterm

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/302ef886-2235-45df-8ecd-5a444d9a3195)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/b1b8e345-64c0-4e8d-a0f1-948fb6a1bac0)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/b3884e27-c4cc-4092-99f1-2925e963fea1)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/a504d6fc-4c39-4122-b64e-857144562511)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/15bb3b0f-3768-4f44-bd51-83f050cbfa15)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/eacea51a-4d82-4a1e-abac-8c4f3c0c55fe)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/02fb83df-25be-453f-81c2-335755f46d9d)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/a034ad50-b487-4e3a-8659-ad9e682b3931)

# go to Your Git hub Repo – Select Settings – Actions—Runner

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/cd5e8795-1635-4c05-9726-9f49491af3d4)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/e4362a0a-ff47-4d5c-a835-a65375ef6ff6)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/cb8851cb-731b-45e4-a1df-0ec2841a62aa)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/47bb13f5-1548-4e49-827e-11cf556c0b1c)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/1088cf99-6395-4667-bbd0-0431a81e5bd7)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/6dd2fe40-f415-4c8c-bd7f-02e0f61861e3)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/8db3235c-14a5-4eda-9929-92d9927dc16e)

# go to repo – select Setting – Actions – Runner – created – it’s  in idle state 

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/d0db14ac-aecc-4fc9-a401-a5527cbefc77)

# Same Go back to setting -select – secrete & variables Col Section – click Actions

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/783792ed-59b4-476b-b4b1-b4868231f196)

#  now to app.py..  # comment on the code & commit it see  the changes

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/5ffe3b28-ea77-45d3-b011-8d17d10bc3df)

# Commit

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/c20c8c65-9fba-4b30-9cf5-dcc77a4d68b6)

# go to action page

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/af3494dc-27c1-4be4-a5d4-9876ce355c7d)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/6dcf6fcc-1187-4847-88da-590aca113068)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/771b5152-645b-4f73-806a-3aa71cb46c8f)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/aaf504a1-d9fb-415a-995b-081fb7d5aed7)

# ERROR

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/6587f2ba-de56-4316-bc92-de80ebfcdc6a)

# Go to Repo- setting- Secrete& variables- Actions- update - below

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/5b1e10f2-f30d-434b-bd82-b0ee4b43a253)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/9e9350ba-0a1c-4568-972c-18137025ba14)

# Go back to Actions – Re-Run All the Jobs

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/d55dfb37-7736-43f2-8580-29918ca2de6d)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/400acf2d-8428-4f97-accc-9554214c8ad5)

# final Completion- CI/CD pipeline

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/9bac6bef-7a7b-43bd-b471-3259f17639cc)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/84f4666f-4fa5-4980-ba07-fa26bea36c96)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/5b63565c-cb01-4821-8969-2ce2b59b595e)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/c583da18-c98d-41a0-9dcb-b1834f911183)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/133f303d-9c49-4d80-bdc9-94dd13baf4c1)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/c6db6480-8b71-4775-8f2f-abb405943ce4)

# https Working

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/a0ed12fb-df02-45c6-b15e-797b7290a5e4)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/b17de20d-e4ba-49ae-8f79-5751f0029048)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/bff5dcbe-2cfa-4e07-8ae9-b70c9f1ec31d)

![image](https://github.com/Siddhartha082/AWS_using_ECR_EC2_Instance_CI-CD_Pipeline_Docker_Container/assets/110781138/43dd7b77-6bf8-4120-bf23-deef24a0dd6a)


































