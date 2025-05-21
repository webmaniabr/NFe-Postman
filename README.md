<p align="center">
  <img src="https://wmbr.s3.amazonaws.com/img/logo_webmaniabr_github2.png">
</p>

Utilize a ferramenta Postman para realizar testes instântaneos nas API's da Webmania® e obter exemplos de integração em mais de 15 linguagens de programação. É só importar e testar, veja como é simples.

## Requisitos
  - Instalar Postman: [Download](https://www.getpostman.com/downloads/)
  - Contrate um dos planos de Nota Fiscal Eletrônica da Webmania®). [Assine agora mesmo](https://webmaniabr.com/nota-fiscal-eletronica/)

## Workspace Postman
Acesse o **Workspace Webmania®** e fique sempre atualizado: https://bit.ly/3mGuGKV

## URL Postman
- **API de Nota Fiscal:** https://www.postman.com/grey-water-1853/workspace/webmania/collection/2938302-1c4e3b72-df62-4114-91ed-0d9bf40d257f?action=share&creator=2938302
- **API de CEP e IBGE:** https://www.postman.com/grey-water-1853/workspace/webmania/collection/2938302-a74d75ed-7c82-4376-98a0-beebebf699ff?action=share&creator=2938302
## Vídeo explicativo

Veja no vídeo a seguir como é fácil testar a API de Nota Fiscal da Webmania® utilizando o Postman e Insomnia. Ou se preferir, você pode seguir as instruções logo abaixo.

<p align="center">
  <a href="https://www.youtube.com/watch?v=eBSxSLgYJOk" target="_blank"><img src="https://wmbr.s3.amazonaws.com/img/github/postman/thumb_video.jpg" alt="Vídeo explicativo"></a>
</p>

## Instruções

Com o postman instalado e aberto clique em *import*, que fica localizado na parte superior esquerdo, como na imagem abaixo:

<p align="center">
  <img src="https://wmbr.s3.amazonaws.com/img/github/postman/import_button.jpg">
</p>

Clique na opção *Import* e insira a URL Postman no campo *"Enter a URL"* da API que deseja e clique em *"Continue"*.<br>
Você também pode realizar a importação pelas opções *File* e *Raw text*, utilizando os arquivos .json nas pastas API_CEP, API_NotaFiscal ou API_NotaFiscalServico.

<p align="center">
  <img src="https://wmbr.s3.amazonaws.com/img/github/postman/import_modal.jpg">
</p>

Pronto, o Postman cria automaticamente uma coleção com todos os exemplos de requisições da nossa API:

<p align="center">
  <img src="https://wmbr.s3.amazonaws.com/img/github/postman/requests.jpg">
</p>

Agora é só configurar suas credenciais de acesso para que as requisições funcionem, sem isso, não será possivel realizar os testes na REST API. Para a API 1.0 as credenciais devem ser informados no Headers das requisições:

<p align="center">
  <img src="https://wmbr.s3.amazonaws.com/img/github/postman/credenciais10.jpg">
</p>

Para a API da NFS-e, basta apenas informar o Token da API 2.0 nas váriaveis da collection do Postman:

<p align="center">
  <img src="https://wmbr.s3.amazonaws.com/img/github/postman/credenciais20.jpg">
</p>

Pronto seu Postman está pronto para enviar requisições via API, clique agora em **Send** e receba a resposta da nossa API.

<p align="center">
  <img src="https://wmbr.s3.amazonaws.com/img/github/postman/send.jpg">
</p>

**Resposta:**

<p align="center">
  <img src="https://wmbr.s3.amazonaws.com/img/github/postman/response.jpg">
</p>

## Suporte

Ficou com dúvida? Sem problema, entre em contato com a gente em [Central de Ajuda](https://ajuda.webmaniabr.com) ou acesse o [Painel de Controle](https://webmaniabr.com/painel/) para conversar em tempo real no Chat ou Abrir um chamado.
