# LWM Auto Atacado — Análise de Sugestões

App interno pra cadastrar, analisar e aprovar sugestões de compra de peças, acompanhar o que falta comprar, o desempenho de venda e a venda casada.

## Como funciona

- Login com conta Google (qualquer conta — não precisa de convite).
- Os dados ficam no Firebase (Firestore), compartilhados em tempo real entre todo mundo que acessa.
- Site estático hospedado no GitHub Pages, direto deste repositório.

## Como atualizar o site

1. Faça as alterações no arquivo `index.html`.
2. Suba o arquivo aqui no GitHub, substituindo o que já existe (**Add file > Upload files**).
3. Espera 1-2 minutos e o site atualiza sozinho no link de sempre.

## Estrutura

```
index.html       → o app inteiro (HTML + CSS + JS)
assets/          → logo e ícones das telas
```

## Firebase

- Projeto: `lwm-atacado` (console.firebase.google.com)
- Banco de dados: Firestore
- Autenticação: Google Sign-In

## Telas

- **Sugestão** — cadastro/importação de itens (código, marca, custo, venda, similares, quantidade mínima por fornecedor)
- **Analisar** — aprovar, rejeitar ou comparar com similares
- **Comprar** — definir quantidade (respeitando a mínima de cada fornecedor), data de compra e chegada
- **Desempenho** — o que vendeu e o que ficou parado
- **Venda Casada** — itens comprados em conjunto
- **Importação** — planilhas, relatórios, margens por marca e restauração de backup completo

## Quantidade mínima por fornecedor

Cada item (principal ou similar) pode ter uma "quantidade mínima p/ pedido" cadastrada — tanto no formulário manual quanto na planilha de importação. Se alguém tentar pedir uma quantidade menor que a mínima na tela Comprar, o campo fica vermelho, mostra um aviso e a quantidade não é salva até ser corrigida.


#Feito por Rayssa💙
