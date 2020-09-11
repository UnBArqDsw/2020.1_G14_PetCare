# Metodologia
### Histórico de revisão
Data | Versão | Descrição | Autor |
--------- | ------ | ------------ | --------- |
11/09/2020 | 0.1 | Criação do documento | Ricardo Lima Canela, Fernando Aguilar  |

## Introdução

Nesse documento será apresentado a Metodologia de Desenvolvimento de Software a ser utilizado ao longo do projeto PetCare. Trata-se de uma seleção de métodos, processos e práticas pertencentes a metodologias como Scrum, XP, RUP e Kanban a fim de gerar uma metodologia que se adeque ao projeto.

## Metodologia

Serão reunidos diversos elementos de diferentes metodologias para a construção de um processo a ser seguido pela equipe para o desenvolvimento do projeto. As metodologias a serem utilizadas são:

- Scrum:
Metodologia ágil para gestão e planejamento de projetos.

- RUP (Rational Unified Process):
Conjunto de processos desenvolvido pela IBM com papéis e artefatos bem definidos que são separados em Fases e Disciplinas. Tem como ponto forte a garantia de uma produção de software de alta qualidade que cumpra um cronograma e um orçamento previsíveis por meio de iterações incrementais.

- XP (Extreme Programming):
Metodologia de desenvolvimento de software com conjuntos de valores, princípios e práticas que diferem da forma tradicional de se desenvolver software.

- Kanban:
Metodologia ágil e visual que contribui para o controle de produção e gestão de tarefas através de um quadro de atividades e seus status de desenvolvimento.

## Metodologias de desenvolvimento v1:

#### Scrum:
- Product Backlog: É onde se armazena todas as Histórias de Usuário contendo as funcionalidades desejadas para o sistema que servirão de entrada para cada Sprint Backlog

- Sprint Backlog: É a seleção de Histórias de Usuário que serão desenvolvidas na Sprint em andamento. A seleção é feita durante a Sprint Plannig avaliando as pendências da ultima Sprint e as prioridades do Product Backlog

- Sprint Plannig: É a reunião realizada no início de cada Sprint para o planejar as atividades a serem realizadas ao longo da Sprint.

- Sprint: Representa um período de tempo em que as atividades devem ser executadas. Utilizaremos o perído de tempo de uma semana com início da Sprint na segunda-feira e o fim da sprint no domingo.

- Daily Scrum: É uma reunião diária realizada pela equipe durante a Sprint que deve ser rápida, com um tempo de aproximadamente 15 minutos, onde cada membro diz o que fez ontem, o que fará hoje e se possui algum impedimento. Nós adaptaremos para realizar a Daily 3 vezes na semana (segunda, quarta e sexta) ao meio-dia em ponto.

- Sprint Review: É a reunião onde se apresenta as funcionalidades implementadas durante a Sprint. Essa reunião é realizada no ultimo dia da Sprint e é evidênciado o que foi entregue, se está feito corretamente e quais foram as dividas técnicas para a próxima Sprint.

- Sprint Retrospective: Reunião que ocorre ao final de cada Sprint para identificar pontos positivo e pontos a melhorar e as ações a serem tomadas.


#### RUP (Rational Unified Process)
- Práticas:
- Desenvolvimento iterativo: Realizar desenvolvimento iterativo promove um entendimento melhor do problema e do produto a ser criado conforme são realizadas pequenas entregas e validações. Ao longo das iterações são realizados ajustes nos requisitos e no desenvolvimento garantindo uma construção gradativa e com qualidade.

- Verificação da qualidade de software: A qualidade do sistema deve ser aferida com respeito aos requisitos com base na confiabilidade, funcionalidade e desempenho. A aplicação será constantemente vericada para atender os padrões de qualidade definidos pela equipe e usuários, sendo essas verificações por meio de testes manuais e automatizados.


#### XP (Extreme Programming):
- Valores:
- Comunicação: Todos os envolvidos no projeto devem possuir uma forma clara e bem definida de contactar outros envolvidos. Os canais de comunicação do time serão Telegram e Issues do Github.

- Feedback: É importante coletar feedback o mais cedo possível para evitar que erros cresçam a ponto de serem caros para manutenção. O Feedback deve vim dos membros da equipe e de avaliadores do projeto

- Práticas:
- Programação em pares: A Extreme Programming sugere que todo código produzido no projeto seja implementado por duas pessoas em conjunto no mesmo computador, revezando o teclado. Essa técnica pode ser utilizada de maneira remota utilizando Live Share do VSCode.

- Integração Contínua: Consiste em integrar o trabalho, assegurando que a base de código permaneça consistente ao final de cada integração. A equipe utiliza o Github e cada novo Pull Request o código deverá passar pelo Github Actions ao rodar todos os testes automatizados.


#### Kanban
Técnica que propõe a utilização de um quadro com cartões para acompanhar visualmente o desenvolvimento das atividades de um projeto. Será utilizado as issues do Github com integração do ZenHub para acompanhamento visual das tarefas que possuirão as etapas:

- Backlog: Todas as tarefas do projeto.  
- Sprint Backlog: Tarefas a serem executadas durante a Sprint.  
- Em andamento: Tarefas que estão em andamento.  
- Revisão: Tarefas que precisam ser revisadas para conclusão.  
- Concluido: Tarefas revisadas e concluidas.  

## Conclusão
Com o estudo de metodologias de desenvolvimento de software e a seleção de componentes de cada uma foi possível planejar um processo customizado a ser utilizado pela equipe utilizando elementos que fazem sentido para o contexto do projeto PetCare.