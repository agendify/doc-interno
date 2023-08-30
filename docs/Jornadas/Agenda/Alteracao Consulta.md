---
sidebar_position: 1
---

# Alteração de Marcação

Essa jordana representa a tela/modal onde o usuário poderá alterar uma marcação

### Do Usuário

- Poderá escolher um novo dia/horário/prestador de serviço daquela marcação
- Poderá salvar a marcação com as devidas alteração clicando no botão "Salvar"
- Poderá cancelar as alterações clicando no botão "Cancelar"

### Do Sistema
- Deverá trazer as informações do agendamento selecionado
- Deverá permitir a alteração do dia, horário e prestador de serviço
- Deverá validar se a data selecionada está dentro do range dos campos "tempo_min_antecedencia_minutos" e "tempo_max_antecedencia_dias" na tabela de configuracao_agenda
- Deverá direcionar o usuário para a tela de agenda com a notificação "Alteração feita com sucesso"