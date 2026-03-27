# Checklist de Validação do Protótipo

## Introdução

Este checklist foi elaborado com base no backlog definido no artefato [Decision](Decision.md), e tem como objetivo verificar se o protótipo contempla todas as funcionalidades e fluxos requeridos.

## Theme 1 – Gestão Financeira Base

### Epic 1.1 – Controle de Movimentações Financeiras

#### Feature 1.1.1 – Cadastro de Entradas

- [ ] Tela de cadastro de entrada com os campos: **nome**, **valor**, **fonte** (opcional) e **recorrência**
- [ ] Data preenchida automaticamente (sem campo manual)
- [ ] Listagem de entradas ordenadas por data
- [ ] Ação de editar uma entrada
- [ ] Ação de excluir uma entrada
- [ ] Feedback de validação (valor > 0, nome obrigatório, recorrência obrigatória)

#### Feature 1.1.2 – Cadastro de Saídas

- [ ] Tela/fluxo de cadastro de saída com os campos: **nome**, **valor**, **categoria**, **forma de pagamento** (pix, crédito, débito, dinheiro) e **tipo de gasto** (fixo/variável)
- [ ] Data preenchida automaticamente (sem campo manual)
- [ ] Listagem de saídas ordenadas por data
- [ ] Ação de editar uma saída
- [ ] Ação de excluir uma saída
- [ ] Feedback de validação (valor > 0, nome obrigatório, forma de pagamento obrigatória, tipo de gasto obrigatório, categoria obrigatória)

#### Feature 1.1.3 – Cadastro de Contas Parceladas

- [ ] Tela/fluxo de cadastro de parcelamento com os campos: **nome**, **valor**, **categoria**, **número de parcelas** e **forma de pagamento**
- [ ] Data preenchida automaticamente (sem campo manual)
- [ ] Listagem de parcelamentos ordenados por data
- [ ] Edição permitida apenas quando recém-criado ou na primeira parcela
- [ ] Ação de excluir um parcelamento
- [ ] Ação de antecipar parcelas
- [ ] Visualização do valor antecipado somado à parcela atual
- [ ] Feedback de validação (valor > 0, nome obrigatório, forma de pagamento obrigatória, categoria obrigatória)

#### Feature 1.1.4 – Cadastro de Categorias

- [ ] Tela/fluxo de cadastro de categoria com os campos: **nome**, **descrição** e **cor**
- [ ] Listagem de categorias ordenadas por nome
- [ ] Ação de editar uma categoria
- [ ] Ação de excluir uma categoria
- [ ] Feedback de validação (nome obrigatório, descrição obrigatória, cor obrigatória)

#### Feature 1.1.5 – Extrato Financeiro

- [ ] Tela de extrato com listagem de movimentações ordenadas por data
- [ ] Exibição do saldo atual da conta
- [ ] Filtro por **tipo** (Entrada, Saída, Parcelamento)
- [ ] Filtro por **ano e mês**
- [ ] Filtro por **categoria**
- [ ] Filtro por **forma de pagamento**
- [ ] Filtro por **tipo de gasto**
- [ ] Campo de **pesquisa por nome**

#### Feature 1.1.6 – Simular Gasto

- [ ] Tela/fluxo de simulação de gasto
- [ ] Indicação se o gasto impacta até 30% do orçamento mensal disponível
- [ ] Simulação de parcelamento de gastos
- [ ] Aviso se o gasto está dentro do orçamento mensal
- [ ] Exibição do novo orçamento após o gasto
- [ ] Exibição do novo limite diário após o gasto

---

## Theme 2 – Orçamento Diário e Reserva

### Epic 2.1 – Limite Diário de Gastos

#### Feature 2.1.1 – Definição de Limite Diário

- [ ] Exibição do limite diário calculado automaticamente: `(renda - gastos fixos) / dias do mês`
- [ ] Atualização do limite com os gastos do dia
- [ ] Alerta quando o limite diário é zero
- [ ] Possibilidade de o usuário ajustar manualmente o orçamento máximo do limite diário para um valor menor

#### Feature 2.1.2 – Controle da Reserva

- [ ] Exibição do saldo da reserva
- [ ] Indicação de que o valor não gasto do limite diário é transferido para a reserva
- [ ] Indicação de que o excedente do limite diário é debitado da reserva

#### Feature 2.1.3 – Controle do Extra

- [ ] Exibição do saldo extra (negativo)
- [ ] Indicação de que, ao ultrapassar o limite com reserva zerada, o excedente vira "extra"
- [ ] Indicação de recalculo do limite diário quando há gasto extra

---

## Theme 3 – Gamificação Financeira

### Epic 3.1 – Mecânica de Incentivo

#### Feature 3.1.1 – Wallet (Carteira)

- [ ] Exibição de quanto já foi gasto no dia
- [ ] Exibição de quanto falta para atingir o limite diário
- [ ] Exibição do limite diário
- [ ] Exibição do saldo da reserva
- [ ] Exibição do saldo extra (se houver)

#### Feature 3.1.2 – Progresso na Economia

- [ ] Indicador visual de progresso (sequência de dias dentro do limite)
- [ ] Calendário com dias dentro do limite e da reserva
- [ ] Quebra de sequência apenas quando atinge o "extra"
- [ ] Mensagens de feedback (parabéns ao manter controle / alerta ao ultrapassar)

#### Feature 3.1.3 – Alertas

- [ ] Alerta de aproximação de **70%** do limite diário
- [ ] Alerta ao **atingir** o limite diário
- [ ] Alerta de uso de **50%** da reserva
- [ ] Alerta de uso de **80%** da reserva
- [ ] Alerta ao **esgotar** a reserva

---

## Theme 4 – Dashboard

### Epic 4.1 – Visão Geral

#### Feature 4.1.1 – Dashboard Principal

- [ ] Exibição do saldo de entradas
- [ ] Exibição do saldo de saídas variáveis
- [ ] Exibição do saldo de saídas fixas
- [ ] Exibição do saldo disponível (entradas − saídas)

#### Feature 4.1.2 – Dashboard por Categoria

- [ ] Gráfico de gastos por categoria

#### Feature 4.1.3 – Dashboard por Tendência de Gastos

- [ ] Gráfico de tendência de gastos por dia

---

## Theme 5 – Mensageria e Linguagem Natural

### Epic 5.1 – Registro de Ações por Mensagens

#### Feature 5.1.1 – Integração com Provider de Mensageria

- [ ] Tela/fluxo de envio de mensagem em linguagem natural
- [ ] Feedback ao usuário sobre o processamento da mensagem
- [ ] Tratamento e exibição de erros de comunicação

#### Feature 5.1.2 – Tools via Mensagem

- [ ] Criação de entrada por mensagem
- [ ] Criação de saída por mensagem
- [ ] Criação de parcelamento por mensagem
- [ ] Edição de entrada por mensagem
- [ ] Edição de saída por mensagem
- [ ] Edição de parcelamento por mensagem
- [ ] Exclusão de entrada por mensagem
- [ ] Exclusão de saída por mensagem
- [ ] Exclusão de parcelamento por mensagem
- [ ] Simulação de gasto por mensagem
- [ ] Listagem do extrato por mensagem
- [ ] Listagem de entradas por mensagem
- [ ] Listagem de saídas por mensagem
- [ ] Listagem de parcelamentos por mensagem
