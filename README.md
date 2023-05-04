 # Missão: 
 O sistema tem como objetivo gerenciar os chamados.


# Cliente: 
Empresa que atua na áerea de tecnologia destinada a área industrial(comentado na reunião)


# Requisitos funcionais:(adicionar mais)

1- O sistema deve gerenciar os chamados que são recebidos pela empresa;

2- O sistema deve mostrar a situação em que os chamados se encontram;(ajeitar)

3- O sistema deve ter um recurso em que ele próprio deve identificar os casos de acordo com  "gravidade" dele;

4- O sistema deve possuir um dashboard para cada departamento.

5- O sistema deve possuir uma área de chamados internos para comunicação entre os departamentos;

5- O sistema deve armazenar informações como nome, tipo de chamado, número de celular;

6- O sistema deve emitir um relátorio dos usuários ;

7- O sistema deve controlar o número de chamados;

8- O sistema deve contabilizar o número de chamados;


# Requisitos não funcionais:

1- O software deve ser desenvolvido para WEB, podendo ser utilizado no celular.

2- Não tera integração com nenhum outro sistema da empresa.

3- O sistema deve ser capaz de gerenciar cerca de 10 usuarios simultaneamente.

4- O sistema deve ser responsivo.

5- Seguir as normas SLA, proteger contratado e contratante, além de dar maior credibilidade e confiabilidade à relação.

6- O sistema deve ser desenvolvido em ReactJS


# 5W2H

O que?:O sistema deve ter controle sob os chamados que a empresa recebe;

Quem?:Os usuários como também os trabalhadores da própria empresa

Porque?: O sistema vai funcionar como um facilitador para a empresa controlar as informações recebidas;

Como?: O sistema irá administrar a quantia de chamados e sua procedencia além de criar um dashboard com tais informações;

Onde?: Via WEB, com "suporte" para navegadores no Desktop e mobile

Quando?: Deverá ser finalizado no primeiro semestre de 2023;

Quanto?: Não haverá financero, apenas com equipe se dedicando;




Perguntas Miriam:

- Quem vai manusear o software? O cliente ou um funcionário?
Ex: O cliente abriria o chamado para o funcionário? Ou vice-versa?

- O que aconteceria se tivessem mais de 7 pessoas interagindo com o software? Nós colocaríamos o site com uma fila de espera?


Sobre usuários e permissões, quais permissões terão os usuários de casa setor?



# Missão

* O sistema tem como objetivo gerenciar e organizar os chamados internos e externos da empresa.

# Quem irá utilizar?

* Qualquer pessoa que tiver acesso ao Software, no qual as pessoas se comunicam via chamado. Para tanto, se qualquer integrante do departamento comercial etiver tendo entraves, irá acionar o software pelo seu dispostivo "mobile" ou fixo, e assim, será direcionado ao dashboard geral. Dessa forma, dependendo de como o usuário maneja o software, este poderá categorizar o chamado após ter sido solicitado. Logo, após ter sido requisitado pelo departamento de TI, os próprios funcionários abririam chamado.

# Onde?

O sistema deve funcionar tanto em computadores como em dispositivos móveis.

# Por que?

* Para que ocorra de maneira mais fácil a comunicação entre a empresa e o cliente, possibilitando responder os clientes mais rapidamente.

# Quem?

* Empresa Microméros Tecnologias que atua no setor industrial. A empresa fornece a infraestrutura, a instalação e a manutenção dos sensores, e fornece relatorios com os dados coletados, por meio de gráficos, telas e dashboards. A Microméros atua no meio industrial, atendendo fábricas, transportadoras, etc.

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
  
  3- O sistema deve possuir um prazo pré determinado para que o chamado continue aberto. Depende da categoria de chamado, problemas em 30min, agendados em 48h.
  
  4- O sistema deve possuir uma área de chamados internos para comunicação entre os departamentos.
  
  5- O sistema deve armazenar as seguintes informações dos chamados: nome do usuário que abriu o chamado, número de celular, email, motivo do chamado.
  
  6- O sistema deve separar os chamados pelo nível critico deles. (Critico, alto, medio, baixo)
  
  7- O sistema deve possuir um dashboard para cada departamento, depensendo do seu nível de acesso.
  
  8- O sistema deve possuir a descriçlão do chamado, por título, nível critico e o departamento que abriu o chamado.

# Requisitos não funcionais

1- O software deve ser desenvolvido para WEB, podendo ser utilizado no celular.

2- Não tera integração com nenhum outro sistema da empresa.

3- O sistema deve ser capaz de gerenciar cerca de 10 usuarios simultaneamente.

4- O sistema deve ser responsivo.

5- Seguir as normas SLA, proteger contratado e contratante, além de dar maior credibilidade e confiabilidade à relação.

6- O sistema deve ser desenvolvido em ReactJS.





Fluxo principal: O usuário acessa o sistema de abertura de chamados. O sistema apresenta uma tela com opções para o usuário selecionar o tipo de problema que está enfrentando, como "problemas de hardware", "problemas de software" ou "problemas de rede". O usuário irá selecionar o tipo de problema que está enfrentando. O sistema apresenta uma tela com mais detalhes sobre o tipo de problema selecionado e solicita que o usuário forneça mais informações sobre o problema, como uma descrição detalhada do que está acontecendo e uma captura de tela. O usuário preenche as informações solicitadas e envia o chamado. O sistema confirma o recebimento do chamado e fornece um número de referência para que o usuário possa acompanhar o status do chamado. O sistema encaminha o chamado para o departamento ou técnico responsável pelo tipo de problema relatado. O técnico ou departamento responsável pelo problema recebe o chamado e começa a trabalhar na solução.O técnico ou departamento responsável atualiza o status do chamado regularmente fornece uma resposta para o usuário. O sistema notifica o usuário quando a resposta for enviada.
