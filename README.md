# BDFinal
Repositório do Trabalho Final de Banco de Dados - Tema: Gestão de Saúde (Doenças Cardíacas)
# Projeto de Análise de Dados de Doenças Cardíacas

Este projeto abrange a inspeção e limpeza de dados de um arquivo CSV sobre doenças cardíacas, a criação de tabelas no MySQL, a transferência de dados para o Google BigQuery e o armazenamento de informações adicionais no MongoDB.

## Objetivos

- **Inspeção e Limpeza dos Dados**: Carregar o arquivo CSV e inspecionar a estrutura dos dados para garantir que estejam prontos para análise.
- **Criação das Tabelas no MySQL**: Criar uma tabela no MySQL para armazenar os dados do CSV.
- **Importação dos Dados no MySQL**: Importar os dados do arquivo CSV para a tabela criada no MySQL.
- **Transferência dos Dados para o BigQuery**: Exportar os dados do MySQL e importá-los no Google BigQuery.
- **Armazenamento de Informações Adicionais no MongoDB**: Estruturar e inserir dados adicionais no MongoDB.

## Estrutura dos Dados

O arquivo CSV contém as seguintes colunas:

- **age**: Idade do paciente
- **sex**: Sexo (1 = masculino, 0 = feminino)
- **cp**: Tipo de dor no peito (valores de 0 a 3)
- **trestbps**: Pressão arterial em repouso (em mm Hg)
- **chol**: Colesterol sérico (em mg/dl)
- **fbs**: Açúcar no sangue em jejum > 120 mg/dl (1 = verdadeiro; 0 = falso)
- **restecg**: Resultados eletrocardiográficos em repouso (valores 0, 1 ou 2)
- **thalach**: Frequência cardíaca máxima alcançada
- **exang**: Angina induzida por exercício (1 = sim; 0 = não)
- **oldpeak**: Depressão do ST induzida pelo exercício em relação ao repouso
- **slope**: Inclinação do segmento ST no pico do exercício (valores 0, 1 ou 2)
- **ca**: Número de vasos principais coloridos por fluoroscopia (valores de 0 a 3)
- **thal**: Defeito talâmico (0 = normal; 1 = defeito fixo; 2 = defeito reversível)
- **target**: Diagnóstico de doença cardíaca (1 = sim; 0 = não)
