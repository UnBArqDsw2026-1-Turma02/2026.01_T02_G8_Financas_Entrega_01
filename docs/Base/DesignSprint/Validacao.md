# Validação - Teste de Usabilidade

## Introdução

Esta seção apresenta o roteiro de teste de usabilidade elaborado para validar o protótipo do projeto Finanças. O objetivo é avaliar a experiência do usuário ao realizar os fluxos principais da aplicação — cadastro de entradas, saídas, parcelamentos e simulação de gasto — identificando possíveis problemas de usabilidade e validando se as funcionalidades atendem aos critérios de aceite definidos no [Backlog](Decision.md).

## Metodologia

O teste de usabilidade será conduzido de forma **moderada**, onde um facilitador acompanha o participante durante a execução das tarefas. O método escolhido é o **Teste de Tarefas**, no qual o participante recebe cenários realistas e deve completá-los interagindo com o protótipo de alta fidelidade desenvolvido no Figma.

### Perfil do Participante

- Pessoa que gerencia finanças pessoais (ou tem interesse em começar)
- Faixa etária: 25 anos
- Familiaridade básica com aplicativos mobile/web
- Gênero: Masculino
- Renda: R$ 6.000,00
- Ocupação: Engenheiro de Software

### Ambiente de Teste

- **Ferramenta:** Protótipo interativo no Figma
- **Duração estimada:** 15 a 20 minutos por participante
- **Registro:** Anotações do facilitador e gravação de tela (com consentimento)

---

## Roteiro do Teste

### 1. Recepção e Contextualização (2 min)

- Coletar o consentimento do participante para gravação.
- Verificar se o participante tem alguma dúvida antes de iniciar.

### 2. Perguntas Pré-Teste (2 min)

| #  | Pergunta |
|----|----------|
| 1  | Você costuma controlar suas finanças pessoais? Se sim, como? |
| 2  | Já utilizou algum aplicativo de controle financeiro? Qual? |
| 3  | O que você considera mais difícil no controle de finanças? |

---

### 3. Tarefas do Teste

#### Tarefa 1 — Cadastrar uma Entrada Financeira

**Cenário:** *"Você recebeu seu salário de R$ 3.000,00 hoje. Registre essa entrada no aplicativo."*

| Aspecto | Detalhe |
|---------|---------|
| **Feature relacionada** | 1.1.1 - Cadastro de entradas |
| **Fluxo esperado** | Acessar a tela de entradas → Adicionar nova entrada → Informar preenchimento de nome, valor, fonte e recorrência → Confirmar |
| **Critérios observados** | O participante conseguiu localizar a opção de cadastrar entrada? Conseguiu preencher todos os campos obrigatórios? Entendeu o campo de recorrência? |
| **Tempo máximo** | 3 minutos |

**Perguntas pós-tarefa:**
1. Foi fácil encontrar onde cadastrar a entrada?
2. Algum campo gerou dúvida?
3. O que você mudaria nessa tela?

---

#### Tarefa 2 — Cadastrar uma Saída Financeira

**Cenário:** *"Você foi ao supermercado e gastou R$ 250,00 no débito. Registre essa saída no aplicativo."*

| Aspecto | Detalhe |
|---------|---------|
| **Feature relacionada** | 1.1.2 - Cadastro de saídas |
| **Fluxo esperado** | Acessar a tela de saídas → Adicionar nova saída → Informar preenchimento de nome, valor, categoria, forma de pagamento e tipo de gasto → Confirmar |
| **Critérios observados** | O participante entendeu a diferença entre os campos? Conseguiu selecionar categoria, forma de pagamento e tipo de gasto sem dificuldade? |
| **Tempo máximo** | 3 minutos |

**Perguntas pós-tarefa:**
1. Os campos de categoria, forma de pagamento e tipo de gasto ficaram claros?
2. Você sentiu falta de alguma forma de pagamento?
3. A diferença entre gasto fixo e variável ficou clara?

---

#### Tarefa 3 — Cadastrar um Parcelamento

**Cenário:** *"Você comprou um celular novo de R$ 2.400,00 em 12x no cartão de crédito. Registre esse parcelamento no aplicativo."*

| Aspecto | Detalhe |
|---------|---------|
| **Feature relacionada** | 1.1.3 - Cadastro de contas parceladas |
| **Fluxo esperado** | Acessar a tela de parcelamentos → Adicionar novo parcelamento → Informar preenchimento de nome, valor, categoria, número de parcelas e forma de pagamento → Confirmar |
| **Critérios observados** | O participante entendeu como informar o número de parcelas? Ficou claro o valor por parcela? Conseguiu distinguir parcelamento de uma saída comum? |
| **Tempo máximo** | 3 minutos |

**Perguntas pós-tarefa:**
1. Ficou claro o valor de cada parcela?
2. A diferença entre registrar uma saída e um parcelamento ficou óbvia?
3. Você entendeu que o parcelamento só pode ser editado enquanto estiver na primeira parcela?

---

#### Tarefa 4 — Simular um Gasto

**Cenário:** *"Você quer comprar um notebook de R$ 4.000,00, mas não sabe se cabe no seu orçamento. Use o simulador de gasto para verificar o impacto nas suas finanças."*

| Aspecto | Detalhe |
|---------|---------|
| **Feature relacionada** | 1.1.6 - Simular gasto |
| **Fluxo esperado** | Acessar a funcionalidade de simulação → Informar o valor do gasto → Escolher se quer simular à vista ou parcelado → Visualizar o impacto no orçamento mensal e no limite diário |
| **Critérios observados** | O participante encontrou a funcionalidade de simulação? Entendeu as informações apresentadas (impacto no orçamento, novo limite diário)? Conseguiu simular tanto à vista quanto parcelado? |
| **Tempo máximo** | 4 minutos |

**Perguntas pós-tarefa:**
1. Você encontrou facilmente o simulador de gastos?
2. As informações de impacto no orçamento foram úteis e compreensíveis?
3. O alerta de comprometimento do orçamento (30%) ficou claro?
4. Você usaria essa funcionalidade no dia a dia?

---

### 4. Perguntas Pós-Teste (3 min)

| #  | Pergunta |
|----|----------|
| 1  | De modo geral, o que achou do aplicativo? |
| 2  | Qual tarefa foi mais fácil? E qual foi mais difícil? Por quê? |
| 3  | Teve algum momento em que se sentiu perdido ou confuso? |
| 4  | O que você mais gostou na interface? |
| 5  | O que você mudaria no aplicativo? |
| 6  | Você utilizaria este aplicativo para controlar suas finanças? |

### 5. Escala SUS (System Usability Scale)

Após o teste, o participante deve responder ao questionário SUS[1], atribuindo notas de 1 (discordo totalmente) a 5 (concordo totalmente):

| #  | Afirmação |
|----|-----------|
| 1  | Eu gostaria de usar esse sistema frequentemente. |
| 2  | Achei o sistema desnecessariamente complexo. |
| 3  | Achei o sistema fácil de usar. |
| 4  | Acho que precisaria de ajuda técnica para usar o sistema. |
| 5  | Achei que as funções do sistema estão bem integradas. |
| 6  | Achei que o sistema tem muitas inconsistências. |
| 7  | Imagino que a maioria das pessoas aprenderia a usar o sistema rapidamente. |
| 8  | Achei o sistema muito complicado de usar. |
| 9  | Me senti muito confiante usando o sistema. |
| 10 | Precisei aprender várias coisas antes de conseguir usar o sistema. |

---

## Métricas de Avaliação

| Métrica | Descrição |
|---------|-----------|
| **Taxa de conclusão** | Percentual de tarefas concluídas com sucesso |
| **Tempo por tarefa** | Tempo gasto em cada tarefa |
| **Número de erros** | Quantidade de erros cometidos durante cada tarefa |
| **Pontuação SUS** | Nota final calculada pelo questionário SUS |
| **Satisfação** | Feedback qualitativo coletado nas perguntas pós-tarefa |

---

## Gravação do Teste de Usabilidade

<iframe src="https://drive.google.com/file/d/1zV9iKT_OuirmtLDcc7KE9BMhHjjpAnGY/preview" width="640" height="480"></iframe>

## Referências

[1] BROOKE, John. SUS: A Quick and Dirty Usability Scale. Disponível em: https://www.usability.gov/how-to-and-tools/methods/system-usability-scale.html. Acesso em: 5 abr. 2026.

## Histórico de Versão

| Versão | Data | Descrição | Autor |
|--------|------|-----------|-------|
| 1.0 | 05/04/2026 | Criação do roteiro de teste de usabilidade | Equipe G8 |