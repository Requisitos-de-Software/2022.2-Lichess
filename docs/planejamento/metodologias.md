## 1. Introdução

Nossa equipe utiliza diferentes metodologias, as quais, de certa forma, integram e agilizam nosso processo de desenvolvimento como um todo. Esse documento tem como objetivo informar sobre nossas metodologias em diferentes situações e explicar como nosso time se comunicou e trabalhou durante todo o processo.

## 2. XP (eXtreme Programming)

O método XP é uma metodologia ágil, que pode ser aplicada para otimizar processos e gerar valor ao cliente. Nós escolhemos usar o método XP pois de maneira direta, pois essa metodologia tem como objetivo desenvolver sistemas de qualidade, com um interação mais dinâmica e acessível com o cliente e testagem de ciclos de desenvolvimento rápidos e de maneira constante. Nós adaptamos o modelo ao nosso contexto para que dessa forma pudéssemos aproveitar 100% do processo.

### 2.1  Refatoração

Nossa equipe, de forma dinâmica e constante, busca melhorar e otimizar o projeto, deixando-o mais claro, com menos possibilidade de erros e de duplicação de processos, a partir de revisões e reuniões.

### 2.2 Integração contínua

Nossa equipe está sempre a postos para revisar o quanto antes uma nova tarefa publicada por um dos membros ao longo do desenvolvimento do projeto, para que dessa forma tenhamos um desenvolvimento mais fluido e sem interrupções indesejadas para um processo pleno. Evitando assim, problemas futuros e com a revisão contínua, corrigindo-os quando localizados.

### 2.3 Propriedade coletiva

Com o objetivo de tornar o projeto mais dinâmico e leve para os membros, as nossas atividades são dividas de maneira que tenha ao menos um desenvolvedor e um revisor para evitar envios e conclusões com erros. No processo, de maneira constante, nós debatemos a maioria das decisões em grupo, principalmente quando o tema ou questão é pertinente a todos. Ademais, nas outras atividades consideradas "chave" para o processo de desenvolvimento, nós nos dedicamos na realização a tarefa de maneira coletiva para que possamos assim, ter um pensamento comum e cada membro sinta-se integrado e influente dentro do projeto.

## 3. Proposta de Comunicação

Com o intuito de nos organizarmos e evitar problemas e divergências com as entregas das tarefas, nós nos planejamos em como seria nosso plano de comunicação.

Os membros tem acesso a todas as plataformas disponíveis e essenciais de comunicação e desenvolvimento que nós planejamos utilizar durante o processo de desenvolvimento, são elas: teams, telegram, github e google docs.

As tarefas serão geridas a partir de _issues_ e _pull requests_, de maneira técnica e rápida nos comunicamos a partir de comentários em cada canal.

Os membros da equipe utilizarão também o telegram, o qual é, de certa forma, um meio de comunicação eficiente para troca de informações rápidas e avisos de novas atualizações e mudanças acerca do projeto, bem como também, para tirar dúvidas e esclarecimentos.

## 3.1 Encontros semanais

Além de todos os meios de comunicação por mensagem rápidas e tarefas do git, nós nos reunimos toda semana às terças-feira as 20 horas na plataforma "Teams", para alinharmos nossas questões acerca do projeto e também colocarmos nossas ideias em sincronia com os demais membros da equipe. Ademais, organizamos nosso cronograma e planejamos as tarefas da próxima semana, e se de alguma forma houver alguma tarefa atrasada, colocamos como preferência e como equipe, ajudamos a terminá-la da maneira mais breve possível.

## 4. SCRUM

Afim de assegurar uma quantidade consistente e rápida de entregas, a metodologia ágil SCRUM foi adotada para organização do tempo do time. Foi definido o timebox de uma semana para cada sprint, iniciado e finalizado pelas reuniões semanais nas terças-feiras às 20:00.

As reuniões semanais têm como principais objetivos a realização de um  momento de review (_sprint review_) da sprint finalizada e organização das tarefas da sprint que se inicia (_sprint planning_). A atribuição das tarefas foi feita no início do projeto e encontra-se disponível no [cronograma](/docs/planejamento/cronograma.md), sendo assim, em cada _sprint planning_ será verificado com cada integrante a possibilidade de realizar a entrega à qual ele foi designado.

A organização das tarefas será feita por meio da criação de _issues_ e a revisão dos artefatos será feita durante o _pull request_ referente à cada funcionalidade adicionada. Dessa forma é possível manter uma rastreabilidade das alterações e revisões efetuadas.

## 5. Políticas

### Política de _branches_

As branches devem ser nomeadas de acordo com a _issue_ correspondente, seguindo o seguinte padrão:
`git checkout -b "[tipo]/#issue-descrição`

Onde `tipo` diz respeito ao tipo de _issue_: _feat_ (funcionalidade), _refac_ (refatoração) ou _fix_ (conserto).

> Exemplo:
>
> A branch referente à issue `#3 feature: metodologias` pode ter o nome: `feat/3-metodologias`

### Política de _commits_

As mensagens dos _commits_ devem seguir o padrão:

`git commit -m "#issue descrição`

> Exemplo:
>
> O _commit_ referente a criação do arquivo `metodologias.md` pode ter a mensagem `#3 cria documento de metodologias`

## Referências Bibliográficas

[1] Bourque and R.E. Fairley, eds., Guide to the Software Engineering Body of Knowledge, Version 3.0, IEEE Computer Society, 2014; www.swebok.org.

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 18/11/2022    |  Criação do documento | Davi Silva e Nicolas Souza  | Mauricio |
