# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

As personas levantadas durante o processo de entendimento do problema são apresentadas a seguir:

`Lucas Vieira` é um advogado trabalhista com 5 anos de experiência, atuando em processos judiciais, promovendo defesas de empresas e de clientes em ações trabalhistas. Armando tem grande dificuldade de organizar suas finanças pois ele atende muitos clientes simultaneamente e com varios clientes que necessitam ser cobrados em datas especificas, com este situação ele esta acabando se atrapalhando em fazer as cobraças e administrar suas contas em geral(despesas, ganhos).

`Mateus Rodrigues` é um jovem de 22 anos, recentemente formado como Desenvolvedor e Analista de Sistemas, trabalhando como Desenvolvedor Web Front-End na HP Brasil. Demonstra ter um problema grave de disciplina e organização quando o assunto é Finanças, não tendo controle nenhum sobre seus gastos, fazendo com que ele não consiga criar suas reservas financeiras para seu próprio futuro e para ajudar sua família.

`Daniel Lima` tem 25 anos e está cursando Economia na UFMG. Tem um filho de 5 anos do último relacionamento e paga pensão para a criança. Faz estágio remunerado na área de formação, com rendimento em torno de R$1.572,00. Apesar de estar cursando Economia, não tem conseguido gerir bem as suas finanças para conseguir pagar as suas despesas sem se endividar com empréstimos e cartões de crédito.

`Fernando Andrade` tem 43 anos, mora no interior de Minas Gerais, é criador de gado e tem um casal de filhos gêmeos que entraram recentemente em uma faculdade particular do Rio de Janeiro. Pelo alto valor das mensalidades dos cursos, os gastos mensais do mesmo aumentaram consideravelmente, e por isso ele está com problemas em se organizar financeiramente.No seu tempo livre, gosta de participar de competições de tiro ao alvo.

`Helena Gonçalves` tem 29 anos, estudante universitária, tem dois gatos, namora, mora sozinha, sua renda é de aproximadamente R$5000,00. Nas horas vagas adora assistir séries e uma ou duas vezes por mês se reunir com os amigos. Como mora sozinha e tem muitas contas a serem pagas, fica perdida no que foi pago e no que é preciso pagar, já tentou planilha, anotar em papel mas sempre perde a paciencia de ter que preencher mês a mês.

`Ricardo Machado` tem 39 anos, agricultor, trabalhador do campo, uma pessoa que vive da terra e seus plantios. Tem dificuldades para gerir suas finanças e vive recorrendo a empréstimos para sanar suas despesas e poder manter suas contas em dia. Não tem reservas e tem grandes problemas em suas lavouras devido ao fato de não ter capital de giro para subsidiar seu manejo.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`  |
|--------------------|------------------------------------|-------------------|
| Lucas Vieira | Conseguir preencher uma descrição para cada transação realizada | Para saber qual foi o motivo da transação em questão |
| Lucas Vieira | Administrar meus lançamentos | Gerir de forma direta todas as movimentações financeiras realizadas                     |
| Matheus Rodrigues | Acompanhar o saldo total a minha receita  | Saber o valor que ainda tenho disponível em tempo real              |
| Daniel Lima | Receber um aviso quando meus gastos atingirem alta porcentagem em relação à minha receita | Controlar melhor minha despesas                          |
| Fernando Andrade           | Visualizar de forma geral meus gastos x despesas | Acompanhar meu fluxo de transações        |
| Fernando Andrade            | Acessar de forma rápida minhas receitas bancárias em apenas um lugar | Ter maior controle da minha quantida total disponível todas as minhas contas bancárias                            |
| Helena Gonçalves           | Cadastras minhas contas fixas mensais com as respectivas datas de vencimento  | Evitar a cobrança de juros gerada por falta de pagamento na data correta         |
| Ricardo Machado                | Visualizar de forma fácil e evidente meus lançamentos efetivados e/ou pendentes | Ter maior controle da conta que  que já está paga e da que ainda está em aberto        |
| Ricardo Machado            | Ter a opção de exibir ou não o valor total da receita | Ter mais privacidade sobre meus dados financeiros ao abrir o aplicativo            | 

## Modelagem do Processo de Negócio 

### Análise da Situação Atual

Apresente aqui os problemas existentes que viabilizam sua proposta. Apresente o modelo do sistema como ele funciona hoje. Caso sua proposta seja inovadora e não existam processos claramente definidos, apresente como as tarefas que o seu sistema pretende implementar são executadas atualmente, mesmo que não se utilize tecnologia computacional. 

### Descrição Geral da Proposta

Apresente aqui uma descrição da sua proposta abordando seus limites e suas ligações com as estratégias e objetivos do negócio. Apresente aqui as oportunidades de melhorias.

### Processo 1 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 1. Em seguida, apresente o modelo do processo 1, descrito no padrão BPMN. 

![Processo 1](img/02-bpmn-proc1.png)

### Processo 2 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 2. Em seguida, apresente o modelo do processo 2, descrito no padrão BPMN.

![Processo 2](img/02-bpmn-proc2.png)

## Indicadores de Desempenho

Apresente aqui os principais indicadores de desempenho e algumas metas para o processo. Atenção: as informações necessárias para gerar os indicadores devem estar contempladas no diagrama de classe. Colocar no mínimo 5 indicadores. 

Usar o seguinte modelo: 

![Indicadores de Desempenho](img/02-indic-desemp.png)
Obs.: todas as informações para gerar os indicadores devem estar no diagrama de classe a ser apresentado a posteriori. 

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |

Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)

# Matriz de Rastreabilidade

A matriz de rastreabilidade é uma ferramenta usada para facilitar a visualização dos relacionamento entre requisitos e outros artefatos ou objetos, permitindo a rastreabilidade entre os requisitos e os objetivos de negócio. 

A matriz deve contemplar todos os elementos relevantes que fazem parte do sistema, conforme a figura meramente ilustrativa apresentada a seguir.

![Exemplo de matriz de rastreabilidade](img/02-matriz-rastreabilidade.png)

> **Links Úteis**:
> - [Artigo Engenharia de Software 13 - Rastreabilidade](https://www.devmedia.com.br/artigo-engenharia-de-software-13-rastreabilidade/12822/)
> - [Verificação da rastreabilidade de requisitos usando a integração do IBM Rational RequisitePro e do IBM ClearQuest Test Manager](https://developer.ibm.com/br/tutorials/requirementstraceabilityverificationusingrrpandcctm/)
> - [IBM Engineering Lifecycle Optimization – Publishing](https://www.ibm.com/br-pt/products/engineering-lifecycle-optimization/publishing/)

<hr>

# Gerenciamento de Projeto

A gestão assertiva de um projeto, é parte fundamental para que este alcance resultados positivos ao seu final. Gerenciar um projeto é deter de controle de áreas que são cruciais para estes resultados, tais como: escopo, custos, tempo, qualidade e custos, pois, qualquer alteração em uma dessas áreas, dificilmente não impactará as demais.

Quanto maior for o controle do gestor dos elementos que compõe um projeto, maiores serão suas chances de alcançar os objetivos propostos, vista que, o controle trará respostas mais imediatas aos riscos identificados reduzindo a incidência de problemas. 



## Gerenciamento de Tempo

Todo objetivo é constituído por uma meta que se pretende alcançar, e para tanto, é de extrema importância que se definia quando este evento deve ocorrer, sem que haja um deadline para o alcance de uma meta, esta nunca será de fato alcançado, pois, nunca será priorizada em face do seu limite de tempo para finalização.

https://github.com/orgs/ICEI-PUC-Minas-PMV-ADS/projects/455/views/1

#### As atividades e sua execução, serão acompanhadas através de um kanban contendo todoas as tarefas e seus prazos de início e finalização para uma melhor rastreabilidade da execução
https://github.com/thaisoliveira1356480/template/projects?query=is%3Aopen


## Gerenciamento de Equipe

Projetos entregam resultados, resultados são providos por pessoas, essa relação é algo imutável, pois, é impossível a não incidência de stakeholders no projeto, seja eles diretos ou indiretos. 

Se é necessário ter um assertivo controle no gerenciamento de um projeto para que se obtenha bons resultados ao seu final, o que podemos dizer de uma boa gestão da equipe? Uma equipe de sucesso é composta por profissionais que estão direcionados a obtenção do mesmo objetivo, trabalham focados, envolvendo-se o máximo possível para que ao final, o projeto logre o êxito planejado.

### Descrição da Equipe: 

| # | Função | Nome | 
|-------|---------------------|----|
| 1 | Desenvolvedor Pleno | Leonardo Buck |
| 2 | Desenvolvedor Pleno | Leonardo Lima |
| 3 | Desenvolvedor Sênior | Joe Monteiro de Sousa |
| 4 | Analista de Teste | Thiago Gomes da Silva |
| 5 | Gerente de Projeto | Thaís Cristine Santana Oliveira

### Papéis e responsabilidades

 - <b>Desenvolvedores:</b> executar o escopo elicitado e alvo da solução do projeto. Caberá aos desenvolvedores, as tarefas de criar e corrigir todo o código necessário para que a aplicação proposta funcione corretamente na utilização dos usuários

 - <b>Analista de Teste:</b> realizar todos os testes necessários que atestem a qualidade do código desenvolvido, identificar bugs que devem ser corrigidos e respaldar a solução de possíveis problemas pós a sua entrega

 - <b>Gerente do Projeto:</b> ser o facilitador da equipe, de modo a que todos os impedimentos, problemas e riscos, possam ser mitigados não impactando a qualidade dos entregáveis conforme os requisitos elicitados. 



## Gestão de Orçamento
Projeto tem estimativa de ser realizado durante 5 meses, onde abaixo, temos o descritivo do custo planejado para a execução do projeto contemplando todos os itens necessários para este desenvolvimento.

![image](https://github.com/thaisoliveira1356480/template/assets/110863413/2a2d9fcc-ed57-44c5-95d2-6599a868d75e)
