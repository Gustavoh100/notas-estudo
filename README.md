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
 
 montamos uma equipe para o projeto intragador

## -git hub 
git 
alert
prompt
criar repositório 
documetos , dom
troca para pr-br
format doc 
cd doc 
git clone clonar nome ssh do repositorio com botao direito 
cd nome do repositorio 
code . 
fazer algum css botao colorido alguma coisa !
h2 
button 
scripts src 
button> dois espaços entre button e > colocando id 
funçao
getElementById
addEventListner 
atividade :
function questao1() {
    //escreva o enunciado aqui 
    //some 2 numeros 
    const numero = Number(prompt("Digite um numero:"))
    const numero2 = Number(prompt("Digite um numero:"))
    alert(numero + numero2)
}
const buttonQuestao1 = document.getElementById("questao1")
buttonQuestao1.addEventListener('click', () => { questao1() }) 

acabou commit fim de avalição 
pegar link e enviar para o professor git hub
