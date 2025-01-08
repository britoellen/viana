// Definindo uma função para calcular a média
func media(lista):
    soma = 0
    para item em lista:
        soma = soma + item
    retorno soma / lista.tamanho()

// Usando a função media
valores = [10, 20, 30, 40, 50]
resultado = media(valores)
imprimir("A média é:", resultado) // Saída: A média é: 30
