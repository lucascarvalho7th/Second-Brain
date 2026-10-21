---
description: Organiza texto solto ou o Inbox - separa tarefas, ideias, pessoas e decisões e arquiva cada uma no lugar certo
argument-hint: [texto solto; vazio processa o 00-Inbox]
allowed-tools: Read, Glob, Grep, Write, Edit
---
Organize este despejo: $ARGUMENTS

Se o texto acima estiver vazio, processe cada arquivo de `00-Inbox/`.

1. Quebre o conteúdo em itens e classifique cada um:
   - Tarefa → na nota do projeto ou da área relacionada. Se for para hoje, também na nota do dia.
   - Ideia ou aprendizado → na nota do projeto ou área relacionada, ou numa nova nota em `06-Conhecimento/`.
   - Informação sobre uma pessoa → `05-Pessoas/Nome.md` (crie a partir de `99-Templates/pessoa.md` se não existir).
   - Algo que eu preciso decidir → nova nota em `04-Decisoes/` a partir de `99-Templates/decisao.md`, com `status: aberta`, só com o contexto e as opções que eu citei.
   - Atualização de projeto ou área → acrescente na seção "Registro" da nota, com a data na frente.
   - Reflexão, sentimento ou registro do dia → seção "Notas do dia" da nota de hoje.
2. Antes de criar uma nota, procure se já existe uma sobre o assunto (nome parecido ou link).
3. Mantenha as minhas palavras; só resuma o que for longo. Crie os [[links]] entre as notas tocadas.
4. Arquivos do Inbox já processados vão para `99-Arquivo/Inbox processado/`. Não apague nada.
5. Se não souber onde algo vai, não invente: deixe no Inbox e me pergunte no fim.
6. Responda com uma lista curta: item → onde foi parar (link). Depois, as dúvidas, se houver.
