# Alunos

## Cenário principal
As opções dos alunos serão geradas mediante o cadastramento da pessoa física quando a mesma optar pela opção “efetuar matrícula”. Após a quitação dos encargos financeiros, o sistema atribui em questão um ID de matrícula, como também solicitará o complemento dos dados; Nome Completo, Data de Nascimento, Dados Financeiros, Endereço.
- **Atores:** Alunos.
- **Pré-condição:** O aluno deve ter realizado o cadastro de pessoa física na instituição, conforme solicitado pelo sistema, preenchendo os campos de e-mail e criando uma senha pessoal.
- **Pós-condição:** Após a validação dos encargos financeiros para com a compra do usuário realizado e o preenchimento dos campos necessários para a finalização do cadastro, o sistema irá liberar o acesso do usuário. Disponibilizando todo o material incluso no AVA para os alunos que tiverem o seu ID de matrícula autorizado e aprovado.

### Cenário 1 (alternativo)
Diante de uma situação onde o aluno não esteja numa situação positiva para com os seus encargos financeiros juntamente com a instituição, o sistema enviará por e-mail sinalizando ao usuário o cenário atual e informará que o mesmo terá um prazo para normalizar sua situação. Caso não tenha realizado algum acordo ou quitação, o sistema bloqueará o acesso do AVA e informará novamente ao usuário o motivo da paralisação, garantindo o retorno ao acesso somente após a regularização da pendência.
- **Atores:** Alunos.
- **Pré-condição:** O aluno deve estar com pendência financeira, o que irá acionar um alerta dentro do uso do mesmo no sistema. Será realizada também a contagem dos dias permitidos pela instituição para ter o acesso liberado ao AVA.
- **Pós-condição:** Diante de algum encargo financeiro atrelado ao ID de matrícula, o sistema restringe o acesso do usuário e direciona tanto na interface do sistema como pelos canais de comunicação informando o cenário atual do aluno e transmitindo as opções cabíveis para cada caso.