1. Firstly on this course we need install Terraform.exe and added path file into "System environtment variable" to access it every where on cmd
2. After that we need ``` mkdir learn-terraform-docker-container ```. you can specify where you want create those folder anywhere like C: or D: where you like its oke. 
3. Then ``` cd learn-terraform-docker-container ``` to enter that folder we created. 
4. We can touch main.tf to create file or echo "" > main.tf
5. The code is on ``` main.tf ``` then we can do ``` > terraform init ``` that will create generate file configuration, plugin, modules, and information on working folder. thats why we create folder for it. It will have prompt "yes" to perform it.
6. After that, we prompt on cmd ``` terraform apply ```, it will downloaded on WSL, window system linux (using Win 11 Home)
7. We can verify it with ``` docker ps ``` on cmd, and access it from browser access it from url ``` localhost:8000 ```\
8. And last we ``` terraform destroy ``` and prompt input ``` yes ``` to destroy container and the image from docker. 

And we learn here provisioned and destroy NGINX Webserver from Terraform. ❤️🎉

----
Course link: https://developer.hashicorp.com/terraform/tutorials/docker-get-started/install-cli
Editor, using Visual Studio Code with Extension HashiCorp Terraform
