# Checklist de Validação do Protótipo

## Introdução

Este checklist foi elaborado com base no backlog definido no artefato [Decision](Decision.md), e tem como objetivo verificar se o protótipo contempla todas as funcionalidades e fluxos requeridos.

## Theme 1 – Gestão Financeira Base

### Epic 1.1 – Controle de Movimentações Financeiras

#### Feature 1.1.1 – Cadastro de Entradas

- [x] Tela de cadastro de entrada com os campos: **nome**, **valor**, **data**, **fonte** (opcional) e **recorrência**
- [x] Listagem de entradas ordenadas por data
- [x] Ação de editar uma entrada
- [x] Ação de excluir uma entrada

#### Feature 1.1.2 – Cadastro de Saídas

- [x] Tela/fluxo de cadastro de saída com os campos: **nome**, **valor**, **categoria**, **data**, **forma de pagamento** (pix, crédito, débito, dinheiro) e **tipo de gasto** (fixo/variável)
- [x] Listagem de saídas ordenadas por data
- [x] Ação de editar uma saída
- [x] Ação de excluir uma saída

#### Feature 1.1.3 – Cadastro de Contas Parceladas

- [x] Tela/fluxo de cadastro de parcelamento com os campos: **nome**, **valor**, **data**, **categoria**, **número de parcelas** e **forma de pagamento**
- [x] Listagem de parcelamentos ordenados por data
- [x] Edição permitida apenas quando recém-criado ou na primeira parcela
- [x] Ação de excluir um parcelamento
- [x] Ação de antecipar parcelas
- [x] Visualização do valor antecipado somado à parcela atual

#### Feature 1.1.4 – Cadastro de Categorias

- [x] Tela/fluxo de cadastro de categoria com os campos: **nome**, **descrição** e **cor**
- [x] Listagem de categorias ordenadas por nome
- [x] Ação de editar uma categoria
- [x] Ação de excluir uma categoria

#### Feature 1.1.5 – Extrato Financeiro

- [x] Tela de extrato com listagem de movimentações ordenadas por data
- [x] Exibição do saldo atual da conta
- [x] Campo de pesquisa

#### Feature 1.1.6 – Simular Gasto

- [x] Tela/fluxo de simulação de gasto
- [x] Indicação se o gasto impacta até 30% do orçamento mensal disponível
- [x] Simulação de parcelamento de gastos
- [x] Aviso se o gasto está dentro do orçamento mensal
- [x] Exibição do novo orçamento após o gasto
- [x] Exibição do novo limite diário após o gasto

---

## Theme 2 – Orçamento Diário e Reserva

### Epic 2.1 – Limite Diário de Gastos

#### Feature 2.1.1 – Definição de Limite Diário

- [x] Exibição do limite diário calculado
- [x] Possibilidade de o usuário ajustar manualmente o orçamento máximo do limite diário para um valor menor

#### Feature 2.1.2 – Controle da Reserva

- [x] Exibição do saldo da reserva
- [x] Indicação de que o valor não gasto do limite diário é transferido para a reserva
- [x] Indicação de que o excedente do limite diário é debitado da reserva

#### Feature 2.1.3 – Controle do Extra

- [x] Exibição do saldo extra (negativo)
- [x] Indicação de que, ao ultrapassar o limite com reserva zerada, o excedente vira "extra"
- [x] Indicação de recalculo do limite diário quando há gasto extra

---

## Theme 3 – Gamificação Financeira

### Epic 3.1 – Mecânica de Incentivo

#### Feature 3.1.1 – Wallet (Carteira)

- [x] Exibição de quanto já foi gasto no dia
- [x] Exibição de quanto falta para atingir o limite diário
- [x] Exibição do limite diário
- [x] Exibição do saldo da reserva
- [x] Exibição do saldo extra (se houver)

#### Feature 3.1.2 – Progresso na Economia

- [x] Indicador visual de progresso (sequência de dias dentro do limite)
- [x] Calendário com dias dentro do limite e da reserva
- [x] Quebra de sequência apenas quando atinge o "extra"
---

## Theme 4 – Dashboard

### Epic 4.1 – Visão Geral

#### Feature 4.1.1 – Dashboard Principal

- [x] Exibição do saldo de entradas
- [x] Exibição do saldo de saídas variáveis
- [x] Exibição do saldo de saídas fixas
- [x] Exibição do saldo disponível (entradas − saídas)

#### Feature 4.1.2 – Dashboard por Categoria

- [x] Gráfico de gastos por categoria

#### Feature 4.1.3 – Dashboard por Tendência de Gastos

- [x] Gráfico de tendência de gastos por dia

---