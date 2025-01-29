
### **TLDR**
 - **Processamento**:
  - Kaggle Notebook ([link](https://www.kaggle.com/code/rafaeldeabreu/projeto-an-lise-explorat-ria-da-empresa-loggi/edit))
 - **Fontes**:
  - GitHub ([link](https://raw.githubusercontent.com/andre-marcos-perez/ebac-course-utils/main/dataset/deliveries.json));

  - ## Objetivo
   O objetivo deste projeto foi desenvolver gráficos e insights para aprimorar a visualização e o entendimento do sistema de entregas da Loggi na região de Brasília. A análise permitiu identificar as áreas com maior e menor volume de entregas, contribuindo para a otimização do processo logístico e a tomada de decisões estratégicas. 
  - ## Dataset
    Os dados utilizados neste projeto foram extraídos de duas fontes confiáveis:

  Os dados foram extraídos do GitHub no formato JSON, permitindo uma análise estruturada e precisa das entregas na região de Brasília, GitHub ([link](https://raw.githubusercontent.com/andre-marcos-perez/ebac-course-utils/main/dataset/deliveries.json))
   
  - ## Tecnologias utilizadas
  - Jupyter
  - Python
  - Numpy
  - Pandas
  - Geopandas
  - Matplotlib
  - Seaborn
    
  - ## Metodologia
 Utilizei PYTHON no Google Colab para realizar uma análise exploratória de dados logísticos.
Após baixar um arquivo JSON contendo os dados, explorei-os com a biblioteca PANDAS,
manipulei informações geográficas usando GEOPY e GEOPANDAS, e criei visualizações com
MATPLOTLIB e SEABORN. Entre os insights gerados, identifiquei a região de Brasília como
destaque em densidade de entregas, analisei os subúrbios com maior e menor volume de
entregas e examinei o tamanho das entregas por região.
  

  - ## Resultados
Localização e Abrangência de Cada Distrito

Foram mapeados todos os distritos, incluindo a localização exata e a região abrangida por cada um deles. Isso permitiu uma compreensão detalhada da cobertura geográfica das entregas. 

Quantidade de Entregas por Distrito

A quantidade de entregas realizada em cada distrito foi analisada, proporcionando uma visão clara de como as entregas estão distribuídas entre os diferentes distritos.

Distritos com Maior e Menor Quantidade de Entregas por Região

Foram identificados os distritos com maior e menor quantidade de entregas dentro de cada região. Esses dados ajudam a entender as áreas de maior demanda e as que apresentam menor volume de entregas.

Top 10 Subúrbios com Maior Quantidade de Entregas

A análise revelou os 10 subúrbios com maior número de entregas realizadas. Essa informação é útil para otimizar as rotas e alocar recursos de maneira mais eficiente.

op 10 Subúrbios com Menor Quantidade de Entregas

Foram identificados também os 10 subúrbios com menor quantidade de entregas realizadas, o que pode indicar áreas com baixa demanda ou que necessitam de ajustes na logística.

Regiões com Maior Índice de Entregas Grandes

A análise também focou nas entregas grandes (itens volumosos ou de maior valor). As regiões com maior índice de entregas grandes foram destacadas, ajudando a identificar onde é necessário um planejamento logístico mais robusto.

 ## Próximos passos

   Para aprimorar o projeto e torná-lo ainda mais informativo, os próximos passos incluem:

Implementar a opção de análise por diferentes períodos (semanal, mensal e trimestral), permitindo uma visão mais ampla das tendências ao longo do tempo.

Adicionar filtros para seleção de regiões (Ex.: Norte, Sul, Sudeste), possibilitando uma análise comparativa entre diferentes localidades.

Aprimorar a visualização dos dados, tornando o dashboard mais dinâmico e interativo para facilitar a extração de insights estratégicos.

## Como executar 
Clonar o Repositório
Acesse o repositório no GitHub e copie o link.

Executar o Código no Google Colab ou VS Code

Abra o Google Colab ou um ambiente local como VS Code.

Caso utilize o Google Colab, faça o upload dos arquivos necessários ou acesse diretamente pelo GitHub.

Execute todas as células do notebook para processar os dados e gerar as tabelas.

 Configurar o Dashboard no Looker Studio
 
Acesse o Looker Studio.

Importe o arquivo CSV gerado pelo código.

Configure os gráficos e filtros conforme necessário para explorar os dados interativamente.

 Explorar os Dados

Analise tendências, como número de casos confirmados, mortes e vacinação ao longo do tempo.

Utilize os filtros para visualizar os dados por períodos e regiões.

Esse processo garantirá que você consiga reproduzir as análises e interagir com os dados no dashboard de forma eficiente. 🚀
    

  ## Licença
    
  - MIT License

  - ## Habilidades adquiridas 

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/-Pandas-333333?style=flat&logo=pandas)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-000000?style=flat&logo=python)
