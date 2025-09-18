# This is a tutorial on how to make a virtual machine on Google Cloud and Oracle using Ubuntu
[This is the link to the tutorial](https://www.loom.com/share/4944d7a34b2041c28633588b6f27d0fb?sid=1e59d66c-5e4c-4923-b475-3e484118d5c6)

# Google Cloud
1. Log in to your Google Cloud account
2. Click the sandwich icon(triple line) on the top right and click on "Computer Engine"
3. Click on "VM instances" and then click on "Create Instance"
4. Please do the following:
    - Select the closest region
    - create the smallest/lowest-costing machine
      - E2 and E2-micro
    - select Ubuntu image
6.   Create an instance and launch SSH from your VM
7.   Enter the command "sudo apt-get update" to update your VM
8.   Once you are finished with the VM, terminate the machine in the action tab.



# Oracle Cloud
1. Log in to your Oracle Cloud Account
2. Click "create instance"
3. Please do the following:
    - Set image to Ubuntu and change shape to E2.1.Micro
4. You can either create a new virtual cloud network or select an existing virtual cloud network
5. Download your private and public keys and create your instance
6. Once the machine is running, open up your terminal (Mac OS) or command (Windows)
7. Enter the command "chmod 600 (path to private key)" to allow your VM to read the key
8. Enter the command "ssh -i (path to private key) ubuntu@(public IP)
   - The public IP can be found under your Oracle VM details on your browser.
9. Enter the command "sudo apt-get update"
10. Once you are finished with the VM, terminate the machine in the action tab.
