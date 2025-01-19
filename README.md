# Sistema de Recomendação de filmes

Um sistema de recomendação é uma técnica que utiliza dados e algoritmos para sugerir itens relevantes para um usuário com base em suas preferências ou no comportamento de outros usuários. 
O objetivo desde projeto é recomendar um filme de maneira mais eficiente sem a necessidade de uma busca ativa.


Neste projeto utilizamos a Filtragem Baseada em Conteúdo, esse tipo de sistema de recomenda itens com base nas caracteristicas do próprio item por exemplo, gênero, autor e descrição.

# Tecnologias usadas

1 - Python 

2 - Biblioteca de análise de dados (pandas, numpy)

3 - Vetorização com o CountVectorizer

Foi utilizado conceitos de algebra linear, em especifico, similaridade de cosseno, ela é usada para medir a aproximidade entre dois vetores em um espaço vetorial. A ideia central desta técnica é comparar a orientação de dois vetores
independentes de seu comprimento.

A fórmula para calcular a **similaridade de cosseno** entre dois vetores A e B é dada por:

similaridade de cosseno (A, B) = (A ⋅ B) / (||A|| ||B||)

Onde:
- A ⋅ B é o produto escalar entre os vetores A e B.
- ||A|| e ||B|| são as normas (ou magnitudes) dos vetores A e B.
