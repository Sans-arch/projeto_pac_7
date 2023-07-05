# Especificação do Projeto
Apresentar em um repositório as especificações do projeto a ser desenvolvido, seguindo os itens escolhidos do playbook do portfólio. Será avaliado o problema abordado, a relevância desse problema e os artefatos (especificação) que representam a resolução do problema.

# Pipeline da aplicação:
![Pipeline](https://github.com/Sans-arch/projeto_pac_7/assets/69471715/0f9af85d-a089-4742-9030-6b58c3caa820)

# Arquitetura:
![Arquitetura](https://user-images.githubusercontent.com/69471715/230235372-680cedd2-f3a3-453b-adc2-e58db59b2785.png)

# Problema abordado:
Avaliar a quantidade de pontos atingida por cada time numa liga específica conforme uma quantidade de temporadas, isto é, simular com base em um determinado numero de temporadas e verificar como seria a tabela de classificação desses times. Para exemplificar, foram utilizados datasets da Série A do Brasileirão (Campeonato Brasileiro de Futebol).

# Relevância do problema
- O projeto resolve algum problema real?
Sim, é interessante para um analista esportivo ou para qualquer um que goste das estatisticas esportivas saber quais são os parâmetros ou características de um time competitivo que consegue subir de divisão, com base nesssa características será possível traçar uma ideia ou desenvolver um planejamento/estrategia para a temporada do time.

- A forma como o projeto resolve o problema é adequada?
Sim

- O projeto possibilita continuidade de modo aprimorar seu domínio de solução?
Acredito sim, quanto mais características e aspectos das bases de dados forem utilizadas e exploradas, mais refinados e mais limpos serão os dados, o que irão aprimorar as análises esportivas.

- O projeto demandou aplicação de conceitos estudados ao longo da graduação?
Sim, principalmente os conceitos que estamos aprendendo nas disciplinas do 7° semestre, Ciência de Dados e Aprendizado de Máquina. Além de utilizar conteúdos de probabilibade estatística do semestre anterior.

- O projeto demandou esforço consistente para sua solução?
Sim, a cada sprint o projeto foi melhorado/alterado.

# Critérios escolhidos (70%) do playbook do portfólio:
- Relevância do Projeto e Complexidade do Projeto: 10%
- Documentação: 20%
- Código-Fonte: 20%
- Estruturas de Engenharia: 25%
- Apresentação: 25%

# Utilizados:
- Relevância do Projeto e Complexidade do Projeto: 10%
- Documentação: 20%
- Código-Fonte: 20%
- Apresentação: 25%

# Matéria:
- Ciência de dados
- Aprendizado de máquina

# Dados:
- Dados puros obtidos de diversas fontes esportivas.
- Foi realizado o processamento dos dados para transforma-los em planilhas .csv.
- Foram obtidos datasets das planilhas.
- Foi feito um pré-processamento e pós-processamento nos datasets.
- Transfermarkt, Softscore (sites relacionados a estatísticas de futebol).

# Processo de desenvolvimento:
Para a obtenção do resultado esperado (tabela do campeonato brasileiro com as devidas escalações) foi utilizado a Distribuição de Poisson,
graças a ela foi possível estimar as posições que os times se encontrariam ao passar das temporadas.
Para a plottagem dos gráficos foi utilizado a biblioteca matplotlib, para trabalhar com os datasets foi utilizada a biblioteca **pandas**,
para trabalhar com numeros e dados matemáticos foi utilizada a biblioteca **numpy**, e por ultimo, para trabalharmos com a distribuição de Poisson
foi utilizada a biblioteca **scipy**.

Após a obtenção da tabela com as escalações dos times, foram realizadas diversas plottagens com dados que são interessantes para a exploração dos dados obtidos, entre eles temos:
-  Gráfico relacionado aos pontos conquistados dos 10 primeiros colocados.
- Gráfico da média de pontos dos 10 primeiros colocados.
- Gráfico da média de pontos dos 4 ultimos colocados.

Além dos gráficos em si, foi feita uma verificação de quais times iriam se classificar para a competição CONMEBOL Libertadores da América e para a competição CONMEBOL Copa Sul-americana.


# Escopo do projeto e a escolha dos artefatos a serem desenvolvidos:
- Utilização da distribuição de Poisson para prever o desempenho dos times de futebol conforme o passar das temporadas.
