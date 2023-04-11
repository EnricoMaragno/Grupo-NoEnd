# Missão

* Desenvolver um sistema de gerenciamento de chamados, voltado para a parte administrativa da empresa, onde o funcionario possa monitorar os chamados abertos fechados e em espera.

# Quem ira utilizar?

1- Funcionarios, podem abrir chamados internos, vão monitorar os chamdos, respondendo e encaminhando informações para os clientes.

2- Clientes, podem abrir chamados externos e capacidade de acompanhar os chamados em andamento.

# Onde?

* Para melhoria do sistema atual da empresa, que no momento não é orientada a chamdos, dificultando a comunicação com o cliente e entre os setores da empresa.

# Por que?

* Para que ocorra de maneira mais fácil a comunicação entre a empresa e o cliente, possibilitando responder os clientes mais rapidamente.

# Requisitos funcionais:

## Login e Cadastro de usuários.
  1- O sistema deve possuir um autenticador de cadastro.
  
  2- O sistema deve possuir um login e senha diferente para cada usuário de cada departamento.
  
  3- Apenas usuários do setor de tecnologia tem a permissão para cadastrar novos usuários.
  
  4- O sistema deve ter uma listagem com clientes cadastrados.
  
  5- O sitema deve exigir email corporativo e senha para logar.
## Interface de chamados.

  1- O sistema deve possuir uma interface que mostre os chamados abertos, concluidos e em espera.
  
  2- O sistema deve possuir um botão para abrir chamados na interface principal.
  
  3- O sistema deve possuir um prazo pré determinado para que o chamado continue aberto. Depende da categoria de chamado, problema-30min, agendado-48h.
  
  4- O sistema deve possuir uma área de chamados internos para comunicação entre os departamentos.
  
  5- O sistema deve armazenar informações como nome, tipo de chamado, número de celular.
  
  6- O sistema deve separar os chamados pelo nível critico deles. (Critico, alto, medio, baixo)
  
  7- O sistema deve possuir um dashboard para cada departamento, depensendo do seu nível de acesso.
  
  8- O sistema deve possuir a descriçlão do chamado, por título, nível critico e o departamento que abriu o chamado.

















9- O sistema guardará os sistemas em logs.



11- Error 500 se não tiver conexão com o servidor.

12- O sistema deve separar os chamados pelo nível critico deles.

# Requisitos não funcionais
```
1- O software deve ser desenvolvido para WEB, podendo ser utilizado no celular.

2- Não tera integração com nenhum outro sistema da empresa.

3- O sistema deve ser capaz de gerenciar cerca de 7 usuários simultaneamente.

4- O sistema deve ser responsivo.

5- Seguir as normas SLA, proteger contratado e contratante, além de dar maior credibilidade e confiabilidade à relação.

6- O sistema deve ser desenvolvido em ReactJS.

7- Quando o servidor ficar indisponivel deve ter um timeout.
```
