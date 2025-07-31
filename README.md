# 📊 Análise de Dados: Taxa de Rotatividade de Funcionários com Power BI

Este projeto tem como objetivo explorar e visualizar uma base de dados de colaboradores, utilizando o Power BI para gerar indicadores relevantes e apoiar a tomada de decisões estratégicas na área de gestão de pessoas.

Arquivo base: collaborators_base.csv 
Disponível em: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data
Contém informações sobre idade, cargo, departamento, nível educacional, tempo de empresa, salário, entre outros.

# Colunas calculadas criadas:

Age Group – Agrupamento por faixa etária

Income Level – Classificação de nível salarial

YearsAtCompany Group – Agrupamento por tempo de empresa

YearsAtCompany Order – Coluna de ordenação para gráficos

# Medidas DAX criadas:

Attrition Rate – Taxa de rotatividade

Average Age – Idade média

Average Monthly Income – Renda mensal média

Gender Distribution – Distribuição por gênero

Attrition Numeric – Conversão de texto para valor numérico

Salary Difference – Diferença salarial entre homens e mulheres

# Visualizações Criadas:

Cartões de Indicadores: Exibem KPIs como Total de colaboradores, Funcionários que saíram e Percentual de rotatividade

Gráfico Donut:
Para visualização de Attrition e Total Employees.

Gráfico de Barras:
Para visualização de Taxa de Rotatividade por Faixa Etária 

Gráfico de Dispersão:
 Correlação entre YearsAtCompany Group e Attrition Rate
 
Matriz de Comparação:
 Comparação entre OverTime, MaritalStatus, EployeeNumber e Attrition.

Segmentações para filtragem por:
Nível Salarial |
Gênero |
Departamento |
Cargo 

# Ferramentas Utilizadas:

Power BI

Linguagem DAX para medidas e colunas calculadas

Limpeza e transformação de dados via Power Query

# Observações:

Este README tem o objetivo de documentar tecnicamente a estrutura do projeto. As análises interpretativas e insights extraídos a partir dos dados estão disponíveis no painel interativo e na documentação.



