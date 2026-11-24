# Skill 3 - Adaptar Plano à Rotina

**Descrição de gatilho:** Distribui as tarefas do Plano de Ação em blocos de tempo reais respeitando compromissos fixos, sono, lazer, Google Agenda e turno de energia.

---

## Quando usar
Use quando o plano de ação já existir e o usuário quiser **encaixar as tarefas em horários reais**, respeitando compromissos fixos, sono, lazer e níveis de energia. Também serve para reencaixar uma semana inteira. **Não use** para imprevistos do dia (Skill 6).

## Entradas
- Base **Rotina & Eventos**: blocos fixos, janelas cognitivas (alta energia), janelas simples (baixa energia), lazer protegido, sono e buffer.
- Base **Plano de Ação**: tarefas sem bloco de tempo (ou da semana a replanejar).
- Compromissos pontuais (provas, entregas, eventos): leia a base de tarefas/agenda que o usuário indicar ou peça que ele cole os eventos do Google Agenda da semana.

## Passo a passo
1. Monte a grade da semana a partir da Rotina. Marque como **indisponível**: compromissos fixos, sono, refeições e lazer protegido. Nunca agende nesses horários.
2. Remova da grade os compromissos pontuais da semana (provas, entregas, feriados). Se um dia tiver uma entrega importante, **reduza pela metade** o bloco cognitivo desse dia.
3. Calcule a capacidade real: soma das janelas livres − 15% de folga. Compare com o esforço das tarefas da semana.
4. Distribua respeitando energia:
   - tarefas *Cognitivas* → janelas cognitivas (ex.: tarde);
   - tarefas *Simples* → janelas simples (ex.: noite);
   - em dias longos de compromisso, apenas 1 tarefa simples curta;
   - nenhuma tarefa após o horário-limite antes do sono definido na Rotina.
5. Se faltar capacidade, use o buffer semanal; se ainda faltar, mova tarefas de prioridade Baixa para a semana seguinte e avise.
6. Atualize o **Bloco de Tempo** (data e hora de início e fim) de cada tarefa. Registre nas notas o motivo de ajustes (ex.: "bloco reduzido por entrega X").

## Saída esperada
Grade da semana em tabela (dia | horário | tarefa | energia), capacidade vs. carga, lista de ajustes feitos e tarefas adiadas. Lembre o usuário de **copiar os blocos para o Google Agenda** se quiser lembretes. Sugira: **Skill 4 - Antecipar Obstáculos**.

## Casos especiais
- Base de Rotina vazia: pergunte horário de acordar/dormir, compromissos fixos por dia e turno de maior energia antes de agendar.
- Conflito entre tarefa e evento pontual descoberto depois: o evento sempre vence; reencaixe a tarefa.
