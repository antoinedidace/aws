# Switch to Azure utility directory.
$ cd <PROJECT_ROOT_DIR>
$ cd /opt/source/devel/slst/my-cloud-project

# Initialize Packer module.
$ packer init aws/image/Ubuntu-linux-2024.pkr.hcl

# Validate Packer module.
$ packer validate aws/image/Ubuntu-linux-2024.pkr.hcl

# Build VM image using Packer module.
$ packer build aws/image/Ubuntu-linux-2024.pkr.hcl