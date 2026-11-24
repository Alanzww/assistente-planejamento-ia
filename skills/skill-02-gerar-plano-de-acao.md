# Skill 2 - Gerar Plano de Ação

**Descrição de gatilho:** Quebra um objetivo registrado em 3 a 5 marcos e tarefas de 25 a 180 min com esforço estimado e tipo de energia (Cognitiva ou Simples).

---

## Quando usar
Use quando já existir um objetivo registrado (com critério de pronto e prazo) e o usuário quiser saber **o que fazer** para alcançá-lo. **Não use** para definir horários (Skill 3) nem para listar riscos (Skill 4).

## Entradas
- O registro do objetivo na base **Objetivos** (título, prazo, critério de sucesso, horas/semana).
- A base **Plano de Ação** do mesmo Planner.
- Contexto opcional do usuário (ex.: número de módulos do curso, materiais já disponíveis).

## Passo a passo
1. Leia o objetivo e calcule o orçamento total: **semanas até o prazo × horas/semana**. Reserve ~15% como folga.
2. Divida o caminho em **3 a 5 marcos sequenciais** (fases ou semanas), cada um com um resultado verificável.
3. Para cada marco, crie tarefas que:
   - comecem com verbo ("Assistir", "Praticar", "Publicar");
   - durem **entre 25 e 180 minutos** (quebre o que for maior);
   - tenham esforço estimado em minutos, prioridade e **tipo de energia**: *Cognitiva* (conteúdo novo, criar, resolver) ou *Simples* (revisar, organizar, resumir).
4. Inclua em cada semana pelo menos 1 tarefa de revisão e, no último marco, a tarefa de entrega/recompensa final.
5. Some o esforço estimado e compare com o orçamento. Se ultrapassar, corte ou simplifique tarefas de prioridade Baixa e diga o que foi cortado.
6. Busque o schema da base **Plano de Ação** e crie todas as tarefas em um único lote, relacionadas ao objetivo, com status inicial "Não iniciado". **Não preencha o bloco de tempo** - isso é papel da Skill 3.

## Saída esperada
Tabela resumida por marco (tarefas, minutos totais) + total geral vs. orçamento + link da base. Sugira a próxima etapa: **Skill 3 - Adaptar Plano à Rotina**.

## Casos especiais
- Objetivo sem prazo ou sem horas/semana: peça esses dois dados antes de gerar o plano.
- Já existem tarefas ligadas ao objetivo: mostre-as e pergunte se deve complementar ou substituir; nunca apague sem confirmação.
