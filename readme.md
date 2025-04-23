<h3 align="center">Automatização Para Envio de Mensagens Whatsapp</h3>

## ProjetoEletronicaCastro

### Desenvolvido por:
## - Patrick Gabriel


### Sobre o Projeto
Projeto criado para enviar mensagens automaticas utilizando o https://app.botconversa.com.br/.
Utilizei o API do bot para integrar ao script PhP para facilitar envios de mensagens para quando os vendedores
efetuarem cadastro dos clientes no sistema, assim que forem feito os cadastro sobe para o banco principal, e utilizo o PDI (Pentaho) para fazer a manipulação dos dados e enviar para o banco de dados da integração.

* Utilizei um Banco de dados (MySql) para não interferir na produção do sistema principal.
* O Sistema usa um Banco proprio e o dados são extraidos pelo PDI, Organizados e Enviados para o novo banco.
* Usando a API do botconversa ela faz o envio das mensagens para o os clientes.
* O Proprio script identifica quais clientes ainda não receberam a mensagem, envia e altera para 1 (No Banco) para identificar que ja foi enviado a mensagem.