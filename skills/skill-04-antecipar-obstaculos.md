# Skill 4 - Antecipar Obstáculos e Planos B

**Descrição de gatilho:** Antecipa de 4 a 6 obstáculos concretos do plano com probabilidade, impacto, gatilho de alerta, prevenção e Plano B (Se X, então Y).

---

## Quando usar
Use depois que o plano estiver encaixado na rotina e antes de começar a execução, ou quando o usuário perceber um risco novo. Objetivo: prever o que pode travar o plano e deixar uma resposta pronta. **Não use** para registrar o progresso (Skill 5).

## Entradas
- Objetivo, plano de ação com blocos de tempo e base de Rotina.
- Base **Obstáculos** do Planner.
- Histórico de check-ins, se existir.

## Passo a passo
1. Procure riscos em 5 categorias: **Tempo/Agenda**, **Energia/Cansaço**, **Conhecimento/Técnico**, **Motivação** e **Imprevisto**. Use evidências do próprio plano (dias sobrecarregados, feriados, entregas próximas, tarefas longas seguidas).
2. Selecione **de 4 a 6** obstáculos mais prováveis. Não liste riscos genéricos sem relação com o plano.
3. Para cada um, defina:
   - **Probabilidade** e **Impacto** (Alta/Média/Baixa);
   - **Gatilho**: sinal observável de que está acontecendo (ex.: "2 blocos seguidos pulados");
   - **Prevenção**: ação antecipada que reduz a chance;
   - **Plano B** no formato **"Se [gatilho], então [ação específica]"**, executável em menos de 2 minutos de decisão.
4. Se uma prevenção exigir mudança no plano (ex.: mover tarefa de um dia lotado), proponha a mudança e peça confirmação antes de alterar tarefas.
5. Busque o schema da base **Obstáculos** e crie os registros relacionados ao objetivo, com status "Monitorando".

## Saída esperada
Tabela: obstáculo | probabilidade × impacto | gatilho | Plano B. Destaque os 2 mais críticos (Alta × Alto). Sugira revisar com a **Skill 5** ao fim da semana.

## Casos especiais
- Obstáculo já registrado: atualize em vez de duplicar.
- Usuário relata que um obstáculo ocorreu: mude o status para "Ocorreu - Em contorno" e aplique o Plano B.
