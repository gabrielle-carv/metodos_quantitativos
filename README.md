# Projeto - Tópicos Especiais em Métodos Quantitativos

## Objetivo Geral
O projeto foi elaborado para a cadeira de Tópicos Especiais em Métodos Quantitativos, e consiste na coleta, tratamento, análise e produção de previsões sobre os ganhadores das partidas dos jogos da Copa do Mundo de Futebol Feminino - FIFA. O campeonato deu-se início  em 1991. Desde então já ocorreram 8 edições,  nas quais se disputaram 284 partidas, com 36 seleções distintas participantes.

## Organização do projeto:
O projeto está organizado em quatro etapas, são elas:
 - A coleta dos dados, incluindo todas as partidas durante os anos, via _web scraping_, no site oficial da [FIFA](https://www.fifa.com/fifaplus/en/tournaments/womens/womensworldcup/); 
 - O tratamento de dados, que consiste em gerar percentuais de desempenho e em organizar os inputs em uma nova tabela; 
 - A análise, que consiste na produção de visualizações dos dados;
 - A previsão, utilizando-se do método de _Deep Learning_.

 No repositório apresentamos 3 pastas. Na primeira `código`, encontra-se os 4 códigos utilizados em cada etapa, sendo elas a `coleta_dados_fifa.ipynb`, `tratamento_tabela_fifa.ipynb`, `visualizacao_dados_fifa.ipynb`, e `deep_neural.ipynb`. Já na pasta `auxiliar`, temos a versão mais atualizada do _chromedriver_, necessária para a execução do _web scraping_. Por fim, a pasta `input` armazena os dados coletados e tratados.

 
