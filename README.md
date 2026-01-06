# Ficha de Avaliação - Folha de Cálculo - Turno 2

## Instruções

* Esta avaliação é individual.

* Podes rever os exercícios previamente realizados.

* Faz um ***fork*** deste repositório.

![alt text](img/image.png)

* No teu ***fork***, edita o ficheiro **README.md**

![alt text](img/image-1.png)

* Utiliza os espaços indicados para responderes às questões.

* Não desformates o ficheiro.

* Quando terminares, realiza um ***Commit***

![alt text](img/image-2.png)

## Exercícios

1. Explica para que serve o sinal = numa folha de cálculo.
Indica duas situações em que se deve usar uma fórmula.
(3 valores)

        Resposta: O sinal = numa folha de cálculo indica que a célula deve ser interpretado como uma fórmula e não como texto ou número simples. Ele “ativa” os cálculos, permitindo que a célula mostre o resultado de operações como somas, multiplicações ou funções.

        Duas situações em que se deve usar uma fórmula: 1- =SOMA(A1:A10)) e =MÉDIA(B2:B20))

2. O que acontece a uma fórmula quando é copiada para outra célula?
Explica a tua resposta usando o conceito de referências de células.
(3 valores)

        Resposta: Quando uma fórmula é copiada para outra célula, as referências de células dentro dela podem ajustar-se automaticamente, consoante o tipo de referência utilizada.

        referência relativa: ao copiar a fórmula uma linha abaixo, a referência ajusta-se.
        referência absoluta: ela mantém-se fixa, independentemente de para onde a fórmula é copiada.

3. Observa a seguinte fórmula, escrita na célula E4:

        =C4*$A$1

    a) Que tipo de referência é usada em A1? (1 valor)

        Resposta: referência absoluta

    b) O que acontece à referência C4 se a fórmula for copiada para E5? (1 valor)

        Resposta: referência relativa

4. Explica o que é a formatação condicional e indica duas regras que podem ser aplicadas a uma tabela.
(3 valores)

        Resposta: A formatação condicional é uma funcionalidade que permite aplicar automaticamente formatação. A células consoante o seu conteúdo ou o resultado de uma condição lógica.

        Duas regras aplicáveis: Destacar células maiores que um valor por ex.: valores superiores a 100 a vermelho). Ou usar barras de dados para visualizar graficamente a magnitude dos valores dentro de um intervalo.

5. Para que serve um filtro automático numa folha de cálculo?
Dá um exemplo prático relacionado com um inventário ou lista de dados.
(2 valores)

        Resposta: O filtro automático permite mostrar apenas as linhas que cumprem certos critérios, ocultando temporariamente as restantes, facilitando a análise de subconjuntos de dados.
   
        Exemplo prático: Numa lista de produtos com colunas “Categoria”, “Stock” e “Preço”, podemos aplicar um filtro para mostrar apenas os itens da categoria “Material Escritório” com stock inferior a 10 unidades, ajudando a identificar produtos a reabastecer.

7. Completa a frase corretamente (2 valores):

    Ordenar dados serve para ____________, enquanto filtrar dados serve para _____________.

        Resposta 1: organizar os dados por ordem alfabética, numérica ou cronológica.
        Resposta 2: mostrar apenas os dados que obedecem a critérios específicos, escondendo os restantes.

8. Para que serve um gráfico numa folha de cálculo?
Escolhe um tipo de gráfico e refere uma situação concreta em que possa ser usado.
(3 valores)

        Resposta: Um gráfico serve para visualizar dados de forma gráfica, tornando padrões, tendências ou comparações mais evidentes e compreensíveis do que numa tabela numérica.

        Gráfico de barras: Comparar as vendas mensais de diferentes produtos ao longo de um ano, onde cada barra representa um mês e as cores diferentes correspondem a cada produto.

9. Escreve a fórmula necessária para calcular a prestação mensal de um empréstimo de 1000 €, a pagar em 24 meses, com taxa anual de 4%.
Não é necessário calcular o valor final.
(2 valores)

        Resposta: =PGTO(4%/12; 24; -1000). 
