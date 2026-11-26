# ComprasClaras
Compra Claras

Plataforma de análise e visualização de preços em compras públicas

O Compra Clara é um projeto acadêmico desenvolvido com o objetivo de facilitar a consulta, organização e análise de informações relacionadas aos preços de materiais e serviços registrados em compras públicas do Governo Federal.

A solução utiliza técnicas de Engenharia de Dados, análise estatística e Business Intelligence (BI) para identificar possíveis anomalias nos preços e apresentar os resultados de maneira organizada e acessível.

---

Objetivos do projeto

- Coletar informações de compras públicas por meio de fontes de dados abertos.
- Realizar o tratamento e a padronização dos dados.
- Identificar possíveis anomalias nos preços utilizando métodos estatísticos.
- Disponibilizar uma interface para consulta de materiais e serviços.
- Facilitar a interpretação dos dados por meio de gráficos e painéis visuais.

Funcionalidades

- Consulta de materiais utilizando o catálogo CATMAT.
- Consulta de serviços utilizando o catálogo CATSER.
- Pesquisa de registros por nome ou código.
- Identificação estatística de possíveis anomalias.
- Apresentação de indicadores como média, desvio-padrão e Z-score.
- Visualização de informações por meio de tabelas, gráficos e painéis de alertas.

Tecnologias utilizadas

Tecnologia| Aplicação
Python| Linguagem principal
Pandas| Manipulação e organização dos dados
PySpark| Processamento e transformação dos dados
Gradio| Desenvolvimento da interface web
Google Colab| Ambiente de desenvolvimento
Parquet| Armazenamento dos dados processados
GitHub| Controle de versão e colaboração

Arquitetura de dados

O projeto utiliza a arquitetura Medalhão, dividida em três camadas:

Bronze — Dados brutos

Armazenamento das informações coletadas diretamente das fontes de dados.

Silver — Dados tratados

Limpeza, padronização, filtragem e remoção de registros duplicados.

Gold — Dados preparados para análise

Armazenamento dos resultados processados e das informações utilizadas na identificação de possíveis anomalias.

Detecção de anomalias

O Compra Clara utiliza o método estatístico Z-score para avaliar o afastamento dos preços em relação à média do conjunto analisado.

A classificação utilizada considera o seguinte limite:

"|Z-score| >= 2.0"

Os registros que ultrapassam esse limite são destacados como possíveis anomalias, indicando valores que merecem uma análise mais aprofundada.

Importante: a identificação estatística de uma anomalia não representa, isoladamente, comprovação de irregularidade.

Fonte de dados

Os dados utilizados no projeto são obtidos por meio da API de Dados Abertos de Compras Governamentais.

Documentação da API:
https://dadosabertos.compras.gov.br/swagger-ui/index.html

Repositórios e ambientes de desenvolvimento

- Código-fonte: https://github.com/GeoxCode/ComprasClaras

Organização da equipe

Projeto desenvolvido de forma colaborativa por estudantes, com atividades distribuídas entre Engenharia de Dados, Desenvolvimento da Interface e BI e Visualização de Dados.

Instituição parceira: Touti Cosmetics.

Contexto acadêmico

Projeto desenvolvido no contexto de atividade acadêmica de extensão, com a finalidade de aplicar conhecimentos de tecnologia da informação na construção de uma solução voltada à análise e interpretação de dados públicos.

Melhorias futuras

- Ampliação das fontes de dados utilizadas.
- Aprimoramento dos métodos estatísticos de detecção.
- Melhorias na interface e na experiência do usuário.
- Expansão dos recursos de visualização.
- Automatização das etapas de atualização e processamento dos dados.


Feito por:
GeoxCode
joaohelioleal
Luís-agosto07
pedro-89op
ViniciusAlmeida1prog

---

Compra Clara — Transformando dados públicos em informações mais acessíveis.
