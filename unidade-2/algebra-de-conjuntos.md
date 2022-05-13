# Álgebra de Conjuntos

Conjuntos são coleções não ordenadas de objetos que podem ser, de alguma forma, relacionados (FERREIRA, 2001).
Estudaremos, portanto, que relações são essas, direcionando nosso olhar especialmente para as operações de
união (∪) , intersecção (∩) e diferença (−) entre conjuntos.

## União

Consideremos, por exemplo, o conjunto M constituído por todos os alunos de uma determinada universidade.
Podemos afirmar que o conjunto A, formado pelos alunos do curso de Análise e Desenvolvimento de Sistemas
dessa mesma universidade, é um subconjunto de M (A⊆M), ou seja, cada aluno que pertence ao conjunto A
(alunos do curso de Análise e Desenvolvimento de Sistemas) também pertence ao conjunto M (também são
alunos da universidade). Analogamente, consideremos também o conjunto B, formado pelos alunos do curso
de Matemática dessa mesma universidade, logo, podemos afirmar que B também é subconjunto de M (B⊆M).

Um novo conjunto de alunos pode ser definido como consistindo em todos os alunos que sejam estudantes do curso de Análise e Desenvolvimento de Sistemas ou Matemática (ou ambos). Esse conjunto é chamado de união de A e B. Segundo Gersting (1995), a operação de união de A e B pode ser denotada como A∪B= {x | x ∈ A ou x ∈ B}. Nesse exemplo, a união A∪B compreende todos os alunos que cursam Análise e Desenvolvimento de Sistemas (A) ou Matemática (B) ou ambos os cursos.

# Intersecção

Outro conjunto pode ser definido como sendo composto por todos os alunos do curso de Análise e Desenvolvimento de Sistemas e do curso de Matemática, ou seja, alunos que cursam simultaneamente ambos os cursos. Esse novo conjunto (que pode ser vazio) é chamado de intersecção de A e B. Segundo Gersting (1995), a operação de intersecção de A e B pode ser denotada como A∩B= {x|x∈A e x∈B}. Nesse exemplo, a união A∩B compreende todos os alunos que cursam simultaneamente Análise e Desenvolvimento de Sistemas (A) e Matemática (B).

## Continência

Podemos relacionar um conjunto com outro através da relação de continência, ou seja, se todo elemento
do conjunto A está também no conjunto B, temos que A ⊂ B (A está contido em B).
Nesse caso dizemos também que A é subconjunto de B.

A boca do simbolo "⊂" refere-se ao conjunto que contem o outro.

## Exemplos

Exemplo 1: Sejam os conjuntos A ={10,11,12,13,14,15} e B ={13,14,15,16,17,18,19} , o conjunto A∪B

formado por todos os elementos de A e de B.

A ∪ B ={10,11,12,13,14,15,16,17,18,19} .

Repare que há elementos pertencentes a ambos os conjuntos, porém, ao efetuarmos a operação união (∪) , esses elementos são contabilizados uma única vez. Em relação à cardinalidade desses conjuntos, temos que: A = 6 , B = 7 e A ∪ B =10 .

Já o conjunto A∩B consiste no conjunto formado pelos elementos comuns aos conjuntos A e B.

A ∩ B ={13,14,15} .

Temos ainda que A ∩ B = 3 .

## Diferença

Além das operações união (∪) e intersecção (∩), outra operação que costuma aparecer com frequência ao estudarmos álgebra de conjuntos é a operação diferença de conjuntos. Sejam A e B dois conjuntos, de acordo com Scheinerman (2015), a diferença A - B é o conjunto de todos os elementos de A que não estão em B, ou seja: A− B = {x| x ∈ A e x∉B} . Considere, por exemplo, os conjuntos A ={1,2,3, 4, 5} e B ={4,5,6,7} . Para determinarmos a diferença A - B temos de verificar quais elementos pertencem ao conjunto A, mas não pertencem ao conjunto B, ou seja, A − B = {1,2,3} . Analogamente, podemos definir o conjunto B - A , que consiste em todos os elementos pertencentes a B, mas que não pertencem ao conjunto A, ou seja, B − A = {6,7} .

## Diferença Simétrica

Outra operação utilizada na álgebra de conjuntos é a chamada diferença simétrica. Segundo Scheinerman (2015), a diferença simétrica de A e B pode ser denotada por ADB . A diferença simétrica de A e B é o conjunto de todos os elementos que pertencem a A, mas não pertencem a B ou que pertencem a B, mas não pertencem a A. Essa diferença simétrica pode ser representada como A∆B =(A − B)∪(B − A) .

Considere, por exemplo, os conjuntos A ={1,2,3, 4, 5} e B ={4,5,6,7} . A diferença simétrica A∆B ficaria definida como:

A∆B =(A − B)∪(B − A)=(1,2,3)∪(6,7)=(1,2,3,6,7) .

## Cardinalidade

Considere, por exemplo, que em uma pesquisa com profissionais do setor de Tecnologia da Informação de uma grande empresa responsável pela elaboração e manutenção de páginas (homepages) na Internet foi perguntado qual era o navegador de Internet utilizado durante o trabalho. Essa pesquisa apresentou os seguintes resultados: 280 profissionais alegaram utilizar o navegador A, 300 disseram utilizar o navegador B e 120 profissionais afirmaram utilizar ambos os navegadores. Sabendo que todos os funcionários do setor de Tecnologia da Informação dessa empresa responderam a essa pesquisa, como você determinaria o número desses profissionais?

A ∪ B = A + B − A ∩.

Para responder a esse problema, podemos recorrer ao método de contagem chamado inclusão-exclusão. Vamos considerar como conjunto A o conjunto dos profissionais que utilizam o navegador A, e como conjunto B o conjunto dos profissionais que utilizam o navegador B. Temos que:

|A∪B| = |A| + |B| - | A∩B| = 280+300-120=460.

Ou seja, essa empresa tem 460 profissionais trabalhando no setor de Tecnologia da Informação.

## Complementos de um conjunto

Seja o conjunto A um subconjunto de U, ou seja, A⊆U. O complemento do conjunto A contido no conjunto U, denotado por CUA , é a diferença entre os conjunto U e A ou seja, é o conjunto de todos os elementos que pertencem ao conjunto U e não pertencem ao conjunto A (PEREIRA; SODRÉ, 2006).

Seja A ={1,2,3, 4,5,6,7,8,9,10} e B ={1,2,3,5,8,9} . O complemento de B em relação a A consiste no conjunto constituído por todos os elementos pertencentes a A que não pertencem a B. Temos, portanto: CAB ={4,6,7,10} .

Em outras palavras, podemos dizer que o complemento de B em relação a A consiste no conjunto formado por elementos que pertencem exclusivamente a A, quando comparados com os elementos de B.

Segundo Ferreto (2019), há dois fatos que merecem atenção no estudo do complemento de um conjunto. O primeiro fato ao qual devemos ficar atentos é que para que um conjunto complementar a outro exista, há uma condição que deve ser respeitada: para que haja o cálculo do conjunto complementar de B em relação a A, B deve ser subconjunto de A.

Outro fato que também merece atenção diz respeito à maneira como o conjunto complementar é representado simbolicamente. É importante notar que CAB ≠ CBA . Para determinarmos CAB fazemos A-B , enquanto que para determinarmos CBA fazemos B - A (lembrando que nem sempre é possível determinar o complemento de um determinado conjunto).

## Produto cartesiano

Sejam os conjuntos A e B. O produto cartesiano de A e B, denotado por A ｘ B , é o conjunto de todos os pares ordenados (listas de dois elementos) formados, tomando-se um elemento de A juntamente com um elemento de B de todas as maneiras possíveis.

Considere os conjuntos A ={4,5,6} e B ={6,7,8}.

Vamos definir os produtos cartesianos A ｘ B e B ｘ A.

A×B ={(4,6),(4,7),(4,8),(5,6),(5,7),(5,8),(6,6),(6,7),(6,8)}

B×A ={(6, 4),(6,5),(6,6),(7, 4),(7,5),(7,6),(8, 4),(8,5),(8,6)}

Note que A×B ≠ B×A . Isso acontece porque a operação produto cartesiano não é uma operação comutativa.
