# Descrição do projeto
### Contexto
Você é analista em uma grande loja online. Junto com o departamento de marketing, você compilou uma lista de hipóteses que podem ajudar a aumentar a receita.

Você precisa priorizar essas hipóteses, lançar um teste A/B e analisar os resultados.

# Objetivo do projeto
lançar um teste A/B e analisar os resultados para ajudar o departamento de marketing aumentar a receita.


## Datasets
- hypotheses_us.csv
- orders_us.csv
- visits_us.csv

# Descrição dos dados
### Dados usados na primeira parte do projeto: hypotheses_us.csv

- Hypotheses — breves descrições das hipóteses
- Reach —  alcance do usuário, em uma escala de um a dez
- Impact -  impacto nos usuários, em uma escala de um a dez
- Confidence - confiança na hipótese, em uma escala de um a dez
- Effort - os recursos necessários para testar uma hipótese, em uma escala de um a dez. Quanto maior o valor de Effort, mais recursos são necessários para o teste.

### Dados usados na segunda parte do projeto: orders_us.csv - visits_us.csv

- transactionId -  identificador do pedido
- visitorId -  identificador do usuário que fez o pedido
- date -  do pedido
- revenue -  do pedido
- group  - o grupo de teste A/B ao qual o usuário pertence

- date - data
- group - grupo de teste A/B
- visits - o número de visitas na data especificada para o grupo de teste A/B especificado

## Etapas para conclusão do projeto

# Etapa 1: Priorizando Hipóteses.
* O arquivo hypotheses_us.csv contém nove hipóteses para aumentar a receita de uma loja online com Reach, Impact, Confidence e Effort especificados para cada um.
# A tarefa é:
* Aplicar o framework ICE para priorizar hipóteses. Classifique-os em ordem decrescente de prioridade.
* Aplicar o framework RICE para priorizar hipóteses. Classifique-os em ordem decrescente de prioridade.
* Mostre como a priorização de hipóteses muda quando você usa RICE em vez de ICE. Dê uma explicação para as alterações.

# Etapa 2: Análise de teste A/B
* Você realizou um teste A/B e obteve os resultados descritos nos arquivos orders_us.csv e visits_us.csv.

# Tarefa

* Analise o teste A/B:

- 1. Faça um gráfico da receita acumulada por grupo. Tire conclusões e crie conjecturas.
- 2. Faça um gráfico do tamanho médio acumulado do pedido por grupo. Tire conclusões e crie conjecturas.
- 3. Faça um gráfico da diferença relativa no tamanho médio acumulado do pedido para o grupo B em comparação com o grupo A. Faça conclusões e crie conjecturas.
- 4. Calcule a taxa de conversão de cada grupo como a proporção de pedidos para o número de visitas para cada dia. Trace as taxas de conversão diárias dos dois grupos e descreva a diferença. Tire conclusões e crie conjecturas.
- 5. Faça um gráfico da diferença relativa na conversão cumulativa para o grupo B em comparação com o grupo A. Tire conclusões e crie conjecturas.
- 6. Calcule os percentis 95 e 99 para o número de pedidos por usuário. Defina o ponto em que um ponto de dados se torna uma anomalia.
- 7. Faça um gráfico de dispersão dos preços dos pedidos. Tire conclusões e crie conjecturas.
- 8. Calcule os percentis 95 e 99 dos preços dos pedidos. Defina o ponto em que um ponto de dados se torna uma anomalia.
- 9. Encontre a significância estatística da diferença na conversão entre os grupos usando os dados brutos. Tire conclusões e crie conjecturas.
- 10. Encontre a significância estatística da diferença no tamanho médio do pedido entre os grupos usando os dados brutos. Tire conclusões e crie conjecturas.
- 11. Encontre a significância estatística da diferença na conversão entre os grupos usando os dados filtrados. Tire conclusões e crie conjecturas.
- 12. Encontre a significância estatística da diferença no tamanho médio do pedido entre os grupos usando os dados filtrados. Tire conclusões e crie conjecturas.
- 13. Tome uma decisão com base nos resultados do teste. As decisões possíveis são: 1. Pare o teste, considere um dos grupos o líder. 2. Pare o teste, conclua que não há diferença entre os grupos. 3. Continue o teste.



## 🛠 Habilidade
Python


<svg xmlns="http://www.w3.org/2000/svg" width="256" height="256" fill="none" viewBox="0 0 256 256"><rect width="256" height="256" fill="#242938" rx="60"/><path fill="url(#paint0_linear_2_47)" d="M127.279 29C76.5066 29 79.6772 51.018 79.6772 51.018L79.7338 73.8284H128.185V80.6772H60.4893C60.4893 80.6772 28 76.9926 28 128.222C28 179.452 56.3573 177.636 56.3573 177.636H73.2812V153.863C73.2812 153.863 72.369 125.506 101.186 125.506H149.24C149.24 125.506 176.239 125.942 176.239 99.4123V55.5461C176.239 55.5461 180.338 29 127.279 29ZM100.563 44.339C105.384 44.339 109.28 48.2351 109.28 53.0556C109.28 57.8761 105.384 61.7723 100.563 61.7723C95.7426 61.7723 91.8465 57.8761 91.8465 53.0556C91.8465 48.2351 95.7426 44.339 100.563 44.339Z"/><path fill="url(#paint1_linear_2_47)" d="M128.721 227.958C179.493 227.958 176.323 205.941 176.323 205.941L176.266 183.13H127.815V176.281H195.511C195.511 176.281 228 179.966 228 128.736C228 77.5062 199.643 79.323 199.643 79.323H182.719V103.096C182.719 103.096 183.631 131.453 154.814 131.453H106.76C106.76 131.453 79.7607 131.016 79.7607 157.546V201.412C79.7607 201.412 75.6615 227.958 128.721 227.958ZM155.437 212.619C150.616 212.619 146.72 208.723 146.72 203.903C146.72 199.082 150.616 195.186 155.437 195.186C160.257 195.186 164.154 199.082 164.154 203.903C164.154 208.723 160.257 212.619 155.437 212.619Z"/><defs><linearGradient id="paint0_linear_2_47" x1="47.22" x2="146.333" y1="46.896" y2="145.02" gradientUnits="userSpaceOnUse"><stop stop-color="#387EB8"/><stop offset="1" stop-color="#366994"/></linearGradient><linearGradient id="paint1_linear_2_47" x1="108.056" x2="214.492" y1="109.905" y2="210.522" gradientUnits="userSpaceOnUse"><stop stop-color="#FFE052"/><stop offset="1" stop-color="#FFC331"/></linearGradient></defs></svg>




## Bibliotecas utilizadas
- pandas 
- matplotlib
- numpy
- scipy

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/Oliverrafael
)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rafael-oliveira-528400335/
)