# Aula_14-09
---
# Código VSCode
### Usar código por meio do modo edição!!

programa {
	funcao inicio() {
		caracter parar
		parar = 'N'
		enquanto (parar != 'S') {
		        escreva ("Deseja parar o laço? (S/N)")
		        leia (parar)
		}
	}
}
--------------------------------------------------------------------
programa {
	funcao inicio() {
		real aresta, area
		faca {
		        escreva ("Informe o valor da aresta: ")
		        leia (aresta)
		} enquanto (aresta <= 0)
		area=aresta*aresta
		escreva("A área é: ", area)
		
	}
}
--------------------------------------------------------------------
programa {
	funcao calcularPorcentagem(){
	    escreva("Dentro da função calcular porcentagem\n")
	    real numero = 30.0, porcentagem = 20.0, resultado
	    resultado = (numero * (porcentagem/100))
	    escreva ("O resultado da porcentagem é ", resultado)
	}
    funcao inicio(){
        escreva("Inicio do progama principal")
        escreva("\n")
        escreva("Final do progama principal")

    }
}
------------------------------------------------------------------
programa {
	funcao calcularQtdAguaDiaria(){
	    real peso, resultado
	    caracter praticaAtividadeFisica
	    faca {
	        escreva("Digite seu peso: ")
	        leia(peso)
	    } enquanto (peso <=0)
	        faca {
	                escreva("digite S se você pratica atividade fisica ou N caso não pratique: ")
	                leia(praticaAtividadeFisica)
        } enquanto (praticaAtividadeFisica !='S' e praticaAtividadeFisica != 'N')
            se(praticaAtividadeFisica == 'S'){
                resultado = peso * 0.04
            } senao {
                resultado = peso * 0.035
            }
            escreva ("Você deve beber ", resultado, " Litros de aguá por dia.")
	   }
funcao inicio(){
        escreva("Início do programa principal\n")
        calcularQtdAguaDiaria()
        escreva("\nFinal do programa principal")
 }
}
