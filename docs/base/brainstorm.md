# Brainstorm
### Histórico de revisão
Data | Versão | Descrição | Autor |
--------- | ------ | ------------ | --------- |
10/09/2020 | 0.1 | Criação do documento | Ricardo Canela, Fernando Aguilar  |

## 1. Introdução
O brainstorm é uma técnica de elicitação de requisitos que consiste em reunir _steakholders_ e discutir sobre tópicos do projeto. No brainstorm é incentivado todo tipo de ideia que possa contribuir com o projeto e são evitadas críticas para permitir que todos se sintam a vontade de propor novas ideias.


## 2. Metodologia
A equipe se reuniu por video chamada por um período de 3 horas para debater ideias sobre possibilidades de projeto e o Ricardo Canela foi o moderador, direcionando a equipe com questões e transcrevendo as respostas para o documento.

## Brainstorm v1

#### Quais são as possibilidades de projetos que podemos trabalhar, levando em consideração nossos limites de tempo (4 meses de projeto) e recursos (3 pessoas) para a matéria de Desenho e Arquitetura de Software?

Voluntariados 
- Suporte Psicologico / social  
- Limpeza pública  
- Pessoas com deficiencia / idosos/ moradores de rua /  hospitalizados
- Mobilidade urbana
- Reforço escolar  
- Ajuda a animais com necessidades
- Serviço braçal (limpeza de casa, jardinagem) 

#### Dentre as possibilidades levantadas, o projeto que mais chamou nossa atenção foi a de Suporte a animais com necessidades. Como poderíamos dar suporte a esses animais?

Tipos de suporte a animais
- Alimentação 
- Vacinas 
- Remédios 
- Veterinário 
- Cirurgia (Castração) 
- Doação financeira para suprir demandas de saúde
- Levar para passear (aumenta o escopo?) 
- Compartilhar necessidades entre redes sociais 
- Transparência de que a doação está sendo feita de forma correta

#### Observando as formas elicitadas de como dar suporte a esses animais, qual seria o objetivo principal do projeto?

Desenvolver um projeto para melhorar a saúde e qualidade de vida de pets através de um sistema capaz de interligar donos de pets (podendo ser canis, ONGs ou donos comuns sem capacidade financeira) a amantes de pets que possuem condições para realizar doações financeiras.

#### Como se daria o processo de doação financeira de amantes de pets para donos de pets?

Um dono deverá se registrar no sistema (informando cpf para evitar fraudes), registrar um ou mais pets e inserir a demanda que o pet está tendo, podendo ser custos de veterinário, remédios, vacinas, cirurgias ou ração.  
O amante de pets teria a opção de doar para um pet específico ou colaborar com uma quantia (podendo ser uma vez ou mensalmente) para dar suporte a todos os pets necessitados que estarão na fila de espera para receber a doação.  
Assim que a publicação da demanda do pet atingir o valor estabelecido, o dono receberá o suporte financeiro e terá que comprovar o correto uso do valor recebido por meio de nota fiscal.

#### Ideias para uma possível melhoria do sistema no futuro:

- Ter outras contribuições sem ser apenas a financeira
- Poder gerar renda através de amantes de pets assistindo anúncios que seriam doados para a fila de espera
- Poder incluir participação de veterinários que queiram ajudar na melhoria da saúde de pets com necessidades
- Poder incluir atividades e mutirões para dar suporte a animais de ruas para quem quer ajudar e não pode fazer de forma financeira

## Requisitos elicitados

| ID | Descrição |
| --- | --- |
| BS01 | O dono do pet deve criar uma conta e realizar login |
| BS02 | O doador deve criar uma conta e realizar login |
| BS03 | O dono do pet deve registrar um ou mais pets |
| BS04 | O dono do pet pode criar um perfil de apresentação do pet |
| BS05 | O dono do pet deve publicar uma ou mais necessidades para cada pet |
| BS06 | O doador pode ver uma lista de pets com necessidades |
| BS07 | O doador pode fazer a doação para um pet selecionado da lista |
| BS08 | O doador pode fazer uma doação única ou mensal para contribuir com a fila de espera |
| BS09 | O dono do pet deve ser notificado e indicar confirmação quando a publicação da necessidade do pet atingir o valor requisitado |
| BS10 | O sistema deve depositar o dinheiro na conta do dono do pet |
| BS11 | O dono do pet deverá inserir uma nota fiscal indicando correto uso do dinheiro |

## Conclusão

Através da técnica de Brainstorm, conseguimos elicitar os primeiros requisitos do projeto.