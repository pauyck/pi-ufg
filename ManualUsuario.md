#Manual do Usuário

#### Grupo 3 - Projeto 1

## Histórico

 Data  |   Versão |  Descrição  |  Autor 
:-----:|:--------:|:-----------:|:------:

19/09/2017 | 1.0 | Criação Inicial do Documento | Paulo Henrique Abreu |
:-----:|:--------:|:-----------:|:------:
21/09/2017 | 1.1 | Criação Inicial do Documento | Paulo Henrique Abreu |



## Sumário
* [Apresentação](# "Apresentação")



### 1. Apresentação

#### 1.1 Sobre o Manual

O Manual do Usúario tem por objetivo descrever a forma correta de usar o Software de Chat sob protocolo IRC, com sockets em nodejs, do Grupo 3 da disciplina de Aplicações Distribuidas (Instituto de Informática - UFG).<br />

#### 1.2 Definições
* <b>Cliente:</b> Um cliente é qualquer coisa que se conecta a um servidor que não é outro servidor. Cada cliente é distinguido de outros clientes por um apelido (nick) exclusivo com um comprimento máximo de nove (9) caracteres. - RFC.

* <b>Servidor:</b>
 

### 2. Como Usar
#### 2.1 Requisitos
Para executar/acessar o chat é necessário ter instalado os seguintes softwares/complementos:
* Firefox - [https://www.mozilla.org/pt-BR/firefox/new/]
* ChatZilla - add-on IRC do Firefox - [https://addons.mozilla.org/en-US/firefox/addon/chatzilla/]

##### 2.1.1 ChatZila
O ChatZilla fornece todos os recursos usuais do cliente IRC: vários servidores, uma lista incorporada de redes padrão, fácil busca e classificação de canais disponíveis, registro e conversas de conversas e arquivos DCC, além de personalização fácil com plug-ins JavaScript e estilo CSS.
- Instale o ChatZilla como AddOn no Firefox através do link fornecido nos requisítos.

- Abra o Firefox e Clique em Ferramentas, em seguida clique em ChatZilla para abrir o mesmo.

Usaremos o ChatZilla através de comandos, para fixação de aprendizagem do conteúdo.

#### 2.1 Comandos Básicos (IRC)
Para uso do Chat com IRC é necessário usar alguns comandos. Aqui listamos os comandos necessários para usar o nosso software
Obs.: para qualquer comando usando IRC se faz necessário o uso da "/" (barra) precedento o comando.

##### 2.1.1 Acesso
- <b>/server NOMESERVIDOR </b>: Com este comando é possível conectar a um servidor IRC. Por exemplo, teste no ChatZilla o comando: /server freenode (Acessará um server existente o freenode);

- <b>/nick APELIDO </b>: O comando /nick possibilita alterar ou incluir o seu "Usuário" (nome de usuário, também conhecido como apelido, é como se identifica no Chat). Por exemplo: /nick paulohenrique - O apelido no servidor seria definido como paulohenrique.

- <b>/join CANAL </b>: O comando /join permite entrar em um canal, por exemplo: /join #ad-si-2017 (neste caso, adentraria no canal ficticio de Aplicações Distribuidas. A única exigência para usar um canal, é que o primeiro caractere do nome do mesmo seja '&', '#', '+' ou '!'. 

- <b>/part</b> : Esse comando serve para sair de um Canal;
- <b>/partall</b>: Para sair de Todos os Canais;

 
 ##### 2.1.2 Mensagens
- <b>/msg NICK_USUARIO MENSAGEM</b> : para enviar mensagem para um nick/usuário específico em um canal. Por exemplo: /msg paulohenrique Olá! (Envia a mensagem Olá para o usuário paulohenrique);

- <b>/msg #CANAL MENSAGEM </b>: Este comando envia mensagem para todos em um canal específico. Por exemplo: /msg #ad-si-2017 Olá Galera! (Envia mensagem para todos os usários que estão no Canal);

- <b>/PRIVMSG <target> [Mensagem]</b> : Este comando envia uma mensagem privada entre usuários ou para Canais. Por exemplo: /PRIVMSG <paulohenrique> Fala Paulo Henrique, BLZ? (Envia mensagem privada para paulohenrique). No mesmo caso para canais - /PRIVMSG <#ad-si-2017> E ai galera do Canal. 



