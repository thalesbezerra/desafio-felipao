## Comandos do git

…or create a new repository on the command line
echo "# desafio-felipao" >> README.md

* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/thalesbezerra/desafio-felipao.git
* git push -u origin main

…or push an existing repository from the command line
* git remote add origin https://github.com/thalesbezerra/desafio-felipao.git
* git branch -M main
* git push -u origin main


https://github.com/thalesbezerra/desafio-felipao

* git init
* git add .
* git branch -M main
* git remote add origin https://github.com/thalesbezerra/desafio-felipao.git
* git push -u origin main

* node index.js
- ou
* node src/index.js
* git add .
* git commit -m "meu segundo commit"
* git push -u origin main

* git clone https://github.com/thalesbezerra/desafio-felipao.git

* cd desafio-felipao


---------------------------------------------------------------------------------------------------------------------------
Entendendo o Desafio
 
Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos explorados até aqui e replique (ou melhore, porque não?) este projeto prático. Para isso, crie seu próprio repositório e aumente ainda mais seu portfólio de projetos no GitHub, o qual pode fazer toda diferença em suas entrevistas técnicas 😎
 
Neste repositório, insira todos os links e arquivos necessários para seu projeto, seja um arquivo de banco de dados ou um link para o template no Figma.
 
Dica: Se o expert forneceu um repositório Github, você pode dar um "fork" no repositório dele para organizar suas alterações e evoluções mantendo uma referência direta ao código-fonte original.
 
Instruções para entrega
# 1️⃣ Desafio Classificador de nível de Herói

**O Que deve ser utilizado**

- Variáveis
- Operadores
- Laços de repetição
- Estruturas de decisões

## Objetivo

Crie uma variável para armazenar o nome e a quantidade de experiência (XP) de um herói, depois utilize uma estrutura de decisão para apresentar alguma das mensagens abaixo:

Se XP for menor do que 1.000 = Ferro
Se XP for entre 1.001 e 2.000 = Bronze
Se XP for entre 2.001 e 5.000 = Prata
Se XP for entre 5.001 e 7.000 = Ouro
Se XP for entre 7.001 e 8.000 = Platina
Se XP for entre 8.001 e 9.000 = Ascendente
Se XP for entre 9.001 e 10.000= Imortal
Se XP for maior ou igual a 10.001 = Radiante

## Saída

Ao final deve se exibir uma mensagem:
"O Herói de nome **{nome}** está no nível de **{nivel}**"

 
 
 
Bons estudos 😉

## Codigo fonte das aulas de javascript

torrar()


function torrar() {
    console.log("torrando o pão")
    injetarPao()
}

function injetarPao() {
    console.log("preparando para injetar o pão")
    console.log("finalizado")
}

##

function enviarDados() {
    let nomeDoBanco = "banco-de-dados"
    console.log("salvando dados em: : " + nomeDoBanco)
}

##
torrar("pão de forma")
torrar("pão integra")

function torrar(pao) {
    console.log("torrada feita com " + pao)
}

##
torrar("pão integral", "Janaina")

function torrar(pao, nome) {
    console.log("torrar feita com " + pao)
    console.log("ela é um pedido de " + nome)
}

##

torrar("pão integral")

function torrar(pao, nome = "Cliente") {
    console.log("torrar feita com " + pao)
    console.log("ela é um pedido de " + nome)
    console.log(" ")
}

torrar("pão integral", "Janaina")

function torrar(pao, nome = "Cliente") {
    console.log("torrar feita com " + pao)
    console.log("ela é um pedido de " + nome)
    console.log(" ")
}

torrar("pão integral", "Janaina", 70)

function torrar(pao, nome = "Cliente", valor) {
    console.log("torrar feita com " + pao)
    console.log("ela é um pedido de " + nome)
    console.log("O Valor total é " + valor)
    console.log(" ")
}

torrar("pão integral", 70)

function torrar(pao, valor, nome = "Cliente") {
    console.log("torrar feita com " + pao)
    console.log("ela é um pedido de " + nome)
    console.log("O Valor total é " + valor)
    console.log(" ")
}



