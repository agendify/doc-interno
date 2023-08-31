---
sidebar_position: 4
---

# Ativar/Desativação de Categorias

Essa jornada representa a desativação de um serviço

### Do Usuário
- O usuário selecionará a categoria que desaja ativar/desativar e deverá confirmar essa ativação/desativação na modal apresentada clicando em "Desativar" ou "Ativar"

### Do Sistema
- O sistema deverá apresentar uma modal com o texto "Tem certeza que deseja desativar/ativar a categoria <<nome_categoria>>", com um alerta informando que essa ação ativara/desativara todos os serviços vinculados a aquela categoria e com os botões de confirmar e cancelar
- Após a confirmação o sistema deverá direcionar o usuário para a jornada de listagem de categorias com uma notificação "Desativação/Ativação realizada com sucesso"
- Após a ativação/desativação o sistema deverá ativar/desativar todos os serviços vinculados para aquela categoria
- Após o cancelamento o sistema deverá fechar a modal aberta