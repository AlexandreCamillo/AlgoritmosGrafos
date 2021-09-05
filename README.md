# Algoritmos e Grafos
Colaboratory com alguns algorimos conhecidos de Grafos

## Formato de entradas
Todo grafo precisa ser inicializado a lista de adjacências sendo um **dict** com as **chaves sendo o nome dos vértices** e os **valores sendo a lista de vétices vizinhos**
Ex:
``` python
lista_adjacencias = { # ciclo de 5 vertices
    '1': ['2', '5'], 
    '2': ['1', '3'], 
    '3': ['2', '4'], 
    '4': ['3', '5'], 
    '5': ['1', '4']
}
```
Para inicializar um grafo como a lista de adjacências execute:
> **Ps:** Primeiro parâmetro é o nome do grafo e o segundo a lista base de construção do grafo
``` python
grafo = Grafo('Grafo', lista_adjacencias)
```
**É isto...**