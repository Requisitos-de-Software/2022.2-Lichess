# Introspecção

## Introdução

O presente documento apresenta os requisitos elicitados por meio da técnica de introspecção. De acordo com o dicionário Michaelis de Língua Portuguesa [1], a palavra **introspecção** possui dois significados, descritos abaixo, que são as premissas da técnica de elicitação por meio da introspecção.

> 1. Observação e descrição por determinada pessoa de suas experiências e seus padrões de comportamento.
> 2. `Psicologia` Método de observação e descrição objetiva dos fatos psíquicos e do conteúdo da consciência do próprio observador em termos de seus elementos e atributos. O objetivo da elicitação de requisitos por meio da introspecção é elencar os principais requisitos do sistema a partir do ponto de vista dos participantes da sessão de introspecção. A elicitação foi feita pelo membro Nicolas Souza. Essa técnica foi escolhida

## Elicitação de requisitos

A elicitação de requisitos por meio da introspecção consiste em entender as propriedades fundamentais para o sucesso de um sistema, durante essa técnica o Engenheiro de Requisitos explora os cenários de realização de tarefas dentro do sistema e elenca as funcionalidades desejadas nesses cenários. Os resultados obtidos para o aplicativo Lichess estão registrados na Tabela 1, que apresenta os cenários de utilização do sistema e o comportamento esperado, avaliados por meio da introspecção, pelo estudante Nicolas Souza.

| Cenário de uso | Observações |
| -: | :- |
| **Abertura do aplicativo** | A tela inicial deve apresentar as modalidades de jogo de xadrez disponíveis: partida individual contra o computador, partida contra outro jogador e treino de movimentos. |
| **Partida individual** | Ao iniciar uma partida individual deve ser possível escolher o modelo de partida e pausá-la caso seja necessário parar de usar o aplicativo. |
| **Partida contra outro jogador** | Deve ser possível escolher o modelo de partida, mas não deve ser possível pausar a partida. |
| **Treino de movimentos** | Deve ser possível aprender jogadas de forma didática, com um passo a passo detalhado e explicação sobre as peças. Deve haver tutoriais disponíveis para diferentes níveis de familiaridade com o xadrez. |
| **Usabilidade** | O tempo de resposta do aplicativo deve ser rápido (no máximo 1 segundo) [3], o status da partida deve estar visível ao usuário,

<div style="text-align: center">
<p> Tabela 1: Registro da introspecção (Fonte: autor, 2022).</p>
</div>

A partir das observações representadas na Tabela 1, foram elicitados os requisitos da sessão de introspecção, representados na Tabela 2. O identificador de cada requisito é formado por INT + um número, sendo INT uma abreviação de introspecção, e o tipo de requisito refere-se a classificação entre requisitos funcionais (RF) e não funcionais (RNF).

| Identificador | Requisito | Tipo |
| :-: | - | :-: |
| INT01 | Deve ser possível jogar uma partida de xadrez contra o computador          | RF  |
| INT02 | Deve ser possível jogar uma partida de xadrez contra outro jogador         | RF  |
| INT03 | Deve ser possível configurar o modelo de jogo contra outro jogador         | RF  |
| INT04 | Deve ser possível configurar a dificuldade da partida contra o computador  | RF  |
| INT05 | Deve ser possível pausar uma partida contra o computador                   | RF  |
| INT06 | Partidas contra outros jogadores devem seguir sem interrupções e pausas    | RF  |
| INT07 | Deve ser possível aprender movimentos de xadrez                            | RF  |
| INT08 | O aplicativo deve fornecer um tutorial de uso do sistema                   | RF  |
| INT09 | Deve ser possível acessar os modelos de partida a partir da tela inicial   | RNF |
| INT10 | O tempo de resposta das requisições ao aplicativo deve ser menor ou igual a 1 segundo | RNF |
| INT11 | Deve ser possível ver quando o outro jogador está pensando na jogada dele  | RNF |
<div style="text-align: center">
<p> Tabela 2: Requisitos elicitados (Fonte: autor, 2022).</p>
</div>

## Bibliografia

[1] Dicionário Michaelis de Língua Portuguesa, disponível no [link](https://michaelis.uol.com.br/moderno-portugues/busca/portugues-brasileiro/), acesso em novembro de 2022.

[2] SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 2º/2022. 50 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

[3] Response Times: The 3 Important Limits, disponível no [link](https://www.nngroup.com/articles/response-times-3-important-limits/), acesso em novembro de 2022.

## Histórico de Versão

| Versão | Data       | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ---------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 27/11/2022 | Criação do documento.              | Nicolas Souza |  Lucas Macedo |
