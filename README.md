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
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 10.39.05_937243c2.jpg>)
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 10.40.11_198b451a.jpg>)
- Rodando com o powershell no modo normal, não mais como admin.


![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 10.44.26_200cb940.jpg>)

- Credentials:
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 10.46.14_4625471e.jpg>)
- Quando gerei o arquivo pela primeira vez, o arquivo credentials veio vazio.
- Agora está certo:
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 10.47.53_70dd4e03.jpg>)
- Credenciais editadas para ficarem no formato solicitado.

- Main.tf
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 10.51.05_597ade99.jpg>)

- terraform init
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 10.53.43_01c018bb.jpg>)
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 10.54.36_0f16dd5e.jpg>)

- terraform plan rodando com erro
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.00.27_4778300b.jpg>)

- terraform plan rodando certo
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.00.39_472abc28.jpg>)

- terraform apply
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.02.54_1f4532cb.jpg>)
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.03.28_3b54e1b0.jpg>)

- terraform destroy
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.08.01_1627eac7.jpg>)
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.08.48_11682ca3.jpg>)

#### Observação sobre o Github
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.12.15_5c8fec02.jpg>)
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.12.25_b9fe8f6b.jpg>)
![alt text](<Imagem do WhatsApp de 2024-06-11 à(s) 11.13.12_73800574.jpg>)