# G9ONE_Chalenge_TelecomX
Desafio 2 de DS

Análise de Churn - TelecomX Brasil 📊📱
Este projeto realiza uma análise detalhada dos dados da empresa TelecomX para entender os motivos da taxa de cancelamento (churn) e propor estratégias de retenção de clientes.

🚀 Visão Geral
O objetivo principal é explorar o perfil dos clientes, identificar padrões que levam ao cancelamento dos serviços e fornecer recomendações baseadas em dados para reduzir o churn, que atualmente está em torno de 26%.

🛠️ Tecnologias Utilizadas
Python: Linguagem principal.

Pandas: Manipulação e tratamento de dados.

Requests: Extração de dados via API/JSON.

Jupyter Notebook / Google Colab: Ambiente de desenvolvimento.

📋 Etapas do Projeto
1. Extração de Dados 📥

Os dados foram obtidos em formato JSON a partir de um repositório remoto utilizando a biblioteca requests.

2. Transformação e Limpeza 🔧

Conversão dos dados aninhados (dicionários) para um DataFrame estruturado.

Limpeza de valores nulos e campos em branco.

Ajuste de tipos de dados (strings para numéricos).

Padronização e tradução de títulos e categorias para o português.

3. Análise Exploratória (EDA) 🔍

A análise focou em entender o público-alvo e os fatores críticos de cancelamento:

Perfil do Cliente: Identificou-se que a maioria dos clientes tem menos de 60 anos, são solteiros e não possuem filhos.

Comportamento de Churn: Clientes com esse perfil específico e aqueles com contratos mensais são os mais propensos a cancelar.

Tempo de Contrato: Há uma forte tendência de cancelamento logo no início da relação contratual.

💡 Recomendações Estratégicas
Com base nos dados, o projeto sugere:

Campanhas Focadas: Criar ações de marketing direcionadas ao perfil jovem e solteiro.

Incentivos Contratuais: Oferecer benefícios financeiros para migração de contratos mensais para planos anuais ou bianuais.

Retenção Inicial: Implementar estratégias de engajamento nos primeiros meses de contrato para reduzir a evasão precoce.

Projeto desenvolvido como parte do desafio G9ONE Challenge.
