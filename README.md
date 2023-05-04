# Missão

* O sistema tem como objetivo gerenciar e organizar os chamados internos e externos da empresa.

# 5W2H

## O que?

* O sistema deve ter controle sob os chamados que a empresa recebe.

## Quem?

* Os usuários como também os trabalhadores da própria empresa.

## Porque?

* O sistema vai funcionar como um facilitador para a empresa controlar as informações recebidas.

## Como?

* O sistema irá administrar a quantia de chamados e sua procedencia além de criar um dashboard com tais informações.

## Onde?

* Via WEB, com "suporte" para navegadores no Desktop e mobile.

## Quando?

* Deverá ser finalizado no primeiro semestre de 2023.

## Quanto?

* Não haverá apoio financeiro, apenas a equipe se dedicando.

# Requisitos funcionais:

## Login e Cadastro de usuários.

  1- O sistema deve possuir um autenticador de cadastro.
  
  2- O sistema deve possuir um login e senha diferente para cada usuário de cada departamento.
  
  3- Apenas usuários do setor de tecnologia tem a permissão para cadastrar novos usuários.
  
  4- O sistema deve ter uma listagem com clientes cadastrados.
  
  5- O sistema deve possuir uma tela de login apenas com campos para por email corporativo e senha, e um botao para entrar.
  
  6 - Os principais atores do sistema são os funcionários da empresa (usuários), os quais irão interagir diretamente com o sistema, ajudando a definir a sua função       nesse software.
  
  7- O principal objetivo desse caso de uso é a criação de uma forma de gerência de chamados, abertos, fechados ou em andamento.
  
  8- O usuário terá um cadastro próprio, colocando suas informações nesse campo. 
  
## Interface de chamados

  1- O sistema deve possuir uma interface que mostre os chamados abertos, concluidos e em espera.
  
  2- O sistema deve possuir um botão para abrir chamados na interface principal.
  
  3- O sistema deve possuir um prazo pré determinado para que o chamado continue aberto. Depende da categoria de chamado, problemas em 30min, agendados em 48h.
  
  4- O sistema deve possuir uma área de chamados internos para comunicação entre os departamentos.
  
  5- O sistema deve armazenar as seguintes informações dos chamados: nome do usuário que abriu o chamado, número de celular, email, motivo do chamado.
  
  6- O sistema deve separar os chamados pelo nível critico deles. (Critico, alto, medio, baixo).
  
  7- O sistema deve possuir um dashboard para cada departamento, depensendo do seu nível de acesso.
  
  8- O sistema deve possuir a descrição do chamado, por título, nível crítico e o departamento que abriu o chamado.

# Requisitos não funcionais

  1- O software deve ser desenvolvido para WEB, podendo ser utilizado no celular.

  2- Não ter integração com nenhum outro sistema da empresa.

  3- O sistema deve ser capaz de gerenciar cerca de 7 usuários simultaneamente.

  4- O sistema deve ser responsivo.

  5- Seguir as normas SLA, proteger contratado e contratante, além de dar maior credibilidade e confiabilidade à relação.

  6- O sistema deve ser desenvolvido em ReactJS.
  
  # Casos de uso: Abertura de um chamado
 
 - Descrição: O usúario ira acessar o site, conceder seus dados e informações, assim, estruturando o chamado, para resolver suas pendências.
  
 - O cliente irá conceder seus dados ao usuário do setor de tecnologia, que irá inserir os dados, estruturando o chamado.
  
 - Ator principal do sistema: funcionários
  
 - Pré-Condição: O usuário deve ter acesso ao sistema de abertura de chamados, O usuário deve estar registrado no sistema, O usuário deve estar autorizado a abrir chamados de acordo com a política e os procedimentos da organização, O usuário deve ter informações suficientes para descrever o problema que está enfrentando com detalhes, incluindo o tipo de problema, o local onde o problema ocorreu, a natureza do problema e outros detalhes relevantes e também o usuário deve concordar em seguir as políticas e procedimentos do sistema de abertura de chamados, incluindo a maneira como as informações são coletadas, armazenadas e compartilhadas, e o prazo para a solução do problema.
  
 - Fluxo principal: O usuário acessa o sistema de abertura de chamados. O sistema apresenta uma tela com opções para o usuário selecionar o tipo de problema que está enfrentando, como "problemas de hardware", "problemas de software" ou "problemas de rede". O usuário irá selecionar o tipo de problema que está enfrentando. O sistema apresenta uma tela com mais detalhes sobre o tipo de problema selecionado e solicita que o usuário forneça mais informações sobre o problema, como uma descrição detalhada do que está acontecendo e uma captura de tela. O usuário preenche as informações solicitadas e envia o chamado. O sistema confirma o recebimento do chamado e fornece um número de referência para que o usuário possa acompanhar o status do chamado. O sistema encaminha o chamado para o departamento ou técnico responsável pelo tipo de problema relatado. O técnico ou departamento responsável pelo problema recebe o chamado e começa a trabalhar na solução.O técnico ou departamento responsável atualiza o status do chamado regularmente fornece uma resposta para o usuário. O sistema notifica o usuário quando a resposta for enviada.

![WhatsApp Image 2023-05-04 at 10 18 00](https://user-images.githubusercontent.com/115193063/236216540-6ea67746-961d-4af8-8d5e-83ce234087b2.jpeg)
  
  - Fluxo alternativo: O usuário acessa o sistema de abertura de chamados. O sistema apresenta uma tela com opções para o usuário selecionar o tipo de problema que está enfrentando, como "problemas de hardware", "problemas de software" ou "problemas de rede". O usuário seleciona o tipo de problema que está enfrentando.O sistema apresenta uma tela com mais detalhes sobre o tipo de problema selecionado e solicita que o usuário forneça mais informações sobre o problema, como uma descrição detalhada do que está acontecendo e uma captura de tela. O usuário preenche as informações solicitadas e envia o chamado. O sistema confirma o recebimento do chamado e fornece um número de referência para que o usuário possa acompanhar o status do chamado. O sistema exibe uma mensagem informando que o tempo de resposta padrão pode não ser suficiente para atender ao problema do usuário e fornece uma opção para que o usuário possa indicar que se trata de um problema urgente.O usuário seleciona a opção "problema urgente". O sistema notifica imediatamente o técnico ou departamento responsável pelo tipo de problema relatado, a fim de garantir que o problema seja tratado com prioridade máxima. O técnico ou departamento responsável pelo problema recebe o chamado e começa a trabalhar na solução com prioridade máxima.O técnico ou departamento responsável atualiza o status do chamado regularmente e, quando a solução é encontrada, fornece uma resposta para o usuário. O sistema notifica o usuário quando a resposta for enviada e, se necessário, orienta o usuário sobre as etapas adicionais que precisam ser tomadas.
  
  - O sistema deve possuir a descrição do chamado, por: título, nível crítico (alto, médio e baixo) e departamento que abriu o chamado um dashboard para cada setor,     dependendo do seu nível de acesso.
  
  - Pós condição: O chamado estará aberto.
  
  - Frequência de uso: 24 horas por dia, sendo agendado em até 48 horas.
  
  - Campos: Apenas usuários do setor requisitado pelo cliente terá direção e aptidão para resolver o problema solicitado.
  
  - Prioridade: Essencial

