Userdata code for launching a Windows EC2 Instance with a GPU.
It will:
-Download the latest NVIDIA drivers for the EC2 Instance
-Disable the Windows Firewall (the EC2 security groups is they way to handle network security for EC2)
-Download NiceDCV server software
-Initialize and format the NVMe disk attached to G* instances as D:, and call it CACHE
-Install the AWS CLI version 2
