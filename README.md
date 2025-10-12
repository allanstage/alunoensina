# alunoensina

**Exercícios de lógica de programação da apostila da Unicesumar,
convertidos para códigos funcionais no Portugol Studio.**

---

## ⚠️ Atenção

Os exemplos da apostila são **pseudocódigos**,
Eles servem para entender a lógica, mas **não funcionam diretamente no Portugol Studio**.  
Aqui você encontra a versão **pronta para copiar e colar**, que funciona sem erros.

---

## 📖 Exemplo 1 — Soma de dois números

### Como aparece na apostila

<img width="447" height="478" alt="Screenshot_1" src="https://github.com/user-attachments/assets/16a4df51-92d5-4220-ad1b-f5b858a90ccf" />


---

### 💻 Código que funciona no Portugol Studio

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


