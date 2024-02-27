# Professores

## Cenário principal: 
Os professores devem realizar o cadastro com usuário e senha. O sistema por sua vez irá verificar as credenciais e liberar o acesso ao corpo docente da instituição.
- **Atores:** Professores.
- **Pré-condição:** O sistema está ativo e o usuário tem permissão para acessar a função de cadastro de professores.
- **Pós-condição:** As informações do professor são registradas no sistema de forma correta.

### Cenário 1 (alternativo): 
Caso o professor não preencha os dados corretamente ou deixe de acrescentar os dados obrigatórios na etapa 3 do fluxo principal, o sistema exibirá uma mensagem de erro. O professor deve preencher todos os campos obrigatórios, com as informações corretas.
- **Atores:** Professores.
- **Pré-condição:** O sistema impede o cadastro do professor, se ele digitar dados incorretos ou omitir algum campo.
- **Pós-condição:** O sistema pede ao professor que reveja os dados fornecidos nos campos obrigatórios e preencha os que estiverem vazios.

### Cenário 2 (alternativo): 
Ainda na etapa 3 do fluxo principal, se o professor já for cadastrado neste sistema, ele será notificado. A mensagem remete ao cadastro já realizado por parte deste profissional, induzindo-o a realizar o login na instituição ou revisar suas informações.
- **Atores:** Professores.
- **Pré-condição:** O sistema notifica o professor de que o seu cadastro já foi realizado nesta instituição.
- **Pós-condição:** O sistema sugere ao professor que realize o login com seu usuário e senha ou revise os devidos dados fornecidos.
