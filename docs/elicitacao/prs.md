# Priorização

O principal objetivo das técnicas de priorização de requisitos é auxiliar na escolha das funções ou funcionalidade mais essenciais em um sistema em desenvolvimento, definindo estratégias e parâmetros capazes de fornecer um resultado mais apropriado para cada tipo de problema. Essa prática é de relevante importância em um cenário em que as expectativas do cliente são altas, os prazos são curtos e os recursos são limitados.

## 1. MoSCoW

### 1.1 Introdução

O método MoSCoW é uma técnica priorização de requisitos que pode ajudar o time de desenvolvimento no processo de tomada de decisão. Alguns dos objetivos dessa estrutura são:

>1. Identificar o grau de prioridade das tarefas em um projeto.
>2. Alinhar stakeholders sobre o que deve ser feito, de acordo com a ordem de importância dos elementos considerados.

### 1.2 Metodologia

Suas iniciais representam:
- **M**ust-Have
- **S**hould
- **Co**uld-Have
- **W**ould/Want/Won't-Have

#### 1.2.1 Must-Have
Correspondem às tarefas indispensáveis para a realização do projeto e que precisam ser priorizadas. Tudo que for considerado Must-Have é fundamental para o Produto. São iniciativas de alto impacto, que agregam valor ao produto e que, caso não sejam feitas, prejudicam a experiência do cliente. Essas demandas são as mais urgentes, e o time deve concentrar esforços para resolvê-las primeiro. 

#### 1.2.2 Should-Have
Devem ser incluidos aqueles que são importante para a realização do projeto, mas não fundamentais, como as atividades Must-Have.

#### 1.2.3 Could-Have
São menos importantes que requisitos should-have. Agregam valor ao projeto, mas sua ausência não impacta significantemente

#### 1.2.4 Would/Want/Won't-Have
São aqueles que não tem importância significativa para o projeto. A presença ou ausência desses requisitos não tem impacto na conclusão satisfatória do projeto.


## 2. Fist Things First

### 2.1 Introdução
First Things First é uma técnica de priorização em que um levantamento de dados de benefícios, custos e riscos relacionados a cada requisito são levantados. Assim como a técnica MoSCoW, ela é utilizada para criar uma ordem de prioridades dos requisitos a serem implementados.

### 2.2 Metodologia
Para a respectiva técnica de priorização é apresentada, em forma de tabela, os riscos, custos, benefícios e a penalidade relativa de cada requisito elicitado para o projeto, além de equilibrar os posicionamentos do cliente e do desenvolvedor.  

Segue o esquema:

>1. Listar todos os requisitos em uma tabela, retirando aqueles dependentes de outro requisito.
>2. Estimar o benefício relativo que cada recurso fornece ao cliente ou ao negócio de 1 a 9, em que 1 é o menos significativo e 9 o mais significativo.
>3. Estimar a penalidade que o negócio sofreria, se o recurso não fosse incluído, de 1 a 9, em que 1 é o com menor penalidade e 9 maior penalidade.
>4. A Coluna valor total é a soma do (Benefício Relativo * Peso Relativo + Penalidade Relativa * Peso Relativo), o peso relativo utilizado nesse caso foi de 1.
>5. Estimar o custo relativo de implementação de cada requisito, de 1 a 9.
>6. Estimar o grau relativo ao risco a cada requisito de uma escala de 1 a 9.
>7. Calcular a prioridade para cada requisito usando: valor % / (custo % * Peso custo + risco % * Peso Risco). O Peso custo e risco aqui utilizados foram iguais a 1.
>8. Ordenar a lista em ordem decrescente de prioridade.

## 3. Referências

## 4. Histórico de versões

|    Data    | Versão |                  Descrição                        | Autor | Revisor |
| :--------: | :----: | :-----------------------------------------------: | :---: | :-----: |
| 29/11/2022 | `1.0`  | Criação do documento de priorização de requisitos | Renan |   --    |
