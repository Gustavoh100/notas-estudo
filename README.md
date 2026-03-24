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

<<<<<<< HEAD
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
>>>>>>> edfee94ab7691c8b388eb4b8570054e9f3140f49
createElement
h1 id= " pao " >batata</h1>
script>
const h1 = document.getElementbyid("pao")
script>
 const elementoNovo = documento.createElement("h1")
 elementoNovo.textContent = "batata" 
 divExemplo.appendChild(elementoNovo)
## function
 function questao1() {...

 }
const buttonQuestao1 = document.getElementById("questao1")
buttonQuestao1.addEventListener('click', () => { questao1() }) 

## if e else 
são estruturas condicionais que permitem executar diferentes blocos de codigo com base em uma condição ou expressão booleana.

if = se  
else if = se nao  


if(ocupado== 1 ){  
consloge.log("ocupado);
}else if (ocuupado == 2 ){
  console.log("reservado");
}else  
 ## butão e script 
 button id="exercicios" > texto do botão - executar exercicios </ button>
    script src="./pasta script criada "></ script>
    
## Dentro da atividade 
 funcion 
 getelement 
 addEVentLister  