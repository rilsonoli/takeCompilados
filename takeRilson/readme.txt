Bem vindo ao Take Chat.

O Take chat é uma aplicação cliente/servidor para envio de mensagens eletrônicas.

São duas aplicações, um web site com interface para realizar conversas entre participantes logados no sistema.
No chat é possível enviar mensagens para todos os participantes, mensagens públicas para um usuário específico 
e mensagens privadas para um usuário logado.

A aplicação utiliza o protocolo TCP para realizar a cominicação entre os clientes e o servidor. 
A aplicação web como cliente envia uma solicitação de conexão via TCP e as mensagens são enviadas utilizando 
StreamWriter e lidas com StreamRead. Ao realizar a conexão, uma thread é disparada e fica esperando receber 
mensagens.
 