## Pipocão Movies

<img src="" alt="logo" style="zoom: 90%;" />

O objetivo desse projeto é realizar o estudo de Sistemas de Recomendações utilizando a técnica de Processamento de Texto + Cálculo de Distância de Vetores.

O contexto de negócio é fictício. Todavia, o planejamento, execução, desenvolvimento e implementação da solução seguem todos os passos de um projeto real.


## PROBLEMA DE NEGÓCIO

A Pipocão Movies é uma plataforma de streaming de filmes que oferece aos seus assinantes uma ampla variedade de títulos. No entanto, a empresa enfrenta o desafio de manter os usuários engajados e satisfeitos, garantindo que eles continuem consumindo conteúdo regularmente. Para atender a esse objetivo, a Pipocão Movies decidiu investir em um Sistema de Recomendação automatizado.

O desafio é fidelizar os clientes e incentivá-los a assistir mais filmes na plataforma. A solução proposta consiste em recomendar filmes aos usuários após eles assistirem a um primeiro filme. O Sistema de Recomendação automatizado analisará dados do usuário, como avaliações, gêneros preferidos e filmes assistidos, para gerar sugestões personalizadas. Dessa forma, os clientes não precisam navegar extensivamente pela plataforma em busca de filmes relevantes.

O Cientista de Dados contratado pela Pipocão Movies terá a tarefa de projetar e implementar esse Sistema de Recomendação, considerando desafios como dados esparsos e escolha de algoritmos eficazes. O sucesso desse sistema será fundamental para o crescimento contínuo da empresa e a satisfação de seus clientes!


### Planejamento de Solução

**Qual é a solução?** A solução para esse problema é realizar uma análise exploratória dos dados da base de filmes da Pipocão e, com isso,  realizar processamento de texto e vetorização para encontrar o melhor Sistema de Recomendação utilizando técnicas de distância de vetores.
                                     

## PREMISSAS DE NEGÓCIO

Premissas assumidas:

* O usuário já é assinante da Pipocão Moveis e, assistiu a um primeiro filme. A partir disso, quer a recomendação de outro filme baseado nesse primeiro.

### Ferramentas Utilizadas

- Python 3.10.0
- Jupyter Notebook
- Metodologia CRISP-DM
- Git/GitHub
    
## ESTRATÉGIA DE RESOLUÇÃO

**Etapa 01 - Carregamento dos Dados:** Carregamento dos dados e uma breve análise sobre os atributos.

**Etapa 01 - Descrição dos Dados:** Detalhamento dos atributos.

**Etapa 02 - Preparação dos Dados:** Tratamento e lipeza de dados de texto, remoção de duplicidades e dados nulos, processamento de texto, vetorização de dados de texto e criação de novas features. 

**Etapa 03 - Sistema de Recomendação:** Cálculo da distância de vetores e construção do modelo de Sistema de Recomendação.


## PRÓXIMOS PASSOS

Em um próximo ciclo desse projeto, será colocado como objetivo:

- API para consumo desse Sistema
- Introdução de novas features.
- Teste A/B para validar a qualidade da recomendação.


**NoteBook com os códigos e desenvolvimentos:** [Notebook Pipocão Movies](https://github.com/jefferson-datascience/project_insight_house_rocket/blob/main/project_insight_house_rocket.ipynb)

**Dados Utilizados**: [Fonte de Dados Pipocão](https://github.com/jefferson-datascience/dashboard_house_rocket/blob/main/house_rocket_company_app.py)
