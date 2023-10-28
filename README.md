
# Aws project using terraform 

# Prerequisites 
  - AWS account.
  - Terraform installed.
  - Aws CLI installed.

# Authenticate the credentials to terraform.

## Step 1. Create CLI credentials in AWS if you don’t know follow this doc.

[Vist the doc](https://docs.aws.amazon.com/singlesignon/latest/userguide/howtogetcredentials.html)

## Step 2. run the following command.
```
Aws configure
```
Just enter access key and secret key copied from AWS.

<img width="542" alt="Screenshot 2023-10-28 at 19 10 51" src="https://github.com/Fitah-farah/Terraform_AWS_project/assets/120061777/84d8d94e-c4f5-405c-b533-e1f88614e936">

# Let's Create the Resources

### To initialize a working directory containing Terraform configuration files run.
```
terraform init
```
### To view the changes that Terraform plans to make to your infrastructure run.

```
terraform plan
```
### To execute the terraform files and create the resources run.

```
terraform apply --auto-approve
```
NOTE: I have used --auto-approve flag which is not recommended in the Production environment if you are deploying in a crucial environment just run Terraform apply.

## Clean up

To delete the resources that you have created Run.

```
Terraform destroy
```

### Done✅ 🚀


