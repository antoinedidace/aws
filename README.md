# AWS utility


## Build Amazon EC2 AMI using Packer
```bash
# Switch to AWS utility directory.
$ cd <PROJECT_ROOT_DIR>
$ cd /opt/source/devel/slst/my-cloud-project

# Initialize Packer module.
$ packer init aws/ec2/ami/amazon-linux-2023.pkr.hcl

# Validate Packer module.
$ packer validate aws/ec2/ami/amazon-linux-2023.pkr.hcl

# Build VM image using Packer module.
$ packer build aws/ec2/ami/amazon-linux-2023.pkr.hcl
```