---
sidebar_position: 5
---

# Ativação/Desativação de funcionários

Essa jornada representa a desativação de um funcinário

### Do Usuário
- O usuário selecionará o usuário que desaja desativar e deverá confirmar essa desativação na modal apresentada digitando o primeiro nome do funcionário e clicando em "Desativar" ou "Ativar"


### Do Sistema
- O sistema deverá apresentar uma modal com o texto "Tem certeza que deseja desativar/ativar o funcionário <<nome_funcionario>>", com um input para que o usuário digite o primeiro nome do funcionário para habilitar a desativação com os botões de confirmar e cancelar
- Em caso de desativação o sistema deverá apresentar na modal aberta um alerta informando que o usuário ficará ativo até o fechameto do mês recorrente(data de fechamento da fatura atual)
- Em caso de ativação o sistema deverá apresentar na modal aberta um alerta informando que o valor de cobrança poderá soferer alteração a partir daquele mês
- Após a confirmação o sistema deverá direcionar o usuário para tela de listagem de funcionários com uma notificação "Desativação/Ativação realizada com sucesso"