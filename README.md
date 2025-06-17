# 📊 TelecomX - Análise de Evasão de Clientes (Churn)

Este projeto foi desenvolvido como parte da minha formação no programa **Oracle Next Education (ONE)** em parceria com a **Alura**. O desafio propõe a análise de dados da empresa fictícia **TelecomX** para entender os principais fatores que levam à evasão de clientes (churn) e propor estratégias para reduzir esse índice.

## 🚀 Objetivo

O objetivo principal foi aplicar técnicas de **análise de dados** e **ciência de dados** para:
- Identificar padrões e variáveis relacionadas ao cancelamento de clientes;
- Explorar os dados da base fornecida;
- Gerar visualizações e insights;
- Propor **recomendações práticas** com base nas análises.

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## 🗃️ Estrutura dos Dados

A base original está em formato **JSON** com informações demográficas, contratuais e de serviços dos clientes. Durante o projeto, os dados foram tratados, normalizados e enriquecidos com novas colunas.


## 📈 Etapas do Projeto

1. **Importação e Tratamento de Dados**  
   Conversão do JSON para DataFrame, limpeza, padronização, tradução para PT-BR e transformação de variáveis categóricas em binárias (One-hot Encoding).

2. **Análise Exploratória**  
   Análise gráfica e estatística das principais variáveis relacionadas ao churn, incluindo:
   - Tipo de contrato
   - Permanência
   - Valor mensal
   - Quantidade de serviços contratados
   - Tipo de pagamento
   - Idade (idoso)

3. **Correlação de Variáveis**  
   Análise de correlação entre variáveis numéricas e binárias com o cancelamento, buscando fatores de risco.

4. **Geração de Insights e Recomendações**  
   Sugestões baseadas nas descobertas para ajudar a empresa fictícia a **reduzir a evasão de clientes**.

## 📘 Dicionário de Dados Completo

O dicionário com todas as transformações aplicadas, colunas novas e significados está documentado no notebook principal. Inclui:
- Traduções
- Conversões
- Colunas derivadas (`quantidade_servicos`, `contas_diarias`, etc.)

## 📌 Principais Conclusões

- Contratos mensais possuem maior taxa de cancelamento.
- Clientes com menor tempo de permanência tendem a cancelar mais.
- Alto valor mensal contribui levemente para a evasão.
- Fibra óptica tem maior churn comparado a outras tecnologias.
- Idosos e clientes com débito em conta demonstraram maior propensão ao cancelamento.

## 💡 Recomendações

- Incentivar contratos de longo prazo com benefícios.
- Melhorar a experiência nos primeiros meses de relacionamento.
- Investir em suporte para idosos e usuários de fibra óptica.
- Oferecer vantagens para clientes que usam débito automático.
- Criar programas de fidelidade e descontos progressivos.

## 📝 Conclusão

Este projeto demonstrou como a **análise de dados pode ser uma ferramenta poderosa para negócios**, revelando oportunidades de melhoria e estratégias para reduzir a perda de clientes. O trabalho segue boas práticas de tratamento, análise e visualização de dados com potencial de extensão para modelos preditivos de churn.

