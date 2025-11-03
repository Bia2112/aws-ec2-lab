# Arquitetura AWS - Projeto do Curso

Este projeto mostra a arquitetura de uma instância EC2 com EBS.

## Componentes

- **Usuário**: acessa via navegador.  
- **Web**: internet, canal de comunicação.  
- **EC2**: servidor que processa a aplicação.  
- **EBS**: armazenamento persistente do EC2.

## Fluxo de Dados

1. Usuário envia requisição.  
2. Passa pela web e chega na EC2.  
3. EC2 processa e interage com EBS.

## Diagrama

Veja `aws-ec2-ebs.drawio`.

