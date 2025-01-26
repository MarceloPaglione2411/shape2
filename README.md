# shape

Pipeline:

1º Login no Azure, usando GitHub Secret AZURE_CREDENTIALS para autenticar no Azure.

2º Login no ACR e faz o Build da imagem:

3º Cria a imagem Docker com o código atualizado e Push 

4º Envia a imagem Docker para o ACR.

5º Configura o App Service para utilizar a nova imagem Docker.
