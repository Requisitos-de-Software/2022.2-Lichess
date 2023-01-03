# Backlog do Produto

## Introdução

O backlog é uma lista com prioridades dos requisitos ou funcionalidades do projeto que fornecem valor comercial ao cliente. Os itens podem ser adicionados ao backlog a qualquer momento do projeto. Os requisitos são descritos em diferentes níveis de abstração, a saber: [histórias de usuário](us.md), épicos e temas, sendo os temas as formas mais abstratas e as histórias de usuário as menos abstratas.

## Metodologia

A elaboração do backlog do produto partiu da análise e verificação dos requisitos funcionais elicitados, seguida pelo agrupamento destes requisitos em temas e épicos, que foram a base para a criação das [histórias de usuário](us.md).

## Requisitos Elicitados

Na Tabela 1 estão registrados todos os requisitos elicitados durante o processo de [elicitação](../../elicitacao/tecnicas_planejadas.md), juntamente com a origem de cada requisito.

| Identificador | Requisito | Rastreabilidade |
| :-: | :-: | :-: |
| RF01 | Deve existir um sistema de recompensas para incentivar os jogadores | [Q04](../../elicitacao/questionario.md) |
| RF02 | Deve existir uma apresentação inicial do aplicativo para o usuário no primeiro acesso | [Q10](../../elicitacao/questionario.md) |
| RF03 | Deve haver uma classificação, em termos de nível, dos jogadores. | [Q04](../../elicitacao/questionario.md)<br/> [Q08](../../elicitacao/questionario.md) |
| RF04 | Deve ser possível adicionar outros jogadores | [ST07](../../elicitacao/storytelling.md) |
| RF05 | Deve ser possível aprender movimentos de xadrez por meio de tutoriais | [INT07](../../elicitacao/introspeccao.md)<br/> [Q13](../../elicitacao/questionario.md)<br/> [ST11](../../elicitacao/storytelling.md) |
| RF06 | Deve ser possível assistir partidas de outras pessoas | [ST06](../../elicitacao/storytelling.md) |
| RF07 | Deve ser possível configurar a dificuldade da partida contra o computador | [INT04](../../elicitacao/introspeccao.md) |
| RF08 | Deve ser possível configurar a modalidade de jogo ao iniciar uma partida. | [GLO01](../../elicitacao/glossario.md)<br/> [INT03](../../elicitacao/introspeccao.md)<br/> [ST04](../../elicitacao/storytelling.md) |
| RF09 | Deve ser possível configurar o tempo de duração da partida e incremento ao iniciar uma partida. | [ENT01](../../elicitacao/entrevista.md)<br/> [GLO02](../../elicitacao/glossario.md)<br/> [ST04](../../elicitacao/storytelling.md) |
| RF10 | Deve ser possível configurar um estilo de jogo para o robô, baseado em jogadores famosos, nas partidas contra o computador. | [ENT02](../../elicitacao/entrevista.md)<br/> [ST04](../../elicitacao/storytelling.md) |
| RF11 | Deve ser possível consultar as estatísticas das partidas anteriores | [ST09](../../elicitacao/storytelling.md)<br/> [Q02](../../elicitacao/questionario.md) |
| RF12 | Deve ser possível consultar as regras da modalidade de jogo em andamento. | [GLO03](../../elicitacao/glossario.md) |
| RF13 | Deve ser possível consultar um tutorial de uso do aplicativo | [INT08](../../elicitacao/introspeccao.md) |
| RF14 | Deve ser possível elaborar tutoriais para outros jogadores | [ST13](../../elicitacao/storytelling.md) |
| RF15 | Deve ser possível escolher o nível do oponente ao iniciar uma partida contra outro jogador | [Q08](../../elicitacao/questionario.md)<br/> [Q04](../../elicitacao/questionario.md) |
| RF16 | Deve ser possível jogar partidas não ranqueadas | [ST03](../../elicitacao/storytelling.md) |
| RF17 | Deve ser possível jogar partidas online sem criar uma conta | [Q09](../../elicitacao/questionario.md) |
| RF18 | Deve ser possível jogar uma partida de xadrez contra o computador | [INT01](../../elicitacao/introspeccao.md) |
| RF19 | Deve ser possível jogar uma partida de xadrez contra outro jogador aleatório ou escolhido. | [INT02](../../elicitacao/introspeccao.md)<br/> [ST02](../../elicitacao/storytelling.md)<br/> [ST05](../../elicitacao/storytelling.md) |
| RF20 | Deve ser possível pausar uma partida contra o computador | [INT05](../../elicitacao/introspeccao.md) |
| RF21 | Deve ser possível receber notificações sobre torneios ao vivo | [Q03](../../elicitacao/questionario.md) |
| RF22 | Deve ser possível resolver quebra cabeças elaborados por outros jogadores. | [GLO04](../../elicitacao/glossario.md)<br/> [INT12](../../elicitacao/introspeccao.md)<br/> [ST12](../../elicitacao/storytelling.md) |
| RF23 | Deve ser possível resolver tutoriais elaborados por outros jogadores | [ST13](../../elicitacao/storytelling.md) |
| RF24 | Deve ser possível trocar mensagens com outros jogadores | [ST08](../../elicitacao/storytelling.md) |
| RF25 | Deve ser possível visualizar dados sobre os quebra-cabeças concluídos | [Q02](../../elicitacao/questionario.md) |
| RF26 | Deve ser possível visualizar e filtrar o ranqueamento de jogadores | [Q06](../../elicitacao/questionario.md)<br/> [ST10](../../elicitacao/storytelling.md) |
| RF27 | Não deve ser possível pausar uma partida contra outro jogador | [INT06](../../elicitacao/introspeccao.md) |
| RF28 | Deve ser possível criar quebra cabeça para outros jogadores resolverem. | [GLO04](../../elicitacao/glossario.md)<br/> [INT15](../../elicitacao/introspeccao.md) |

<div style="text-align: center">
<p> Tabela 1: Requisitos funcionais elicitados (Fonte: autor, 2023).</p>
</div>

## Backlog

### Temas

Após a etapa de verificação e análise dos requisitos, foi observado que eles poderiam ser organizados em cinco grande temas, que compõem o maior nível de abstração do backlog.

- Partidas
- Tutoriais
- Ranqueamento
- Socialização
- Torneios

Após a definição dos temas, os requisitos foram especificados em um maior nível de abstração, por meio dos épicos. Os épicos são histórias de usuário que ainda podem ser mais especificadas, e foram escritos utilizando o mesmo padrão do utilizado nas histórias de usuário.

### Épicos

Para diminuir o nível de abstração expresso nos temas, foram registrados os épicos, que são histórias de usuário que ainda podem ser mais especificadas. Para facilitar a leitura da tabela de backlog (Tabela 2), os épicos estão especificados a seguir.

#### E01 - Configuração de partida

Eu, como usuário, desejo configurar uma partida antes de iniciá-la para treinar as habilidades específicas.

#### E02 - Partida contra o computador

Eu, como usuário, desejo configurar uma partida contra o computador, para se adequar ao meu estilo de jogo.

#### E03 - Partida contra oponente

Eu, como usuário, desejo configurar uma partida contra outro jogador, para se adequar ao meu estilo de jogo

#### E04 - Partidas casuais

Eu, como usuário, desejo jogar partidas casuais para me divertir.

#### E05 - Manual do usuário

Eu, como usuário, desejo aprender a utilizar o aplicativo, para navegar com mais facilidade.

#### E06 - Estudar xadrez

Eu, como usuário, desejo aprimorar minhas habilidades no xadrez, para me preparar para as partidas.

#### E07 - Ensinar xadrez

Eu, como usuário, desejo ensinar xadrez para outros jogadores, para transmitir o conhecimento.

#### E08 - Estatísticas de partidas

Eu, como usuário, desejo ter acesso a um feedback sobre o meu desempenho nas partidas de xadrez, para me manter motivado.

#### E09 - Estatísticas de quebra cabeças

Eu, como usuário, desejo ter acesso a um feedback sobre o meu desempenho nos quebra cabeças, para me manter motivado.

#### E10 - Comunicação

Eu, como usuário, desejo me comunicar com outros jogadores por meio do aplicativo, para conhecer novas pessoas

#### E11 - Torneios

Eu, como usuário, desejo participar e assistir a torneios, para me manter atualizado sobre as técnicas de xadrez

<table>
    <tr>
        <th style="text-align: center" colspan=6> Backlog do produto </th>
    </tr>
    <tr>
        <td style="text-align: center"> <b> Tema  </b></td>
        <td style="text-align: center"> <b> Épico  </b></td>
        <td style="text-align: center"> <b> História de Usuário (US)  </b></td>
        <td style="text-align: center"> <b> ID </b></td>
        <td style="text-align: center"> <b> Prioridade  </b></td>
        <td style="text-align: center"> <b> Origem  </b></td>
    </tr>
    <tr>
        <!-- Tema  -->
        <td rowspan=9 style="vertical-align: middle"> Partidas </td>
        <!-- Épico -->
        <td rowspan=3 style="vertical-align: middle; text-align: center"> <a href="#e01-configuracao-de-partida">E01</a></td>
        <!-- Histórias de Usuário (3) -->
        <td>Eu, como usuário, desejo configurar o tempo de partida e incremento ao iniciar uma partida para adequar ao meu estilo de jogo.</td>
        <td><a href="../us">US01</a></td>
        <td>Could</td>
        <td><a href=#requisitos-elicitados>RF09</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo configurar a modalidade e dificuldade do jogo ao iniciar uma partida para não me frustrar com a partida.</td>
        <td><a href="../us">US02</a></td>
        <td>Must</td>
        <td><a href=#requisitos-elicitados>RF08<br> RF07<br> RF15</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo escolher jogar contra o computador ou contra um jogador para refletir as minhas necessidades do momento.</td>
        <td><a href="../us">US03</a></td>
        <td>Must</td>
        <td><a href=#requisitos-elicitados>RF18</td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> <a href=#e02-partida-contra-o-computador>E02</a></td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como usuário, desejo poder pausar uma partida contra o computador para poder retomá-la depois.</td>
        <td><a href="../us">US04</a></td>
        <td>Could</td>
        <td><a href=#requisitos-elicitados>RF20</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo configurar um estilo de jogo para o robô, baseado em jogadores famosos, para me preparar para os campeonatos de xadrez.</td>
        <td><a href="../us">US05</a></td>
        <td>Would</td>
        <td><a href=#requisitos-elicitados>RF10</td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> <a href=#e03-partida-contra-oponente>E03</a> </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como usuário, desejo escolher o meu oponente podendo filtrar por por nome e nível, para não me frustrar com a partida.</td>
        <td><a href="../us">US06</a></td>
        <td>Would</td>
        <td><a href=#requisitos-elicitados>RF15<br/> RF19</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo que meu oponente não possa pausar uma partida, para manter o jogo justo.</td>
        <td><a href="../us">US07</a></td>
        <td>Must</td>
        <td><a href=#requisitos-elicitados>RF27</td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> <a href=#e04-partidas-casuais>E04</a> </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como usuário, desejo jogar partidas casuais sem interferir no meu ranqueamento, para não diminuir minha pontuação.</td>
        <td><a href="../us">US08</a></td>
        <td>Could</td>
        <td><a href=#requisitos-elicitados>RF16</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo jogar partidas online sem precisar criar uma conta, para me divertir.</td>
        <td><a href="../us">US09</a></td>
        <td>Must</td>
        <td><a href=#requisitos-elicitados>RF17</td>
    </tr>
    <tr>
        <!-- Tema  -->
        <td rowspan=7 style="vertical-align: middle"> Tutoriais </td>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> <a href=#e05-manual-do-usuario>E05</a> </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como usuário, desejo que um tutorial do aplicativo seja exibido na primeira vez que eu utilizá-lo, para que eu não fique desorientado.</td>
        <td><a href="../us">US10</a></td>
        <td>Could</td>
        <td><a href=#requisitos-elicitados>RF02</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo ter acesso à uma seção de tutorial do aplicativo, para me sentir seguro durante momentos de dúvida.</td>
        <td><a href="../us">US11</a></td>
        <td>Must</td>
        <td><a href=#requisitos-elicitados>RF13</td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=3 style="vertical-align: middle; text-align: center"> <a href=#e06-estudar-xadrez>E06</a> </td>
        <!-- Histórias de Usuário (3) -->
        <td>Eu, como usuário, desejo aprender movimentos de xadrez por meio de tutoriais, para melhorar meu desempenho.</td>
        <td><a href="../us">US12</a></td>
        <td>Must</td>
        <td><a href=#requisitos-elicitados>RF05<br/> RF23</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo aprimorar movimentos de xadrez por meio de quebra cabeças, para me sentir desafiado.</td>
        <td><a href="../us">US13</a></td>
        <td>Could</td>
        <td><a href=#requisitos-elicitados>RF22</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo ter acesso às regras utilizadas na modalidade de xadrez durante a partida, para não me sentir desorientado.</td>
        <td><a href="../us">US14</a></td>
        <td>Could</td>
        <td><a href=#requisitos-elicitados>RF12</td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> <a href=#e07-ensinar-xadrez>E07</a> </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como usuário, desejo cadastrar tutoriais para outros usuários, para auxiliar outras pessoas.</td>
        <td><a href="../us">US15</a></td>
        <td>Would</td>
        <td><a href=#requisitos-elicitados>RF14</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo criar quebra cabeças para outros usuários resolverem, para desafiar outras pessoas.</td>
        <td><a href="../us">US16</a></td>
        <td>Would</td>
        <td><a href=#requisitos-elicitados>RF28</td>
    </tr>
    <tr>
        <!-- Tema  -->
        <td rowspan=4 style="vertical-align: middle"> Ranqueamento </td>
        <!-- Épico -->
        <td rowspan=3 style="vertical-align: middle; text-align: center"> <a href=#e08-estatisticas-de-partidas>E08</a> </td>
        <!-- Histórias de Usuário (3) -->
        <td>Eu, como usuário, desejo participar de um sistema de ranqueamento, para me sentir motivado.</td>
        <td><a href="../us">US17</a></td>
        <td>Could</td>
        <td><a href=#requisitos-elicitados>RF01<br/> RF03</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo consultar as estatísticas das minhas partidas, para me preparar melhor.</td>
        <td><a href="../us">US18</a></td>
        <td>Could</td>
        <td><a href=#requisitos-elicitados>RF11</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo visualizar e filtrar o ranqueamento dos jogadores, para me manter motivado.</td>
        <td><a href="../us">US19</a></td>
        <td>Could</td>
        <td><a href=#requisitos-elicitados>RF26</td>
    </tr>
    <tr>
        <!-- Épico -->
        <td style="vertical-align: middle; text-align: center"> <a href=#e09-estatisticas-de-quebra-cabecas>E09</a>  </td>
        <!-- Histórias de Usuário (1) -->
        <td>Eu, como usuário, desejo consultar as estatísticas dos quebra cabeças resolvidos, para me preparar melhor.</td>
        <td><a href="../us">US20</a></td>
        <td>Would</td>
        <td><a href=#requisitos-elicitados>RF25</td>
    </tr>
    <tr>
        <!-- Tema  -->
        <td rowspan=2 style="vertical-align: middle"> Socialização </td>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> <a href=#e10-comunicacao>E10</a> </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como usuário, desejo adicionar outros jogadores como contatos, para fazer novos amigos.</td>
        <td><a href="../us">US21</a></td>
        <td>Would</td>
        <td><a href=#requisitos-elicitados>RF04</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo trocar mensagens com outros jogadores, para fortalecer minhas amizades.</td>
        <td><a href="../us">US22</a></td>
        <td>Would</td>
        <td><a href=#requisitos-elicitados>RF24</td>
    </tr>
    <tr>
        <!-- Tema  -->
        <td rowspan=2 style="vertical-align: middle"> Torneios </td>
        <!-- Épico -->
        <td rowspan=3 style="vertical-align: middle; text-align: center"> <a href=#e11-torneios>E11</a> </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como usuário, desejo assistir partidas de outros jogadores, para observar as técnicas usadas.</td>
        <td><a href="../us">US23</a></td>
        <td>Must</td>
        <td><a href=#requisitos-elicitados>RF06</td>
    </tr>
    <tr>
        <td>Eu, como usuário, desejo ser notificado quando partidas de outros jogadores iniciarem, para não perder partidas importantes para mim.</td>
        <td><a href="../us">US24</a></td>
        <td>Would</td>
        <td><a href=#requisitos-elicitados>RF21</td>
    </tr>

</table>

<div style="text-align: center">
<p>
Tabela 2: Backlog do produto (Fonte: autor, 2023).
</p>
</div>

## Bibliografia

[1] WIEGERS K., BEATTY J. Software Requirements, 3ª edição.

[2] VAZQUEZ C., SIMÕES G. Engenharia de Requisitos, 1ª edição.

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 03/01/2023    | Criação do documento               | Nicolas Souza |               |
