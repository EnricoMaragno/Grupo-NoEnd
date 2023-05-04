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


--------------------------------------------------------------
Casos de Uso:  Abertura de um Chamado 
Título : sistema orientado a chamado.

Descrição: O cliente irá conceder seus dados ao usuário do setor de tecnologia, que irá inserir os dados ,assim estruturando o chamado.

Ator primário;  Funcionário do sistema.

Pré-condições: o chamado constar no sistema que foi aberto

condição seguinte: após o chamado constar no sistema, ele deve possuir suas respectivas informações tais como o nome do cliente que solicitou o chamado , seu número de celular e também o motivo do chamado , evidentemente na área da empresa o qual solicita ajuda. 

Melhor cenário de implementação: o usuário introduz os dados no sistema, é validado pelo sistema de autenticador de cadastro, os dados constarem no dashboard do chamado, consequentemente o chamado será agendado em menos de 48 hrs.

Extensões:.O sistema deve possuir a descrição do chamado, por título, nível crítico( alto, medio, baixo) e o departamento que abriu o chamado, tendo este um dashboard para cada , dependendo do seu nível de acesso.

Frequência de uso: 24 horas por dia, sendo o chamado agendado até 48 horas.

Dono: Apenas usuários do setor requisitado pelo cliente terá direção e aptidão para resolver o problema solicitado.

Prioridade: Essencial.

