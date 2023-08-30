---
sidebar_position: 4
---

# Ativar/Desativação de serviços

Essa jornada representa a desativação de um serviço

<mark>OBS.: ACRESCENTAR O CAMPO "status" NA TABELA DE SERVICOS</mark>

### Do Usuário
- O usuário selecionará o serviço que desaja ativar/desativar e deverá confirmar essa ativação/desativação na modal apresentada clicando em "Desativar" ou "Ativar"


### Do Sistema
- O sistema deverá apresentar uma modal com o texto "Tem certeza que deseja desativar/ativar o serviço <<nome_servico>>", com os botões de confirmar e cancelar
- Após a confirmação o sistema deverá direcionar o usuário para a jornada de listagem de serviços com uma notificação "Desativação/Ativação realizada com sucesso"
- Após o cancelamento o sistema deverá fechar a modal aberta