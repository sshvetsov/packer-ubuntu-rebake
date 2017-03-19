This Packer template demonstrates how to remove ephemeral block device mappings from latest Canonical Ubuntu Trusty 14.04 x86_64 AMI by creating a new AMI in your AWS account.

For this example to work you will need to:
# install Packer and awscli
# configure your .aws/credentials
# update variables section to matach your Region, VPC, Subnet
# run `packer build ubuntu-14.04-x86_64.json`