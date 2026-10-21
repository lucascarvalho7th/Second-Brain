---
description: Abre o dia - cria ou atualiza a nota de hoje com prioridades, pendências e decisões abertas
argument-hint: [prioridades ou o que está na cabeça]
allowed-tools: Read, Glob, Grep, Write, Edit
---
Abra o meu dia no segundo cérebro. O que eu disse agora (pode estar vazio): $ARGUMENTS

1. Descubra a data de hoje. A nota do dia é `01-Diario/AAAA-MM-DD.md`.
2. Leia a nota de diário mais recente antes de hoje. Pegue as tarefas não marcadas (`- [ ]`) e o que ficou em "Amanhã".
3. Veja o que está em `00-Inbox/`.
4. Procure em `04-Decisoes/` notas com `status: aberta` ou com `revisar_em` igual ou anterior a hoje.
5. Procure em `03-Projetos/` notas com `status: ativo` e leia o "Próximo passo" de cada uma.
6. Se a nota de hoje não existir, crie a partir de `99-Templates/diario.md`. Se existir, atualize sem apagar o que eu já escrevi.
7. Preencha:
   - Prioridades: se eu passei prioridades, use as minhas. Senão, sugira 3 com base em pendências, projetos e prazos, marcadas como "(sugestão)".
   - Pendências: as tarefas que vieram de ontem, com link para a nota de origem.
   - Decisões abertas: links para as notas, destacando as com revisão vencida.
8. Responda no chat em até 8 linhas: as 3 prioridades, quantos itens há no Inbox (sugira `/despejo` se houver) e as decisões que pedem atenção. Se as prioridades foram sugestão sua, pergunte se eu confirmo.
