# Projeto Integrador
Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal.

[Sprint 1](#sprint-1) | [Sprint 2](#sprint-2) | [Sprint 3](#sprint-3)


### O que é? 
O projeto visa criar uma plataforma de análise de imagens de satélite através de
um serviço de Inteligencia Artificial (IA) capaz de identificar talhões e disponibilizar
um catálogo de imagens para o usuário realizar download de sua busca.

### Team Members

+ Bruno Ferro -- Product Owner
+ Fabio Rodrigues -- FullStack Developer
+ Leonardo Tamanhão -- IA Developer
+ Luciano Cabral -- Scrum Master
+ Luis Belo -- Web Developer
+ Matheus Froes -- Backend Developer

## Artefatos e Repositórios

[Documentação separada por Sprint](https://drive.google.com/drive/u/3/folders/1AS1eB-qsdInLgi0UW6xuLSZGDQpPwmha)

[Planejamento de Custos e Horas](https://drive.google.com/open?id=1b351IJFYBzuri6sx5ZlnqnobeXm4cSlS)

[Dashboard de acompanhamento do projeto](https://dev.azure.com/lucianocruz01/Projeto%20Integrador/_dashboards/dashboard/c8bfe7ca-7bb5-4261-91a6-a9f078a0a09f)

[Backlog do projeto](https://dev.azure.com/lucianocruz01/Projeto%20Integrador/_backlogs/backlog/Projeto%20Integrador%20Team/Epics/?showParents=true)

[Repositório da API](https://github.com/projeto-integrador-g1/Flask-API)

[Repositório do WebGIS](https://github.com/projeto-integrador-g1/WebGIS-Plataform)

[Repositório do Serviço de IA](https://github.com/projeto-integrador-g1/Servico-IA)

## Sprint 1:

Objetivo: Pesquisar sobre o tema proposto, sobre as ferramentas que serão utilizadas na resolução do problema e 
desenvolver a primeira página da plataforma com a visualização do mapa e uma ferramenta básica de seleção

**[Documentation](https://drive.google.com/drive/u/3/folders/1qhnUQBDBVUIaxGOdL0TgIpf6z5JP8yfo)** 

**[Backlog](https://dev.azure.com/lucianocruz01/Projeto%20Integrador/_sprints/backlog/Projeto%20Integrador%20Team/Projeto%20Integrador/Sprint%201)** 

**[Burndown Trend](https://drive.google.com/file/d/17-GJRLwojfrG0i1MGky5YRGeooD243Mi/view?usp=sharing)** 

## Sprint 2:

Objetivo: Criar um modelo simples de IA de classificação de imagens, desenvolver uma API de inferface para o 
WebGIS e um banco de dados para o armazenamento das máscaras geradas pelo serviço de IA.

**[Documentation](https://drive.google.com/drive/u/3/folders/1XwToOaDLgdvcC0wSQAwXWRerNUuRDqb4)** 

**[Backlog](https://dev.azure.com/lucianocruz01/Projeto%20Integrador/_sprints/backlog/Projeto%20Integrador%20Team/Projeto%20Integrador/Sprint%202)** 

**[Burndown Trend](https://drive.google.com/file/d/1kFeO5KuLCDPC3ru2azyv0U8Ce5XZlj8K/view?usp=sharing)** 

**[Vídeo Explicativo](https://drive.google.com/file/d/1PdccgYjTxWIP8tYIAMJokku05IiwubY8/view)**

## Sprint 3:

Objetivo: Atualizar o modelo de IA para imagens de satélite, contrução do Catálogo de Imagens no WebGIS, simplificação da API e do banco de dados
e incorporação da API do Imgur como forma de armazenamento e acesso as imagens geradas pelo serviço de IA.

**[Documentation](https://drive.google.com/drive/u/3/folders/1klPyxhUSB8RrO4Xbtqx4uCAeug1uDU-b)** 

**[Backlog](https://dev.azure.com/lucianocruz01/Projeto%20Integrador/_sprints/backlog/Projeto%20Integrador%20Team/Projeto%20Integrador/Sprint%203)** 

**[Burndown Trend](https://drive.google.com/file/d/1VSnrsmPxhER5Sl1u5kdtaMa0jR_KfjMn/view?usp=sharing)** 

**[Vídeo Explicativo](https://drive.google.com/file/d/13XdghdyzcxnF0Pk03Qyz9ir4PzfKkvkz/view)**

## Tecnologias utilizadas:

**[Imgur API](https://apidocs.imgur.com/?version=latest)** To store and provide images
for the WebGIS plataform.

**[MongoDB](https://docs.mongodb.com/manual//)** NoSQL Database to store users informations and
allowing requests queries to be run.

**[Keras](https://keras.io/) [Tensor Flow](https://www.tensorflow.org/)** Neural network
that will be the core of the project written in Python and capable of running on top of
TensorFlow.

**[WebGIS](http://www.webgis.com/) with [VueJS](https://vuejs.org/)** To develop the frontend 
of the platform.

**[Mapbox](https://www.mapbox.com/)** For the Map Tile Engine os the plataform.

**[Flask](https://palletsprojects.com/p/flask/)** To create the RESTFull-API

**[GeoPandas](https://geopandas.org/)** To manipulate the data in the IA service
