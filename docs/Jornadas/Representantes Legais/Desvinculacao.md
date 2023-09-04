---
sidebar_position: 1
---

# Desvinculaão de representantes legais

Essa jordana representa a jornada de desvinculação do representante legal desse usuário

### Do Usuário
- O usuário selecionará o representante que desaja desvincular e deverá confirmar essa desativação na modal apresentada digitando o primeiro nome do representante e clicando em "Desvincular"


### Do Sistema
- O sistema deverá apresentar uma modal com o texto "Tem certeza que deseja desvincular o representante <<nome_do_representante>>", com um input para que o usuário digite o primeiro nome do representante para habilitar a desvinculação com os botões de confirmar e cancelar
- Em caso de desvinculação o sistema deverá apresentar na modal aberta um alerta informando que o usuário do representante ficará ativo até o fechameto do mês recorrente(data de fechamento da fatura atual)
- Após a confirmação o sistema deverá direcionar o usuário para tela de listagem de representantes com uma notificação "Desvinculação realizada com sucesso"