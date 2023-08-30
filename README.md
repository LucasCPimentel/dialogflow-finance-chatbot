# dialogflow-finance-chatbot

# Chatbot Bancário de Notícias usando o Dialogflow

## Visão Geral
Este projeto implementa um chatbot que gera notícias bancárias e financeiras usando a plataforma de processamento de linguagem natural Dialogflow. O chatbot interage com dados de usuários obtidos de uma API externa e usa as intenções do Dialogflow para criar mensagens de notícias personalizadas para cada usuário.

## Tecnologias Utilizadas
- Python
- Pandas
- Requests
- NumPy
- Matplotlib
- Google Cloud Dialogflow

## Funcionalidades
- Recupera dados de usuários de uma API externa.
- Gera mensagens de notícias personalizadas sobre bancos e investimentos usando o Dialogflow.
- Atualiza os perfis dos usuários com as notícias geradas.
- Realiza análise estatística dos saldos das contas e dos limites de crédito.

## Como Executar
1. Clone este repositório em sua máquina local.
2. Instale as bibliotecas Python necessárias com `pip install -r requirements.txt`.
3. Configure o seu projeto Google Cloud Dialogflow e obtenha as credenciais em formato JSON.
4. Atualize o `dialogflow_project_id` e `json_credentials_path` no código.
5. Execute o código usando `python main.py`.

## Exemplo de Saída
Análise das Contas Bancárias:
Média dos saldos das contas: 2917.0
Mediana dos saldos das contas: 2100.0
Desvio padrão dos saldos das contas: 2046.586964264415

Análise dos Limites de Crédito:
Média dos limites de crédito: 4650.0
Mediana dos limites de crédito: 4000.0
Desvio padrão dos limites de crédito: 2226.7958199351543


Análise dos Limites de Crédito:
Média dos limites de crédito: 4650.0
Mediana dos limites de crédito: 4000.0
Desvio padrão dos limites de crédito: 2226.7958199351543
