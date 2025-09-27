# Entrega do Projeto 01

## Integrantes
- João Pedro Martiori  
- José Olavo Passolli  
- Nicholas de Moraes Felix  
- Evandro Friederich Meurer  

---

## Engenharia de Requisitos
Baseado no problema da proposta de trabalho da entrega, complete o documento a seguir.

---

## Histórias de Usuário

| ID   | Descrição |
|------|-----------|
| **HU01** | Como um fã de Pokémon, eu quero poder visualizar uma lista de pokémons, para que eu possa ter um acesso rápido a informações primárias do pokémon. |
| **HU02** | Sinto dificuldade para encontrar algum pokémon, tenho toda vez que ler linha a linha até encontrá-lo. |
| **HU03** | Não consigo ver qual pokémon de uma característica em específico que é melhor, toda vez tenho que procurar um por um pra poder diferenciar. |
| **HU04** | Tenho um arquivo com todos os pokémons que gosto, porém não consigo encontrar com facilidade e nem ler as características dele sem ter que ficar scrolando. |

---

## Requisitos Funcionais

| ID     | Descrição | Prioridade |
|--------|-----------|------------|
| **RF001** | O sistema deve exibir uma lista paginada de todos os Pokémons | |
| **RF002** | O sistema deve permitir buscar um Pokémon pelo nome | |
| **RF003** | O sistema deve permitir aplicar filtros com base em características (ex.: tipo, habilidades, estatísticas) | |
| **RF004** | O sistema deve exibir uma tela com todas as informações detalhadas de um Pokémon selecionado. | |
| **RF005** | O sistema deve permitir ordenar a lista por ordem alfabética | |
| **RF006** | O sistema deve permitir favoritar Pokémons para visualização rápida e utilização como filtro | |
| **RF007** | O sistema deve permitir filtrar por intervalo (range) de valores de um atributo específico, como poder ou velocidade | |

---

## Requisitos Não Funcionais

| ID      | Descrição |
|---------|-----------|
| *RNF001* | O sistema deve rodar em um servidor web |
| *RNF002* | O sistema deve utilizar um banco de dados para armazenar e recuperar informações dos Pokémons |
| *RNF003* | A interface deve ser responsiva, adaptando-se para dispositivos móveis, tablets e desktops |
| *RNF004* | O sistema deve ser otimizado para ter um baixo uso de CPU/RAM |
| *RNF005* | Queries (Pesquisas) devem ser guardadas em cache, para aumentar a velocidade e evitar repetir operações de análise e cálculos |
