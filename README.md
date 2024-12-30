Trabalho Final Algoritmos:
Sistema para Academia
* Individual ou em duplas *

Você foi contratado(a) para desenvolver um sistema para uma academia de musculação. O objetivo de seu programa é possibilitar que o administrador da academia gerencie o cadastro dos alunos, bem como os exercícios de seus respectivos treinos.

Abaixo, são detalhadas as opções que devem estar presentes no menu principal.

 

1 - Cadastrar aluno
O cadastro de um aluno contempla os seguintes dados:

Nome;
CPF;
Peso;
Altura;
Status: valor booleano que indica se o aluno encontra-se com matrícula ativa no momento (True) ou não (False). No momento do cadastro, não é necessário que o administrador informe este dado, pois o sistema deverá setá-lo automaticamente com o valor False.
A lista de alunos da academia deve ser mantida em um vetor. A cada novo aluno, deve ser inserida também uma nova linha na matriz de treinos, conforme explicado abaixo.

2 - Gerenciar treino
Cada aluno será vinculado a um treino, que corresponde a uma lista de até 10 exercícios. Cada exercício do aluno é representado pelas seguintes informações:

Nome do exercício;
Número de repetições;
Peso utilizado no exercício.
A partir da opção Gerenciar treino do menu principal, o administrador deve realizar uma busca pelo aluno cujo treino deve ser editado. As opções possíveis são:

incluir um novo exercício no treino do aluno (caso este ainda não exista);
alterar um exercício existente no treino, editando suas informações;
excluir um exercício específico do treino do aluno;
excluir todos os exercícios do treino do aluno.
Todas as operações devem realizar validações e/ou verificações (ex: não permitir a inclusão do mesmo exercício mais de uma vez; verificar se um exercício existe antes de editar/excluir, etc.). Mensagens apropriadas devem ser exibidas para cada situação.

Ao finalizar cada operação, o campo status do respectivo aluno deve ser atualizado: se seu treino possui pelo menos um exercício, o status será True; se o treino estiver vazio, o status deve ser False.

Os treinos de todos os alunos da academia são armazenados em uma única matriz. A correspondência entre o vetor de alunos e a matriz de treinos se dá pelo número do índice da linha (isto é, o aluno armazenado no índice 5 do vetor de alunos tem seu treino armazenado na linha 5 da matriz de treinos).

3 - Consultar aluno
Permite buscar um aluno pelo nome. Se o aluno existe, o sistema exibe seus dados de cadastro, bem como uma tabela com todos os exercícios constantes em seu treino. Se a busca não encontrou nenhum aluno, uma mensagem deve ser exibida.

4 - Atualizar cadastro do aluno
Permite que os dados de um determinado aluno sejam atualizados.

5 - Excluir aluno
Permite buscar um aluno pelo nome e remover seu cadastro e seu treino. Solicitar confirmação antes da exclusão.

6 - Relatório de alunos
Ao acessar esta opção, o sistema deve perguntar o que o administrador deseja visualizar: todos os alunos, somente alunos ativos ou somente alunos inativos. Em seguida, exibir a lista de alunos, filtrados conforme opção descrita acima. A lista deve vir ordenada pelo nome do aluno.

 

Avaliação
1 - Execução correta e boa explicação: 80%

Serão feitos vários testes durante a apresentação.
2 - Estilo de programação: 10%

Código comentado (sem excesso), bem estruturado, nomes de variáveis significativas, etc.
Devem ser utilizadas funções para cada operação (ex: função cadastrar, função buscar, etc.)
3 - Opções adicionais para melhorar a funcionalidade básica da aplicação: 10%

Por exemplo: implementar validação de cpf, cálculo do IMC na consulta do aluno, etc.
Trabalhos iguais irão resultar em nota igual à zero para todos os envolvidos