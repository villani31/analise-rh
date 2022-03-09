# analise-rh

Um projeto real de Data Science, que passou por todas as etapas, pude resolver o problema de como utilizar os dados para responder questões importantes, permitindo que uma empresa tenho conhecimento sobre seu funcionário:

* Quais são os fatores que influenciam para um colaborador deixar a empresa?.
* Como reter pessoas?.
* Como antecipar e saber se um determinado funcionário vai sair da empresa?.

E por fim disponibilizar recurso, para que a empresa consiga realizar a predição para verificar se um colaborador vai ou não deixar a empresa, com base em atributos, como comportamento e carga de trabalho, nível de satisfação, com a empresa, e resultados de performance.

Tecnologias utilizadas

Para resolver esse problema, foi construido uma solução completa para armazenamento, gestão e automatização de fluxo de dados, utilizando as tecnologias como:

* Apache Airflow.
* Docker.
* Minio.
* Mysql Server.

Alem de explorar um suite poderoso de tecnologias, para trabalhar com Análise de Dados e Machine Learning, que são:

* Pandas.
* Scikit-Learn.
* PyCaret.
* SweetViz.
* Streamlit.

Depois da infraestrutura devidamente criada e configurada, levando em consideração o desafio proposto, foram criados e modelados atributos relevantes para a análise, utilizando fonte de dados de diversos arquivos, em formatos xlsx, json, e dados no sistema de banco de dados.

Analise dos Dados

Na etapa da analise exploratória de dados, foram descobertos vários insights importantes:

* A empresa tem uma rotatividade de 24%.
* Podemos assumir que os empregados que mais deixam a empresa, estão insatisfeitos.
* A maioria dos empregados que saíram, tinham salário baixo ou médio.
* Todos os funcionário que estavam inserido em muitos projetos, deixaram a empresa.
* Colaboradores insatisfeito com a empresa, tem uma tendencia maior de deixar a empresa.

Através da analise, foi possível desenvolver 3 grupos distintos, para agrupar colaboradores que deixam a empresa por comportamento similares, são:

Grupo 1 (Empregados insatisfeitos e trabalhadores): A satisfação foi inferior a 20, e a avaliação foram superiores a 75.

Que correspondem ao grupo de funcionários que deixam a empresa e eram bons trabalhadores.
Grupo 2 (Empregados ruins e insatisfeitos): Satisfação entre 35 a 50, e as avaliações a baixo de 58.

Correspondem aos empregados que foram mal avaliados, e se sentiram mal para o trabalho.

Grupo 3 (Empregados satisfeitos e trabalhadores): Representam os empregados ideais, que gostam do seu trabalho, e são bem avaliado por seu desempenho.

Este grupo pode indicar os empregados que deixam a empresa, porque encontram outra oportunidade de trabalho.

Machine Learning

Para estimativa, com o objetivo de predizer se um empregado vai deixar a empresa, foi implementado um modelo utilizando o algoritmo Gradient Boosting Classifier (mesmo não sendo o melhor modelo na analise, optei por usar esse), que atingiu uma performanse de AUC em 0.80.

Conclusão

Através desse projeto, foi possível praticar e implementar conceitos importantes da Ciência, Engenharia de Dados, e propor uma solução para um problema latente e recorrente de qualquer empresa, que é a retenção de talentos, através da Analise de Dados de Recursos Humanos.

Como um processo de melhoria continua, podemos desenvolver a automação para executar não só o pipeline, mas a coleta e transformação de dados, e automatizando os passos das etapas de Machine Learning e Deploy.


