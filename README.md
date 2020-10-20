# Kotlin_Madcode
//Carla Gramoso Natal

//1. Desenvolva um algoritmo que armazene seu nome em uma variável e imprima a //mensagem "Olá, [nome]" utilizando a Concatenação ou Template String 

fun main() {
    var nome = "Carla"
    println("Ola: $nome")
}

//2. Desenvolva um algoritmo com duas variáveis do tipo Double e imprima a soma das mesmas

fun main() {
    var a = 50.2
    var b = 17
    var soma = a+b
    println("A soma de $a e $b é $soma")
}

//3. Desenvolva um algoritmo que imprima o valor ao quadrado de um número

fun main() {
    var a = 50.2
    var quadrado = a*a
    println("O quadrado de $a é $quadrado")
}

//4. Desenvolva um algoritmo que imprima o dobro de um número

fun main() {
    var a = 50.2
    var dobro = a*2
    println("O dobro do $a é $dobro")
}

//5. Desenvolva um algoritmo que utilize os operadores aritméticos e imprima o antecessor e o 
//sucessor de um número

fun main() {
    var a = 50
    var antecessor = a-1
    var sucessor = a+1
    println("O antecessor de $a é $antecessor,")
    println("e o sucessor de $a é $sucessor")
}

//6. Desenvolva um algoritmo que calcule e imprima o total de dias em 7 meses, considerando 
//que cada mês tenha 30 dias

fun main() {
    var meses = 7
    var dias = 30
    var total = meses * dias
    println("O total de dias de $meses meses é $total dias")
}

//7. Desenvolva um algoritmo que calcule e imprima a média das cinco notas de um aluno

fun main() {
    var nota1 = 5
    var nota2 = 3
    var nota3 = 7
    var nota4 = 9
    var nota5 = 2
    var media = ((nota1+nota2+nota3+nota4+nota5)/5)
    println("O média das notas é $media")
}

//8. Desenvolva um algoritmo que converta metros para centímetros e imprima o resultado

fun main() {
    var metros = 1
  	var cent = (metros*100)
    println("Em $metros mt tem $cent centimetros")
}

//9. Desenvolva um algoritmo que calcule o desconto na venda de um produto

fun main() {
    var pinicial =100
  	var pfinal = 90
    var desconto  = (pfinal%pinicial)*0.01
    println("O cliente obteve $desconto % de desconto")
   
}
