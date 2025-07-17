
#  ⚓ 🛳️ Data Science Aplicada às Paralisações Portuárias: Um Estudo de Padrões e Tendências ⚓ 🛳️

 O presente trabalho tem como objetivo a aplicação de técnicas e práticas de **Data Science e Big Data**
 na análise e previsão de paralisações portuárias. Para isso, utilizou-se a linguagem de programação **Python**,
 juntamente com bibliotecas especializadas como **Pandas,Seaborn e Matplotlib**,com vistas à coleta,tratamento
 e exploração de dados históricos disponibilizados pela ANTAQ (Agência Nacional de Transportes Aquaviários),
 abrangendo o período de 2020 a 2024. A abordagem adotada permitiu identificar padrões, tendências e fatores
 de risco recorrentes associados às paralisações, gerando insights estratégicos para a gestão eficiente das
 operações portuárias. Foram empregadas técnicas de pré-processamento, limpeza e visualização de dados,
 comointuito deassegurar a integridade e a confiabilidade das análises desenvolvidas. Os resultados obtidos
 demonstram o potencial das ferramentas de ciência de dados para apoiar a tomada de decisão, otimizar
 processos logísticos e fortalecer a resiliência dos portos brasileiros frente a eventos críticos e interrupções
 operacionais

## Objetivos

 Análise de dados da ANTAQ sobre paralisações portuárias, por meio de técnicas de Data Science e Big Data, com uso de Python e bibliotecas auxiliares.
 **Objetivos Específicos:**
 - Identificar os portos mais afetados no país
 - Identificar os tipos de paralisações existentes
 - Analisar o Porto de Paranaguá em específico
 - O comportamento das paralisações nas Regiões Geográficas


## Metodologia
 A ANTAQ disponibiliza um painel estatístico em seu portal, oferecendo acesso à informações cruciais sobre
 as operações portuárias no Brasil, incluindo um dashboard interativo para facilitar a navegação dos usuários. Para a análise dos dados, foram coletados os registros do período de 2020 a 2024, abrangendo uma ampla gama de variáveis e indicadores relevantes. . A linguagem Python foi escolhida devido à sua robustez na manipulação de grandes volumes de dados e à ampla integração com bibliotecas especializadas, como Numpy, Seaborn, Pandas e Matplotlib. Além disso, a integração com ferramentas de visualização como Power BI, Excel, Google Colab e Google Drive torna a análise mais fluida e acessível.


## Sobre os Dados
- Fonte: https://www.gov.br/antaq/pt-br
- Período: análise de 2020 a 2024
- Variáveis Relevantes: Porto Atracação, Data Atracação, Data Chegada, Data Desatracação, Data Início da Operação, Data Final da Operação, Tipo de Operação, Região Geográfica, UF, Município, DescricaoTempoDesconto


## Resultados

Os gráficos apresentados ao longo do trabalho evidenciam, de forma clara, que a **Região Sul** e, em particular, o estado do Paraná concentra o maior número de paralisações no período analisado. O **Porto de Paranaguá** destacou-se com elevados índices de interrupções operacionais, superando outros portos relevantes da
 região, como Rio Grande (RS) e São Francisco do Sul (SC). Os resultados mostraram que os gargalos logísticos, sobretudo relacionados ao **transporte rodoviário** de acesso ao porto, representam uma das principais
 causas operacionais de ineficiência, refletindo diretamente no **tempo de atracação e na produtividade** das
 operações portuárias. Adicionalmente, a **dependência das condições climáticas** reforça a necessidade de sistemas preditivos que auxiliem no planejamento e na mitigação dos impactos operacionais.

## Limitações
- Dados do tipo Nan (n/a, vazias)
- Correções de datas de anos anteriores (2024 -> 2021,2022)
- Limpeza e tratamento
- Remoção de colunas desnecessárias


## Próximos Passos

A ampliação da base de dados, incorporando variáveis externas, como informações climáticas detalhadas, tráfego rodoviário em tempo real e indicadores econômicos, além de um monitoramento maiseficiente das condições meteorológicas que impactam diretamente a operação portuária.
<p align="center">
  <img src="Artigo - Vanessa Mereles.png" width="45%" />
  <img src="Artigo - Vanessa Mereles2.png" width="45%" />
</p>

