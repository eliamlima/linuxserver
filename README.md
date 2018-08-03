# linuxserver
Udacity Full-Stack Dev Linux Server Project 5
Using Amazon Lightsail Server Instance

1) IP Address: 18.188.74.220
   URL: http://18.188.74.220
   SSH Port: 2200

2) This is a website that is a sample of a Sports Store. 
You click on the items and you can see the details. 
You also can use Login button to login with Google.


3) Software and websites used
- Vagrant and VirtualBox for accessing the server
- Git Bash to use the terminal on Windows
- Amazon Lightsail account to configure the server
- Git for uploading the project
- Recursos de terceiros:
  - The configuration for this project was made using the link below:
https://github.com/kongling893/Linux-Server-Configuration-UDACITY/...
blob/master/README.md
  - StackOverflow
  - Forum Udacity
  
  4) Configurações feitas
  - atualizações para todos os pacotes necessários como: 
    apache, ssh, postgres, flask, request, oauth, etc.
  - UFW: permite porta 80, 123, 2200 e não permite 22
  - Usuario grader criado com permissões de root para o avaliador.
  - Retirada permissão de root para terceiros no arquivo sshd_config
  - Geradas chaves SSH para maior segurança
  - configuração do modo wsgi
 
