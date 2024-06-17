# AtividadeLiviaC-S9M10BuildInfrastructure

### AWS Academy

![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.40.26_a1872abc.jpg>)
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.40.33_2a5d0657.jpg>)
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.40.41_60d6ee8b.jpg>)

### Download Automático do Terraform 1.0.11 para Windows Usando PowerShell
### Invoke-WebRequest -Uri https://releases.hashicorp.com/terraform/1.0.11/terraform_1.0.11_windows_amd64.zip -OutFile terraform.zip 

![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.41.09_9a2f2945.jpg>)

### Extração do Arquivo Terraform.zip para o Diretório C:\terraform Usando PowerShell
### Expand-Archive -Path terraform.zip -DestinationPath C:\terraform

![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.41.45_03a97ef1.jpg>)

### Configuração do PATH do Sistema para Incluir o Diretório C:\terraform Usando PowerShell
### [System.Environment]::SetEnvironmentVariable('PATH', $env:PATH + ';C:\terraform', [System.EnvironmentVariableTarget]::Machine)

![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.41.56_64cfd255.jpg>)

### Verificando instalação do Terraform

![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.42.09_cbb80b16.jpg>)
- Primeira tentativa - erro

![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.42.14_dd4a0eec.jpg>)
- Segunda tentativa - ok

### Comandos instalação AWS CLI

![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.42.20_8bc88931.jpg>)






