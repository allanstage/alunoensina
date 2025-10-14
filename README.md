# alunoensina

**Exercícios de lógica de programação da apostila da Unicesumar,
convertidos para códigos funcionais no Portugol Studio.**

---

## ⚠️ Atenção

Os exemplos da apostila são **pseudocódigos**,
Eles servem para entender a lógica, mas **não funcionam diretamente no Portugol Studio**.  
Aqui você encontra a versão **pronta para copiar e colar**, que funciona sem erros.

Download do Portugol Studio: https://univali-lite.github.io/Portugol-Studio



#### 📚 Menu de Navegação

- [📖Página 15 — Soma de dois números](#pg15)
- [📖Página 32 — Problema 1](#pg32)
- [📖Página 36 — Problema 2](#pg36)
 _____________________________________________________ 
- [🚀10 Super dicas para destravar sua mente](#dicas) 
- Exercícios para treino
- [Cadastro simples de informações](t1)
- [Área do Triângulo](#t2)
- [Média de notas de um aluno](#t3)

  
---
<a name="pg15"></a>
#### 📖 Página 15 — Soma de dois números

##### Como aparece na apostila

<img width="398" height="220" alt="Screenshot_1" src="https://github.com/user-attachments/assets/4cd3481d-13ef-448f-9b7e-6811f91af8b7" />


#### 💻 Código que funciona no Portugol Studio 💡

```portugol
programa
{
	funcao inicio()
	{
		inteiro n1, n2, s
		
		escreva("Digite o primeiro número: ")
		leia(n1)
		
		escreva("Digite o segundo número: ")
		leia(n2)
		
		s = n1 + n2
		
		escreva("A soma é: ", s, "\n")
	}
}
```

---

<a name="pg32"></a>
#### 📖 Página 32 — Problema 1
🎯Objetivo do algoritmo:

Ler e apresentar nome, idade, peso, altura e telefone de uma pessoa.
##### Como aparece na apostila

<img width="445" height="530" alt="pagina 32 - problema1" src="https://github.com/user-attachments/assets/14ce9907-100c-4a9f-b6ef-d2319bfc8e3c" />

##### 💻 Código que funciona no Portugol Studio 💡

```portugol
programa
{
	funcao inicio()
	{
		cadeia nome
		inteiro idade
		real peso
		real altura
		inteiro telefone

		escreva("Qual é seu nome: ")
		leia(nome)

		escreva("Qual é a sua idade: ")
		leia(idade)

		escreva("Qual seu peso (exemplo: 78.8):  ") //  Não use virgula aqui (,)
		leia(peso)
		
		escreva("Qual sua altura (exemplo: 1.75):  ") //  Use ponto (.)
		leia(altura)

		escreva("Qual seu telefone: ")
		leia(telefone)

		escreva("\n") // Pular uma linha

		escreva("Seu nome é: ",nome, "\n")
		escreva("Sua idade é: ",idade,"\n")
		escreva("Seu peso é: ", peso,"\n")
		escreva("Sua altura é: ", altura,"\n") 
		escreva("Seu telefone é: ", telefone,"\n")
		
	}	
}
```
---
<a name="pg36"></a>
#### 📖 Página 36 — Problema 2
Objetivo do algoritmo:

calcular o perímetro e a área de um quadrado.
##### Como aparece na apostila

<img width="444" height="311" alt="problema 2" src="https://github.com/user-attachments/assets/dbb75d89-d580-4dd4-aa06-c8e8c7d74057" />

##### 💻 Código que funciona no Portugol Studio 💡

```portugol
programa
{
	
	funcao inicio()
	{
		inteiro lado, area, perimetro
		
		escreva("Qual é o tamanho de um lado do quadrado: ")
		leia(lado)

		perimetro  = lado * 4 // porque um quadrado tem 4 lados!
		area = lado * lado // base * altura

		escreva("O perimetro do quadrado é: ",perimetro, "\n")
		escreva("A area do quadrado é: ",area)
	}
}
```
---
<a name="dicas"></a>
##  Super dicas para destravar sua mente!!! ⚡
---

##### 1. Entenda o propósito de aprender com PORTUGOL STUDIO.

💭 **PORQUE:**  
Só para treinar com exercícios de lógica de programação.  

🧩 **COMO:**  
Pegue um exercício e faça.  
Digite olhando de um código pronto.  
Depois faça sem olhar.  

⏳ **ATÉ QUANDO:**  
Quando você tiver feito 100 exercícios.  

🏁 **FIM:**  
Agora você está pronto para trocar o Portugol para uma linguagem de programação
**Escolha uma única linguagem de programação** e faça os 100 exercícios.

---
##### 2.Tipos principais no Portugol Studio

inteiro → números completos sem vírgula, sem ponto. 
Ex: inteiro  numero

	numero = 10

real → números com ponto
Ex: real ponto

	ponto = 3.14

cadeia → texto
Ex: cadeia nome

	nome = "olá"

logico → verdadeiro/falso
	Ex: logico mundial
	
	palmeiras = mundial
```portugol
programa
{
    funcao inicio()
    {
        logico mundial
        inteiro palmeiras

        palmeiras = 51
        mundial = verdadeiro
        
        escreva("Qual o ano que o palmeiras ganhou o mundial: ")
        leia(palmeiras)

        se (palmeiras == 51) {
            escreva("Palmeiras tem mundial! \n")
            escreva(" Título é verdairo ou falso? ",mundial)
        } senao {
            escreva("51 é pinga! ")
            
        }
    }
}
```



---
##### 3. Estrutura basica do programa

No Portugol Studio, a estrutura básica de um código completo precisa começar com a palavra-chave `programa`.

👉 **Explicando de forma simples:**

- `programa` → diz ao Portugol Studio que tudo o que vem dentro das chaves `{ }` faz parte do teu programa.  
- `funcao inicio()` → é o bloco principal que será executado quando o programa rodar.

Então, o código completo fica assim:

```portugol
programa
{
	funcao inicio()
	{
		escreva("Olá mundo!")
	}
}
```
---

##### Visualize um bloco de codigo como uma caixa

O que fica entre '{ }' funciona como uma caixa que guarda comandos relacionados.

Na imagem a seguir: Tudo está dentro da palavra `programa`,
e depois tudo está dentro de `funcao inicio()`


<img width="358" height="338" alt="Screenshot_3" src="https://github.com/user-attachments/assets/3174b8b2-fd3e-4cc5-9edf-a5e429819d7c" />

---
##### 4. Entenda o fluxo (Entrada,Processamento,Saída)

💭 Lógica:
Todo programa segue a mesma lógica:
entra dado → processa → mostra resultado.

🧩 Todo programa resolve alguma coisa.

```portugol
programa
{
   funcao inicio()
   {
      real numero, resultado

      escreva("Digite um número: ") 			// Entrada
      leia(numero)

      resultado = numero * 2					// Processamento

      escreva("O dobro é: ", resultado, "\n")   // Saída
   }
}
```
---


 — Exercícios para treino 🏆
 ---
 <a name="t1"></a>
##### 1- Cadastro simples de informações
**Descrição:**  
Este exercício tem como objetivo mostrar o uso de variáveis em um programa simples.
O algoritmo pede ao usuário que informe seu nome, idade e altura, e em seguida exibe as informações formatadas na tela.

```portugol
programa
{
	funcao inicio()
	{
		inteiro idade
		cadeia nome
		real altura

		escreva("Qual é seu nome: ")
		leia(nome)

		escreva("Qual é a sua idade: ")
		leia(idade)

		escreva("Qual sua altura: ")
		leia(altura)

		escreva("Seu nome é: ",nome)
		escreva("Sua idade é: ",idade)
		escreva("Sua altura é: ", altura)
	}	
}
```
---
<a name="t2o"></a>
##### 2- Área do Triângulo

**Descrição:**  
Calcule a área de um triângulo a partir da base e altura fornecidas pelo usuário. O programa deve mostrar o cálculo completo e o resultado.

**Fórmula:**  
Área = (base * altura) / 2

```portugol
programa
{
    funcao inicio()
    {
        inteiro base, altura, calculo, area

        escreva("Digite a base: ")
        leia(base)
        
        escreva("Digite a altura: ")
        leia(altura)

        calculo = base * altura 
        area = calculo / 2

        escreva("Base x Altura / Dividido por 2", "\n")
        escreva(base, " * ", altura," = ", calculo, " / 2 = ",area )
           
    }
}
```
---
<a name="t3"></a>
##### 3 - Média de notas de um aluno
**Descrição:**  

Este exercício tem como objetivo ler o nome, a idade e duas notas de um aluno, calcular a média das notas e exibir os resultados na tela.
Além disso, o programa adiciona 0.5 ponto de bônus à média final — uma forma divertida de mostrar como atualizar valores em variáveis.

```portugol
programa
{
	funcao inicio ()
	{
		cadeia nome
		inteiro idade
		real nota1, nota2, soma

		escreva("Digite seu nome: ")
		leia(nome)
		escreva("Digite sua idade: ")
		leia(idade)
		escreva("Digite sua nota 1: ")
		leia(nota1)
		escreva("Digite sua nota 2: ")
		leia(nota2)
		

		soma = (nota1 + nota2) / 2   // soma e divide por 2

		escreva("Seu nome é ",nome, "\n")
		escreva("Você tem ",idade, " anos", "\n")

		escreva("Sua média é: ",soma,"\n")
		soma = soma + 0.5
		escreva("Voce fez essa atividade ganhou mais meio ponto. +(0.5)","\n")
		escreva("Nota atual: ",soma)
		
		
	}
}
```
---
##### 4- Feliz ano novo! 2026
Você vai criar um programa que conta regressivamente de 10 até 1,
simulando a chegada do Ano Novo, exibe uma mensagem final de comemoração.

```portugol
programa
{
   funcao inicio()
   {
      inteiro numero
      numero = 10  // contagem regressiva de 10 até 1

      escreva("Contagem regressiva para o Ano Novo!\n\n")

      enquanto (numero > 0)
      {
         escreva(numero, "\n")
         numero = numero - 1
      }

      escreva("\nFeliz Ano Novo! 2026 \n")
   }
}
```
---
##### 5- Média de combustível
**Descrição:**  
Este programa calcula a média de consumo de um carro.
O usuário informa quantos quilômetros percorreu e quantos litros de combustível gastou.
O programa retorna quantos quilômetros o carro faz com 1 litro de combustível.

```portugol
programa
{
	funcao inicio()
	{

		real km, litros, media

		escreva("Digite quantos km andou: ")
		leia(km)
		escreva("Digite quantos litros gastou: ")
		leia(litros)

		media = km / litros

		escreva("Seu carro anda ", media, " km com 1 litro.")
	}
}
```
---
