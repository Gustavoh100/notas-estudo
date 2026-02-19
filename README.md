# notas-estudo
## Anotaçoes  
## parte 1 
Instalar o Github, uma ferramenta que salva o estado de cada arquivo na hora do versionamento e caso o arquivo não sofra alteração ele cria um link para o arquivo não editado, depois verificamos o Github, abrimos o terminal de comando e digitamos
 git –version
 ## configuração do git local com alguns comandos:
 ```
>git config –global user.name “seu nome”
```
```
 >git config –global user.email  “seu email”
 ```
## Criamos uma conta no site do Git hub e configuramos o ssh no git bash
 verificamos se existe uma chave, adicionamos uma nova chave, com: 
ssh-keygen -t ed25519 -C” seu emailexemple.com “
 ## iniciando agente-ssh:
 ```
 eval “$(ssh-agent -s)”
 ```
##  adicionamos uma chave ao ssh ao agente:
```
ssh-add ~/.ssh/id_ed25519
```
## copiamos a chave shh e adicionamos no git hub e testamos conexão

## criamos e clonamos um repositório no git hub e instalamos o vscode
 para clonar entramos no git bash e colocamos: 
```
cd documents/
````
```
git clone/
  ```
  ```
  cd nome do seu repositorio 
  ```
  ```
  code . 
  ```