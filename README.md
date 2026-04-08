# Tech Challenge Fase 3  - Pós Tech Data Analytics - FIAP 
## Objetivo do Projeto
Utilizar a base de dados do IBGE a respeito das pesquisas realizadas na época da pandemia da COVID-19 para trazer uma breve análise de todo o contexto, organizando um banco de dados através de perguntas selecionadas para responder à um hospital quais seriam os melhores procedimentos a serem adotados caso ocorra um novo surto de COVID-19.

## Premissas Adotadas
 - Utilização de 3 meses como amostra para os dados;
 - Utilização de no máximo 20 perguntas realizadas na pesquisa;
 - Utilização de características clinicas, econômicas e comportamentais da sociedade.

## Ferramentas
- Plataforma AWS Lab: S3, AWS Glue e Athena
- SQL
- Python
- Jupyter Notebook

## Metodologia
### 1. Extração dos Dados:
Dados obtidos no site do PNAD COVID19 (https://covid19.ibge.gov.br/pnad-covid/), no qual foram exportados os arquivos referentes aos meses de setembro, outubro e novembro assim como os seus respectivos dicionarios.

### 2. Tratamento dos Dados:
Através da plataforma da AWS foi possivel explorar os dados e organiza-los de forma que foram realizadas consultas em SQL e elas foram exportadas como arquivos em formato .csv disponíveis na pasta "CSVs_Exportados"

### 3. Desenvolvimento e Análise:
O desenvolvimento foi feito via Jupyter Notebook no qual os dados obtidos foram tratados para gerar insights através de graficos e elementos visuais que foram implementados na apresentação final

### 4. Apresentação Final:
A apresentação final está disponivel no arquivo "Apresentacao Tech Challenge Fase 3" no qual foram detalhados os procedimentos e as análises feitas de forma que ela também possa ser apresentada ao cliente final
