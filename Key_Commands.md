# Key Commands

## AWS CLI Commands

### EC2
- **List Instances**
    ```bash
    aws ec2 describe-instances
    ```
- **Start Instance**
    ```bash
    aws ec2 start-instances --instance-ids i-1234567890abcdef0
    ```

### S3
- **List Buckets**
    ```bash
    aws s3 ls
    ```
- **Copy File to Bucket**
    ```bash
    aws s3 cp myfile.txt s3://mybucket/
    ```

### IAM
- **Create User**
    ```bash
    aws iam create-user --user-name newuser
    ```
- **Attach Policy to User**
    ```bash
    aws iam attach-user-policy --user-name newuser --policy-arn arn:aws:iam::aws:policy/AmazonS3ReadOnlyAccess
    ```

## Useful Scripts

### Launch EC2 Instance
```bash
aws ec2 run-instances --image-id ami-0abcdef1234567890 --count 1 --instance-type t2.micro --key-name MyKeyPair --security-group-ids sg-0123456789abcdef0 --subnet-id subnet-6e7f829e
```
### Create S3 Bucket
```bash
aws s3 mb s3://my-new-bucket
```
