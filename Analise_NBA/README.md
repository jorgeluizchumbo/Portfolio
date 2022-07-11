<h1 style='color: blue; font-size: 36px; font-weight: bold;'>EDA e Modelo de Previsão do MVP da NBA</h1>

# Tópicos
## Objetivo
Analisar as estatísticas obtidas dentro do período de 1991 até 2021, sobre os jogadores da NBA e criar um modelo de previsão do jogador que será eleito o MVP da temporada regular.
## Obtenção dos Dados
Os dados foram retirados do Kaggle do VIVO VINCO, e podem ser acessados por meio do link:
    
https://www.kaggle.com/datasets/vivovinco/19912021-nba-stats
    
Os arquivos com que iremos trabalhar possuem estatísticas de jogadores, equipes e MVPs da NBA, de 1991-2021. Os dados foram coletados pelo autor VIVO VINCO por meio de web scraping adaptado do canal Dataquest do Youtube. O canal Dataquest e a fonte dos dados podem ser acessados nos links:
    
https://www.youtube.com/watch?v=JGQGd-oa0l4    

https://www.basketball-reference.com/

Como iremos trabalhar com os dados previamente coletados, nosso projeto parte do ponto após a coleta.
## Apresentação dos Dados
Nesta seção iremos observar de forma geral os dados presentes no dataset.
Os dados estão distribuídos em 4 arquivos, dentre eles:
- mvps.csv: Contém as estatísticas apenas dos jogadores da NBA que receberam votos para MVP nos anos de 1991 até 2021
- nicknames.csv: Contém os nomes dos times e suas respectivas abreviações
- players.csv: Contém as estatísticas dos jogadores da NBA nos anos de 1991 até 2021
- teams.csv: Contém as estatísticas dos times da NBA nos anos de 1991 até 2021
## Limpeza dos Dados
Aqui realizaremos a limpeza dos dados. Verificaremos cada arquivo mencionado acima a fim de encontrar dados a serem excluídos ou transformados.
## Análise Exploratória dos Dados
Este tópico contém a análise exploratória dos dados. Analisaremos as estatísticas dos jogadores ao longo do tempo, as estatísticas por posição, como a bola de 3 pontos está, a cada temporada que passa, cada vez mais sendo utilizada e quais os impactos disso para o desempenho de uma equipe.
## Criação do Modelo de Previsão
Nesta seção iremos criar um modelo de previsões que utilizará os dados previamente coletados para entender o que faz um jogador ser eleito MVP da temporada. Compararemos dois modelos, Rigde e Lasso, e escolheremos um deles para treinar nosso modelo e testar nossas previsões.
## Próximos Passos
Avaliando o resultado do modelo, aqui apresentamos o que podemos fazer para melhorar futuramente o modelo de previsões.
## Conclusão
Uma breve conclusão sobre o presente estudo.
## Referências
VIVO VINCO. 1991-2021 NBA Stats. Kaggle. Disponível em: https://www.kaggle.com/datasets/vivovinco/19912021-nba-stats. Acesso em 7 mai. 2022.

BASKETBAAL REFERENCE. Basketball-Reference.com. Disponível em: https://www.basketball-reference.com/. Acesso em: 7 mai. 2022.

WIN SHARE (WS/48). NbaStuffer.com. Disponível em: https://www.nbastuffer.com/analytics101/win-share/#:~:text=Win%20Share%20is%20a%20measure,to%20distribute%20among%20the%20players.%E2%80%9D. Acesso em: 8 mai. 2022.

BASKETBAAL REFERENCE GLOSSARY. Basketball-Reference.com. Disponível em: https://www.basketball-reference.com/about/glossary.html#:~:text=SRS%20%2D%20Simple%20Rating%20System%3B%20a,thorough%20explanation%20of%20this%20method. Acesso em: 8 mai. 2022.

ANDRADE, Gustavo. Posições de basquete: quais são e as funções dos jogadores. EsporteLândia, 2019. Disponível em: https://www.esportelandia.com.br/basquete/posicoes-basquete/. Acesso em 8 mai. 2022.

DATAQUEST. Web Scraping NBA Stats With Python: Data Project [Part 1 of 3]. Youtube jan. 2022. Disponível em: https://www.youtube.com/watch?v=JGQGd-oa0l4. Acesso em: 9 mai. 2022.

FREITAS, Vinícius. A história do arremesso de 3 pontos na NBA. PlayMaker Brasil, 2020. Disponível em: https://www.playmakerbrasil.com.br/noticia/historia-do-arremesso-de-3-pontos-na-nba. Acesso em 9 mai. 2022.

NBA AWARDS. ESPN.com. Disponível em: http://www.espn.com/nba/history/awards/_/id/33. Acesso em 9 mai. 2022.

SAN ANTONIO SPURS PLAYOFF HISTORY. Basketball.Realgm.com. Disponível em: https://basketball.realgm.com/nba/teams/San-Antonio-Spurs/26/Playoff-History. Acesso em 9 mai. 2022.
# Técnicas e Tecnologias Utilizadas
 - Python
 - Jupyter Notebook
 - Análise de dados
 - Rigde
 - Lasso
 - Machine Learning
# Autor
Jorge Luiz Chumbo
