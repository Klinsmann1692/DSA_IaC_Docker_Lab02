# Instruções do Lab 2


# Abra o terminal ou prompt de comando e navegue até a pasta onde você colocou os arquivos do Lab2 (não use espaço ou acento em nome de pasta)


# Execute o comando abaixo para criar a imagem Docker

docker build -t dsa-terraform-image:lab2 .


# Execute o comando abaixo para criar o container Docker

docker run -dit --name dsa-lab2 dsa-terraform-image:lab2 /bin/bash


# Verifique as versões do Terraform e do AWS CLI com os comandos abaixo

terraform version
aws --version

# Próximos passos

Acessar o terminal pelo container no docker e fazer login na conta AWS.
Executar comandos HCL para criação da infraestrutura como código
