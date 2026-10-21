---
description: Conduz uma decisão pessoal ou profissional - entrevista, busca o histórico no vault, contesta e registra
argument-hint: [a decisão, em uma frase]
allowed-tools: Read, Glob, Grep, Write, Edit
---
Quero pensar nesta decisão: $ARGUMENTS

Siga as etapas uma de cada vez. Não pule direto para a recomendação.

1. Procure em `04-Decisoes/` se já existe nota sobre isso. Se existir, continue nela. Senão, crie `04-Decisoes/AAAA-MM-DD Título curto.md` a partir de `99-Templates/decisao.md`, com `status: aberta`.
2. Entrevista: faça UMA pergunta por vez, no máximo 5 no total, só sobre o que ainda faltar entre:
   - o contexto e por que decidir agora;
   - as opções (inclusive "não fazer nada" e opções que eu não citei);
   - o que pesa para mim (critérios) e do que eu não abro mão;
   - o prazo e o que acontece se eu não decidir;
   - qual opção eu estou inclinado a escolher, e por quê.
3. Histórico: busque no vault (decisões, diários, projetos, pessoas, áreas) o que tem relação, mesmo sem a palavra exata. Em "O que o histórico diz", cite cada achado com [[link]] e uma linha. Destaque decisões parecidas e o que aconteceu depois. Se não achar nada, diga.
4. Contra-argumentos: escreva o melhor caso contra a opção que eu prefiro, os riscos, o que precisaria ser verdade para ela dar certo e se a decisão é fácil ou difícil de desfazer.
5. Mostre um resumo curto: tabela de opções x critérios, o que o histórico diz e a pergunta que você acha que eu ainda não respondi.
6. Pergunte qual é a minha decisão. Quando eu responder, preencha "Decisão e porquê" e "O que espero que aconteça", mude para `status: decidida` e sugira um `revisar_em` (padrão: 3 meses). Se eu ainda não decidir, deixe `aberta`.
7. Linke a decisão na nota do dia e na nota do projeto ou da área relacionada.

Nunca decida por mim. Você pode dizer qual opção parece mais forte e por quê, deixando claro que é a sua leitura.
