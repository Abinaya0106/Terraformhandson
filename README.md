# Terraformhandson
Installation and Hands-on Project available

**Step : **1 # A binary distribution is avaialble for all environments. Let's grab the latest version of it for linux.
wget https://releases.hashicorp.com/terraform/1.12.2/terraform_1.12.2_linux_amd64.zip
**Step : 2** # Then unzip the archive
$ unzip terraform_1.12.2_linux_amd64.zip
**Step : 3** # Check the executable permission on the binary, if it's not executable, make it executable using the below commmand,
$ chmod +x terraform
**Step : 4** # Finally make sure that terrform is avaiable in PATH. So, let's move the binary into /usr/local/bin directroy,
$ sudo mv terraform /usr/local/bin
5. Now you are ready to run terraform commands. Open up a new termnal and run a command terraform and enter
terraform -version

**Enable Tab Completion**
If you use either bash or zsh you can enable tab completion for Terraform commands. To enable autocomplete, run the following command and then restart your shell.
$ terraform -install-autocomplete
