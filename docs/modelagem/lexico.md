# Léxicos

## Introdução

O Léxico é uma técnica que procura descrever os símbolos de uma linguagem. O principal objetivo dos engenheiros de requisitos é buscar frases e símbolos do domínio da aplicação. Cada um desse símbolo é descrito com uma noção e um impacto, sendo a noção relacionada com o símbolo e o impacto com a descrição do efeito do símbolo na aplicação ou do efeito de algo na aplicação sobre o símbolo.

Essas descrições seguem o princípio circular e o princípio do vocabulário mínimo. O princípio da circularidade torna cada extensão da descrição ou a conotação, referindo-se a outros símbolos da linguagem. A parte não simbólica da descrição deve vir de um subconjunto reduzido de palavras com significado claro (vocabulário mínimo).

## Metodologia

Os léxicos do Lichess foram identificados a partir do uso do aplicativo e dos requisitos elicitados na etapa anterior. Abaixo temos o exemplo de como o léxico será apresentado:

|     Léxico     | Sinônimo |  Noção  |       Impacto       |    Classificação    |
| :------------: | :------: | :-----: | :-----------------: | :-----------------: |
| Nome do Léxico | Sinônimo | Símbolo | Descrição do efeito | Verbo/Objeto/Estado |

<div style="text-align: center">
<p> Tabela 1: Modelo dos léxicos (Fonte: autor, 2022).</p>
</div>

## Descrição dos Léxicos

### L01 - Inteligência artificial

|         Léxico          |    Sinônimo     |              Noção              |                                               Impacto                                                | Classificação |
| :---------------------: | :-------------: | :-----------------------------: | :--------------------------------------------------------------------------------------------------: | :-----------: |
| Inteligência Artificial | Computador, Bot | Jogador inimigo em modo offline | Ao jogar partidas sem ter de fato alguém para jogar uma inteligência artificial assumirá esse papel. |    Objeto     |

### L02 - Usuário

| Léxico  | Sinônimo |                Noção                |                          Impacto                           | Classificação |
| :-----: | :------: | :---------------------------------: | :--------------------------------------------------------: | :-----------: |
| Usuário | Jogador  | Classe padrão de usuário do Lichess | Usuários possuem acesso máximo aos elementos do aplicativo |    Estado     |

### L03 - Tabuleiro

|  Léxico   | Sinônimo |                                Noção                                 |                                                           Impacto                                                            | Classificação |
| :-------: | :------: | :------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: | :-----------: |
| Tabuleiro |   Mapa   | Artefato que guarda informações sobre peças de xadrez em uma partida | Identifica as posições das peças, possíveis futuros movimentos e estado de jogo, e responde conforme esses estados atualizam |    Objeto     |

### L04 - Partida

| Léxico  |  Sinônimo   |                     Noção                     |                                  Impacto                                  | Classificação |
| :-----: | :---------: | :-------------------------------------------: | :-----------------------------------------------------------------------: | :-----------: |
| Partida | Match, jogo | Instância em Lichess de uma partida de xadrez | Conecta os jogadores para permitir que compitam em uma partida de xadrez. |    Objeto     |

### L05 - Jogar

| Léxico | Sinônimo |               Noção                |                 Impacto                  | Classificação |
| :----: | :------: | :--------------------------------: | :--------------------------------------: | :-----------: |
| Jogar  |   Play   | Dar início a uma partida de xadrez | Jogador inicializa uma partida de xadrez |     Verbo     |

### L06 - Partida Online

|     Léxico     |      Sinônimo       |                     Noção                     |                 Impacto                  | Classificação |
| :------------: | :-----------------: | :-------------------------------------------: | :--------------------------------------: | :-----------: |
| Partida online | Partida multiplayer | Partida em que o adversário é um pessoal real | Usuário consegue jogar com pessoas reais |    Estado     |

### L07 - Partida com computador

|         Léxico         |                       Sinônimo                        |                                                             Noção                                                              | Impacto | Classificação |
| :--------------------: | :---------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------: | :-----: | :-----------: |
| Partida com computador | Partida offline, Jogar contra inteligência artificial | Partida em que o adversário é uma inteligência artificial realizando jogadas de acordo com um nível de dificuldade selecionado | Estado  |

### L08 - Buscar partida

|     Léxico     | Sinônimo |                    Noção                     |                                     Impacto                                      | Classificação |
| :------------: | :------: | :------------------------------------------: | :------------------------------------------------------------------------------: | :-----------: |
| Buscar partida |    -     | Ato de procurar partida de xadrez disponível | Apresenta ao usuário uma partida de xadrez compatível com seu nível de expertise |     Verbo     |

### L09 - Torneio

| Léxico  |  Sinônimo  |                            Noção                             |                                                        Impacto                                                         | Classificação |
| :-----: | :--------: | :----------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------: | :-----------: |
| Torneio | Competição | Séries de partidas onde são declarados vencedores do torneio | Permite usuário competir com usuário em nível mais alto e se desenvolver em uma série de rápidas partidas consecutivas |    Objeto     |

### L10 - Placar de líderes

|      Léxico       |  Sinônimo   |                                           Noção                                            |                             Impacto                             | Classificação |
| :---------------: | :---------: | :----------------------------------------------------------------------------------------: | :-------------------------------------------------------------: | :-----------: |
| Placar de líderes | Leaderboard | Lista de usuários com base na sua pontuação e modo de jogo. Ordenado de forma decrescente. | Permite o usuário identificar os melhores jogadores de Lichess. |    Objeto     |

### L11 - Modo de jogo

|    Léxico    |     Sinônimo      |                           Noção                           |                              Impacto                               | Classificação |
| :----------: | :---------------: | :-------------------------------------------------------: | :----------------------------------------------------------------: | :-----------: |
| Modo de jogo | Variações do jogo | Diferentes regras inseridas no sistema de jogos de xadrez | Possibilita usuário experimentar diferentes formas de jogar xadrez |    Estado     |

### L12 - Buscar jogador

|     Léxico     |           Sinônimo            |                     Noção                      |                      Impacto                      | Classificação |
| :------------: | :---------------------------: | :--------------------------------------------: | :-----------------------------------------------: | :-----------: |
| Buscar jogador | Buscar usuário, Buscar player | Ato de pesquisar um usuário através de sua tag | Permite usuário pesquisar por pessoas específicas |     Verbo     |

### L13 - Ping

| Léxico |   Sinônimo   |                              Noção                              |                               Impacto                                | Classificação |
| :----: | :----------: | :-------------------------------------------------------------: | :------------------------------------------------------------------: | :-----------: |
|  Ping  | Sinal, delay | Atraso de internet entre ações do usuário e resposta do Lichess | Modifica a experiência do usuário em acessar os elementos de Lichess |    Objeto     |

### L14 - Aulas de xadrez

|     Léxico      |       Sinônimo        |                                  Noção                                  |                     Impacto                      | Classificação |
| :-------------: | :-------------------: | :---------------------------------------------------------------------: | :----------------------------------------------: | :-----------: |
| Aulas de xadrez | Classes, aprendizados | Artigos juntos de análises sobre determinado movimento/teoria do xadrez | Permite usuário aumentar sua expertise no xadrez |    Objeto     |

### L15 - Estudar aulas de xadrez

|         Léxico          |           Sinônimo           |                   Noção                    |                     Impacto                      | Classificação |
| :---------------------: | :--------------------------: | :----------------------------------------: | :----------------------------------------------: | :-----------: |
| Estudar aulas de xadrez | Evoluir habilidade de xadrez | Ler e aplicar conceitos de aulas de xadrez | Permite usuário aumentar sua expertise no xadrez |     Verbo     |

### L16 - Aulas em alta

|    Léxico     |  Sinônimo   |                Noção                 |                           Impacto                            | Classificação |
| :-----------: | :---------: | :----------------------------------: | :----------------------------------------------------------: | :-----------: |
| Aulas em alta | Hot classes | Aulas de xadrez com maior relevância | Facilita o usuário na escolha de aulas de xadrez para estudo |    Estado     |

### L17 - Assistir partidas

|      Léxico      |            Sinônimo             |                                                        Noção                                                         |                                                                Impacto                                                                | Classificação |
| :--------------: | :-----------------------------: | :------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: | :-----------: |
| Assistir partidas | Visualizar jogos, Assistir jogos | Usuário descobre formas diferentes de jogar e pode acabar querendo seguir os padrões de jogo dos usuários da partida | Usuário descobre novas jogadas de forma inconsciente e pode acabar querendo seguir os padrões de movimento de dos usuários da partida |     Verbo     |

### L18 - Treinamento

|   Léxico    | Sinônimo |                    Noção                     |                         Impacto                          | Classificação |
| :---------: | :------: | :------------------------------------------: | :------------------------------------------------------: | :-----------: |
| Treinamento | Prática  | Partida de xadrez para simular conhecimentos | Permite usuário treinar determinada habilidade no xadrez |    Estado     |

### L19 - Relógio

| Léxico  |      Sinônimo       |                   Noção                   |                                Impacto                                 | Classificação |
| :-----: | :-----------------: | :---------------------------------------: | :--------------------------------------------------------------------: | :-----------: |
| Relógio | Temporizador, clock | Contador de tempo para partidas de xadrez | Ao esgotar o tempo, jogador não poderá mais executar movimento no jogo |    Objeto     |

### L20 - Busca Avançada

|     Léxico     | Sinônimo |                                        Noção                                         |                             Impacto                             | Classificação |
| :------------: | :------: | :----------------------------------------------------------------------------------: | :-------------------------------------------------------------: | :-----------: |
| Busca Avançada |    -     | Busca de partidas/ jogos de forma mais extensiva com diversos elementos de filtragem | Permite o usuário ter um refinamento na hora de realizar buscas |    Estado     |

## Conclusão

Portanto, os léxicos encontrados foram buscados e reconhecidos através do uso do aplicativo, identificando o que poderia ser visto como uma figura de linguagem que passa a descrição de algo ou como um simples ícone. Com isso concluímos que alguns deles tem rastreabilidade conexa com a atividade de cenários estipulando uma conexão entre os artefatos e permitindo ainda mais a rastreabilidade entre eles.

## Bibliografia

[1] CONSTRUÇÃO do léxico de aplicações. Proceedings of the International Joint Conference IBERAMIA/SBIA/SBRN 2006 : 4th Workshop in Information and Human Language Technology, Ribeirão Preto, Brazil, 23 out. 2006. CD-ROM.

[2] SERRANO, Milene. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 10](https://aprender3.unb.br/pluginfile.php/2307501/mod_resource/content/1/Aula%2010.pdf). Acesso em: 04 de março de 2022.

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 27/11/2022    | Criação da versão inicial do documento   | Maurício Machado    | Nicolas Souza  |
