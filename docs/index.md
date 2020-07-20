# <center> KnowledgeBase </center>

<center> Página criada com a finalidade de oferecer uma base de conhecimentos com base em meu ponto de vista.</center>

---

## VSCODE

**EXTENSÕES E PLUGINS**

```
1. Auto Close Tag - Serve para fechar tags automaticamente
2. Auto Rename Tag - Se você altera o nome na abertura da tag, altera automaticamente no final.
3. Bracket Pair Colorizer - Colore as chaves de forma que não confunda quando aninhadas
4. Color Highlight - Ao digitar uma cor, Seja em HEX, RGB ou nome, automaticamente a cor é mostrada, como background da palavra
5. HTML Snippets - Atalhos para gerar html
6. Intellisense for CSS class names in HTML - autocompleta os nomes das classes do css
7. TODO Highlight - Tu pode configurar pra mais, mas ao comentar TODO: , FIXIT: fica destacado para uma anotação importante
8. GraphQL for VScode - É um syntax highlight pra codar em grapql
9. Import Cost - Bem importante pra ver o tamanho dos imports das libs que você faz no seu projeto, mostrando ela normal e gizipada
10. Indenticator - Mostra o bloco de codigo que você está, meio inutil nas novas versões do Vscode, pois há nativamente já.
11. Es7 react/redux/graphql/react-native -Extensões do react e snippets do ES7
12. ESLint - MUITO IMPORTANTE Ajuda a padronizar seu codigo e ter boas condutas ao codar ( te faz um programador melhor, ao longo do tempo)
13. Quokka.js - Da pra codar Js e ver os resultados em tempo real direto no editor, bom pra testar umas logicas rápidas
14. REST Client - tu faz requisições no próprio editor e obtém as respostas para ver se ta tudo certo..etc
15. JSON Tools - Formatar, minificar e manipular JSON, uma maravilha para quem trabalha com bastante jsons..
16. Vetur - IMPORTANTE* Pra quem trabalha com Vue é indispensável, Há snippets, syntax-highlihting, Emmet, Linting / Error Checking, formatting, auto Completion, e debug.
17. Version Lens - Mostra versões de suas libs e diz se há uma nova versão ou se a sua está depreciada.
18. Configura pra formatar e deixar o codigo bonitinho
19. VS Live Share - Permite você mais outras pessoas codarem o mesmo codigo em tempo real :) (muito cuidado kkkkkk)
20. JavaScript (ES6) code snippets - Snippets pra features do ES6
21. Babel es6/es7 - colore e ajuda na visualização das features do es6 e es7
22. Path Intellisense - Te mostra e completa caminhos pra importar algo
23. Dracula official - Apenas um tema que adoro muito :)
24. Material Icon theme - apenas pack de icons para ajudar na visualização dos arquivos
25. todotree
26. azure cosmodb conectar no mongo
27. image preview preview da imagem
28. preview markdown preview de markdown

```
**COMANDOS CURTOS**

```
* CTRL + shift + p (configurações)
* CTRL + p (listar arquivos)
* alt + seta cima/ seta baixo (mover linha(s))
* alt + seta esquerda/ seta direita (mover entre palavras)
* shift CTRL K (apagar linha)
* CTRL f (localizar dentro do arquivo)
* alt  CTRL f (localizar e substituir dentro do arquivo)
* CTRL d/b alterar mesmas variáveis
* emmet html>body>div.conteudo

```

## LINUX

**TELA**
```
Tela GRUB do boot

```
### DIRETÓRIOS
```
* raiz (/)
* Binários executáveis: /bin (cp, mv, ping e grep)
* Binários do sistema: /sbin (ifconfig, fdisk)
* Programas diversos: /usr
* Configurações do sistema: /etc
* Bibliotecas: /lib
* Opcionais: /opt
* Aquivos pessoais: /home
* Inicialização: /boot
* Volumes e mídias: /mnt e /media
* Serviços: /srv
* Arquivos de dispositivos: /dev (usb)
* Arquivos variáveis: /var
* Processos do sistema: /proc
* Arquivos temporários: /tmp

```
### COMANDOS

**Cancela comando**
```
CTRL + C 

```
**Autocompletar**
```
tab

```
**Retorna comandos anterior**
```
Seta para cima e seta para baixo

```

**Sistema**
```
uname

```
**Data**
```
date

```
**Calendario**
```
cal

```
**Hora**
```
time

```
**Retorna os últimos 1000 comando no console**
```
history

```
**Vários comandos juntos**
```
date; cal

```
**Calculadora**
```
bc
2+2
sqrt(81)

```
**Caminho atual**
```
pwd

```
**Entrar ou sair de um diretório**
```
cd
cd ..
cd / (raiz)
cd enter (diretório padrão)

```
**Listar o conteúdo de um diretório**
```
ls
ls -l (lista mostrando os tipos)
ls -la (lista mostrando os tipos e quem esta oculto
começa com d = diretório
começa com l = link
começa com - = arquivo

```
**Limpar a tela do console**
```
clear

```
**Criar arquivo com texto**
```
touch arquivo.txt
> teste01

```
**Criar pasta**
```
mkdir pasta

```
**Renomear ou Mover**
```
mv message.txt message2.txt

```
**Remover pasta**
```
rm -rf pasta

```
**Copiar de caminho para outro**
```
cp minhapasta1/message.txt minhapasta2

```
**Mostra o conteudo de um arquivo**
```
cat arquivo
echo conteudo > arquivo

```
**Mostrar manual de um comando**
```
man echo

```
**Exibir os dados de IP**
```
ifconfig

```
**Criar usuário**
```
adduser teste

```
**Criar senha**
```
passwd teste

```
**Acessar o usuário**
```
su teste

```
**Remover o usuário**
```
deluser teste

```
**Exibir o conteudo desse arquivo**
```
cat /etc/passwd
tac arquivo (mostra o conteúdo com as linhas invertidas)

```
**Mostrar o conteudo desse arquivo no editor NANO**
```
nano /etc/network/interfaces

```
**Rede**
```
netstat -nlpt

```
**Atualizar repositório**
```
apt-get update

```
**Atualizar repositório**
```
apt-get upgrade

```
**Mostra qual é meu usuario**
```
whoami

```
**Informações do linux**
```
uname -s -r

```
**Permissão**
```
chmod 777 arquivo.txt

```

Chow cleiton: cleiton arquivo.txt

**Dono** 
```
chow -R 777 * .

```
**Abrir com terminal e em background**
```
firefox &

```
**Listar processo**
```
top

```
**Matar processo**
```
kill -9 98989

```

**Reiniciar**
```
sudo shutdown -r now
reboot

```
**Desligar**
```
sudo shutdown -h now
shutdown -h 1 (vai desligar em 1 minuto)
halt
Sair do terminal
exit

```
## SHELL SCRIPT
```
variavel= “ola”
echo "$variavel"

```
```
read teste
echo "foi $teste"

```
```
$USER
$SHELL
$PATH

```
```
-lt <
-gt >
-le <=
-ge >=
-eq ==
-ne !=

```
```
read nota
if ("$nota" -ge "6")
then
echo "passou"
else
echo "rodou"
fi

```
```
for i in ${seq 1 10}
do
echo "$1"
done

```



## VIM/VI

**COMANDOS**
**Abrir o arquivo**
```
vim arquivo.txt

```
**Abrir o arquivo e colocar o cursor no fim**
```
vim arquivo.txt + 

```
**Abrir o arquivo e colocar o cursor na linha 8**
```
vim arquivo.txt +8

```
**Abre na linha que tiver bsd**
```
vim arquivo.txt +/bsd

```
**Abre vários arquivos**
```
vim -o arquivo.txt arquivo2.txt

```
**Salvar arquivo**
```
esc : w 

```
**Sair**
```
esc : q

```
**Salvar e sair**
```
esc : w q
:x
zz

```
**Sair sem salvar**
```
esc : q!

```
**Salvar**
```
esc : set autowrite
:set aw

```
**Desfaz**
```
esc v

```
**Salva tudo aberto**
```
esc : w a 

``` 
**Salva e sai de todos**
```
esc : wqa

```
**Fim da linha**
```
esc $ 

```
**Inicio da linha**
```
esc ^

```
**Fim do arquivo**
```
esc :$ (dois pontos cifrao)
esc G

```
**Inicio do arquivo**
```
esc gg

```
**Linha 8**
```
esc :8
esc 8G

```
**Pula para próxima palavra**
```
esc w

```
**Pula para palavra anterior**
```
esc b

```
**Pula para frase anterior**
```
esc [

```
**Pula para frase posterior**
esc ]

**Pula para paragrafo anterior**
```
esc {

```
**Pula para paragrafo posterior**
```
esc }

```
**Pesquisar palavra linux**
```
esc /linux

```
**Insere na onde está**
```
esc i

```
**Insere após a posição**
```
esc a

```
**Insere nova linha após**
```
esc o

```
**Insere reescrevendo**
```
esc r

```
**Para cima**
```
esc K

```
**Para direita**
```
esc l

```
**Para esquerda**
```
esc h

```
**Para baixo**
```
esc j

```
**Seleciona o paragrafo**
```
esc shift v

```

### REDES

```
cd /etc/network/interfaces
vi interfaces
12 #
13 auto enp0s3
14 iface enp0s3 inet static
15 address 192.168.25.242
16 netmask 255.255.255.0
17 network 192.168.25.0
18 broadcast 192.168.25.255
19 gateway 192.168.25.1

vi /etc/resolv.conf
nameserver 192.168.25.1

```
**Calcular IP**
```
apt-get install ipcalc
ipcalc 192.168.0.10

```
**Restartar o Apache**
```
systemctl restart apache2

```
**VPN**
```
VIRTUAL PRIVATE NETWORK

```
**SEGURANÇA**
```
Pilares: Confidencialidade; Integridade; Disponibilidade

```
**BACKUP**
```
Tipos
full, incremental

```
**Gerenciadores de Backup**
```
BackupPC, Amanda, Bacula

```
**Ataques**
```
* SPOOFING
* SMURF ATTACK
* SNIFFING
* CAVALO DE TRÓIA
* FORÇA BRUTA
* DESFIGURAÇÃO DE SITE
* DOS
* DDOS

```
**EMULA REDE**
```
GNS3 
PACKETTRACE


```
**MODELO OSI**
Open System Interconnection 

**7 Camadas** 
```
* Aplicação
* Apresentação
* Sesão
* Transporte
* Rede
* Enlace
* Física

```
**Análise Top Down do Modelo OSI**
```
* Aplicação
* Apresentação
* Sesão
* Transporte
* Rede
* Enlace
* Física

```
**Exemplos**
```
* FISICA = REPETIDOR/HUB
* ENLACE = PONTE/BRIDGE
* ENLACE = SWITCH

```

**Tipos de Redes**
```
* PAN = Rede pessoal
* LAN = Rede Local
* MAN = Rede Metropolitanea
* WAN = Rede de Longa Distância
* DAN = Rede Departamental
* GAN = Rede Global

```
**WIRELESS WIFI** 
```
WIRE CABO
LESS SEM

```
**INTERFERIR NA REDE SEM FIO**
```
MICROONDA / TELEFONE SEM FIO PODEM 

```
**Software para rede**
```
WIFI DEADSPOT
WIFI ANALYZE

```
## PENTEST
```
Teste de penetracao = teste de intrusao

```
**Ferramentas**
```
* ferramentas de engenharia social
* ferramentas de trojan
* ferramentas de força bruta
* The Harveste
* Net craft ferramenta para analisar um domínio
* fierce ferramenta de força bruta
* fierce -dns site

```
**Comando site**
```
site: acunetix login
site: acutenix filetype:txt
link: acutenix login
site: acunetix intitle: password
site: XXX intitle: “index.of” “attachments”
```
**Nikito**
```
nikto -H
nikto -h site -Tuning 9
nikto -h site
```

## ANDROID

**DEFINIÇÃO**
```
SO baseado em linux usado em smartphone, tv, relógios.

```
**Apps do SO**
```
Apps do Usuário

```
**VERSÕES**
```
* Honeycomb
* Ice Cream Sandwich
* Jelly Bean
* KitKat
* Lolipop
* Marshmallow
* Nougat
* Oreo
* Pig

```

## GIT
**Instalação Linux**
```
sudo apt-get update
sudo apt-get install git

```
**Versão**
```
git --version

```
**Configuração**
```
git config --global user.name "Your Name"
git config --global user.email "youremail@domain.com"

git config --list

```
**Clonando/Copiando**
```
git clone https://github.com/cleibp/baseLinks.git

```
**Verificando os status**
```
git status

```
**Adicionando os arquivos**
```
git add .

```
**Commit**
```
git commit -m "aasa"

```
**Enviando/Empurrando**
```
git push
```

## JAVASCRIPT

**DEFINIÇÃO**
```
Javascript !== Java
Livescript Javascript Ecmascript
Ecma = comite
POO baseada em prototipos
sincrono = if, while, for
assincrono = setTimout
Navegadores (MOSAIC, Netscape, IE, Opera, Safari, Firefox, Chrome, Edge)
Variável é espaço de memória para armazenar um valor e identificador é nome da variável;
Case sensitive;
Palavras reservadas;
Comentário de uma linha //
Comentário para várias linhas /* */
fracamente tipado
Tipos de dados primitivos (String, number, boolean, undefined, null)
Tipos de dados referência (object, array, function, date, RegExp, Error)
objeto window escopo global
Operadores(aritméticos, atribuição, comparação, lógicos, ternário, unário)
Hoisting = elevaçao ( move a declaracao para o topo do método)
notacao literal de objetos != javascript object anotation
Estrutura de Controle  (If else; switch)
Estrutura de Repetição (for while do while)

```

**Variávies e tipos**
```
var nome;
nome = “Cleiton”
var idade = 34;
var salario = 3277.22;
var vr = true;

```
**Concantenado**
```
var dado1 = “Bom”
var dado2 = “Dia”
var dado3 = “Brasil \
. \
Acorda”
var dados = dado1 + “” + dado2  + dado3

```
**Verificando o tipo**
```
var whoAmI = “teste”
typeof whoAmI

```
**Valores Falso**
```
!! “”
!!0
!!-0
!!null
!! undefined
!!NaN

```
**Valores True**
```
!!Array
!!Object
!!Function

```
Undefined != Null
```
tpeof undefined
typeof null

```

**OPERADORES**
```
ARITMÉTICOS (+ - * / % ++ – **)
var soma = 20 + 20

UNÁRIO
typeof soma


ATRIBUIÇÃO ( =  += -= *= /= %= **= )
var  numero   = 10
numero += 2

COMPÁRAÇÃO ( > < <= >= != )
var n1 = 10
var n2 = 10
var r =  n1 == n2

LÓGICOS (&& || ! )
var res = (n1 > n2) && (n1> n3)
var res = (n1 > n2) || (n2 > n3)
 var res = n1 != n2

TERNÁRIO
var idade = 18
idade >= 18 ? “maior” : “menor” 

OUTROS TIPOS DE OPERADORES
( typeof  instanceof  in . [] new)

variavel instanceof String

var objeto = {nome: “Cleiton”}
nome in objeto

var array = new Array(“a”, “b”, “c”)
0 in array

var objeto = {nome: “Cleiton”, teste: true}
delete  objeto.teste

var array = [“a”, “b”, “c”]
delete array[0]

```

**ARRAY**
```
var array = []
array[0] = ‘teste’
array.push(“teste 2”)
console.log(array)

var nomes = [‘Paulo’, ‘Joao’, ‘Maria’]
console.log(nomes)
console.log(nomes[0])
console.log(nomes.length)

var numeros = new Array();
var numbers = new Array(25, 30, 50);

var tipagem = [
“string”,
25.88,
true,
{livro: ‘JS’, autor: ‘Cleiton’},
[0, 1, 2, 3],
function(a,b){
	return a + b
}
]

var a = [5, 7, 9, 11]
var teste = 5 in a
console.log(teste)

var espaco = [‘teste’, ‘c’, ,,, true]
espaco[20] = 20

var ultimo = [13, 14, 18, 22]
ultimo.push(24) // insere no final
console.log(array)

var primeiro = [4, 5, 6, 7]
primeiro.unshift(1) // insere no comeco
console.log(primeiro)

var excluir = [44, 55, 66, 77]
delete excluir[3]
console.log(excluir)

excluir.pop() // deleta a ultima posicao
console.log(excluir)

excluir.shift() // deleta a primeira posicao
console.log(excluir)

excluir.splice(2,1) // indice e quantidade
console.log(excluir)

var x = [1, 2, 3, 4, 5]
x.length = 15

Object.defineProperty(x, ‘length’, {writable: false})
Object.getOwnPropertyDescriptores(x)

var numeros = [0, 1, 2, 3, 5]
numeros.join(“.”)
console.log(numeros)

var arrayAll = [‘a’, true, new Date()]
arrayAll.toString()
console.log(arrayAll)

arrayAll.toLocaleString()
console.log(arrayAll)

var arrayReverse = [1, 2, 3, 4, 5]
arrayReverse.reverse()
console.log(arrayReverse)

var arraySort = [90, 20, 55, 95, 102]
arraySort.sort(function(x,y){
	return x - y
})
console.log(arraySort)

var arrayConcat = [1, 2, 3, 4, 5]
arrayConcat.concat(6, 7, 8, 9, 10)
console.log(arrayConcat)

var arraySice = [‘arroz’, ‘feijao’, ‘açucar’, ‘sal’, ‘oleo’]
arraySice.slice(0, 3)
console.log(arraySice)

var arraySplice = [1, 2, 3, 4, 5]
arraySplice.splice()
console.log(arraySplice)

var arrayMap = [2, 6, 8, 10, 12]
var dobro = arrayMap.map(function(valorElementoArray, indiceDoArray, array) {
	return  valorElementoArray * 2;
})
console.log(dobro)

var arrayFilter =  [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14]
var menoresQueCinco =  arrayFilter.filter(function(valor, indice, array){
	return valor < 5
})
console.log(menoresQueCinco)

var arrayEvery = [2, 9, 5, 6, 7, 15]
var menoresQueVinte =  arrayEvery.every(function(item, indice, array){
	return < 20
})
console.log(menoresQueVinte)

var arraySome = [2, 9 , 5, 6, 7, 15]
var  menoresQueDez =  arraySome.some(function(item, indice, arrayAll){
	return item > 10
})
console.log(menoresQueDez)
var arrayReduce = [1, 2, 3, 4, 5]
var soma = arrayReduce.reduce(function(acumulador, valorEleArray, indice, array){
	return   acumulador + valorEleArray
}, 0)
console.log(soma)

var arrayIndexOf = [‘maria’,  ‘jose’, ‘paulo’]
var resposta =  arrayIndexOf.indexOf(‘paulo’)
console.log(resposta)

var arrayLastIndexOf = [‘maria’,  ‘jose’, ‘paulo’]
var resposta =  arrayLastIndexOf.lastIndiceOf(‘paulo’)
console.log(resposta)

```
**OBJETO**
```
var obj =
{
	nome: "Cleiton",
	idade: 50
}
var json = JSON.stringify(obj)

```
**JSON**
```
json (nao aceita funcao no valor)
{
 	"nome": "Cleiton",
	"idade": 20,
	"filiacao": {
		"pai": "nome do pai",
		"mae": "nome da mae"
	},
	"cursos": ['tecnico', 'pos'] 
}
var obj = JSON.parse(json)

var objPessoa = Object.create(Object.prototype)
objPessoa.nome = ‘Joao’

var meuObjeto = {
	nome: ‘Cleiton’,
	saudacao: function() {
		return “Olá” + this.nome
	}
}


var pedido = new Object()
pedido.total = 400.00
console.log(“cliente” in pedido) // verifica  se  existte
pedido.hasOwnProperty(“total”)
delete pedido.total

var folhaPagamento = {
	_total: 0,
	set total(valor) {
		this._total = valor
	},
	get total() {
		return this._total
	}
}

folhaPagamento.total = 77.000
console.log(folhaPagamento.total)
console.log(Object.getOwnPropertyDescription(folhaPagamento))

var objeto = {a:2, b: 3, c: 5}
Object.defineProperty(objeto, “a”, {
	enumerable: false,
	configurable: false,
})

Object.seal(variavel)
Object.isSealed(variavel)
Object.isExtensible(variavel)
Object.freeze(variavel)
Object.isFrozen(variavel)

```

```
Objeto window
typeof window
typeof Window
window.console.log(“teste”)

```
**WRAPPER**
```
var vstring = “Curso JS”
vstring.substr(0,5)

String(variavel)
Number(variavel)
Boolean(variavel)
Object(variavel)


```
**FUNCÕES**
```
function mensagem() {
	console.log(“Olá”)
}
mensagem()


function boasVinda(nome){
	console.log(“Olá”, nome)
}
boasVindas(“Paulo”)

function soma(valor1, valor2){
	return valor1 + valor2
}
console.log(soma(10, 20))

var elevarQuadrado = function(numero){ return numero * numero }
console.log(elevarQuadrado(8))
var mult = function() {return 2 * 2}()
console.log(mult)

var objeto = { 
	qtde: 8, 
	valor: 10,
	somar: function(){
		return this.qtde * this.valor
	}
}

console.log(objeto.somar())

```
**IIFE**
```
(function () {

})()

```
**CLOSURE**
```
function makeFunc() {
  var name = "Mozilla";
  function displayName() {
    alert(name);
  }
  return displayName;
}

var myFunc = makeFunc();
myFunc();

```
**ANÔNIMA**
```
var minhaFuncao = function() {
	console.log(“funcao”)
}
minhaFuncao()

```
**CALLBACK**
```
function mostrarCliente(nome){
	console.log(nome)
}

function realizarVenda(calback){
	callback(‘Pedro’)
}
realizarVenda(mostrarCliente)

```

**SETTIMOUT E SETINTERVAL**
```
setTimout(function(){

}, 1000)


setInterval(function(){

}, 2000)


```
**Literal**
```
var nome = “Cleiton”

var numero = 30

var bool = true

var item = {}

var item = {nome: “refrigerante”, preco: 5.1, descricao: “pet 2L”}

var produtos = []

var produtos = [‘sorvete’, ‘biscoito’, ‘banana’ ]

var regexpLiteral = /js/
var string = “Minha expressao com js”
regexpLiteral.test(string)
regexpLiteral.exec(string)

function soma(v1, v2) {
	return v1 + v2
}
console.log(soma(5,3))

try {

}
catch () {

} finally () {

}
function soma (a, b) {
	return a + b
}

```

**Construtor**
```
var nome = new String(‘Cleiton Bezerra’)
nome.length
nome.charAt(2)
nome.charCodeAt(2)
nome.indexOf(“C”)
nome.lastOf(“o”)
nome.concat(“Paiva”)
nome.substr(“Cleiton”)
nome.replace(“i”,”y”)
nome.split(“/”, -)
nome.toLowerCase()
nome.toUpperCase()
nome.match(/d/g)
nome.trim(()
nome.repeat(3)

var numero = new Number(30)
numero.toString()
numero.toFixed(2)
Number.parseInt()
Number.isInteger
Number.isNaN
numero.toPrecision(6)
numero.isFinite(2/2)
Number.MAX_VALUE
Number.MIN_VALUE

var bool = new Boolean(true)


var item = new Object()
item.nome = “refrigerante”
item.preco = 5.1
descricao = “pet 2L”

var produtos = new Array(‘sorvete’, ‘biscoito’,  ‘banana’)
produtos[0]
produtos[2] = “maca”

var data = new Date()
var data = new Date(“2020-10-23”)
data.getFullYear()
data.getMonth()
data.getDay()
data.getDate()
data.getHours()
data.getMinutes()

var regex = new RegExp(‘js’)

throw new Error(“ocorreu erro”)

```

**ESCOPO GLOBAL**
```
fora de metodo e objeto é global
var a = 2 ou a = 2

```

**ESCOPO LOCAL**
```
variaveis dentro de objeto ou funcao

```
```
const = constante;
var = escopo global;
let = escopo local;

let nao sofre hosting

var pessoa = {nome: 'Ana', idade: 20};
var {nome, idade} = pessoa;
console.log(nome, idade);

var {nome: n, idade: i} = pessoa;
console.log(n, i);

var genero, situacao = 'Ativa'} = pessoa;
console.log(genero, situacao);

var pessoa = {
	nome: 'Ana',
	endereco: { rua: 'A', numero: 100 }
}

var { endereco: { rua, numero, cep } } = pessoa;
console.log( rua, numero, cep);

var [a] = [10];
console.log(a);

var [n1, ,n3, ,n5, n6 = 0] = [10, 7, 9, 8];
console.log(n1,n3,n5,n6);

var [,[,nota]] = [[7,8,8],[9,6,8]];
console.log(nota)

```

**MAP**
```
let nomeString = {nome: "Cleiton", idade: 34}
const map = new Map()
map.set(nomeString, sexo)
map.get(nomeString)
map.delete(nomeString)
map.has('cleiton')

```

**WEAKMAP**
```
WeakMap.prototype.set()
WeakMap.prototype.get()
WeakMap.prototype.has()
WeakMap.prototype.delete()

const weakMap = new WeakMap()
weakMap.set(objeto, objeto)
weakMap.get(objeto)
weakMap.has(objeto)
weakMap.delete(objeto)

```

**SET**
```
const set = new Set([1, 2, 3])
set.add(23)
set.add({teste: 'teste'})
set.size
set.delete(1)

```

**WEAKSET**
```
const weakSet = new weakSet()
weakSet.add(objeto)
weakSet.has(objeto)
weakSet.add(objeto)
weakSet.delete(objeto)

```

**SPREAD**
```
function mostrarNumeros(a, b, c, d){
	console.log(a, b, c, d)
}
const arrayNumeros = [1, 2, 3, 4, 5, 6, 7, 8, 9]
mostrarNumeros(...arrayNumeros)

let arrayLetras = [a, b, c, d]
let arrayNumeros = [1, 2, 3]
let arrayNumeros2 = [6, 8, 9]

let arraySpreed = [...arrayLetras, ...arrayNumeros, ...arrayNumeros2]


exemplo = spread + reduce

```

**TEMPLATE STRING**
```
let nome = "Cleiton"
let texto = `Template string ${5 + 5} ${nome}`

```

**ARROW**
```
const somar = (a, b) => {
	return a + b;
}
somar(10, 20)

```

**MELHORIAS LET**
```
let nome = "Maria", idade = 27, sexo = "F"
let objES5 = {nome: nome, idade: idade, sexo: sexo}
let objES6 = {nome, idade, sexo}

```

**MELHORIAS OBJETO**
```
objCalcES5 = {
	msg: function msg() {
		console.log('Olá')	
	},
	somar: function somar(a, b) {
		console.log(a + b)
	}
}
objCalcES5.msg()
objCalcES5.somar(10, 20)


objCalcES6 = {
	msg() {
		console.log('Olá')	
	},
	soma(a, b) {
		console.log(a + b)
	}
}
objCalcES6.msg()
objCalcES6.somar(10, 20)


objPropES5 = {
	nome: "Cleiton"
}
objPropES5["seq + 23"] = 23


objPropES6 = {
	nome: "Cleiton",
	["seq + 23"]: 23
}

```

**MELHORIAS DESTRUTURACÂO**
```
let objDest = {
	nome: "Cleiton",
	sexo: "M"
	idade: 34
} 
let es5 = objDest.nome
let {nome, idade} = objDest


let array = [1, 2, 3, 4, 5, 6, 7, 8, 9];
let [um, dois, tres,,,,,nove, dez] = array;


let pessoas = [
	{nome: 'Cleiton', telefone: '988378457'},
	{nome: 'Lilian', telefone: '993837481'}
]
let [, {nome, telefone}] = pessoas

```

**MELHORIAS CLASSE**
```
function PessoaES5(nome, cpf){
	this.nome = nome;
	this.cpf = cpf;
}
PessoaES5.prototype.nomeUpper = function() {
	return this.nome.toUpperCase();
}

function FuncionarioES5(nome, cpf, matricula){
	PessoaES5.call(this, nome, cpf);
	this.matricula = matricula
}

var objPessoaES5 = new PessoaES5('Cleiton', '33744628809')
objPessoaES5.nomeUpper()

FuncionarioES5.prototype = Object.create(PessoaES5.prototype)
FuncionarioES5.prototype.constructor = FuncionarioES5;

var objFuncionario = new FuncionarioES5("Cleiton", "3374460","12346")



class PessoaES6{
	constructor(nome, cpf){
		this.nome = nome;
		this.cpf = cpf;
	}
	nomeUpper(){
		return this.nome.toUpperCase();	
	}
}

class FuncionarioES6 extends PessoaES6{
	constructor(nome, cpf, matricula){
		super(nome, cpf);
		this.matricula = matricula
	}
}


var objPessoaES6 = new PessoaES6('Cleiton', '33744628809')
objPessoaES6.nomeUpper()
var objFuncES6 = new FuncionarioES6('Antonio', '122.444.566-89', '555')

```

**DOM – MODELO DE OBJETO DINÂMICO**
```
API de acesso a elementos da página

getElementById
getElementByTagName
getElementByName
getElementByClassName
querySelector
querySelectorAll  input[type=text]

createElement creatTextNode
appendChild insertBefore innerHTML
removeChild replaceChild

```

**IF**
```
var numero = 1
if (numero == 1) {
	console.log(“1”)
} else if (numero == 2) {
	console.log(“2”)
} else{
	console.log(“outro”)
}

```

**SWITCH**
```
var numero = 1
switch (numero) {
	case 1:
		console.log(“1”)
		break
	case 2:
		console.log(“2”)
		break
	default:
		console.log(“outro”)
		break
}

```

**FOR**
```
for (var i=0; i < 10; i++) {

}

FOR IN
var obj = {nome: “Cleiton”, idade: 34}
for (var chave in obj)  {
	console.log(chave)
}

FOR OF
var array = [“a”, “b”, “c”]
for (var valor of array) {
	console.log(valor)
}

```

**WHILE**
```
var i = 0
while (i < 10) {
	console.log(“i”)
	i++
}

```

**DO WHILE**
```
var i = 0
do {
	console.log(“i”)
} while (i < 10)

```

**HORA PARA HOSTS**
```
ntp.br

```

**SESSIONSTORAGE**
```
let key = "Key1";
sessionStorage.getItem(key);
sessionStorage.setItem(key, data: "Cleiton");
sessionStorage.removeItem(key)
sessionStorage.clear();

```

**LOCALSTORAGE**
```
let key2 = "localStorage";
localStorage.getItem(key);
localStorage.setItem(key, data: "Cleiton");
localStorage.removeItem(key)
localStorage.clear();
```

## FERRAMENTAS NODE
**WEBPACK**

**DEFINIÇÃO**
```
empacotador de modulos
npm install -y
npm install --save-dev webpack webpack-cli
webpack.config.js
const path = require('path');

```

**MÓDULOS**
```
module.exports = {
  entry: './src/index.js',
  output: {
    path: path.resolve(__dirname, 'dist'),
    filename: 'bundle.js'
  }
};

package.json
dev: "webpack --node development --watch",
build: "webpack --node production",

Crio as classes em seus arquivos
Crio as instancias das classes
import no index.js as instancias

babel-polyfill
let p = new Promise(function(resolve, reject){
	let teste = true;
	if (teste){
		resolve("ok")
	}else{
		reject("erro")
	}
})
p.then(retorno => {
	console.log(retorno)
}).catch(retorno => {
	console.log(retorno)
})

npm install --save-dev webpack-dev-server

```
**package.json**
```
start: "webpack-dev-server --node development --open"

npm install --save-dev style-loader
npm install --save-dev css-loader
```

**BABEL**

**DEFINIÇÃO**
```
Babel é um compilador javascript
transformar seu codigo moderno em uma versão antiga mais estavel.

```

**COMANDOS**
```
npm init -y
npm install --save-dev babel-cli babel-preset-env
.babel.rc
{
	"presets": [
	    [
	      "@babel/env"
	    ]
  	]
}

```
**package.json**
```
build: "babel src -d dist"
```


**GRUNT**


**DEFINIÇÃO**
```
Automatizador de tarefas

```

**INSTALAÇÃO**
```
npm install load-grunt-task  grunt-contrib-connect grunt-newer grunt-contrib-copy  grunt-contrib-compress  grunt-contrib-simlink grunt-contrib-concat --save-dev

```

**ARQUIVO**
```
Gruntfile.js
module.export = function(grunt) {
	require('load-grunt-task')(grunt)
	grunt.initConfig({
		jshint: {
			sample: {
				files: 'src/*.js'			
			}		
		},
		watch: {
			sample: {
				files: 'src/*.js',
				tasks: 'jshint'			
			}
		},
		connect: {
			server: {
				options: {
					base:'www',
					keepalive: true,
					open: {
						target: 'http://localhost:8000/index.html',
						appName: 'fff',
						callback: function() {
							console.log("OK")						
						}
					}				
				}			
			}		
		}
	})
	grunt.loadNpmTask('grunt-contrib-jshint');
	grunt.registerTask('default', []);
};

```

**COMANDO**
```
grunt
grunt connect watch
grunt copy
grunt compress
grunt simlink
grunt concat

```


**GULP**

**DEFINIÇÃO**
```
Plataforma de automatização de tarefas

```
**INSTALAÇÃO**
```
npm install gulp gulp-sass gulp-htmlmin gulp-notify del --save-dev 
npm install browser-sync --save-dev

```

**TAREFAS**
```
task, src, dest, watch, pipe

```

**DIRETÓRIOS**
```
src
dist

```

**ARQUIVO**
```
gulpfile.js
var gulp = require('gulp');
var html = require('gulp-htmlmin');
var sass = require('gulp-sass');
var notify = require('gulp-notify');
var browserSync = require('browser-sync').create();

gulp.task('sass', function(){
	return gulp.src('./src/scss/style.scss')
		.pipe(sass({outputStyle:"compressed"}))
		.on("error", notify.onError("Error: <%= error.message %>"));
		.pipe(gulp.dest('./dist/'));
		.pipe(browserSync.stream());
});

gulp.task('html', function(){
	return gulp.src('./src/index.html')
		.pipe(html({collapseWhitespace:true}))
		.on("error", notify.onError("Error: <%= error.message %>"))
		.pipe(gulp.dest('./dist/'));
});

gulp.task('BS', ['html', 'sass'], function(){
	browserSync.init({
		server: {
			baseDir: './dist/css'		
		}	
	})
	gulp.watch('./src/index.html', ['html']);
	gulp.watch('./src/scss/style.scss', ['sass']);
});

gulp.task('default', ['BS']);

```

**COMANDO**
```
gulp
```

## PREPROCESSADORES

**TYPESCRIPT**


**DEFINIÇÃO**
```
Super set do javascript criado pela Microsoft.

```

**INSTALAÇÃO**
```
npm install -g typescript

```
**ARQUIVO**
```
arquivo.ts

class Pessoa {
	nome: string
	constructor(pessoa: string){
		this.nome = pessoa;
	}
	exibirNome(){
		return `Ola ${this.nome}`
	}
}
let pessoa = new Pessoa("Cleiton");
console.log(pessoa.exibirNome())

```

**VARIAVEIS**
```
var p1: string = "Ola";
let p2: string = 'Bom Dia';
const pi: number = 3.14;
readonly bonus: number;

```

**TIPO DE DADOS**
```
let nome: string = "Cleiton";
let numero1: number = 45;
let numero2: number = 12.5;
let ativo: boolean = true;
let teste: any 
let array1: number[1, 2, 3];
let array2: Array<string> = ['a', 'b', 'c'];
let array3: any[] = ['a', 2, true]
let tuple: [string, number] = ["cleiton", 22]
let exemplo1: undefined;
let exemplo2; null;

(<string> var1)
(va1 as string)


enum Day{SEGUNDA, Terça}
let day: Day = Day.SEGUNDA

```
**FUNCOES**
```
function func(): void {
	console.log("Teste")
}

function add(v1:number, v2:number, v3?:number): number{
	if (v3 !== undefined)
		return v1 + v2 + v3

	return v1 + v2
}


let sum = (n1: number, n2: number) => n1 + n2
let sum = (n1: number, n2: number) => { return n1 + n2 }

```
**OPERADORES**
```
===, !==

```

**FOR**
```
let array = ["Cleiton", "LLLL"];
for(let i = 0; i < array.length; i++){
}

for(let prop in array){
}

for(let prop of array){
}

```

**MAP**
```
let nam = new Map<string, number>();
nam.set("Adao", 14);

```
**SET**
```
let nameset = new Set<string>();
nameset.add("Cleiton");
nameset.has(value: "Cleiton");
nameset.delete(value: "Cleiton");

```
**PROMISE**
```
let promise = new Promise((resolve, reject)=> {
	let isOpen: boolean = true;
	if (isOpen) {
		resolve("open");
	}else {
		reject("erro");
	}
})
promise.then(onfull: (res) => {
	console.log(res);
}).catch(onreject: (rej) => {
	console.log(rej);
})

```

**DECORATOR**
```
@course
class Person{
	name: string;
}

function course(target: any){
	Object.defineProperty(target.prototype, propertyKey: "course", attribute: {value: () => "Typescript"})
}
let p24 = new Person();
p24.course()
@course({
	course: "Dev"
})

```


**INTERFACES**
```
interface Person {
	name: string;
}

interface Employee extends Person {
	salary: number;
}

let pe: Person = {name: "Cleiton"};
let emp: Employee = {name: "Cleiton", salary: 2000};

```


**CLASSES**
```
class Person{
	private _name: string;
	constructor(name: string){
		this._name = name;
	}
	print(): void{
		console.log(`${this._name}`)
	}

	get name() {
		return this._name
	}

	set name(value: string){
		this._name = value;
	}

}

class Employee extends Person{
	private _salary: number;
	constructor(name: string, salary: number){
		super(name);
		this._salary = salary;
	}
	print(): void{
		super.print();
		console.log(`${this._salary}`)
	}

	get salary(): number{
		return this._salary;
	}

	set salary(value: number){
		this._salary = value;
	}
}
let p1 = new Person("Cleiton");
let emp = new Employee("Cleiton", 5000)

```

**NAMESPACE**
```
namespace validacao {
	let emailRegex:RegExp = ;
	export class EmailValidacao{
		return(): boolean{
			return emailRegex.test(str);		
		}
	}
}

import EmailValidacao = Validation.EmailValidacao
let emailExample = ["lll@bol.com.br"]
emailExample.forEach((email) => {
	console.log(`${new EmailValidacao().isValid(email)}`)
})


arquivo.ts
export class EmailValidacao{
	return(): boolean{
		return emailRegex.test(str);		
	}
}

arquivo2.ts
import {EmailValidacao} from "./arquivo.ts"

```

**ERRO**

```
try{

} catch (err) {
	throw err;
	console.log("Erro");
} finally {
	console.log("sempre");
}

```


**COMANDO**
```
tsc helloword.ts

```


## FRAMEWORKS JS
**ANGULARJS**

**BIND**
```
<div ng-app="">
  <p>Name: <input type="text" ng-model="name"></p>
  <p ng-bind="name"></p>
</div>

```

**EXPRESSÕES**
```
<div ng-app="">
  <p>My first expression: {{ 5 + 5 }}</p>
</div>

```

**MÓDULOS**
```
<div ng-app="myApp">...</div>

<script>

var app = angular.module("myApp", []);

</script>

```

**DIRETIVAS**
NG-APP NG-MODEL NG-INIT NG-SHOW NG-DISABLE NG-HIDE NG-REPEAT
```
<div ng-app="" ng-init="firstName='John'">

<p>Name: <input type="text" ng-model="firstName"></p>
<p>You wrote: {{ firstName }}</p>

</div> 

<div ng-app="myApp" ng-controller="myCtrl">
  Name: <input ng-model="name">
</div>

<div ng-app="myApp" ng-controller="myCtrl">
  Name: <input ng-model="name">
  <h1>You entered: {{name}}</h1>
</div>

<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope) {
  $scope.name = "John Doe";
});
</script> 

<form ng-app="" name="myForm">
  Email:
  <input type="email" name="myAddress" ng-model="text">
  <span ng-show="myForm.myAddress.$error.email">Not a valid e-mail address</span>
</form>

<form ng-app="" name="myForm" ng-init="myText = 'post@myweb.com'">
  Email:
  <input type="email" name="myAddress" ng-model="myText" required>
  <h1>Status</h1>
  {{myForm.myAddress.$valid}}
  {{myForm.myAddress.$dirty}}
  {{myForm.myAddress.$touched}}
</form>


<div ng-app="" ng-init="mySwitch=true">

	<p>
		<button ng-disabled="mySwitch">Click Me!</button>
	</p>

	<p>
		<input type="checkbox" ng-model="mySwitch">Button
	</p>

	<p>
		{{ mySwitch }}
	</p>

</div>


<div ng-app="">

	<p ng-hide="true">I am not visible.</p>

	<p ng-hide="false">I am visible.</p>

</div> 

<div ng-app="" ng-init="names=['Jani','Hege','Kai']">
  <ul>
    <li ng-repeat="x in names">
      {{ x }}
    </li>
  </ul>
</div>

```

**COMPLETO**
```
<div ng-app="myApp" ng-controller="myCtrl">
  <h1 ng-click="changeName()">{{firstname}}</h1>
</div>

<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope) {
  $scope.firstname = "John";
  $scope.changeName = function() {
    $scope.firstname = "Nelly";
  }
});
</script>

```

**ESCOPO**

```
$scope.minhaVariavelTexto = "texto"

$scope.minhaVariavelNumerica = 2

$scope.ativo = true

```

```
<div ng-app="myApp" ng-controller="myCtrl">

<h1>{{carname}}</h1>

</div>

```
```
<script>
var app = angular.module('myApp', []);

app.controller('myCtrl', function($scope) {
  $scope.carname = "Volvo";
});
</script> 

```

**FILTRO**
```
{ firstName | uppercase }
{ firstName | lowercase }

```
```
<div ng-app="myApp" ng-controller="namesCtrl">

<ul>
  <li ng-repeat="x in names | orderBy:'country'">
    {{ x.name + ', ' + x.country }}
  </li>
</ul>

</div>

```

```
<div ng-app="myApp" ng-controller="costCtrl">
	<h1>Price: {{ price | currency }}</h1>
</div> 

```


```
<div ng-app="myApp" ng-controller="namesCtrl">

<table border="1" width="100%">
  <tr>
    <th ng-click="orderByMe('name')">Name</th>
    <th ng-click="orderByMe('country')">Country</th>
  </tr>
  <tr ng-repeat="x in names | orderBy:myOrderBy">
    <td>{{x.name}}</td>
    <td>{{x.country}}</td>
  </tr>
</table>

</div>

```
```
<script>
angular.module('myApp', []).controller('namesCtrl', function($scope) {
  $scope.names = [
    {name:'Jani',country:'Norway'},
    {name:'Carl',country:'Sweden'},
    {name:'Margareth',country:'England'},
    {name:'Hege',country:'Norway'},
    {name:'Joe',country:'Denmark'},
    {name:'Gustav',country:'Sweden'},
    {name:'Birgit',country:'Denmark'},
    {name:'Mary',country:'England'},
    {name:'Kai',country:'Norway'}
  ];
  $scope.orderByMe = function(x) {
    $scope.myOrderBy = x;
  }
});
</script> 

```


**SERVIÇOS**
```
var app = angular.module('myApp', []);
app.controller('customersCtrl', function($scope, $location) {
    $scope.myUrl = $location.absUrl();
}); 

var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope, $http) {
  $http.get("welcome.htm").then(function (response) {
    $scope.myWelcome = response.data;
  });
});

var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope, $timeout) {
  $scope.myHeader = "Hello World!";
  $timeout(function () {
    $scope.myHeader = "How are you today?";
  }, 2000);
});


var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope, $interval) {
  $scope.theTime = new Date().toLocaleTimeString();
  $interval(function () {
    $scope.theTime = new Date().toLocaleTimeString();
  }, 1000);
});

```

**HTTP**
```
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope, $http) {
  $http.get("welcome.htm")
  .then(function(response) {
    $scope.content = response.data;
    $scope.statuscode = response.status;
    $scope.statustext = response.statusText;
  });
});


var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope, $http) {
  $http.get("wrongfilename.htm")
  .then(function(response) {
    // First function handles success
    $scope.content = response.data;
  }, function(response) {
    // Second function handles error
    $scope.content = "Something went wrong";
  });
}); 

```

**SELECT**
```
<select ng-model="selectedCar" ng-options="y.brand for (x, y) in cars">
</select>

```

**EVENTOS**

```
    ng-blur
    ng-change
    ng-click
    ng-copy
    ng-cut
    ng-dblclick
    ng-focus
    ng-keydown
    ng-keypress
    ng-keyup
    ng-mousedown
    ng-mouseenter
    ng-mouseleave
    ng-mousemove
    ng-mouseover
    ng-mouseup
    ng-paste

```

```
<div ng-app="myApp" ng-controller="myCtrl">

<button ng-click="count = count + 1">Click me!</button>

<p>{{ count }}</p>

</div>
<script>
var app = angular.module('myApp', []);
app.controller('myCtrl', function($scope) {
  $scope.count = 0;
});
</script> 

```

**INCLUDE**
```
<body ng-app="">

	<div ng-include="'myFile.htm'"></div>

</body> 

```

**ROTAS**
```
<body ng-app="myApp">

<p><a href="#/!">Main</a></p>

<a href="#!red">Red</a>
<a href="#!green">Green</a>
<a href="#!blue">Blue</a>

<div ng-view></div>

<script>
var app = angular.module("myApp", ["ngRoute"]);
app.config(function($routeProvider) {
  $routeProvider
  .when("/", {
    templateUrl : "main.htm"
  })
  .when("/red", {
    templateUrl : "red.htm"
  })
  .when("/green", {
    templateUrl : "green.htm"
  })
  .when("/blue", {
    templateUrl : "blue.htm"
  });
});
</script>
</body>


```

**ANGULAR**

**DEFINIÇÃO**
```
> 2 rescrito com typescript, spa, web, mobile, desktop

```

**INSTALAÇÃO**
```
npm install -g @angular/cli

npm install bootstrap jquery popper
angular.json adicionar os styles e scripts

```

**COMANDO**
```
ng new myapp
cd myapp
ng serve ou ng serve --open 
porta 4200
ng build
ng build --prod

ng --version

```

**COMPONENTES**
```
ng g c /componentes/home/home-carousel

import {HomeComponente} from 'componentes/home/home-carousel.component'


<a [router-link]=['home/home-carousel'] routerLinkActive="router-link-active"> Home </a>

<router-outlet><router-outlet>

```

**DECORATORS**
```
@NgModule, @Component

```

**CLASSES**
```
ng generate class classes/ConfigClass

```

**SERVIÇOS**
```
ng generate service servicos/galeria/galeria

```

**BIBLIOTECAS**
```
ngBootstrap

```

**EVENTOS**
```
ngOnInit()
(change) = ""
(click) = ""

```
**DIRETIVAS**
```
*ngIf, 
*ngSwitch 
*ngFor = ""
[hidden] = ""
[formGroup] = ""
formControlName = ""
(ngSubmit) = "onSubmit()"
[(ngModel)] = "pessoa.id"

```

**FILTROS**
```
{{ filtro.nome |uppercase }}
{{ filtro.nome |lowercase }}
{{ filtro.salario |currency }}

```

**PACKAGE.JSON**
```
"scripts": {
	"ng": "ng"
	"start": "ng serve"
	"build": "ng build"
	"test": "ng test"
	"lint": "ng lint"
	"e2e": "ng e2e"
}

```

**COMANDOS IMPORTANTES**
```
npm install -g @angular/cli

ng --version

ng new myapp

cd myapp

ng serve ou ng serve --open  
(porta 4200)

ng build

ng build --prod

```
**VUEJS**

```
new Vue({
    el: '#app'.
    data: {
        msg: 'Teste',
        idade: 34,
        frutas: ['maçã', 'banana', 'uva'],
        aluno: {nome: 'Cleiton', ra: '23232'},
        url: 'http://vuejs.org',
        texto: '<b> teste </b>',
        input: '',
        show: true
    },
    methods: {
        minhaFuncao(){
            return this.frutas
        },
        alert(event){
            event.target.style = "background: red";
        }
    }
})

```

**BIND**
```
<img v-bind:src="img" v-bind:title></img>


<a v-bind:href="url"> Vue</a>

v-bind:src = :src 
v-bind:title = :title
v-bind:href = :href

v-bind:class="{red: colors.vermelho}"
```

**TEXTO**
```
<p v-text="texto"> Paragrafo</p>

```

**HTML**
```
<div v-html="texto"> Div </div>

```
**MODEL**
```
<input type="text" v-model="input">

```
**IF/ELSE**
```
<p v-if="show == true"> 1</p>
<p v-else="show == false"> 2</p>

```
**FOR**
```
<ul>
    <li v-for="(fruta, index) in frutas"> {{fruta}}</li>
</ul>

```
**CLICK**
```
<button v-on:click="minhaFuncao()"> 
    Botão 
</button>

v-on:click = @click
:click = nao pode pq começa a chamar direto

<form v-on:submit.prevent="minhaFuncao">
</form>

v-on:keyup.enter="minhaFuncao()"
v-on:keyup.space="minhaFuncao()"

```

**COMANDOS IMPORTANTES**
```
npm install -g @vue/cli

vue --version

vue create myapp

cd myapp

npm run serve
porta 8080

```

**REACT**

**usa jsx que é dom virtual**

**CLI**
```
npm install -g create-react-app

create-react-app --version

npx create-react-app myapp

cd myapp

npm start (rodando na porta 3000)

```

**Exemplos**
**Exemplo 1**

**src/app.js**
```
import React from 'react';
import ReactDom from 'react-dom';

ReactDom.render(
    <h1>Olá mundo</h1>,
    document.getElementById("app")
);

```

**index.html**
```
<html>
<body>
    <div id="app"></div>
    <script src="/js/app.min.js"></script>
</body>
<html>

```

**Exemplo 2**
**src/components/App.js**
```
import React from 'react';

export default class App extends React.Component {
    render() {
        return <h1> Olá Mundo </h1>
    }
}

```

**src/app.js**
```
import React from 'react';
import ReactDom from 'react-dom';

import App from './components/App';

ReactDom.render(
    <App />,
    document.getElementById("app")
);

```


**index.html**
```
<html>
<body>
    <div id="app"></div>
    <script src="/js/app.min.js"></script>
</body>
<html>

```

**COMANDOS IMPORTANTES**
```
npm install -g create-react-app

create-react-app --version

npx create-react-app myapp

cd myapp

npm start
porta 3000

```

## FRAMEWORKS MOBILE
**IONIC**

**DEFINIÇÃO**
```
plataforma mobile

```

**INSTALAÇÃO**
```
npm install ionic cordova -g
ionic start exemplo blank
cd exemplo

ionic cordova platform add ios
ionic cordova run ios

Substitute ios for android if not on a Mac.


npm install -g ionic@latest

```

**COMANDOS**
```
ionic -v
ionic start myapp tabs
ionic start exemplo sideMenu --type=angular
ionic serve


ionic g page sobre


Aplicativo do celular para rodar
ionic dev

```

**ESTRUTURA**
```
config.xml (configurações para ios e android)
resources (para android e ios)
src (codificação)

```
**DIRETIVAS**
```
Baseado no angular

```

**BIBLIOTECAS**
```
npm i firebase angularfire2

```

**NATIVESCRIPT**

**COMANDOS**
```
tns create exemplo --template angular
cd exemplo
tns run android

tns resources generate splashes 

```
**DIRETIVAS E ARQUITETURA**
```
Baseado no angular

```



## JAVA

**DEFINIÇÃO**
```
baseada em C, OO
criada pela SUN Microsystem por meio do projeto Green chefiado por James Gosling
maskote duke
multiplataforma

``` 

**COMANDOS**
```
java -version
javac exemplo.java
java exemplo

```
**CONCEITOS**
```
JVM -> Maquina Virtual JAVA
JRE -> Ambinte de Execução Java
JDK -> Kit de Desenvolvimento Java

```

**Escrever na tela**
```
System.out.println("Teste")

```

**COMENTÁRIOS**
```
// Uma linha

/*
Varias 
Linhas
*/

```
**VARIÁVEIS**
```
String nome = "Cleiton";

```
**CONSTANTES**
```
final PI = 3.14;

```

**TIPOS DE DADOS**
```
String nome = "Meu Nome";
Integer idade = 43;
Double d = 10.2;
Float f = 100.45;
boolean ativo = true;
(Long Short Byte)

```

**OPERADORES**
```
ARITMÉTICOS + - * / %
LÓGICOS && || !
COMPARAÇÃO = != > < >= <=

```

**ENTRADAS DE DADOS**
```
Integer valor;
Scanner scanner = new Scanner(System.in);
System.out.println("Informe um numero");

valor = scanner.nextLine();
System.out.println(valor + 1);

String nome = "Cleiton";
String sobrenome = "Paiva";
String nomeCompleto = nome + "" + sobrenome;



int a1 = 10; // tipo primitivo
Integer a2 = 10; // tipo oo a objeto tem métodos

```

**FUNÇÕES**
```
private helloWorld(String str) {
	return "Tamanho" + str.length() + "palavra"
}

public static void main(String[], args){
	Funcoes funcoes = new Funcoes();
	System.out.println(helloWorld("Ola"));
}


String nome = "Cleiton";
nome.charAt(0)
nome.startsWith("C");
nome.endsWith("on");
nome.substring(0,2);
nome.toUpperCase();
nome.toLowerCase();
nome.trim();
nome.length();

```

**EXCEÇÕES**


```
try{
	String str = "Bla Bla";
	str.charAt(200);
}catch(e){
	System.out.println(e);
}finally {
	System.out.println("Exceção");
}

```

## KOTLIN

**DEFINIÇÃO**
```
criada pela JetBrains
baseada JAVA, C#, Scala e Grovy
focada para plataforma Android

```

**COMENTARIOS**
```
// uma linha

/*
Duas
linha
*/

```
**ESCREVER NA TELA**
```
println("Hello World")
print("OI")

```
**VARIAVEL**
```
var idade = 19

```

**CONSTANTE**
```
val PI = 3.14

```
**INTERPOLAÇÃO**
```
println("idade $idade")

```

**TIPO DE DADOS**
```
var nome: String
var idade: Int
var salario: Double
var x: Float
var ativo: Boolean
var paises = arrayOf("Brasil, Colombia", "Chile")
paises[0] = "Bolivia"
paises.count()
paises.reverse()
paises.sortBy()

var cores = arrayListOf<String>("Vermelho", "Branca")
cores.add("Azul")
cores.remove("Branca")
cores.size
cores.last()
var ultimo = cores[cores.size - 1]

```



**CONVERSÃO**
```
x.toString()
x.toInt()
x.toFloat()
x.toDouble()

```

**ENTRADA E SAIDA**
```
var x = readLine()?toInt()!!

import javax.swing.JOptionPane
fun main(args: Array<String>){
	var nome = JOptionPane.showInputDialog("Digit o nome")
	var saida = String.format("%s %s", "Bem Vindo", nome)
	JOptionPane.showMessageDialog( parentComponent: null, saida)
}

```

**OPERADORES**
```
ARITMETICOS +, -, *, /, %

COMPARAÇÃO ==, !=, >, <, >=, <=, 
x is Int 

LÓGICOS && || !

ATRIBUIÇÃO =, +=, -=, *=, /=

```

**IF**
```
if(a>b){
	print("A")
}else if(b>a){
	print("B")
}else{
	print("A = B")
}


idade in 1..17

```

**WHEN**
```
when(idade){
	in 1..11 -> println("Criança")
	in 12..17 -> println("Adolescente")
	in 18..59 -> println("Adulto")
	else -> println("Idoso")
}

```

**WHILE**
```
var i = 0
while (i < 10) {
	println(i)
	i++
}

```


**DO WHILE**
```
var i = 0
do {
	println(i)
	i++
} while(i < 10)

```

**FOR**
```
for(var i = 0; i < 10; i++) {
	println(i)
}

```

**FOR IN**
```
for(fruta in frutas){
	println(fruta)
}

```

**FOREACH**
```
frutas.foreach({ fruta ->
	println(fruta.toUpperCase())

})

```


**FUNÇÕES**

```
fun main(args: Array<String>){
	var rs = somar(x: 10, y: 10)
	print($rs)

}

fun somar(x: Int, y: Int){
	var r = x + y
	return r
}

```




## RUBY

**DEFINIÇÃO**
```
OO, Tipagem Dinâmica, Reflexão, metaprogramação, interpretada
MRI interpretador de ruby
RVM Maquina virtual ruby
Tudo é objeto

```

**COMANDOS**
```
irb  //shell
exit
ruby arquivo.rb

gem install pry
pry

```

**SINTAXES**
```
arquivo.rb

```
**VARIAVEIS**
```
texto = "meu texto"

```
**CONSTANTE**
```
MAX_USUARIOS = 10

```

**ENTRADA E SAIDA**
```
puts "Digite seu nome"
nome = gets.chomp 
puts nome

puts "Digite a idade"
idade = gets.chomp.to_i
puts idade

```
**COMENTARIOS**
```
# uma linha

```

**TIPOS DE DADOS**

```
nome = "Cleiton"
texto = "b o m"
texto.strip // tira o espaços
texto.downcase! // deixa tudo minusculo
texto.upcase! // deixa tudo maiusculo
marca = "Volkswagem"
modelo = "Voyage"
frase = "#{marca} #{modelo}"
texto2 = <<EOS
a
linha
EOS


numero = 10
salario = 2000.50

ativo = true

nome_completo = nill

array = []
array = [1, 2, 3, 4]
array.size
array.empty?
array[0]
array[1..2] // da posicao 1 ao 2
array[0] = 44
array.push(10)
array.insert(0, 10) //0 => posicao
array.last()
array.first()
array.join ','
array.sort
array.each { |i| puts i}
array.reduce(0) { |resultado, proximo_valor| resultado + proximo_valor }
array.map { |numero * numero }

```
**SYMBOL**
```
:nome_completo

```
**HASH**
```
capitais = HASH.new ou capitais = {}
capitais = {acre: 'Rio Branco', saopaulo: 'Sao Paulo'}
capitais.delete(:acre)

hash = {nome: 'cleiton', idade: 20}
hash[:idade]

```
**RANGE**
```
1..10

```

**ESCOPO DE VARIAVEIS**
```
Do lado de fora escopo global
Dentro de função escopo local
$global

```
**OPERADORES**
```
ARITMÉTICOS +, -, *, /, %, **
COMPARAÇÃO >, >=, <, <=, ==, !=
lÓGICOS !, &&, ||, not, and, on

```

**IF**
```
if a > b then
	puts "a > b"
elseif
	puts "b > a"
else
	puts "iguais"
end

puts "A > B" if a > b

puts "B > A" unless a > b

```

**CASE**
```
marca = "tesla"
when "tesla"
	puts "Tesla"
when "ford"
	puts "Ford"
when "fiat"
	puts "FIAT"
else
	puts "SEM MARCA"
end

```

**WHILE**
```
i = 0
while i <= 10
	puts i
	i++
end


i = 0
begin
	puts i
	i++
end while i <= 10

```

**FOR**
```
for i in [10, 20, 30]
	puts i
end


for i in 1..10
	puts i
end

```

**LOOP DO**
```
loop do
	puts "loop infinito"
	break
end

```

**COLLECTIONS**
**EACH**
```
["laranja", "maça", "uva"].each do |fruta|
	puts fruta
end

["laranja", "maça", "uva"].each { |fruta puts fruta}

```

**UPTO**
```
10.upto(100) { |i| puts i }

```

**MAP**
```
array = [1, 2, 3, 4]
newarray = array.map do |a|
	a * 2
end

array.map! do |a|
	a * 2
end

```

**SELECT**
```
array = [1, 2, 3, 4, 5]
selection = array.select do |a|
	a >= 2
end
puts selection

```

**FUNÇÕES**
```
def talk
	puts 'Como vc está?'
end
talk


def talk(firstname, lastname)
	puts "#{firstname} #{lastname}"
end

firstname = "Cleiton"
lastname = "Paiva"
talk(firstname, lastname)

def sinal(color = 'vermelho')
	puts "#{color}"
end

sinal
color = 'verde'
sinal(color)



def soma(a, b)
	a+b
end
soma(1, 2)


lamb = -> () { puts "lambda" }

```

**GEM**
```
rubygens

```
```
gem install os
gem unistal os
require 'net/http'

require 'os'
def my_od
	if OS.windows?
		"Windows"
	elseif OS.linux?
		"Linux"
	elseif OS.mac?
		"MAC"
	else
		"Nao consegui identificar"
	end
end
puts "#{OS.cpu_count} #{OS.bits} #{OS.my_od}"

```

**CLASSES**
```
class Carro
	def velocidade_maxima
		250
	end

	def adiciona_marca(marca)
		@marca	= marca
	end

	def marca
		@marca
	end

end

novo_carro = Carro.new
puts "Variavel carro #{novo_carro}"

carro.adicion_marca("Ford")
puts carro.marca


class Moto
	attr_accessor :marca, :modelo
	# attr_reader :marca, :modelo // get
	# attr_write :marca, :modelo // set

	def velocidade_maxima
		250
	end

	def descricao
		"Marca #{marca} e modelo #{modelo}"
	end

end

moto = Moto.new
moto.marca = "Honda"
moto.modelo = "CB300"
puts "Marca" + moto.marca
puts "Modelo" + moto.modelo
puts "Descricao" + moto.descricao


class Caminhao
	attr_accessor :marca, :modelo

	def initialize(modelo, marca)
		@modelo = modelo
		@marca = marca
	end
end

caminhao = Caminhao.new
puts caminho

```

**HERANÇA**
```
class Automovel
	verifica_combustivel()
	def self.tipo_cambio
		puts "Manual"
	end

	def acelera
		puts "Acelerando Automovel"
	end


	private
		def verifica_combustivel
			puts "verifica combustivel"
		end
end


class Carro < Automovel
	def acelera
		puts "Verificando equipamentos"
		super
	end

end


Automovel.acelera
Automovel.tipo_cambio
Carro.tipo_cambio

```

**MODULO**
```
module Compartilhado
	def imprime_texto
		puts "Texto"
	end
end

class Carro
	include Compartilhado
	def metodo_carro
		puts "Carro"
	end
end
c = Carro.new
c.imprime_texto

```

**BLOCKS**

```
5.times {puts "teste}


numbers = [5, 10, 15]
numbers.each {!number| sum += number}

```

**REGEX**
```
/abc/.class

```

**TIME**
```
time = Time.now
puts time.year
puts time.day
puts time.month
```

**DEFINIÇÃO**
```
OO, Tipagem Dinâmica, Reflexão, metaprogramação, interpretada
MRI interpretador de ruby
RVM Maquina virtual ruby
Tudo é objeto

```

**COMANDOS**
```
irb  //shell
exit
ruby arquivo.rb

gem install pry
pry

```

**SINTAXES**
```
arquivo.rb

```
**VARIAVEIS**
```
texto = "meu texto"

```
**CONSTANTE**
```
MAX_USUARIOS = 10

```

**ENTRADA E SAIDA**
```
puts "Digite seu nome"
nome = gets.chomp 
puts nome

puts "Digite a idade"
idade = gets.chomp.to_i
puts idade

```
**COMENTARIOS**
```
# uma linha

```

**TIPOS DE DADOS**

```
nome = "Cleiton"
texto = "b o m"
texto.strip // tira o espaços
texto.downcase! // deixa tudo minusculo
texto.upcase! // deixa tudo maiusculo
marca = "Volkswagem"
modelo = "Voyage"
frase = "#{marca} #{modelo}"
texto2 = <<EOS
a
linha
EOS


numero = 10
salario = 2000.50

ativo = true

nome_completo = nill

array = []
array = [1, 2, 3, 4]
array.size
array.empty?
array[0]
array[1..2] // da posicao 1 ao 2
array[0] = 44
array.push(10)
array.insert(0, 10) //0 => posicao
array.last()
array.first()
array.join ','
array.sort
array.each { |i| puts i}
array.reduce(0) { |resultado, proximo_valor| resultado + proximo_valor }
array.map { |numero * numero }

```
**SYMBOL**
```
:nome_completo

```
**HASH**
```
capitais = HASH.new ou capitais = {}
capitais = {acre: 'Rio Branco', saopaulo: 'Sao Paulo'}
capitais.delete(:acre)

hash = {nome: 'cleiton', idade: 20}
hash[:idade]

```
**RANGE**
```
1..10

```

**ESCOPO DE VARIAVEIS**
```
Do lado de fora escopo global
Dentro de função escopo local
$global

```
**OPERADORES**
```
ARITMÉTICOS +, -, *, /, %, **
COMPARAÇÃO >, >=, <, <=, ==, !=
lÓGICOS !, &&, ||, not, and, on

```

**IF**
```
if a > b then
	puts "a > b"
elseif
	puts "b > a"
else
	puts "iguais"
end

puts "A > B" if a > b

puts "B > A" unless a > b

```

**CASE**
```
marca = "tesla"
when "tesla"
	puts "Tesla"
when "ford"
	puts "Ford"
when "fiat"
	puts "FIAT"
else
	puts "SEM MARCA"
end

```

**WHILE**
```
i = 0
while i <= 10
	puts i
	i++
end


i = 0
begin
	puts i
	i++
end while i <= 10

```

**FOR**
```
for i in [10, 20, 30]
	puts i
end


for i in 1..10
	puts i
end

```
**LOOP DO**
```
loop do
	puts "loop infinito"
	break
end

```

**COLLECTIONS**
**EACH**
```
["laranja", "maça", "uva"].each do |fruta|
	puts fruta
end

["laranja", "maça", "uva"].each { |fruta puts fruta}

```

**UPTO**
```
10.upto(100) { |i| puts i }

```

**MAP**
```
array = [1, 2, 3, 4]
newarray = array.map do |a|
	a * 2
end

array.map! do |a|
	a * 2
end

```

**SELECT**
```
array = [1, 2, 3, 4, 5]
selection = array.select do |a|
	a >= 2
end
puts selection

```

**FUNÇÕES**
```
def talk
	puts 'Como vc está?'
end
talk


def talk(firstname, lastname)
	puts "#{firstname} #{lastname}"
end

firstname = "Cleiton"
lastname = "Paiva"
talk(firstname, lastname)

def sinal(color = 'vermelho')
	puts "#{color}"
end

sinal
color = 'verde'
sinal(color)



def soma(a, b)
	a+b
end
soma(1, 2)


lamb = -> () { puts "lambda" }

```

**GEM**
```
rubygens

```
```
gem install os
gem unistal os
require 'net/http'

require 'os'
def my_od
	if OS.windows?
		"Windows"
	elseif OS.linux?
		"Linux"
	elseif OS.mac?
		"MAC"
	else
		"Nao consegui identificar"
	end
end
puts "#{OS.cpu_count} #{OS.bits} #{OS.my_od}"

```

**CLASSES**
```
class Carro
	def velocidade_maxima
		250
	end

	def adiciona_marca(marca)
		@marca	= marca
	end

	def marca
		@marca
	end

end

novo_carro = Carro.new
puts "Variavel carro #{novo_carro}"

carro.adicion_marca("Ford")
puts carro.marca


class Moto
	attr_accessor :marca, :modelo
	# attr_reader :marca, :modelo // get
	# attr_write :marca, :modelo // set

	def velocidade_maxima
		250
	end

	def descricao
		"Marca #{marca} e modelo #{modelo}"
	end

end

moto = Moto.new
moto.marca = "Honda"
moto.modelo = "CB300"
puts "Marca" + moto.marca
puts "Modelo" + moto.modelo
puts "Descricao" + moto.descricao


class Caminhao
	attr_accessor :marca, :modelo

	def initialize(modelo, marca)
		@modelo = modelo
		@marca = marca
	end
end

caminhao = Caminhao.new
puts caminho

```

**HERANÇA**
```
class Automovel
	verifica_combustivel()
	def self.tipo_cambio
		puts "Manual"
	end

	def acelera
		puts "Acelerando Automovel"
	end


	private
		def verifica_combustivel
			puts "verifica combustivel"
		end
end


class Carro < Automovel
	def acelera
		puts "Verificando equipamentos"
		super
	end

end


Automovel.acelera
Automovel.tipo_cambio
Carro.tipo_cambio

```

**MODULO**
```
module Compartilhado
	def imprime_texto
		puts "Texto"
	end
end

class Carro
	include Compartilhado
	def metodo_carro
		puts "Carro"
	end
end
c = Carro.new
c.imprime_texto

```

**BLOCKS**

```
5.times {puts "teste}


numbers = [5, 10, 15]
numbers.each {!number| sum += number}

```
**REGEX**
```
/abc/.class

```

**TIME**
```
time = Time.now
puts time.year
puts time.day
puts time.month
```


## DART

**Definição**
```
Linguagem de Programação do google. Também é fundamental para o flutter no quesito mobile e angular para web.

```
```
dart --version

```
**Escrever na tela**
```
arquivo.dart
void main () {
	String nome = 'Cleiton';
	print("Hello World" + nome);
}

```
**COMENTÁRIO**
```
// Uma Linha

/* 
	Varias
	linhas	
*/

```
**VARIÁVEIS**
```
var letra = "A";
dynamic idade = 34;

```
**TIPOS DE DADOS**
```
String nome = "Cleiton";

int numero = 5;
double number = 10.3

bool ativo = true;

List listaProdutos = [
1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 
arroz, 1.50, true
]
print(listaProdutos)
print(listaProdutos[10])

Map usuario = {
	'nome': 'Cleiton',
	'idade': 24,
	'altura': 1.72,
	'ativo': true
}
print(usuario.length)
print(usuario['nome'])

```

**CONSTANTES**
```
const name = "Cleiton";
final String name2 = "Cleiton";

```
**CONVERSÕES**
```
var number = int.parse('25');
var number2 = double.parse('5.10');
print(number.toString())
print(number.toStringAFixed())

```
**CONCATENAR**
```
String name = 'Bom' + 'Dia';
var frase = 'Muito bom $name';
var frase = 'Muito bom ${name.toUpperCase()}';

```
**LISTAS**
```
var list = [1, 2, 3];
list.add(4);
list.removeAt(0)

print(list.length);
print(list.first);
print(list.last);

var maps = {
	"nome": "Cleiton",
	"idade": 34,
	"sexo": "m"
}
print(maps["nome"]);
maps["nome"] = "Pedro";

Map<String, dynamic> maps = {
	"nome": "Cleiton",
	"idade": 34,
	"sexo": "m"
}

List<Map<String, dynamic>> cadastro = [];

```

**OPERADORES**
```
ARITIMÉTICOS (+, -, *, /, %)
COMPARAÇÃO (==, !=, >, <, <=, >=)
RELACIONAIS (&&, ||, !)

```
**IF**
```
import 'dart:io';
void main() {
	print("Digite uma idade");
	var input = stdin.readLineSync();
	var idade = int.parse(input);	

	if (idade >= 18) {
		print("Adulto");
	} else if (idade >= 12 && idade < 18) {
		print("Adolescente");
	else {
		print("Criança");
	}
}

```


**SWITCH**
```
String status = 'andamento';

switch (){
	case 'aberto':
	print("Aberto");
	break;

	case 'fechado':
	print("Fechado");
	break;

	case 'pendente':
	print("Pendente");
	break;

	case 'encerrado':
	print("Encerrado");
	break;
	
	default:
	print("Aberto");
	break;
}

```
**FOR**
```
for(int i = 0; i < 10; i++) {
	print(i);
}


List products = ['arroz', 'cafe', 'açucar']
for (var item in products) {
	print(i);
}

List<String> nomes = ["Cleiton", "Guilherme", "Ingrid", "Lilian", "Raiane"];

```

**WHILE**
```
int i = 0;
while (i < 10) {
	print(i);
	i++;
}

```

**FUNÇÕES**
```
void main(){
	print(soma(20, 30));
}
double soma(double a, double b) {
	double res = a + b;
	return res;
}

```
**ARQUIVOS**
```
calcular.dart
int calculate() {
	return 6 * 7;
}

import 'pakage:calcular/calcular.dart' as calcular
main(List<String> arguments) {
	print('Teste ${calcular.calculate()}')
}

```
**ESCOPO GLOBAL**

```
criar variavel fora do main

```

## FLUTTER

**Quem usa?**
```
nubank, globo, 
```

**Layout**
```
material
cupertino

```
**Animação** 
```
Flare

```
**Lotties**
```
https://lottiefiles.com/


```
```
Flutter Web
Dart na Web
DDC Dart2Js

```
**Requisição**
```
grpc
graphql
rest

```

```
teste de widget

engine c++ skia

```

**FERRAMENTA**
```
Flutter
Android Studio
Visual Studio Code
extensoes dart e flutter

flutter new project

flutter devices
flutter run -d emulator-5554

```

## PYTHON
**DEFINIÇÃO**
```
linguagem alternativa ao C, dinamica

```

**COMENTARIO**
```
# uma linha

""" 
varias
linhas
"""

```

**ENTRADA E SAIDA**
```
print("ola bom dia")

entrada = input("Digite seu nome")

inteiro = int(input("Digite inteiro"))
decimal = float(input("Digite decimal"))

```

**VARIAVEIS**
```
texto = "Olá mundo"

```

**TIPOS DE DADOS**
```
texto = "Olá mundo"

```
```
texto1 = "Bom"
texto2 = "Dia"
texto3 = texto1 + "" + texto2

nome = "cleiton"
len(nome)
nome[0:2]
nome.lower()
nome.upper()
nome.strip() //remove os espacos
saudacao = "Bom dia"
saudacao.split(" ")
saudacao.replace("Bom", "Otimo")

numero = 47
decimal = 24.7

ativo = true

lista1 = [1, 2, 3]
lista2 = ["a", "b", "c"]
lista3 = [1, "a", 2, true]

lista1[0]

tamanho = len(lista1)
print(tamanho)

lista1.append(4)
lista1.del[:] //tudo
lista1.del[:1, 3]

lista1.sort()
lista1.sort(reverse=True)

lista.reverse()

novalista = sorted(lista1)

```

**DICIONARIO**
```
dic = {"a": "ameixa", "b": "bola", "c": "cachorro"}
dic
dic["c"]

for i in dic.items():
	print(i)

 
for i in dic.values():
	print(i)

for i in dic.keys():
	print(i)

```

**OPERADORES**
```
ARITMETICOS (+, -, *, /, %, ^)
COMPARACAO (==, !=, >, >=, <, <=)
LOGICOS (and, or, !)

```

**COMANDOS**
```
arquivo.py

python
python arquivo.py

```

**IF**
```
if a > b:
	print("A maior")
elife a < b:
	print("B maior")
else:
	print("Sao iguais")

```
**WHILE**
```
x = 0
while x < 10:
	print(x)
	x = x + 1

```

**FOR**

```
lista1 = [1, 2, 3]
for i in lista1:
	print(i)

for i in range(0, 10, 1)
	print(i)

```

**ESCOPO GLOBAL E LOCAL**
```
Fora é global
Dentro da funcao é local

```
**FUNCOES**
```
def soma(a, b):
	print(a + b)

soma(2, 3)


import random
numero random.randint(0, 10)
print(numero)

```

**ARQUIVOS**
```
arquivo = open("arquivo.txt")
abrindo = arquivo.readlines()
for linha in linhas:
	print(linha)


arquivo = open("arquivo.txt")
abrindo = arquivo.read()

```
**TRATAMENTO DE EXCEÇÕES**
```
try:
	print(a/b)
except:
	print("Não divide por 0")
print(a/a)

```
**LISTA COMPREHENION**
```
x = [1, 2, 3, 4]
y = [i**2 for i in x]
z = [i for i in x if i%2==1]

```
**LISTA ENUMERATE**
```
lista = ["abacate", "bola", "cachorro"]
for i, nome in enumerate(lista):
	print(1,nome)

```
**LISTA FILTER**
```
def pares(i):
	if i % 2 == 0:
		return i

lista = [1, 2, 3, 4, 5, 6, 7]

lista_pares = filter(pares, lista)
print(List(lista_pares))

```
**LISTA MAP**
```
def dobro(x):
	return x+2

valor = [1, 2, 3, 4, 5]

valor_dobrado = map(dobro, valor)

valor_dobrado = list(valor_dobrado)
print(valor_dobrado)

```
**LISTA ZIP**
```
nomes = ["Cleiton", "Aparecido", "Guilherme"]
idades = [34, 59, 10]
alturas = [1.72, 1.70, 1.10]

for nome, idade, altura in zip(nomes, idades, alturas):
	print(nome, idade, valor)
```

## LUA

**INSTALAÇÃO**
```
apt-get install lua

```
**ENGINES**
```
(LOVE2D para jogos)

```
**ARQUIVO E EXTENSÕES**
```
arquivo.lua

```
**COMENTÁRIOS**
```
Comentários de uma linha ou várias
Operadores Aritméticos (+; -; *; /; %;)
Operadores de Comparação (>; <; >=; <=; ~=; ==)
Operadores Lógicos (and; or; not)
Váriaveis (letras, numero, undescore, sem espaço, case sensitivo, sem palavras reservados)
Tipos (String, Numero, Boolean, null ou nil)
Funções
IF
WHILE

```

**COMENTÁRIOS**
```
-- Exemplo de comentario
--[[ Exemplo
de 
varias
linhas
]]--

```

**ESCREVER NA TELA**
```
print("Ola Mundo")
print(123456)
print(1+1) 

```

**VÁRIAVEIS**
```
variavel = "ola mundo"

texto1 = "Bom"
texto2 = "Dia"
nome = "Caixa d\' agua"
outra = "Voce é \"rico\""
print(texto1 .. texto2 .. "(o^o)")

variavel2 = 45
novoNumero = -2
outroNumero = 3.14
operacao = 2 + 2

ativo = false
print(ativo == false)

umaVariavel = nil

```

**INTERAGINDO**
```
print("Qual é o seu nome")
nome = io.read()
print("Nome" .. nome)

```

**CHUNKS**
```
do

end

```
**FUNÇÕES**
```
function somar()
	print(1+1)
end
somar()

function somarDois(n1,n2)
	print n1 + n2
end
somarDois(2,2)

function somarDois2(n1,n2)
	return n1 + n2
end
print(somarDois2(2,2))


function genSoma(parcela)
	function s (b)
		return parcela + b
	end
	return s
end
soma2 = genSoma(2)
print(soma2(10))

function join(sep, words)
	return table.concat(words, sep)
end
print("Cachorro ".."quente")

```
**ESCOPO GLOBAL**
```
-- (global)
nome = "Jesus" 

```
**ESCOPO LOCAL**
```
function qualONOme(nome)
	-- (local)
	print(nome)
end
qualONome("Alfred")

local variavel --posso colocar dentro de um bloco

```
**WRAPPER**
```
tostring(string)
tonumber(number)
valor
isNaN(valor)

```

**TABELA**
```
a = {10, 20, 30}
table.insert(a, 41)

```

**IF**
```
if (valor1 > valor2) then
	print("Valor1 maior")
elseif(valo1 == valor2)
	print("Valores iguais")
else
	print("Valor2 maior")
end


if (n1 > n2) and (n1 > n3)
	print("N1 maior")

```


**WHILE**
```
indice = 0
while indice <= 10 do
	print(indice)
	indice = indice + 1
end

```
**FOR**
```
for i = 1, 10, 1 do
	print(i)
end

```
**REPEAT**
```
indice = 0
repeat
	print(indice)
	indice = indice + 1
until indice <= 10

```

**VETOR = TABELA**
```
inimigos = { 10, 13, 50, 80 }
print(#inimigos)
print(inimigos[3])
inimigos[3] = 99

qtde = #inimigos
inimigos[qtde + 1] = 33
print(inimigos[11])
inimigos[#inimigos + 1] = 260

for idx = 1, #inimigos, 1 do
	print(idx)
end

itens = {
	machado = 1000,
	["espada"] = 450,
	escudo = 500,
	Elmo = 150,
	chave = 45
}

print(itens["machado"])
print(itens.machado)
itens.armadura = 1000
print(itens.armadura)

contagem
for chave, valor in pairs(items) do
	print(chave .. ":" .. valor)
	contagem = contagem + 1
end

cores = {
	moeda = "amarela"
	armadura = "prateada"
}
print(cores.moeda)
posicoes = {
	arqueiro = {10, 20},
	canhao = {120, 40}
}
posicoes.arqueiro["arqueiro"][1]

pessoa = {}
pessoa = {
	nome = "Cleiton",
	idade = "34",
	endereco = "Av. XV de Novembro, 123",
}

```
**BIBLIOTECAS**
```
math.floor(0.5)
math.max(3, 6, 2, 7)
math.sqrt(81)
string.gsub("LUA", "Lua")
io.lines("mapa.txt")

for line in to.lines("mapa.txt") do
	print(line)
end

require("nomedopacote")
local calculadora = {
	somar = function(x, y)
		return x + y
	end
}
return

local calculadora = require("calculadora")
print(calculadora.somar(1, 1))


partes = split("abcde", ",")
for i, v in ipairs(partes) do
	print(i, v)
end

conteudo = "bla bla"
split(conteudo, " ")

trim(" agua") => "agua"

io.write("Digite algo")
a = io.read()
print("!" .. a .. "!")

arquivo = io.open("teste.txt")
arquivo:write("" .. conteudo ..)
arquivo:close()


conteudo = io.open("teste.txt")
if conteudo == nill then
	error("Erro ao abrir")
end

pcall(io.open, "arquivoProblematico", "r")

```
**MODULARIZAÇÃO**
```
dofile("arquivo.lua")

meumodulo = require("arquivo")
meumodulo = require "arquivo"
return meumodulo

package.path

package.cpath

```

**POO**
```
arquivo conta.lua
local conta = {}
function conta.novo(deposito_inicial)
	return {
		saldo = deposito_inicial,
		depositar= function(self, valor)
			self.saldo = self.saldo + valor
		end
	}
end
return conta

arquivo banco.lua
local conta = require("conta")
local banco_brasil = conta.novo(500)
assert(banco_brasil.saldo == 500)
banco_brasil:depositar(500)
assert(banco_brasil.saldo == 1000)
```

## JULIA

**DEFINIÇÃO**
```
Julia é projetado para resolver problemas matemáticos numericamente, que consiste na manipulação numérica dos dados. A maioria dos problemas matemáticos reais (particularmente em engenharia) não têm soluções simbólicas puras.
Aparentemente o nome surgiu a partir de uma conversa aleatória entre os criadores quando alguém sugeriu arbitrariamente que "Julia" seria um bom nome para uma linguagem de programação

```
**JULIABOX**
```
A maneira mais fácil de testar a linguagem de programação Julia é através do JuliaBox. O JuliaBox é um ambiente de programação hospedado na nuvem da Microsoft Azure para codificação em Julia sem a necessidade de inslar qualquer software no computador local. Além da interface do Jupyter para escrever códigos, o JuliaBox permite realizar o download do código em outros formatos (.pdf, .md, .rst, .html e .tex), gerar slides, editar textos científicos em latex e markdown, importação/exportação de projetos para o GitHub e muitas outras funcionalidades.

```

**JUPITER**
```
O Jupyter é uma aplicação web derivado do IPython que significa JUlia, PYthon, and R . Resumidamente, é um ambiente computacional interativo que permite aos usuários criar "notebooks" que incluem: código, widgets interativos, gráficos, texto, equações, imagens, vídeo e outros. O Jupyter combina três componentes:

* O Jupyter Notebook: um aplicativo web interativo para escrever e executar códigos de várias linguagens de programação.

* Kernels: "Os kernels são processos específicos de linguagem de programação que funcionam independentemente e interagem com os aplicativos Jupyter e suas interfaces de usuário" (JUPYTER, 2017). Jupyter possui suporte para mais de 50 linguagens de programação (github.com/jupyter/jupyter/wiki/Jupyter-kernels), incluindo as mais populares em computação científica como Python, R, Julia e Scala. O IJulia.jl é kernel da linguagem Julia.

* Notebooks: são arquivos com extensão ipynb que contêm a estrutura do código no formato JSON. Cada notebook possui seu próprio kernel.

```

**COMANDOS**

```
versioninfo()
? versioninfo
Sys.cpu_info()
Sys.KERNEL
Sys.cpu_summary()

```

**OPERADORES ARITMÉTICOS**
```
+x 	Operador unário de adição
-x 	Operador unário de subtração
x + y 	Operador binário de adição
x - y 	Operador binário de subtração
x * y 	Operador binário de multiplicação
x / y 	Operador binário de divisão
x ÷ y 	Operador binário de divisão inteira
x \ y 	Operador binário de divisão esquerda
x ^ y 	Operador binário de potência
x % y	Operador binário de resto da divisão

```
**OPERADORES DE COMPARAÇÃO**
```
== 	Igual a
=! 	Diferente
> 	maior que
< 	menor que
>= 	maior igual
<= 	menor igual

    isequal(x, y) , verdadeiro se x e y são idêntico
    isfinite(x) , verdadeiro se x é um número infinito
    isinf(x) , verdadeiro se x é infinito (inf)
    isnan(x) , x não é um número
```

**OPERADORES LÓGICOS**
```
~x 	Negação
x & y 	E
`x 	y` 	OU
x ⊻ y 	Ou exclusivo
x >>> y 	deslocamento para a direita
x >> y 	arithmetic shift right
x << y 	logical/arithmetic shift left
```

**IMPRESSÃO**
```
print(sind(45))
println(sind(45))
display(sind(45))
@show sind(45)

```
**FUNÇÕES**
```
rand(0:10)
gcd(7, 14)  //MDC
lcm(60, 50) // MMC
factorial(5)



function raizQ(x)
    if x >= 0
        sqrt(x)
    else
        throw(DomainError(x, "A solução é de domínio complexo"))
    end
end


function raizQ_Er(x)
    
    if x >=0        
        sqrt(x)
    else
        error("Número negativo: $x. Não é possivel calcular raiz Real")
    end
end


function raizQ_TC(x)
    try
         sqrt(x)
    catch
         sqrt(complex(x))
    end
end

```

**FÓRMULAS**
```
s0 = 2
v = 4
t = 10
s0, v, t
s = s0 + v*t
print("O valor do espaço final S é: ",s ,"m")

```


**TIPOS DE DADOS**
```
# real e imaginário
complex(8, 4)

```


**Real e Imaginário**
```
1 + 2im

conj(2 + 3im)


d1 = Dict([("a", 1), ("b", 2),("c", 10)])

```



**IF**
```
if x < y
    println("x é menor que y")
end




if x < y
    println("x é menor que y .","Valor de x: ", x ," Valor de y: ",y)
else
    println("x é maior que y .","Valor de x: ", x ," Valor de y: ",y)
end


if x < y
    println("x é menor que y . Valor de x: $x , Valor de y: $y")
    
elseif x > y
    println("x é maior que y . Valor de x: $x , Valor de y: $y")
    
else
    println("x é igual que y . Valor de x: $x , Valor de y: $y")
end

```

**NÃO TEM O SWITCH**


**FOR**


```
# Laço FOR aplicado a um vetor
print("Valor da função f(x) = sin(x)*cos(x/2)+x: \n\n")
x = [1.0, 4.0, 6.0, 7.0, 9.0] 

for i = 1:length(x)     
    println("f($(x[i])) = ", sin(x[i])*cos(x[i]/2))
end


# Laço FOR aplicado a um vetor
print("Valor da função f(x) = sin(x)*cos(x/2) + x: \n\n")
x = [1.0, 2.0, 3.0, 4.0, 5.0] 

for i = x  # pode ser também x in     
    println("f($i) = ", sin(i)*cos(i/2)) 
end


# Laço FOR aplicado a um vetor
print("Valor da função f(x) = sin(x)*cos(x/2) + x: \n\n")

for x = [1.0, 2.0, 3.0, 4.0, 5.0] # pode ser também x in vetor    
    println("f($x) = ", sin(x)*cos(x/2) )   
end




# Laço FOR aplicado a um vetor com controle de tempo
print("Valor da função f(x) = sin(x)*cos(x/2) + x: \n\n")

for x = [1.0 2.0 3.0 4.0 5.0] # pode ser também x in vetor    
    println("f($x) = ",sin(x)*cos(x/2) )  
    sleep(1)                  # atraso de 1s
end


# Laço FOR aplicado a um vetor reverso
print("Valor da função f(x) = sin(x)*cos(x/2) + x: \n\n")

for x = 5:-1:1 # pode ser também x in vetor    
    println("f($x) = ",sin(x)*cos(x/2) + x)   
end


```
**WHILE**
```
# conta enquanto "a" menor ou igual a 5.
a = 0

while a <= 5    
    println(a)
    a += 1 
end


# conta enquanto "a" menor que o tamanho de b
a = 0
b = 1:5

while  a < length(b) 
    println(a)
    a += 1   
end


DO



# findall retorna o indice do vetor quando encontrar o valor igual a 5
x = 1:0.1:20

findall(x) do x
    x == 5     
end

```




**PACOTES**
```
using Pkg
Pkg.devdir()
Pkg.installed()
Pkg.status()
Pkg.test("Nome_pacote")
Pkg.update()


using Pkg
Pkg.add("Nome_Pacote")
Pkg.add("SymPy")

Pkg.clone("https://github.com/usuario/pacote.jl.git")


Pkg.rm("nome_pacote")
Pkg.rm("SymPy")



using SymPy

x , y = Sym("x , y")

(x, y)

```

**ESCOPO GLOBAL E LOCAL**
```
x = 3; # global
function foo(x)
    x = 2*x; # local 1
    function bar()
        println(x) # x local 1 é visível dentro do escopo local 2 (dentro de bar)
    end
    bar()
    println(x)
end
foo(x)
println(x)


```
**VETORIAIS**
```
v = [1, 2, 3]
u = [4, 5, 6]

display(u + v)
display(u - v)



using Plots
gr()

plot(collect(-5:0.1:5), x -> x^2 - 3*x - 2, label = "equação", size = (400, 300),
    xaxis = ("x", -5:1:10),
    yaxis = ("y", -5:5:40))
plot!(collect(-5:0.1:5), zero, label = "reta zero")

```



**Dados**
```
matriz = rand(Float64,6,6)
vetor = rand(5)
nome = "Arquivos"

```
**Salvar arquivo em disco**
```
save("arquivo_basico.jld", "matriz", matriz, "vetor", vetor , "nome", nome)

```
**Ler os dados do arquivo gravado em disco**
```
arquivo_basico = load("arquivo_basico.jld")

```
**Deletar uma key e seus valores**
```
delete!(arquivo_basico, "vetor")

```

## VALA

**DEFINIÇÃO**
```
Vala é uma linguagem de programação que habilita técnicas modernas à serem usadas para escrever aplicações que rodam na plataforma Gnome, particulamente Glib e GObject.

O código será em texto monoespaçado, e os comandos serão todos prefaciados com o caractere $ do prompt.
```


**COMENTARIOS**
```
// O comentário continua até o final da linha

/* O comentário dura entre os delimitadores */

/**
 * Comentário de documentação
 */
```

**VARIAVEIS**
```
const double MU_BOHR = 927.400915E-26;
```
**TIPOS DE DADOS**
```
string texto = "Um conjunto de caracteres";
string s = @"$a * $b = $(a * b)";

int a = 6, b = 7;
bool b = bool.parse("false");
float percentile = 0.75f
```

**OPERADORES**
```
ARITMETICOS
+, -, /, *, %
+=, -=, /=, *=, %=

COMPARAÇÃO
<, >, >=, <=, !=

RELACIONAIS
!, &&, ||
```

**CASTING**
```
int i = 10;
float j = (float) i;
```
**ARRAY**
```
int[] a = new int[10];
int[] b = { 2, 4, 6, 8 };

int[] c = b[1:3];     // => { 4, 6 }
```


**CONDICIONAL**
```
IF
if (a > 0) { stdout.printf("a is greater than 0\n"); }
else if (a < 0) { stdout.printf("a is less than 0\n"); }
else { stdout.printf("a is equal to 0\n"); }


if (1 < a && a < 5) {}

if (0 < a && a < b && b < c && c < d && d < 255) {
    // do something
}

De uma forma mais natural:

if (1 < a < 5) {}

if (0 < a < b < c < d < 255) {
    // do something
}
```

```
SWITCH
switch (a) {
case 1:
    stdout.printf("one\n");
    break;
case 2:
case 3:
    stdout.printf("two or three\n");
    break;
default:
    stdout.printf("unknown\n");
    break;
}
```

**LAÇO**
```
WHILE
while (a > b) { a--; }

DO WHILE
do { a--; } while (a > b);

FOR
for (int a = 0; a < 10; a++) { stdout.printf("%d\n", a); }

FOREACH
foreach (int a in int_array) { stdout.printf("%d\n", a); }
```

**EXPRESSAO REGULAR**
```
string email = "tux@kernel.org";
if (/^[A-Z0-9._%+-]+@[A-Z0-9.-]+\.[A-Z]{2,4}$/i.match(email)) {
    stdout.printf("Valid email address\n");
}

Regex regex = /foo/;

var r = /(foo|bar|cow)/;
var o = r.replace ("this foo is great", -1, 0, "thing");
print ("%s\n", o);
```

**CLASSE**
```
class ClassName : SuperClassName, InterfaceName {
}




class Demo.OlaMundo : GLib.Object {

    public static int main(string[] args) {

        stdout.printf("Olá, Mundo\n");

        return 0;
    }
}


public class Person : Object {

    /* Construction properties */
    public string name { get; construct; }
    public int age { get; construct set; }

    public Person(string name) {
        Object(name: name);
    }

    public Person.with_age(string name, int years) {
        Object(name: name, age: years);
    }

    construct {
        // do anything else
        stdout.printf("Welcome %s\n", this.name);
    }
}


public class TestClass : GLib.Object {

    /* Fields */
    public int first_data = 0;
    private int second_data;

    /* Constructor */
    public TestClass() {
        this.second_data = 5;
    }

    /* Method */
    public int method_1() {
        stdout.printf("private data: %d", this.second_data);
        return this.second_data;
    }
}
```

**MÉTODOS**
```
int método_nome(int arg1, Object arg2) {
    return 1;
}

string? nome_do_metodo(string? texto, Foo? foo, Bar bar) {
    // ...
}
```

**CONSTRUTOR**
```
public class Point : Object {
    public double x;
    public double y;

    public Point(double x, double y) {
        this.x = x;
        this.y = y;
    }

    public Point.rectangular(double x, double y) {
        this(x, y);
    }

    public Point.polar(double radius, double angle) {
        this.rectangular(radius * Math.cos(angle), radius * Math.sin(angle));
    }
}

void main() {
    var p1 = new Point.rectangular(5.7, 1.2);
    var p2 = new Point.polar(5.7, 1.2);
}
```
**DESTRUTOR**
```
class Demo : Object {
    ~Demo() {
        stdout.printf("no destrutor");
    }
}
```

**POLIMORFISMO**
```
class SuperClass : GLib.Object {
    public void method_1() {
        stdout.printf("SuperClass.method_1()\n");
    }
}

class SubClass : SuperClass {
    public void method_1() {
        stdout.printf("SubClass.method_1()\n");
    }
}



class SuperClass : GLib.Object {
    public virtual void method_1() {
        stdout.printf("SuperClass.method_1()\n");
    }
}

class SubClass : SuperClass {
    public override void method_1() {
        stdout.printf("SubClass.method_1()\n");
    }
}


class SuperClass : GLib.Object {
    public virtual string prop_1 {
        get {
            return "SuperClass.prop_1";
        }
    }
}

class SubClass : SuperClass {
    public override string prop_1 {
        get {
            return "SubClass.prop_1";
        }
    }
```

**CONVERSÃO**
```
/* definindo um apelido para um tipo básico (equivalente ao typedef int Integer em C)*/
[[SimpleType](/SimpleType)] public struct Integer : uint { }

/* Define um novo tipo de um container como GLib.List com elementos do tipo GLib.Value */
public class ValueList : GLib.List<GLib.Value> {

        [CCode (has_construct_function = false)]
        protected ValueList ();
        public static GLib.Type get_type ();
}


Button b = widget as Button;
Button b = (widget is Button) ? (Button) widget : null;
```

**REFERÊNCIA**
```
/* definindo uma classe */
class Track : GLib.Object {             /* herdando de 'GLib.Object' */
    public double mass;                 /* um campo público */
    public double name { get; set; }    /* uma propriedade pública */
    private bool terminated = false;    /* um campo privado */
    public void terminate() {           /* um método público */
        terminated = true;
    }
}
```

**DELEGAÇÕES**
```
delegate void DelegateType(int a);

delegate void DelegateType(int a);

void f1(int a) {
    stdout.printf("%d\n", a);
}

void f2(DelegateType d, int a) {
    d(a);       // Chamando uma delegaçao
}

void main() {
    f2(f1, 5);  // Passando um método como argumento de delegação à outro método
}

class Foo {

    public void f1(int a) {
        stdout.printf("a = %d\n", a);
    }

    delegate void DelegateType(int a);

    public static int main(string[] args) {
        Foo foo = new Foo();
        DelegateType d1 = foo.f1;
        d1(10);
        return 0;
    }
}
```

**INTERFACE**
```
interface InterfaceName : SuperInterfaceName {
}

```
**NAMESPACE**
```
namespace NameSpaceName {
    // ...
}

using NameSpaceName;
```

**STRUCTS**
```
struct NomeStruct {
    public int a;
}


struct Cor {
    public double vermelho;
    public double verde;
    public double azul;
}

Cor c2 = { 0.5, 0.5, 1.0 };
Cor c3 = Cor() {
    red = 0.5,
    green = 0.5,
    blue = 1.0
};

// com inferência de tipo var c4 = Cor();
var c5 = Color() {
    red = 0.5,
    green = 0.5,
    blue = 1.0
};
```

**BIBLIOTECAS**
```
public class MyLib : Object {

    public void hello() {
        stdout.printf("Hello World, MyLib\n");
    }

    public int sum(int x, int y) {
        return x + y;
    }
}

$ valac -C -H test.h --library test test.vala --basedir ./

$ gcc --shared -fPIC -o libtest.so $(pkg-config --cflags --libs gobject-2.0) test.c


void main() {
    var test = new MyLib();
    test.hello();
    int x = 4, y = 5;
    stdout.printf("The sum of %d and %d is %d\n", x, y, test.sum(x, y));
}
```

**COMANDOS**
```
$ valac OlaMundo.vala
$ ./OlaMundo
```

**FERRAMENTAS**
```
valac

valac é o compilador Vala. Sua função principal é transformar o código Vala em código C compilável, embora também possa automatizar todo o projeto de construção e link em casos simples.

Um exemplo simples:

$ valac -o appname --pkg gee-1.0 file_name_1.vala file_name_2.vala

O parâmetro -o solicita que um arquivo de objeto seja criado, em vez de apenas produzir arquivos de origem C. A opção --pkg diz que essa compilação precisa de informações do pacote gee-1.0. Não é necessário especificar detalhes sobre quais bibliotecas será necessário vincular, o pacote tem essas informações internamente. Finalmente, é fornecida uma lista de arquivos de origem. Se você precisar de um processo de compilação mais complicado, use a opção -C para gerar arquivos C em vez de um binário e continuar o processo manualmente ou através de um script.
vapigen

vapigen é uma ferramenta para fazer Bindings. Ele cria arquivos VAPI a partir de metadados de uma biblioteca e qualquer informação extra necessária.
```