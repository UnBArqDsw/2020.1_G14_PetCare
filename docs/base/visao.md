# Documento de Visão

## Histórico de revisão

Data | Versão | Descrição | Autor |
--------- | ------ | ------------ | --------- |
10/09/2020 | 0.1 | Abertura do documento | Fernando Aguilar, Ricardo Canela, |

## 1. Introdução

Nesta introdução serão abordados tópicos referentes a uma visão geral do produto, definindo seu propósito, escopo, definições, acrônimos, abreviações e referências.

### 1.1 Propósito

Esse documento visa especificar todo o escopo de funcionamento do PetCare.

Deixando claro seu objetivo, a razão de sua necessidade e a forma como busca solucionar os problemas aos quais se propõe, deixando claro possíveis restrições.

Assim, sua principal utilidade objetiva também, ao esclarecer o que é o sistema para os desenvolvedores, clientes e usuários. Estabelecendo ponto comum entre as ideias.

### 1.2 Escopo

Suprir a necessidade de um sistema web para auxilio à animais de estimação.

* Pets necessitados a terem uma melhor saúde
* Melhorar a qualidade de vida dos donos de pets
* Fornecer uma plataforma de impacto social para individuos filantropos

### 1.3 Definições, acrônimos e abreviações

| **Abreviação** | **Definição** |
| :--------: | :-------: |
| FGA | Faculdade do Gama |
| UnB | Universidade de Brasília |

### 1.4 Referências

* [Rich Picture PetCare](https://unbarqdsw.github.io/2020.1_G14_PetCare/base/rich-picture/)

### 1.5 Visão Geral

A organização do documento é feita de maneira a prover ao leitor a capacidade de através do mesmo entender o produto em seus vários aspectos de forma coesa.

Para tal, são apresentados primeiramente os tópicos referentes a função geral do software e as motivações que levaram a sua criação, após isso, é descrito o posicionamento do produto em relação ao mercado e as partes interessadas, incluindo a forma como a criação do sistema afetará os usuários.

Por fim, são descritas as principais funcionalidades do software, bem como algumas de suas restrições e requisitos.

## 2. Posicionamento

### 2.1 Oportunidade de Negócios

Este projeto tem como oportunidade de negocios, uma solução social para o problema de disponibilidade de recursos para tratamento adequado dos animais que estão em situação de necessidade. E portanto, uma facilidade aos respectivos donos de adquirir recursos.

### 2.2 Instrução do Problema

|  | |
| :--------: | :-------: |
| **Problema**| Animais que precisam de tratamento |
| **Funções afetadas** | Donos de animais, animais |
| **Efeito** | Recursos excaços |
| **Solução** | Uma plataforma social para arrecadação coletiva de recursos |

### 2.3 Instrução de Posição do produto

|  |  |
| :--: | :--: |
| **Público Alvo** | Donos de Pets |
| **Carência** | Financeira |
| **Solução** | Conectar quem pode ajudar financeiramento com com quem quer ajudar de outros metodos |
| **Descrição da Solução** | Financiar o tratamento e o cuidado de pets através de doações coletivas |
| **Diferenciais** | Parcerias com Organizações nao governamentais e outras instituições |

|  |  |
| :--: | :--: |
| **Público Alvo** | Quem possui recursos |
| **Carência** | Tempo e atenção |
| **Solução** | Tipos de suporte a animais |
| **Descrição da Solução** | Financiar o tratamento e o cuidado de pets através de doações coletivas |
| **Diferenciais** | Parcerias com Organizações nao governamentais e outras instituições |

## 3. Descrição dos Envolvidos e dos Usuários

### 3.1 Descrição dos Usuários

|  |  |
| :--------: | :-------: |
| **Representantes** | Usuario doador |
| **Descrição** | Usuario que realiza uma doação na plataforma |
| **Responsabilidades** | Ajudar com recursos aqueles pets que estao listados |
| **Critérios de Sucesso** | Comprovação de doação realizada |

|  |  |
| :--------: | :-------: |
| **Representantes** | Usuario recebedor |
| **Descrição** | Usuario que recebe uma doação na plataforma |
| **Responsabilidades** | Ajudar com tempo e atenção aqueles pets que estao listados |
| **Critérios de Sucesso** | Recurso disponível para uso |

### 3.2 Ambiente do Usuário

O acesso aos serviços do software poderá ser feito por navegadores de internet, como:

* Google Chrome;
* Mozila Firefox;

### 3.3 Principais necessidades

| **Necessidade** | **Prioridade** |
| :-------: | :-------: |
| Segurança | Alta |
| Confiabilidade | Alta |
| Qualidade | Alta |
| Facilidade de uso | Media |
| Entregabilidade de mudanças | baixa |

## 4. Visão Geral do Produto

Um projeto para melhorar a saúde e qualidade de vida de pets através de um sistema capaz de interligar donos de pets (podendo ser canis, ONGs ou donos comuns sem capacidade financeira) a amantes de pets que possuem condições para realizar doações financeiras.

### 4.1 Requisitos do produto

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

## 5. Recursos do Produto

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

## 6. Restrições

### 6.1 Restrições de implementação

### 6.2 Restrições externas

### 6.3 Restrições de design
