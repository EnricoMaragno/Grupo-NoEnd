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
  
 - Pré-Condição: o sistema deve estar disponível e preparado para o uso.
  
 - Fluxo principal: Após o chamado ser computado no sistema, ele deve possuir suas respectivas informações tais como o nome do cliente que solicitou o chamado , seu número de celular e também o motivo do chamado , evidentemente na área da empresa o qual solicita ajuda. 

![WhatsApp Image 2023-05-04 at 10 18 00](https://user-images.githubusercontent.com/115193063/236216540-6ea67746-961d-4af8-8d5e-83ce234087b2.jpeg)
  
  - Fluxo alternativo: Nesse sentido, o melhor cenário de implementação seria o usuário introduzir os dados no sistema através do autentificador de cadastro, logo, os    dados irão constar no dashboard do chamado, sendo agendado em menos de 48 horas.
  
  - O sistema deve possuir a descrição do chamado, por: título, nível crítico (alto, médio e baixo) e departamento que abriu o chamado um dashboard para cada setor,     dependendo do seu nível de acesso.
  
  - Pós condição: O chamado estará aberto.
  
  - Frequência de uso: 24 horas por dia, sendo agendado em até 48 horas.
  
  - Campos: Apenas usuários do setor requisitado pelo cliente terá direção e aptidão para resolver o problema solicitado.
  
  - Prioridade: Essencial

