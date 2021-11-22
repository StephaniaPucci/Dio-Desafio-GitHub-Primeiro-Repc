# Dio-Desafio-GitHub-Primeiro-Repositorio
Desafio Projeto Git/GitHub da Dio
Repositorio criado para o desafio do projeto.
# Links Úteis
[Sintaxe Básica MarKDown](https://www.markdownguide.org/getting-started/)

## Exercicio Portugol 1 

	funcao inicio()
	{

		cadeia Nome,Janeiro,Fevereiro,Marco,Abril
		real valor1,valor2,valor3,valor4,Total,Media
		
		escreva("Qual seu nome:")
		leia(Nome)
		
		escreva("Total vendas em Janeiro:")
		leia(valor1)
		escreva("Total vendas em Fevereiro:")
		leia(valor2)
		escreva("Total vendas em Marco:")
		leia(valor3)
		escreva("Total vendas em Abril:")
		leia(valor4)

		Total = (valor1+valor2+valor3+valor4)

		escreva("\n" + Nome + " obteve o total de vendas no ciclo de:" + Total)

		Media = (valor1+valor2+valor3+valor4)/4 

		escreva("\n" + Nome + " obteve a media no ciclo de:" + Media)
		
## Exercicio Portugol 2

funcao inicio()
	{
	real nota1,nota2,nota3,nota4,media
	cadeia aluno

	escreva("Digite seu nome:")
	leia(aluno)
	escreva("Digite a nota 1:")
	leia(nota1)
	escreva("Digite a nota 2:")
	leia(nota2)
	escreva("Digite a nota 3:")
	leia(nota3)
	escreva("Digite a nota 4:")
	leia(nota4)

	media = (nota1+nota2+nota3+nota4)/4

	escreva("O aluno:" + aluno + " Obteve a media:" + media)
	
## Exercicio Portugol 3
	
	funcao inicio()
	{

	real nota1,nota2,nota3,nota4,Media
	cadeia aluno
	
		escreva("Digite a seu nome:")
		leia(aluno)
		escreva("Digite a nota 1:")
		leia(nota1)
		escreva("Digite a nota 2:")
		leia(nota2)
		escreva("Digite a nota 3:")
		leia(nota3)
		escreva("Digite a nota 4:")
		leia(nota4)

		Media = (nota1+nota2+nota3+nota4)/4

		escreva(aluno + " obteve media:" + Media)

		se(Media<10) {
			escreva("\n" + "Parabéns! Você foi aprovado")
		}

		senao {
			escreva("\n" + "Infelizmente você foi reprovado")
			
## Exercicio Portugol 4

funcao inicio()
	{
		inteiro contador,limite,resultado,Tabuada

		escreva("Qual tabuada deseja obter resultado?:")
		leia(Tabuada)

		contador = 0
		limite = 10

		faca{

	resultado = Tabuada * contador
	escreva(Tabuada + " X " + contador + "=" + resultado + "\n")
	contador++
		}enquanto (contador<=limite)
