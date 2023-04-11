Casos de Uso: Caso de Login 
Título : Cadastro dos usuários no sistema de login da empresa.

Descrição: O sistema irá exigir Email corporativo e senha para cadastrar o novo usuário, facilitando assim a autenticação dos novos usuários.

Ator primário; usuário (Funcionário do sistema).

Pré-condições: o usuário deve possuir um login e senha diferente. Vale ressaltar que apenas usuários do setor de tecnologia tem a permissão para cadastrar novos usuários.

Condição seguinte: após entrar no sistema, o usuário será levado para a interface principal onde terá um botão para abrir o chamado. Após isso o seu chamado será agendado em no máximo 48 hrs.

Melhor cenário de implementação: o usuário introduz os dados no sistema, e é validado pelo sistema de autenticador de cadastro.

Extensões: O sistema irá estabelecer uma mensagem de erro (seja por erro no cadastro ou por falha na autenticação),então o sistema irá dar um refresh para a tela de login com as mesmas operações.

Frequência de uso: 24 horas por dia, ao conectar numa máquina nova ou reentrar na mesma após desligada.

Dono: Apenas usuários do setor de tecnologia tem a permissão para cadastrar novos usuários, porém todos os funcionários tem permissão para entrar por login, seguindo os requisitos acima.

Prioridade: Essencial.

