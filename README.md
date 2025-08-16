# Challenge Telecom X - Análise de Evasão de Clientes (Churn)

## 📌 Sobre o Projeto  
O objetivo do projeto consiste em analisar os dados de clientes da operadora **Telecom X** e identificar os fatores relacionados à evasão (churn).  
A análise inclui **extração, tratamento e padronização dos dados**, além da **exploração com visualizações** para gerar **insights acionáveis** que possam contribuir na redução da perda de clientes.  

Este desafio foi proposto como atividade prática da formação **"Aprendendo a fazer ETL"** da Trilha de **Data Science da Alura**.  

## 🎯 Objetivos da Análise  
- **Importação e preparação dos dados**: Extração via API, normalização de JSON e limpeza.  
- **Criação de métricas derivadas**: Exemplo → coluna de custo diário (`Contas_Diarias`).  
- **Padronização de variáveis**: Conversão de respostas binárias ("Sim"/"Não") em valores 1 e 0.  
- **Exploração do churn**: Análises considerando gênero, faixa etária, tipo de contrato, serviços contratados, forma de pagamento, tempo de permanência e custo mensal.  
- **Geração de insights e recomendações**: Identificação de padrões relevantes e propostas práticas para retenção de clientes.  

## 🛠️ Tecnologias Utilizadas  
- **Linguagem Python**  
- **Pandas**  
- **Matplotlib**  
- **NumPy**  
- **Google Colab**  
- **Jupyter Notebook**  

## 📊 Principais Resultados  
Durante a análise, alguns padrões relevantes foram identificados:  

- Clientes com **contrato mensal** apresentam taxas de evasão significativamente mais altas.  
- **Pagamentos por Cheque Eletrônico** estão fortemente associados ao churn, enquanto **débito automático** mostra maior retenção.  
- **Idosos** possuem uma taxa de rotatividade de **41,7%**, quase o dobro em relação a clientes mais jovens.  
- Clientes que contratam menos serviços ou apenas o básico apresentam **maior risco de cancelamento**.  
- Custos mensais e diários elevados tendem a aumentar a insatisfação e evasão.  
- A quantidade de serviços contratados tem relação inversa com o churn: **quanto mais serviços, menor a evasão**.  

Esses achados sustentam recomendações estratégicas para **reduzir o churn e fortalecer a fidelização**.  

## 💡 Recomendações  
Com base nos insights obtidos, sugerem-se as seguintes ações:  

- Incentivar a migração para **contratos anuais ou bienais**, oferecendo benefícios adicionais.  
- Criar **campanhas específicas para novos clientes**, principalmente nos primeiros meses.  
- Disponibilizar **combos ou pacotes promocionais** que aumentem o engajamento com mais serviços.  
- Oferecer **planos personalizados** para clientes com alto custo mensal, equilibrando preço e valor percebido.  
- Estimular o uso de **métodos de pagamento mais estáveis**, como o débito automático.  

## 👤 Autora  
Desenvolvido por **[Daniela Andrade]**  
