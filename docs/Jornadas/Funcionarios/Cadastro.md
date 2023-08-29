---
sidebar_position: 2
---

# Cadastro

Essa jordana representa a inserção de novos funcionárioos pelo contratante de serviço

### Do Usuário

 - Deverá informar o nome, sobrenome, data de nascimento, sexo, telefone, numero do documento de identificação e seu orgão emissor, email, perfil de acesso, cep, logradouro, numero, complemento, bairro, cidade e UF


### Do Sistema
- O sistema deverá consultar o endereço pelo CEP, em caso da pessoa não saber o cep deverá direcionar o usuário para a tela de pesquisa nos correios
- Ao final do cadastro do funcionário o usuário deverá ser direcionado para a tela de lista de funcionário com uma notificação e "Cadastro finalizado com sucesso"
- O sistema permitirá apenas funcionário PFs, caso o contratante de serviço tenha contrato com PJs deverá ser cadastrados os PFs dessas empresas parceiras
- O sistema deverá validar se os campo obrigatórios estão preenchidos
- Deverá consultar se o CPF é válido
- Deverá consultar se o email já está em uso por um usuário ativo
- O sistema deverá gerar uma senha automatica e encaminha-la no email do funcionário com as instruções de como efetuar a troca de senha no primeiro acesso
- O sistema populará as tabelas usuario, pessoa_fisica, endereco e funcionario