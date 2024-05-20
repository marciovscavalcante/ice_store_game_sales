## ANÁLISE HISTÓRICA DE VENDAS DA INDÚSTRIA DE GAMES

#### Este projeto visa analisar os dados da venda de jogos da loja on line "Ice" no período de 1980 a 2016 procurando identificar padrões que levam um jogo ao sucesso ou não a fim de colaborar nas projeções para campanhas publicitárias para o ano subsequente.

---

### Bibliotecas utilizadas:

* pandas
* numpy
* scipy
* matplotlib
* seaborn


---

### CONCLUSÃO

Na etapa de preparação dos dados convertemos os colunas e os dados das coluna para minúsculas, assim como os dados dos anos de lançamento para números inteiros e os da coluna de avaliações de usuários para float64, tornando o conjunto de dados mais consistente.
Os valores nulos das colunas ‘User_score’ e ‘Critic_Score’ foram tratados pontualmente de acordo com a necessidade.

A preparação e tratamento dos dados desta maneira permite uma análise mais assertiva.

A análise destes dados trata das mudanças nas vendas de jogos e plataformas de video game desde os anos 1980 mostrando seu surgimento, ascendência, picos e declínios, volumes de vendas, categorias e classificações dadas pro críticos da área e usuários comuns.

É possível ver os ciclos de vida de cada plataforma, os concorrentes de cada período, além de poder comparar o final de ciclos de vida de algumas plataformas ao mesmo tempo do início do ciclo de outras, plataformas que foram substituídas pelas suas novas versões, etc.

É possível ver um aumento significativo nos lançamentos de jogos a partir da década dos anos 1990 e constatar que o ciclo de vida médio das plataformas gira entre 9 e 10 anos, com um destaque para os lançamentos para ‘PC’ que se manteve constante por aproximadamente 20 anos.

No que diz respeito à relação das avaliações dos críticos e usuários e as vendas dos jogos não é possível afirmar que há uma relação direta demonstrando que outros fatores podem ser mais significativos nesta questão.

As classificações etária com mais vendas nas três regiões estudadas são “E” (Everyone), “T” (Teen), “M” (Mature) e “E10+” (Everyone 10+) com uma leve diferença entre a “T” e a “M” a depender da região.

Esta análise pode ajudar a entender o quão dinâmico é este setor e o quanto o avanço da tecnologia pode encurtar os ciclos de vida de cada jogo e/ou plataformas, auxiliando no planejamento da criação de novas plataformas, assim como as campanhas publicitárias podem atuar.

O estudo de perfis de usuários por região podem ajudar a entender as demandas locais podendo indicar tendências que podem estar atreladas à cultura e costumes de cada lugar. Os fabricantes de cada plataforma podem se beneficiar muito de análises como esta direcionando recursos de marketing específicos para cada necessidade regional.

---

### TESTES ESTATÍSTICOS:

Em relação aos testes estatísticos, analisamos 2 hipóteses. Os resultados são os seguintes: 

#### **1ª Hipótese: As classificações médias dos usuários das plataformas Xbox One e PC são as mesmas.**

A Classificação média dos usuários da plataforma Xbox One e PC são 6.52 e 7.06 respectivamente e o teste t de Student REJEITOU a hipótese nula em favor da hipótese alternativa considerando estatisticamente que as classificações médias dos usuários das plataformas Xbox One e PC são DIFERENTES.

#### **2ª Hipótese: As classificações médias de usuários para os gêneros Action (ação) e Sports (esportes) são diferentes.**

A Classificação média dos usuários do gênero Action e Sports são 7.05 e 6,96 respectivamente e o teste t de Student NÃO REJEITOU a hipótese nula em favor da hipótese alternativa considerando estatisticamente que não há evidências suficientes para afirmar que as classificações médias de usuários para os gêneros Action (ação) e Sports (esportes) são iguais.
