# /r/portugal placebot

Este é o bot usado para pintar o espaço de Portugal no [/r/place](https://www.reddit.com/r/place/).

## Instruções de instalação

- Descarregar e instalar o [NodeJS](https://nodejs.org).
- Fazer download do bot [aqui](https://github.com/rafaeldamasceno/reddit-placebot/archive/master.zip).
- Extraír o bot para onde preferirem.
- Na pasta do bot, renomear o ficheiro `users.example.json` para `users.json`.
- Abrir o `users.json` e inserir as credenciais do Reddit da seguinte forma:
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
  "usernamen": "passwordn"
}
```
- Instalar as dependências do bot (ele instala na própria pasta). Em **Windows**, abrir o ficheiro `install.bat`. Em **Linux/macOS**, executar o `install.sh`.
- Iniciar o bot. Em **Windows**, abrir o ficheiro `start.bat`. Em **Linux/macOS**, executar o `start.sh`.

## License

The Reddit Placebot is released under the [MIT License](http://www.opensource.org/licenses/MIT).
