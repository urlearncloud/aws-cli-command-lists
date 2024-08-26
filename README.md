# aws-cli-command-lists

### EC2

#### create key-pair

aws ec2 create-key-pair --key-name anyname --query 'keymaterial' --output text > anyname.pem

#### check key-pair

aws ec2 describe-key-pairs

#### delete key-pair

aws ec2 delete-key-pair --key-name ami-02b49a24cfb95941c

#### create instance

aws ec2 run-instances --image-id ami-02b49a24cfb95941c --count 1 --instance-type t2.micro --key-name anyname --security-group-ids sg-04156b506868cdce5
