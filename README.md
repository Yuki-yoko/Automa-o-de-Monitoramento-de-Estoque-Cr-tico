# Automação de Monitoramento de Estoque Crítico

## Descrição

Este projeto consiste em uma automação desenvolvida utilizando o n8n para monitorar diariamente os níveis de estoque de produtos armazenados em uma planilha do Google Sheets.

O objetivo é identificar itens cujo estoque atual esteja abaixo do estoque mínimo definido pela empresa e enviar automaticamente um relatório por e-mail para os responsáveis pela reposição.

## Arquitetura do Workflow
<img width="973" height="161" alt="image" src="https://github.com/user-attachments/assets/a26c227e-b29f-4c52-9f76-babddc57ab50" />


## Problema Resolvido

Em muitas empresas, o acompanhamento manual dos níveis de estoque pode levar a atrasos na reposição de produtos e possíveis rupturas no abastecimento.

Esta automação elimina a necessidade de verificações manuais diárias, notificando automaticamente os responsáveis sempre que forem encontrados produtos com estoque insuficiente.

## Fluxo da Automação
<img width="1270" height="257" alt="image" src="https://github.com/user-attachments/assets/2e8d9ee5-ccc6-4ad4-8e0b-dfc83fac5229" />

## Tecnologias Utilizadas

* n8n
* Google Sheets API
* Gmail API
* Docker
* OAuth 2.0
* Google Cloud Platform

## Exemplo de Planilha
<img width="818" height="238" alt="image" src="https://github.com/user-attachments/assets/8fdbb572-e270-4201-b6b4-5173511968b5" />

## E-mail Gerado
<img width="870" height="437" alt="image" src="https://github.com/user-attachments/assets/be61e131-0c0a-4380-97fd-52a1c65169de" />

## Como Executar

1. Importe o workflow JSON no n8n.
2. Configure as credenciais do Google Sheets.
3. Configure as credenciais do Gmail.
4. Atualize o ID da planilha desejada.
5. Ative o workflow.

## Melhorias Futuras
* Envio para múltiplos destinatários.

🤝 Contribuições são sempre bem-vindas!

## Autor

Cristina Yuki Yokomizo

