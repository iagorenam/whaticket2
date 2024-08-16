

## CRIAR SUBDOMINIO E APONTAR PARA O IP DA SUA VPS ##

FRONTEND_URL: app.seudominio.com.br
BACKEND_URL:  api.seudominio.com.br

## CHECAR PROPAGAÇÃO DO DOMÍNIO ##

https://dnschecker.org/

## COPIAR A PASTA PARA ROOT E RODAR OS COMANDOS ABAIXO ##

apt update && apt upgrade -y
cd /home

sudo chmod +x ./whaticketsaas
cd ./whaticket_shell_saas
sudo ./whaticketsaas

===================================================

login: admin@admin.com
senha: 123456