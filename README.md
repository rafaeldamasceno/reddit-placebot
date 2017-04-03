# /r/portugal placebot

Este é o bot usado para pintar o espaço de Portugal no [/r/place](https://www.reddit.com/r/place/).
Podes consultar como se encontra atualmente [aqui](https://www.reddit.com/place?webview=true#x=722&y=412).

## Instruções de instalação

- Descarregar e instalar o [NodeJS](https://nodejs.org). Em **Linux/macOS**, para instalarem através de um gestor de pacotes, sigam [estas](https://nodejs.org/en/download/package-manager/) instruções.
- Fazer download do bot [aqui](https://github.com/rafaeldamasceno/reddit-placebot/archive/master.zip).
- Extraír o bot para onde preferirem.
- Na pasta do bot, renomear o ficheiro `users.example.json` para `users.json`.
- Abrir o `users.json` com um editor de texto (Bloco de notas, Notepad++) e inserir as credenciais do Reddit da seguinte forma:
- **1 utilizador:**
```
{
  "username": "password"
}
```
- **2 utilizadores ou mais:**
```
{
  "username1": "password1",
  "username2": "password2",
  ...
  "usernameX": "passwordX"
}
```
- Instalar as dependências do bot (ele instala na própria pasta). Em **Windows**, abrir o ficheiro `install.bat`. Em **Linux/macOS**, executar o `install.sh`.
- Iniciar o bot. Em **Windows**, abrir o ficheiro `start.bat`. Em **Linux/macOS**, executar o `start.sh`.

__NOTA__: Não é necessário atualizar a imagem a pintar, dado que o bot verifica automaticamente a imagem disponível neste repositório e usa-a. Será sempre a imagem mais atualizada.

## Imagem a pintar

Caso tenhas a tua própria instalação do `reddit-placebot`, podes configurar o `REMOTE_TARGET_URL` para `https://github.com/rafaeldamasceno/reddit-placebot/raw/master/target.bmp`.

A imagem é, atualmente, a seguinte (os [píxeis](https://www.priberam.pt/dlpo/pixel) rosa `#ff00ff` são ignorados):

![Imagem do /r/portugal](https://github.com/rafaeldamasceno/reddit-placebot/raw/master/target.bmp)

## License

The Reddit Placebot is released under the [MIT License](http://www.opensource.org/licenses/MIT).
