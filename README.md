# LWM Auto Atacado — Análise de Sugestões

App interno pra cadastrar, analisar e aprovar sugestões de compra de peças, acompanhar o que falta comprar, o desempenho de venda e a venda casada.

🔗 **Acesse em:** https://rayssaln.github.io/sugestao-lwm/

## Como funciona

- Login com conta Google (qualquer conta — não precisa de convite).
- Os dados ficam no Firebase (Firestore), compartilhados em tempo real entre todo mundo que acessa.
- Site estático hospedado no GitHub Pages, direto deste repositório.

## Como atualizar o site

1. Faça as alterações no arquivo `index.html` (ou peça pro Claude gerar a versão atualizada).
2. Suba o arquivo aqui no GitHub, substituindo o que já existe (**Add file > Upload files**).
3. Espera 1-2 minutos e o site atualiza sozinho em https://rayssaln.github.io/sugestao-lwm/.

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

- **Sugestão** — cadastro/importação de itens
- **Analisar** — aprovar, rejeitar ou comparar com similares
- **Comprar** — definir quantidade, data de compra e chegada
- **Desempenho** — o que vendeu e o que ficou parado
- **Venda Casada** — itens comprados em conjunto
- **Importação** — planilhas, relatórios, margens por marca e restauração de backup
```
Feito por Rayssa💙
