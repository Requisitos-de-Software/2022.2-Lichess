# Histórias de Usuário

## Introdução

A especificação dos itens do [backlog](backlog.md) foram feitas em termos de histórias de usuários, que são um registro de requisitos focados em o que são os requisitos e não em como serão implementados. As histórias possuem o seguinte formato: "Eu, como [papel], quero [o que], pelo [motivo]". As histórias de usuário devem ser curtas, detalhadas e específicas.

## Especificação das histórias de usuário

### US01

**ID:** US01

**Descrição:** Eu, como usuário, desejo configurar o tempo de partida e incremento ao iniciar uma partida para adequar ao meu estilo de jogo.

**Tema:** Partidas

**Critérios de Aceitação:**

- Deve ser possível selecionar a duração de cada movimento dentro do intervalo de 15 segundos a 180 minutos.
- Deve ser possível selecionar o incremento de cada movimento dentro do intervalo de 0 segundos a 180 segundos.

### US02

**ID:** US02

**Descrição:** Eu, como usuário, desejo configurar a modalidade e dificuldade do jogo ao iniciar uma partida para não me frustrar com a partida.

**Tema:** Partidas

**Critérios de Aceitação:**

- Deve ser possível selecionar a [modalidade](../lexico.md) de jogo entre as possibilidades abaixo, explicadas no [glossário](../../elicitacao/glossario.md), para partidas contra outro oponente ou contra o computador.
  - _Crazyhouse_
  - _Chess960_
  - _King of the hill_ (Rei da colina)
  - _Three-check_ (Três xeques)
  - _Antichess_ (anti-xadrez)
  - _Atomic_ (Atômico)
  - _Horde_
  - _Racing Kings_ (Corrida de reis)
- Deve ser possível selecionar a dificuldade para partidas contra o computador.
- O aplicativo deve oferecer opções padrão selecionadas: modalidade padrão e dificuldade de acordo com o nível em que o usuário se encontra.
- Deve ser possível selecionar o nível do oponente para partidas contra o computador.

### US03

**ID:** US03

**Descrição:** Eu, como usuário, desejo escolher jogar contra o computador ou contra um jogador para refletir as minhas necessidades do momento.

**Tema:** Partidas

**Critérios de Aceitação:**

- Deve ser possível escolher o oponente por nome de usuário.
- Deve ser possível jogar contra um oponente aleatório.

### US04

**ID:** US04

**Descrição:** Eu, como usuário, desejo poder pausar uma partida contra o computador para poder retomá-la depois.

**Tema:** Partidas

**Critérios de Aceitação:**

- Deve ser possível pausar a partida, parando os contadores de tempo e saindo da tela de jogo.
- Não deve ser possível visualizar a tela de jogo durante a pausa.

### US05

**ID:** US05

**Descrição:** Eu, como usuário, desejo configurar um estilo de jogo para o robô, baseado em jogadores famosos, para me preparar para os campeonatos de xadrez.

**Tema:** Partidas

**Critérios de Aceitação:**

- Deve ser possível configurar um estilo de jogo em partidas contra o robô com base em estilos de um conjunto de jogadores famosos.

### US06

**ID:** US06

**Descrição:** Eu, como usuário, desejo escolher o meu oponente podendo filtrar por por nome e nível, para não me frustrar com a partida.

**Tema:** Partidas

**Critérios de Aceitação:**

- Deve ser possível escolher o oponente a partir de uma lista de oponentes online dentro de um filtro de nível.
- Deve ser possível escolher o oponente a partir de uma lista de oponentes online dentro de um filtro de nome.

### US07

**ID:** US07

**Descrição:** Eu, como usuário, desejo que meu oponente não possa pausar uma partida, para manter o jogo justo.

**Tema:** Partidas

**Critérios de Aceitação:**

- Não deve ser possível pausar partidas contra outros oponentes.
- O aplicativo deve sinalizar vencimento por WO caso um oponente feche o aplicativo ou bloqueie a tela do celular.

### US08

**ID:** US08

**Descrição:** Eu, como usuário, desejo jogar partidas casuais sem interferir no meu ranqueamento, para não diminuir minha pontuação.

**Tema:** Partidas

**Critérios de Aceitação:**

- Deve ser possível jogar uma partida casual contra outro usuário sem interferência no ranqueamento.
- Deve ser possível jogar uma partida casual contra o computador sem interferência no ranqueamento.

### US09

**ID:** US09

**Descrição:** Eu, como usuário, desejo jogar partidas online sem precisar criar uma conta, para me divertir.

**Tema:** Partidas

**Critérios de Aceitação:**

- Deve ser possível jogar contra o computador sem criar uma conta.
- Deve ser possível jogar contra outro usuário sem criar uma conta.
- Não deve ser possível jogar partidas ranqueadas sem criar uma conta.

### US10

**ID:** US10

**Descrição:** Eu, como usuário, desejo que um tutorial do aplicativo seja exibido na primeira vez que eu utilizá-lo, para que eu não fique desorientado.

**Tema:** Tutoriais

**Critérios de Aceitação:**

- Deve ser exibido um tutorial na tela inicial do aplicativo ensinando o usuário a configurar uma partida.
- Deve ser apresentada a opção do usuário iniciar um tutorial de xadrez após o tutorial inicial.
- O tutorial exibido deve possuir a opção "pular", caso o usuário não queira vê-lo.

### US11

**ID:** US11

**Descrição:** Eu, como usuário, desejo ter acesso à uma seção de tutorial do aplicativo, para me sentir seguro durante momentos de dúvida.

**Tema:** Tutoriais

**Critérios de Aceitação:**

- Deve existir na aplicação uma seção de ajuda.
- A seção de ajuda deve conter um manual de acesso para cada funcionalidade.
- A seção de ajuda deve conter um espaço destinado às perguntas frequentes (FAC).

### US12

**ID:** US12

**Descrição:** Eu, como usuário, desejo aprender movimentos de xadrez por meio de tutoriais, para melhorar meu desempenho.

**Tema:** Tutoriais

**Critérios de Aceitação:**

- Deve existir na aplicação uma seção de tutoriais separados por nível: iniciante, fácil, médio, intermediário e avançado.
- Os tutoriais devem possuir explicações teóricas e atividades práticas para o usuário.

### US13

**ID:** US13

**Descrição:** Eu, como usuário, desejo aprimorar movimentos de xadrez por meio de [quebra cabeças](../../elicitacao/glossario.md), para me sentir desafiado.

**Tema:** Tutoriais

**Critérios de Aceitação:**

- Deve existir na aplicação uma seção de quebra cabeças separados por nível: iniciante, fácil, médio, intermediário e avançado.
- O usuário deve ter acesso à solução do quebra cabeça caso deseje, após tentar resolvê-lo pelo menos uma vez.
- O quebra cabeça deve conter uma seção de comentários.

### US14

**ID:** US14

**Descrição:** Eu, como usuário, desejo ter acesso às regras utilizadas na modalidade de xadrez durante a partida, para não me sentir desorientado.

**Tema:** Tutoriais

**Critérios de Aceitação:**

- Deve ser possível acessar uma aba de ajuda durante a partida para consultar as regras da modalidade.
- O acesso à ajuda pode pausar o jogo contra o computador.
- O acesso à ajuda não pode pausar o jogo contra outro usuário.

### US15

**ID:** US15

**Descrição:** Eu, como usuário, desejo cadastrar tutoriais para outros usuários, para auxiliar outras pessoas.

**Tema:** Tutoriais

**Critérios de Aceitação:**

- Deve ser possível criar um tutorial para outros usuários.
- O tutorial criado deve ser validado por um usuário de nível avançado antes de ser divulgado.

### US16

**ID:** US16

**Descrição:** Eu, como usuário, desejo criar quebra cabeças para outros usuários resolverem, para desafiar outras pessoas.

**Tema:** Tutoriais

**Critérios de Aceitação:**

- Deve ser possível criar um [quebra cabeça](../../elicitacao/glossario.md) para outros usuários.
- O quebra cabeça criado deve ser validado por um usuário de nível avançado antes de ser divulgado.

### US17

**ID:** US17

**Descrição:** Eu, como usuário, desejo participar de um sistema de ranqueamento, para me sentir motivado.

**Tema:** Ranqueamento

**Critérios de Aceitação:**

- As partidas ranqueadas devem adicionar pontos ao usuário, de acordo com a dificuldade e modalidade.
- Partidas mais difíceis devem valer mais pontos.
- A quantidade de pontos para avançar para o próximo nível deve aumentar proporcionalmente à medida que os níveis progridem.

### US18

**ID:** US18

**Descrição:** Eu, como usuário, desejo consultar as estatísticas das minhas partidas, para me preparar melhor.

**Tema:** Ranqueamento

**Critérios de Aceitação:**

- Deve ser possível ver o tempo de duração dos quebra cabeças resolvidos.
- Deve ser possível ver o usuário do oponente nos quebra cabeças resolvidos.
- Deve ser possível ver a pontuação recebida pelos quebra cabeças resolvidos.
- Deve ser possível ver as modalidades dos quebra cabeças resolvidos.
- Deve ser possível visualizar o percentual de vitórias e derrotas nas últimas partidas.
- Deve ser possível filtrar a visualização por período de tempo.
- Deve ser possível filtrar a visualização por modalidade de jogo.
- Deve ser possível filtrar a visualização por tipo de oponente.

### US19

**ID:** US19

**Descrição:** Eu, como usuário, desejo visualizar e filtrar o ranqueamento dos jogadores, para me manter motivado.

**Tema:** Ranqueamento

**Critérios de Aceitação:**

- Deve ser possível visualizar a pontuação geral dos usuários.
- Deve ser possível filtrar a exibição por nome de usuário.
- Deve ser possível filtrar a exibição por localização (cidade, estado, país) do usuário.
- Deve ser possível filtrar a exibição por modalidade de jogo.

### US20

**ID:** US20

**Descrição:** Eu, como usuário, desejo consultar as estatísticas dos quebra cabeças resolvidos, para me preparar melhor.

**Tema:** Ranqueamento

**Critérios de Aceitação:**

- Deve ser possível ver o tempo de duração dos quebra cabeças resolvidos.
- Deve ser possível filtrar a visualização por período de tempo.
- Deve ser possível filtrar a visualização por nível de dificuldade.

### US21

**ID:** US21

**Descrição:** Eu, como usuário, desejo adicionar outros jogadores como contatos, para fazer novos amigos.

**Tema:** Socialização

**Critérios de Aceitação:**

- Deve ser possível criar um nome de usuário personalizado.
- O nome de usuário deve ser único.
- Deve ser possível encontrar contatos por email ou nome de usuário.
- Deve ser possível adicionar usuários como amigo.
- Um usuário deve ter a possibilidade de negar que outro usuário o adicione como amigo.

### US22

**ID:** US22

**Descrição:** Eu, como usuário, desejo trocar mensagens com outros jogadores, para fortalecer minhas amizades.

**Tema:** Socialização

**Critérios de Aceitação:**

- Deve ser possível enviar mensagens para usuários.
- Deve ser possível bloquear o recebimento de mensagens.
- Deve ser possível filtrar o recebimento de mensagens.

### US23

**ID:** US23

**Descrição:** Eu, como usuário, desejo assistir partidas de outros jogadores, para observar as técnicas usadas.

**Tema:** Torneios

**Critérios de Aceitação:**

- Cada partida deve possuir um código único.
- Deve ser possível assistir uma partida a partir do código dela.
- Deve ser possível assistir uma partida aleatória.
- Deve ser possível visualizar as partidas em andamento.
- Deve ser possível filtrar a visualização das partidas em andamento por modalidade, nível dos jogadores e localização.

### US24

**ID:** US24

**Descrição:** Eu, como usuário, desejo ser notificado quando partidas de outros jogadores iniciarem, para não perder partidas importantes para mim.

**Tema:** Torneios

**Critérios de Aceitação:**

- Deve ser possível habilitar notificações push e/ou por email para partidas de um usuário específico.

## Bibliografia

[1] WIEGERS K., BEATTY J. Software Requirements, 3ª edição.

[2] VAZQUEZ C., SIMÕES G. Engenharia de Requisitos, 1ª edição.

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 03/01/2023    | Criação do documento.              | Nicolas Souza | Lucas Macedo |
