# aws-cli-command-lists

### EC2

#### create key-pair

aws ec2 create-key-pair --key-name anyname --query 'keymaterial' --output text > anyname.pem

#### check key-pair

aws ec2 describe-key-pairs

#### delete key-pair

aws ec2 delete-key-pair --key-name anyname
