---
sidebar_position: 3
---

# Finalização do cadastro
### Do Usuário
Nessa jornada será chamada quando o usuário de perfil admin efetuar o primeiro login. 
 - O cadastro poderá ser para PF ou PJ
 - Caso seja PJ o usuário também deverá informar os dados de um PF( representante legal) que será o usuário admin do sistema.
 - Deverá cadastrar o endereço do PJ e PF
 - Deverá selecionar o plano de contratação( a principio teremos apenas 1 plano no valor de R$ 250,00/mês com 5 usuários e cada usuário a mais será cobrado o valor de R$ 50,00/mês)
 - Deverá selecionar o seguimento de serviço dele( Clínica / Salão / Barbearia/ Prestador de Serviço)
 - Deverá informar os dados do cartão de crédito para cobrança
 
### Do Sistema
- O sistema deverá consultar o endereço pelo CEP, em caso da pessoa não saber o cep deverá direcionar o usuário para a tela de pesquisa nos correios
- Ao final do cadastro o usuário deverá ser direcionado para a tela de home
- No cadastro de PJ o sistema receberá tanto dados do PJ quando do PF(representante legal)
- Deverá permitir o usuário informar apenas um endereço para o PJ e PF
- Deverá validar o cartão de crédito do usuário
- Deverá dar um periodo gratis de 15 dis para o usuário e começar a cobrança a partir do 16 dia 