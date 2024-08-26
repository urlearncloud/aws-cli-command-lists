# aws-cli-command-lists

### EC2

#### create key-pair

aws ec2 create-key-pair --key-name anyname --query 'keymaterial' --output text > anyname.pem
