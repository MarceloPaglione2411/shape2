# shape

Pipeline:

push no branch main: A pipeline é acionada automaticamente ao fazer um push no branch principal.

Login no Azure e no ACR: Faz login nos serviços usando credenciais armazenadas como secrets.

Build e Push da Imagem: Gera uma nova imagem Docker com a tag baseada no commit SHA e faz o push para o ACR.

Atualiza o App Service: Atualiza a configuração do App Service para utilizar a nova imagem Docker.
