# AtividadeLiviaC-S9M10BuildInfrastructure

### AWS Academy
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.40.26_a1872abc.jpg>)

![alt text](<assets\print1.jpg>)
![alt text](<assets\print2.jpg>)
![alt text](<assets\print3.png>)

### Download Automático do Terraform 1.0.11 para Windows Usando PowerShell
### Invoke-WebRequest -Uri https://releases.hashicorp.com/terraform/1.0.11/terraform_1.0.11_windows_amd64.zip -OutFile terraform.zip 

![alt text](<assets\print4.jpg>)

### Extração do Arquivo Terraform.zip para o Diretório C:\terraform Usando PowerShell
### Expand-Archive -Path terraform.zip -DestinationPath C:\terraform

![alt text](<assets\print5.jpg>)

### Configuração do PATH do Sistema para Incluir o Diretório C:\terraform Usando PowerShell
### [System.Environment]::SetEnvironmentVariable('PATH', $env:PATH + ';C:\terraform', [System.EnvironmentVariableTarget]::Machine)

![alt text](<assets\print6.jpg>)

### Verificando instalação do Terraform

![alt text](<assets\print7.jpg>)
- Primeira tentativa - erro

![alt text](<assets\print8.jpg>)
- Segunda tentativa - ok

### Comandos instalação AWS CLI

![alt text](<assets\print9.jpg>)




![alt text](<assets\print4.jpg>)
![alt text](<assets\print4.jpg>)
![alt text](<assets\print4.jpg>)
![alt text](<assets\print4.jpg>)
![alt text](<assets\print4.jpg>)


