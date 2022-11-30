# Glossário

## Introdução

O glossário é, simultaneamente, um processo e um produto. Esse instrumento identifica e define palavras presentes no domínio do problema, e durante o processo de sua construção é possível elicitar requisitos. A escolha dessa metodologia de elicitação deve-se ao vocabulário específico de xadrez utilizado no aplicativo Lichess.

De acordo com Vazquez [1], para identificar os termos candidatos ao glossário, deve prestar-se atenção a termos:

- Únicos para o domínio;
- Com mais de uma definição;
- Com definição distinta do senso comum;
- Com definições não intuitivas;
- Técnicos do negócio;
- Abreviações e siglas;
- Sinônimos e antônimos.

## Glossário

Para uma maior compreensão do aplicativo, foram elencados termos relativos ao domínio do xadrez e as suas definições, representados na Tabela 1. A maioria dos termos possui nomenclatura em inglês, e para os que possuem tradução, esta encontra-se representada entre parênteses.

| Termo | Definição |
| :-: | - |
| Xeque | O ataque a um rei no é chamado de xeque |
| Xeque-mate | Um xeque mate é um xeque no qual o rei atacado não pode escapar do ataque com lances legais|
| Incremento | Quantos segundos são adicionados ao relógio para cada lance jogado. |
| Modalidade | Alteração nas regras convencionais do xadrez geram uma nova modalidade. |
| _Bullet_ <br/> (relâmpago) | Modalidade de xadrez na qual o jogador deve realizar cada jogada em no máximo 1 minuto. |
| _Blitz_ | Modalidade de xadrez na qual todos os lances devem ser completados num tempo fixo de 10 minutos ou menos para cada jogador. |
| _Rapid_ <br/>(rápido) | Modalidade de xadrez em que todos os lances devem ser completos em um tempo fixo de mais de 10 minutos, mas inferior a 60 minutos para cada jogador. |
| _Classical_ <br/>(clássico) | Modalidade clássica de xadrez com tempos mais longos, variáveis de acordo com o torneio. |
| Quebra cabeça | Um tabuleiro é apresentado ao jogador, com posições pré-definidas, e a partir disso ele deve atingir um objetivo, como por exemplo chegar à um xeque-mate em duas jogadas. |
| _Ultrabullet_ | Modalidade de xadrez em que os lances devem ser completados em um tempo menor do que na modalidade bullet. |
| Correspondência | Modalidade em que o jogador manda as coordenadas da jogada para um correspondente, que então responde com a jogada e o jogo segue dessa modalidade por meio de cartas ou mensagens. |
| _Crazyhouse_ | Modalidade onde as peças capturadas por um jogador podem ser usadas a sua disposição durante a partida. |
| _Chess960_ | Modalidade onde as peças da segunda fileira dos jogadores são colocadas em posições aleatórias, seguindo algumas restrições. |
| _King of the hill_ <br/>(Rei da colina) | Modalidade que segue as regras convencionais com um adendo: o primeiro jogador que mover seu rei, de forma legal, até um dos quatro quadrados centrais do tabuleiro vence. |
| _Three-check_ <br/>(Três xeques) | Modalidade na qual o jogador vence se efetuar três xeques contra o adversário.  |
| _Antichess_ <br/>(anti-xadrez) | Modalidade onde vence o jogador que tiver todas as peças capturadas. |
| _Atomic_ <br/>(Atômico) | Modalidade na qual a captura de uma peça causa uma "explosão" que atinge todas as casas imediatamente ao redor da peça capturada, matando todas as peças atingidas, exceto os peões. |
| _Horde_ | Modalidade de xadrez onde o jogador com as peças pretas possui um conjunto convencional de peças, mas o jogador com peças brancas possui apenas peões, 36 exatamente. |
| _Racing Kings_ <br/>(Corrida de reis) | Modalidade na qual o objetivo não é capturar o rei do adversário, mas apostar uma corrida até o lado oposto do tabuleiro. Nessa modalidade as peças pretas e brancas iniciam do mesmo lado do tabuleiro. |

<div style="text-align: center">
<p> Tabela 1: Glossário dos termos de xadrez (Fonte: autor, 2022).</p>
</div>

## Requisitos Elicitados

Após um estudo sobre os conceitos relativos ao domínio do xadrez, foi possível elicitar os requisitos representados na Tabela 2. O identificador de cada requisito é formado por GLO + um número, sendo GLO uma abreviação de glossário, e o tipo de requisito refere-se à classificação entre requisitos funcionais (RF) e não funcionais (RNF).

| Identificador | Requisito | Tipo |
| :---: | - | :-: |
| GLO01 | Deve ser possível personalizar a modalidade de jogo                      | RF  |
| GLO02 | Deve ser possível personalizar o incremento das partidas                 | RF  |
| GLO03 | Deve ser possível consultar as regras da modalidade de jogo em andamento | RF  |
| GLO04 | Deve ser possível solucionar quebra cabeças                              | RF  |
<div style="text-align: center">
<p> Tabela 2: Requisitos elicitados a partir do Glossário (Fonte: autor, 2022).</p>
</div>

## Bibliografia

[1] VAZQUEZ C., SIMÕES G. Engenharia de Requisitos, 1ª edição.

[2] Termos do xadrez, plataforma [chess.com](https://chess.com), disponível no [link](https://www.chess.com/pt-BR/terms/), acesso em novembro de 2022.

[3] Como jogar xadrez, disponível no [link](https://comojogarxadrez.com.br/), acesso em novembro de 2022.

[4] Xadrez forte, disponível no [link](https://www.xadrezforte.com.br), acesso em novembro de 2022.

## Histórico de Versão

| Versão | Data       | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ---------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 27/11/2022 | Criação do documento.              | Nicolas Souza |       Mauricio Machado        |
