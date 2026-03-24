# Backlog do Projeto


# Theme 1 - Gestão Financeira Base

## Epic 1.1 - Controle de Movimentações Financeiras

### Feature 1.1.1 - Cadastro de entradas

#### Story 1.1.1.1

Eu, como usuário, quero cadastrar entradas financeiras para que eu possa ter controle sobre minhas movimentações diárias.

**Tasks**

- [ ] Criar a entidade Entrada
- [ ] Permitir informar valores de: nome, valor, fonte da entrada (opcional) e recorrência 
- [ ] Exibir listagem das movimentações ordenadas por data
- [ ] Permitir editar uma entrada
- [ ] Permitir excluir uma entrada
- [ ] Validar se o valor é maior que 0
- [ ] Validar se o nome não está vazio
- [ ] Validar se a recorrência foi selecionada 
- [ ] Data deve ser inserida automaticamente com a data da adição

**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de cadastrar entradas financeiras.
- [ ] O usuário deve ser capaz de visualizar as entradas financeiras.
- [ ] O usuário deve ser capaz de editar as entradas financeiras.
- [ ] O usuário deve ser capaz de excluir as entradas financeiras.

### Feature 1.1.2 - Cadastro de saídas

#### Story 1.1.2.1

Eu, como usuário, quero cadastrar saídas financeiras para que eu possa ter controle sobre minhas movimentações diárias.

**Tasks**

- [ ] Criar a entidade Saída
- [ ] Permitir informar valores de: nome, valor, categoria, forma de pagamento (pix, crédito, débito, dinheiro) e tipo de gasto (fixo ou variável)
- [ ] Exibir listagem das movimentações ordenadas por data
- [ ] Permitir editar uma saída
- [ ] Permitir excluir uma saída
- [ ] Validar se o valor é maior que 0
- [ ] Validar se o nome não está vazio
- [ ] Validar se a forma de pagamento foi selecionada 
- [ ] Validar se o tipo de gasto foi selecionado 
- [ ] Validar se a categoria foi selecionada 
- [ ] Data deve ser inserida automaticamente com a data da adição

**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de cadastrar saídas financeiras.
- [ ] O usuário deve ser capaz de visualizar as saídas financeiras.
- [ ] O usuário deve ser capaz de editar as saídas financeiras.
- [ ] O usuário deve ser capaz de excluir as saídas financeiras.

### Feature 1.1.3 - Cadastro de contas parceladas

#### Story 1.1.3.1

Eu, como usuário, quero cadastrar contas parceladas para que eu possa ter controle sobre minhas movimentações diárias.

**Tasks**

- [ ] Criar a entidade Parcelada
- [ ] Permitir informar valores de: nome, valor, categoria, numero de parcelas e forma de pagamento (pix, crédito, débito, dinheiro)
- [ ] Exibir listagem das movimentações ordenadas por data
- [ ] Permitir editar quando acabado de criar e/ou ainda na primeira parcela
- [ ] Somar o valor antecipado com o valor da parcela atual
- [ ] Permitir excluir uma parcelamento
- [ ] Permitir antecipar parcelas
- [ ] Validar se o valor é maior que 0
- [ ] Validar se o nome não está vazio
- [ ] Validar se a forma de pagamento foi selecionada 
- [ ] Validar se a categoria foi selecionada 
- [ ] Data deve ser inserida automaticamente com a data da adição

**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de cadastrar parcelas financeiras.
- [ ] O usuário deve ser capaz de visualizar as parcelas financeiras.
- [ ] O usuário deve ser capaz de editar as parcelas financeiras quando acabado de criar e/ou ainda na primeira parcela.
- [ ] O usuário deve ser capaz de excluir as parcelas financeiras.
- [ ] O usuário deve ser capaz de antecipar parcelas financeiras.


### Feature 1.1.4 - Cadastro de categorias

#### Story 1.1.4.1

Eu, como usuário, quero cadastrar categorias para que eu possa organizar minhas movimentações diárias.

**Tasks**

- [ ] Criar a entidade Categoria
- [ ] Permitir informar valores de: nome, descrição e cor
- [ ] Exibir listagem das categorias ordenadas por nome
- [ ] Permitir editar uma categoria
- [ ] Permitir excluir uma categoria
- [ ] Validar se o nome não está vazio
- [ ] Validar se a descrição não está vazia
- [ ] Validar se a cor foi selecionada

**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de cadastrar categorias.
- [ ] O usuário deve ser capaz de visualizar as categorias.
- [ ] O usuário deve ser capaz de editar as categorias.
- [ ] O usuário deve ser capaz de excluir as categorias.

### Feature 1.1.5 - Extrato financeiro

#### Story 1.1.5.1

Eu, como usuário, quero visualizar o extrato financeiro para que eu possa ter controle sobre minhas movimentações diárias.

**Tasks**

- [ ] Criar a entidade Extrato
- [ ] Exibir listagem das movimentações ordenadas por data
- [ ] Exibir saldo atual da conta
- [ ] Implementar filtro por tipo (Entrada, Saída, Parcelamento)
- [ ] Implementar filtro por ano e mês
- [ ] Implementar filtro por categoria
- [ ] Implementar filtro por forma de pagamento
- [ ] Implementar filtro por tipo de gasto
- [ ] Implementar pesquisa por nome

**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de visualizar o extrato financeiro.
- [ ] O usuário deve ser capaz de filtrar o extrato financeiro por tipo.
- [ ] O usuário deve ser capaz de filtrar o extrato financeiro por ano e mês.
- [ ] O usuário deve ser capaz de filtrar o extrato financeiro por categoria.
- [ ] O usuário deve ser capaz de filtrar o extrato financeiro por forma de pagamento.
- [ ] O usuário deve ser capaz de filtrar o extrato financeiro por tipo de gasto.
- [ ] O usuário deve ser capaz de pesquisar no extrato financeiro por nome.

### Feature 1.1.6 - Simular gasto

#### Story 1.1.6.1

Eu, como usuário, quero simular um gasto antes de realiza-lo para que eu possa ter previsao sobre minhas finanças.

**Tasks**

- [ ] Verificar se o gasto impacta em ate 30% do orçamento mensal disponivel (Renda - Gastos Fixos)
- [ ] Permitir simular parcelamento de gastos
- [ ] Avisar se o gasto está dentro do orçamento mensal (Renda - Gastos Fixos)
- [ ] Mostrar qual seria o novo orçamento apos o gasto
- [ ] Mostrar qual sera o novo limite diario (Renda - Gastos Fixos - Gasto) / dias_mes

**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de simular um gasto antes de realiza-lo.
- [ ] O usuário deve ser capaz de simular parcelamento de gastos.
- [ ] O usuário deve ser capaz de visualizar o novo orçamento apos o gasto.
- [ ] O usuário deve ser capaz de visualizar o novo limite diario apos o gasto.

# Theme 2 - Orçamento Diario e Reserva

## Epic 2.1 - Limite Diário de Gastos

### Feature 2.1.1 - Definição de Limite Diário

#### Story 2.1.1.1

Eu, como usuario, quero que o sistema me informe meu limite diário de gastos para que eu possa ter controle sobre minhas movimentações diárias. 

**Tasks**

- [ ] Criar a entidade LimiteDiario
- [ ] Calculo do orçamento do limite diário deve serguir: (renda_mensal - gastos_fixos_mensais) / dias_mes 
- [ ] Atualizar limite com os gastos do dia
- [ ] O valor do limite diário nao pode ser 0, caso seja, alertar usuário
- [ ] O usuário deve ser capaz de ajustar o orçamento maximo do limite diário para um valor menor, assim ficando abaixo do calculado automaticamente

**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de visualizar o limite diário de gastos.
- [ ] O sistema deve calcular o limite diário de gastos automaticamente.
- [ ] O sistema deve atualizar o limite diário de gastos automaticamente.

### Feature 2.1.2 - Controle da Reserva

#### Story 2.1.2.1

Eu, como usuario, quero que o que eu não gaste do meu limite diário seja transferido para uma reserva para que eu possa usar em caso de emergência. 

**Tasks**

- [ ] Criar a entidade Reserva
- [ ] Caso o usuário não gaste o limite diário, o valor restante deve ser transferido para a reserva
- [ ] Caso o usuário exceda o limite diário, o valor é automaticamente debitado da reserva

**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de visualizar o saldo da reserva.
- [ ] O sistema deve calcular o saldo da reserva automaticamente.
- [ ] O sistema deve atualizar o saldo da reserva automaticamente.

### Feature 2.1.3 - Controle do Extra

#### Story 2.1.3.1

Eu, como usuario, quero que caso eu ultrapasse o limite diário e a reserva esteja zerada, fique com saldo negativo marcado como extra. 

**Tasks**

- [ ] Criar a entidade Extra
- [ ] Caso o usuário ultrapasse o limite diário e a reserva esteja zerada, o valor excedente deve ser marcado como extra
- [ ] Caso ocorra um gasto extra, o calculo do limite diario deve ser refeito descontando o valor extra


**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de visualizar o saldo da reserva.
- [ ] O sistema deve calcular o saldo da reserva automaticamente.
- [ ] O sistema deve atualizar o saldo da reserva automaticamente.


# Theme 3 - Gamificação Financeira

## Epic 3.1 - Mecânica de Incentivo

### Feature 3.1.1 - Wallet

#### Story 3.1.1.1

Eu, como usuario, quero que o sistema me informe o estado da minha carteira, para que eu possa ter controle sobre minhas movimentações diárias. 


**Tasks**

- [ ] Criar a entidade Carteira
- [ ] A carteira deve mostrar quanto ja foi gasto no dia
- [ ] A carteira deve mostrar quanto falta para o limite diario
- [ ] A carteira deve mostrar o limite diario
- [ ] A carteira deve mostrar o saldo da reserva
- [ ] A carteira deve mostrar se há saldo do extra

**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de visualizar o saldo da carteira.
- [ ] O sistema deve calcular o saldo da carteira automaticamente.
- [ ] O sistema deve atualizar o saldo da carteira automaticamente.

### Feature 3.1.2 - Progresso na economia

#### Story 3.1.2.1

Eu, como usuario, quero que o sistema me mostre meu progresso na economia, para que eu possa ter controle sobre minhas movimentações diárias. 


**Tasks**

- [ ] Criar indicador visual de progresso, sequencia de dias dentro do limite
- [ ] Calendario com os dias dentro do limite e da reserva, quebra a sequencia apenas quando atinge o extra
- [ ] Mensagens de feedback para o usuário, parabenizando por manter o controle e alertando quando ultrapassar o limite

**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de visualizar o progresso na economia.
- [ ] O sistema deve calcular o progresso na economia automaticamente.
- [ ] O sistema deve atualizar o progresso na economia automaticamente.
- [ ] O sistema deve enviar mensagens de feedback para o usuário.
- [ ] O sistema deve quebrar a sequencia de progresso quando o usuário atingir o extra.

### Feature 3.1.3 - Alertas 

#### Story 3.1.3.1

Eu, como usuario, quero que o sistema me envie alertas sobre meu comportamento de gastos, para que eu possa ter controle sobre minhas movimentações diárias. 

**Tasks**

- [ ] Criar alertas de aproximação de 70% do limite diário
- [ ] Criar alertas de atingiu o limite diário
- [ ] Criar alertas de uso de 50% da reserva
- [ ] Criar alertas de uso de 80% da reserva
- [ ] Criar alertas de esgotou a reserva

**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de receber alertas.

# Theme 4 - Dashboard

## Epic 4.1 - Visão Geral

### Feature 4.1.1 - Dashboard principal

#### Story 4.1.1.1

Eu, como usuario, quero que o sistema me mostre um dashboard com a visão geral das minhas movimentações financeiras, para que eu possa ter controle sobre minhas movimentações diárias. 

**Tasks**

- [ ] Criar a entidade Dashboard
- [ ] O dashboard deve mostrar o saldo de entradas
- [ ] O dashboard deve mostrar o saldo de saidas variaveis
- [ ] O dashboard deve mostrar o saldo de saidas fixas
- [ ] O dashboard deve mostrar o saldo de quanto ainda nao foi gasto (entradas - saidas)

**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de visualizar o dashboard.

### Feature 4.1.2 - Dashboard por categoria

#### Story 4.1.2.1

Eu, como usuario, quero que o sistema me mostre um gráfico de gastos por categoria, para que eu possa ter controle sobre minhas movimentações diárias. 

**Tasks**

- [ ] Criar a entidade DashboardCategoria
- [ ] O dashboard deve mostrar um gráfico de gastos por categoria

**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de visualizar o dashboard.

### Feature 4.1.3 - Dashboard por tendencia de gastos por dia

#### Story 4.1.3.1

Eu, como usuario, quero que o sistema me mostre um gráfico de tendencia de gastos por dia, para que eu possa ter controle sobre minhas movimentações diárias. 

**Tasks**

- [ ] Criar a entidade DashboardTendencia
- [ ] O dashboard deve mostrar um gráfico de gastos por dia

**Critérios de Aceite:**
- [ ] O usuário deve ser capaz de visualizar o dashboard.

# Theme 5 - Mensageria e Linguagem Natural

## Epic 5.1 - Registro de Ações por mensagens

### Feature 5.1.1 - Integrar Provider de Mensageria

#### Story 5.1.1.1

Eu, como usuario, quero que o sistema me permita registrar entradas por mensagens, para que eu possa ter controle sobre minhas movimentações diárias. 

**Tasks**

- [ ] Configurar o Celery como broker de tarefas assíncronas no projeto
- [ ] Criar task Celery para enviar mensagens do usuário para a API da OpenAI
- [ ] Montar o JSON estruturado com as mensagens do usuário e o contexto das tools disponíveis
- [ ] Enviar o JSON estruturado para a API da OpenAI via requisição assíncrona
- [ ] Fazer o parsing da resposta JSON da OpenAI para identificar quais tools devem ser executadas
- [ ] Validar o formato da resposta da OpenAI (verificar se contém tools válidas)
- [ ] Implementar tratamento de erros para falhas na comunicação com a API da OpenAI (timeout, rate limit, resposta inválida)
- [ ] Implementar retry automático na task Celery em caso de falha transitória
- [ ] Executar as tools retornadas pela OpenAI e retornar o resultado ao Provider de mensageria
- [ ] Criar testes unitários para a task Celery de integração com a OpenAI
- [ ] Criar testes de integração para o fluxo completo (mensagem → Celery → OpenAI → tools → resposta)


**Critérios de Aceite**
- [ ] O sistema deve receber mensagens em linguagem natural do Provider de mensageria (ex: "recebi 100 reais de salario")
- [ ] O sistema deve processar as mensagens de forma assíncrona via Celery
- [ ] O sistema deve enviar as mensagens junto a um JSON estruturado para a API da OpenAI
- [ ] O sistema deve interpretar corretamente a resposta JSON da OpenAI com as tools a serem executadas
- [ ] O sistema deve executar as tools indicadas e retornar o resultado ao usuário
- [ ] O sistema deve tratar erros de comunicação com a API da OpenAI de forma resiliente


### Feature 5.1.2 - Tools

#### Story 5.1.2.1

Eu, como usuario, quero que o sistema me permita por mensagens executar as mesmas funcionalidades que tenho na interface web, para que eu possa ter controle sobre minhas movimentações diárias. 

**Tasks**

- [ ] Tool de criação de entrada
- [ ] Tool de criação de saída
- [ ] Tool de criação de parcelamento
- [ ] Tool de edição de entrada
- [ ] Tool de edição de saída
- [ ] Tool de edição de parcelamento (seguindo a regra de negocio)
- [ ] Tool de exclusão de entrada
- [ ] Tool de exclusão de saída
- [ ] Tool de exclusão de parcelamento
- [ ] Tool de simular gasto
- [ ] Tool de listar extrato
- [ ] Tool de listar entradas
- [ ] Tool de listar saídas
- [ ] Tool de listar parcelamentos 

**Critérios de Aceite**
- [ ] O sistema deve permitir que o usuário execute as mesmas funcionalidades que tem na interface web por mensagens