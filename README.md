# Intesivão de python - hashtag 
### OBS: antes baixe o Jupyter e o Anaconda
Tabela de conteúdos
=================
<!--ts-->
   * [Aula 1](#aula-1)
       * [Meu projeto](#meu-projeto-com-coisas-aprendidas-na-aula-1)
   * [Aula 2](#aula-2)
       * [Meu projeto](#meu-projeto-com-coisas-aprendidas-na-aula-2)
   * [Aula 3](#aula-3)
       * [Meu projeto](#meu-projeto-com-coisas-aprendidas-na-aula-3)
   * [Ferramentas](#tecnologias)
<!--te-->
# Aula 1
### Objetivo do desafio:
Fazer um código que automaticamente mande para a diretoria um e-mail com o relatório de vendas
### Para isso simularemos o use do mouse e do teclado com as bibliotecas: pyautogui(imita cliques, atalhos e escreve textos normais) e pyperclip(pode copiar textos com caractéres especiais)
### Passos para resolver grande parte dos problemas com python:
- 1° - Pense como você resolveria ele manualmente com seu computador
- 2° - Traduza essa passo a passo para a linguagem python
### Bibliotecas: muitas pessoas usam python, então provavelmente se você procurar, você achará uma ou mais bibliotecas em python para te ajudarem a resolver mais facilmente o seu problema
### OBS: Principalmente quando você ainda não fez algo em programação muitas vezes é completamente normal um programador olhar no google/nas documentações os comandos que executam certa função
### O  principal problema dessas bibliotecas que usamos nessa aula: elas n se adaptam a diferentes resoluções de telas e pequenas variações em layouts de sites
### Biblioteca para manipular dados/datasets: pandas

## Meu projeto com coisas aprendidas na aula 1
### Objetivo: como estamos passando por uma pandemia, o objetivo era todo dia te enviar um e-mail com os casos ocorridos de Covid-19
### OBS: também usei uma API(https://github.com/M-Media-Group/Covid-19-API/?ref=devresourc.es), além das bibliotecas ensinadas na aula 1, de automação de processos
### Rode: ```pip install requests``` (baixar a biblioteca requests, para consumir APIs), ```pip install pyautogui``` e ```pip install pyperclip``` para instalar essas 3 bibliotecas
# Aula 2
### Tema da aula: análise de dados / Data Science
### Objetivo do desafio principal: uma empresa de telecom está perdendo clientes, como amenizar isso?
### Tema principal da aula: Análise de dados - data science
### OBS: em DS a empresa só fala o problema e você deve resolvê-lo
### Passos da análise dos dados:
- pegar eles e visualizá-los
- corrigir inconsistências neles(OBS: dado que não ajuda atrapalha)
- análise inicial(mensurar o problema e confirmar se as informações básicas te passadas estão corretas, como se realmente foram 26% dos clientes que foram embora)
- análise mais detalhada dos dados
### Quando você não precisa colocar o path todo de um arquivo para lê-lo: quando ele está na mesma identação de pastas que o código rodando
### OBS: churn = cancelamento de um serviço
### Tratamento de dados:
- tire informações inúteis
- arrume formatos errados
    - exemplos de dtypes para colunas:
        - object: texto-string
        - int: números inteiros
        - float: números decimais/de pontos flutuantes
- valores vazios, OBSs:
    - NaNs atrapalham 
    - Se a representividade de linhas com NaNs perante as linhas totais é baixo, pode apenas excluir essas linhas, como fizemos, mas caso contrário, temos que fazer outras coisas, como, por exemplo, pegar a média dos valores da coluna
### Análise inicial:
confirmar as informações passadas para você e medir tamanho do problema, ex: quantos clientes sairam? de quantos?
### OBS: Em DS você quer reconhecer padrões, ex: relacionar/ver se tem um padrão de comportamento com o preço x cancelamento
### Biblioteca para mecher com gráficos: plotly.express > px
### Análise aprofundada:
- 1o: olhe a cada gráfico(cada 'parâmetro' vs o parâmetro 'principal') se uma distribuição chama atenção, se ela é proporcionalmente anormal
- 2o: Pense se os resultados fazem sentido e o que você pode fazer com ele
    - Ex: casados cancelam mais > talvez seja porque eles tem mais pessoas na fámilia > talvez seja interessante criar planos família
## Meu projeto com coisas aprendidas na aula 2
### Objetivo: relacionar a ocorrência de diabetes com alguns parâmetros de saúde, etc.
### Rodar: ```pip install pandas```(biblioteca de manipulação de dados), ```pip install seaborn```, ```pip install matplotlib``` e ```pip install plotly```, as 3 para criação de gráficos.
# Aula 3
### Desafio: você trabalha numa importadora e deve atualizar preços com  cotação dólar, ouro e euro
### Ferramenta: selenium(instalado via pip) > permite controlar tudo do navegador: from webdriver from selenium
- Ele precisa do web driver para fazer isso, que varia por navegador, ex: chrome(chromedriver)
    - Baixe a versão pro seu navegador, ver versão no chrome: 3 pontos > ajuda > sobre o google chrome
    - coloca ele onde seu python tá instalado, na pasta anaconda3 ou na pasta do seu código
### Comparação entre as bibliotecas:
selenium   | pytutogui
--------- | ------
igual em todas resoluções | muda com resolução
usa só navegador | meche em todo o pc
pause entre comandos automático
### Pegar o xpath de um elemento: f11 > símbolo setinha > seleciona elemento > botão direito > copy > copy xpath
## Meu projeto com coisas aprendidas na aula 3
### Objetivo: ver se na Amazon certo produto está mais barato que certo valor
### Rodar: Baixar web driver pro seu navegador e ```pip install selenium```
# Tecnologias

As seguintes ferramentas foram usadas na construção dos projetos:

- [Python](https://www.python.org/)
- [Anaconda](https://www.anaconda.com/)

As seguintes bibliotecas python foram usadas na construção dos projetos:

- [Pyautogui](https://pypi.org/project/PyAutoGUI/)
- [Pyperclip](https://pypi.org/project/pyperclip3/)
- [Pandas](https://pypi.org/project/pandas2/)
- [Plotly](https://pypi.org/project/plotly/)
- [Seaborn](https://pypi.org/project/seaborn/)
- [Selenium](https://pypi.org/project/selenium/)