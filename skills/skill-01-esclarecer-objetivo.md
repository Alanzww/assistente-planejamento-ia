# Skill 1 - Esclarecer e Registrar Objetivo

**Descrição de gatilho:** Esclarece uma ideia vaga com até 4 perguntas, define critérios de pronto observáveis e registra o objetivo na base `Objetivos` do Planner.

---

## Quando usar
Use quando o usuário trouxer uma ideia, desejo ou meta ainda vaga ("quero aprender X", "preciso organizar Y") e quiser transformá-la em um objetivo mensurável registrado no Planner. **Não use** para quebrar o objetivo em tarefas (Skill 2) nem para agendar (Skill 3).

## Entradas
- A ideia do usuário, em texto livre.
- O Planner indicado pelo usuário (página que contenha uma base de **Objetivos**). Se nenhum for indicado, pergunte qual usar.

## Passo a passo
1. Leia a ideia e identifique o que já está claro: resultado desejado, prazo, motivação, recompensa e restrições.
2. Faça **no máximo 4 perguntas**, em uma única mensagem, apenas sobre o que falta. Priorize: (a) como saber que terminou, (b) prazo, (c) horas por semana disponíveis, (d) recompensa ao concluir.
3. Reescreva o objetivo no formato: **verbo de ação + resultado concreto + prazo** (ex.: "Concluir o curso X e emitir o certificado até DD/MM").
4. Defina de 2 a 4 critérios de pronto observáveis (checklist). Evite critérios subjetivos como "entender bem".
5. Verifique realismo: se as horas semanais × semanas parecerem insuficientes para o resultado, avise e proponha prazo maior ou escopo menor. Não decida sozinho.
6. Busque o schema da base **Objetivos** antes de escrever. Crie um registro usando os nomes reais das propriedades (título, área, status "Ativo" ou equivalente, prazo, horas/semana, critério de sucesso, recompensa). Coloque a definição de pronto no corpo da página.

## Saída esperada
Responda com: objetivo reescrito, critérios de pronto, alerta de realismo (se houver) e link do registro criado. Termine sugerindo a próxima etapa: **Skill 2 - Gerar Plano de Ação**.

## Casos especiais
- Usuário não quer responder perguntas: registre com o que houver e marque os campos faltantes como "a definir" no corpo.
- Já existe um objetivo muito parecido na base: mostre-o e pergunte se deve atualizar em vez de duplicar.
- Propriedade esperada não existe: grave a informação no corpo da página e informe o usuário; não altere o schema sem pedir.
