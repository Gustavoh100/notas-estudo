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
```
```
git clone mais chave ssh 
  ```
  ```
  cd nome do seu repositorio 
  ```
  ```
  code . 
  ```
## criamos portifolio 
para javascript e portifolio 

## Git Hub

1-Abra o CMD do computador "Terminal de comando".

2-Use o comando ```git --version``` com o objetivo de conferir a versão do seu ``GIT``.

3-Com o resultado observe o numero da versão caso estiver abaixo de ``2.53.0`` baixe a versão do mais atulizada pelo google.

4-Volte ao Terminal e ultilise o codigo ``git config --global user.name “Seu Nome”`` , com o nome salvo a maquina sempre vai se referir 
ao nome salvo.

5-Agora coloque o comando ``git config --global user.email “seuEmail@gmail.com”`` esse comando especifico ``` coloque o email que você ultiliza/ultilizara do GIT-HUB```

## Git bash

1-Caso você queira verificar se à alguma key na sua maquina use o comando ``ls -al ~/.ssh``

2-Ultilise o comando ```ssh-keygen -t ed25519 -C “your_email@example.com”``` colocando o gmail que você usou no github.

3-Ultilize o comando ```eval "$(ssh-agent -s)"```




4- digite esse comando ```ssh-add ~/.ssh/id_ed25519```

## clone as pastas do git hub para sua maquina 
1-use o comando ``cd document/

2- use comando ```git clone``` e cole a chave ssh 
