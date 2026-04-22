



# Exchange

Conecte-se a servidores Microsoft Exchange para enviar, ler e gerenciar e-mails e pastas por meio de serviços Web.

*Read this in other languages: [English](Manual_exchange.md), [Português](Manual_exchange.pr.md), [Español](Manual_exchange.es.md)*

![banner](imgs/Banner_exchange.png)
## Como instalar este módulo

Para instalar o módulo no Rocketbot Studio, pode ser feito de duas formas:
1. Manual: __Baixe__ o arquivo .zip e descompacte-o na pasta módulos. O nome da pasta deve ser o mesmo do módulo e dentro dela devem ter os seguintes arquivos e pastas: \__init__.py, package.json, docs, example e libs. Se você tiver o aplicativo aberto, atualize seu navegador para poder usar o novo módulo.
2. Automático: Ao entrar no Rocketbot Studio na margem direita você encontrará a seção **Addons**, selecione **Install Mods**, procure o módulo desejado e aperte instalar.


## Descrição do comando

### Configuração de Email

Insira as credenciais para configuração
|Parâmetros|Descrição|exemplo|
| --- | --- | --- |
|Usuário||Usuário|
|Senha||Senha|
|Servidor||Servidor|
|Endereço de email||Endereço de email|
|Variável onde armazenar o resultado|Neste campo, devemos inserir o nome da variável onde iremos armazenar o resultado da ligação.|Variável|

![exchange](example\exchange.png)
### Enviar Email

Envia um email, previamente deve configurar o servidor
|Parâmetros|Descrição|exemplo|
| --- | --- | --- |
|Para||to@mail.com, to2@mail.com|
|Cópia||cc@mail.com, cc2@mail.com|
|Assunto||Nuevo mail|
|Mensagem||Esto es una prueba|
|HTML|||
|Arquivo Anexo||C:\User\Desktop\test.txt|
|Pasta (Vários arquivos)||C:\User\Desktop\Files|

### Get all email

Obtenha IDs de todos os emails não lidos
|Parâmetros|Descrição|exemplo|
| --- | --- | --- |
|Type of filter||Var without {}|
|Filtro||teste|
|Atribuir à Variável||Variável|

### Listar email novos

Obtém os Id's dos email não lidos, por filtro
|Parâmetros|Descrição|exemplo|
| --- | --- | --- |
|Type of filter||Var without {}|
|Filter||test|
|Assign to Variable||Variable|

### Ler email por ID

Lê o conteúdo do email passando o ID
|Parâmetros|Descrição|exemplo|
| --- | --- | --- |
|ID do email||ID|
|Atribuir a variável||Variável|
|Caminho para arquivos anexados|||

### Mover email para pasta

Move email com ID para pasta específica
|Parâmetros|Descrição|exemplo|
| --- | --- | --- |
|ID do email||ID|
|Pasta de destino||Nome da pasta|

### Responder email por ID

Responder email por ID
|Parâmetros|Descrição|exemplo|
| --- | --- | --- |
|ID Email||355|
|Responder a todos||355|
|Mensagem||Esto es una prueba|
|Arquivo Anexo||C:\User\Desktop\test.txt|

### Encaminhar email por ID

Encaminhar email por ID
|Parâmetros|Descrição|exemplo|
| --- | --- | --- |
|ID Email||355|
|Email||test@email.com|
