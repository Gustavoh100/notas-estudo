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

 
 ## ajuda 
 13
 const numero = Number(prompt("Digite um numero:"))
 const media = (numero/2) 
 if (media = 0 ){
    alert("par")
 }else (media !== 0){
    alert("impar")
 }

11
 const numero = Number(prompt("Digite um número: "))
const numero2 = Number(prompt("Digite outro número: "))
const operacao = prompt("Digite uma operação matematica:")

if (operacao == "*"){
    alert(numero*numero2)
}else if (operacao == "/"){
    alert(numero/numero2)
}else if (operacao == "-"){
    alert(numero-numero2)
}else if (operacao == "+"){
    alert(numero+numero2)
}else{
    alert("não encontrado!")
}

const nota1 = Number(prompt("Digite a primeira nota "))
const nota2 = Number(prompt("Digite a segunda nota "))
const nota3 = Number(prompt("Digite a terceira nota "))

const media = (nota1 + nota2 + nota3) / 3
console.log(media)// e ele esta no f12 na aba console

//Aprovado" se a média for maior ou igual a 7
//"Recuperação" se for maior ou igual a 5 e menor que 7
//"Reprovado" se for menor que 5
if (media < 5) {
    alert("REPROVADO")
} else if (media >= 5 && media < 7) {
    alert("RECUPERAÇÃO")
} else if (media <= 10) {
    alert("APROVADO")
} else {
    alert("não existe")
}

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <link rel="stylesheet" href="./style/styles.css">
    <title>Document</title>
</head>
<body>
  <header id="exemplo"  ></header>
    <header>
        um titulo qualquer
    </header>

    <main>
        <h2>Minha pagina de Exercicios</h2>
    
        <button id="exercicio2">Executar Exercicio 2</button>
        <button id="exercicio3">Executar Exercicio 3</button>
        <button id="exercicio4">Executar Exercicio 4</button>
        <button id="exercicio5">Executar Exercicio 5</button>
        <button id="exercicio6">Executar Exercicio 6</button>
        <button id="exercicio7">Executar Exercicio 7</button>
        <button id="exercicio8">Executar Exercicio 8</button>
      
    </main>

    <footer id="footer" >
        todos os direitors reservados - Gustavo Henrique -2026
    </footer>
    <script src="./script/exercicios_13.js"></script>
</body>

</html>