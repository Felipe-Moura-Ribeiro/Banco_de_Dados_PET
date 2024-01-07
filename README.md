# Banco_de_Dados_PET
Este repositório contém o esquema do banco de dados para um sistema de controle relacionado ao Programa de Educação Tutorial (PET). O esquema foi projetado para abranger as entidades Pessoa, Departamento, Item, Empréstimo, Tipo e a relação Classifica entre Item e Tipo.

## 1.Estrutura do Banco de Dados
O banco de dados consiste em várias tabelas inter-relacionadas:

- Pessoa: Representa informações sobre pessoas, incluindo matrícula, nome, telefone, e-mail, e um relacionamento opcional com um Departamento.

- Departamento: Armazena informações sobre os diferentes departamentos, com um identificador e nome do setor.

- Item: Contém detalhes sobre itens, como código, nome, quantidade, valor unitário, data de previsão para devolução, e uma relação com Pessoa, indicando a pessoa associada ao item.

- Empréstimo: Registra informações sobre empréstimos, incluindo data de empréstimo, data de devolução e quantia, associando-se às entidades Pessoa e Item.

- Tipo: Armazena informações sobre tipos de itens, com um identificador e nome do tipo.

- Classifica: Representa a relação entre Item e Tipo.

## 2.Contribuição
Se você encontrar problemas ou tiver sugestões de melhoria, sinta-se à vontade para abrir uma issue ou enviar uma solicitação de pull. Contribuições são bem-vindas!

## 3.Licença
Este projeto é licenciado sob a Licença MIT. Sinta-se à vontade para usá-lo de acordo com suas necessidades.
