# Poiato Gestão — demonstração pública

Uma demonstração interativa de gestão operacional, baseada nas categorias de trabalho que desenvolvo com Python, CustomTkinter e MySQL.

O **software original é uma aplicação desktop**. Este repositório contém uma interface web independente, criada apenas para apresentar a organização dos módulos e demonstrar algumas regras de negócio com registros fictícios. Não é uma publicação do software corporativo.

## O que dá para testar

- Painel financeiro com valor vigente, custos de fornecimentos, margem e markup calculados a partir dos vínculos de demonstração.
- Cadastro e edição de atendimentos e visualização detalhada de cada ficha.
- Catálogo de produtos com custos; alterações repercutem nos atendimentos já vinculados.
- Pregões e contratos com itens, quantidades ganhas, vínculos e saldo disponível.
- Vinculação de produtos a itens vigentes: tamanho físico não define o número do item.
- Indicadores e ranking de uso de produtos.
- Relatórios por contrato, atendimento ou produto com exportação CSV e impressão/PDF pelo navegador.
- Histórico simples de operações, exclusão lógica, restauração, níveis de acesso simulados e exportação JSON da demo.

## Como abrir

Abra `index.html` no navegador ou acesse o link do GitHub Pages, quando ativado.

Não é necessário servidor, Python, MySQL nem dependências externas. As alterações são guardadas no armazenamento local do navegador. **Clique em "Reiniciar dados da demo" para restaurar o cenário inicial.**

## Limites desta demonstração

Todos os registros são inventados. Não há login verdadeiro, banco de dados, API, integração com fornecedores ou emissão de documentos corporativos. Os módulos de relatório, permissões e backup apenas ilustram funcionalidades, com comportamento adaptado para o navegador.

A aplicação profissional de referência foi desenvolvida para desktop com Python, CustomTkinter e MySQL. O código e os dados privados desse ambiente não fazem parte deste repositório.

**Pedro Poiato — Soluções Digitais**
