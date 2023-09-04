---
sidebar_position: 1
---

# Cadastro de representantes legais

Essa jordana representa a tela de cadastro de representantes legais

### Do Usuário

- O usuário poderá incluir um novo representante legal informando os campos : nome, sobrenome,email, cpf, data de nascimento, sexo, telefone, documento de identificação , orgão emissor, logradouro, cep, número, complemento, bairro, cidade
- O usuário deverá selecionar o perfil do novo representante
- O novo representante receberá a senha do primeiro acesso no email cadastrado
- O usuario poderá salvar o representante legal clicando em "Salvar"
- O usuário poderá cancelar o preenchimento do formulário clicando em "Cancelar"


### Do Sistema
- O sistema deverá validar se os campos obrigatórios foram preenchido
- O sistema deverá consultar o endereço pelo CEP
- Caso o usuário não saiba o cep o sistema deverá direciona-lo para a pagina dos correios
- O sistema deverá gerar uma senha aleatória e enviar ela para email do novo representante com as instruções de troca de senha
- O sistema deverá direcionar o usuário para a jornada de Listagem de Representande com a notificação "representante cadastrado com sucesso"
- O sistema deverá salvar o formulário ao clique no botão "Salvar"
- O sistema deverá limpar o formulário e retornar o usuário para a jornada de Listagem de representantes ao clique no botão "Cancelar"