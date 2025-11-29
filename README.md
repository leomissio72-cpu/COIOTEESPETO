# Sistema Restaurante Coiote BBQ

Sistema de gerenciamento para restaurante/churrascaria desenvolvido em HTML, CSS e JavaScript puro.

## Funcionalidades

### Dashboard
- Visao geral com estatisticas de vendas
- Filtros por produto, categoria e data
- Lista de comandas ativas
- Ranking de produtos mais vendidos

### Comandas
- Criar novas comandas com nome do cliente
- Adicionar/remover itens
- Ajustar quantidades
- Fechar comanda com selecao de forma de pagamento

### Produtos
- Cadastro de produtos com nome, categoria e preco
- Edicao e exclusao de produtos
- Categorias: Espeto, Copos, Bebidas, Facas, Itens para Churrasco, Espeto Congelado

### Relatorios
- Historico de vendas
- Visualizacao de notas fiscais anteriores

### Notas Fiscais
- Geracao automatica ao fechar comanda
- Download da nota em arquivo de texto
- Detalhes completos: cliente, itens, forma de pagamento, total

## Tecnologias

- HTML5
- CSS3
- JavaScript (ES6+)
- LocalStorage para persistencia de dados

## Como Usar

1. Clone o repositorio
2. Abra o arquivo `index.html` em um navegador
3. O sistema carrega dados de exemplo automaticamente

Ou hospede em qualquer servidor web estatico.

## Estrutura do Projeto

```
/
├── index.html    # Aplicacao completa (HTML, CSS e JS)
└── README.md     # Este arquivo
```

## Armazenamento

Os dados sao salvos no LocalStorage do navegador:
- `produtos` - Catalogo de produtos
- `comandas` - Comandas ativas
- `vendas` - Historico de vendas
- `ultimoIdComanda` - Contador de IDs

## Licenca

Este projeto e de uso livre.
