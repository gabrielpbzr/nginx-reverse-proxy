# Nginx reverse proxy

Projeto de demonstração da configurações do Nginx como proxy reverso para aplicações.

## Funcionamento

As requisições que chegam ao servidor Nginx são encaminhadas para o servidor com a aplicação web rodando na porta 8080.


## Como rodar este Projeto

1. Baixe/clone este repositório para a sua máquina.
2. No terminal, rode o comando `docker-compose up -d --build`. Aguarde a construção das máquinas virtuais.
3. Acesse no seu navegador o endereço http://127.0.0.1/
