# Métodos dedutivos e inferência lógica

A lógica proposicional é composta por proposições e conectivos lógicos que permitem criar uma série de fórmulas que quando escritas corretamente são chamadas fbfs (fórmula bem-formulada). Uma fbf é valorada em verdadeira (V) ou falsa (F), a partir da valoração das proposições com o conectivo lógico em questão, respeitando a ordem de precedência dos operadores lógicos. A valoração de uma fórmula também depende dos valores lógicos de entrada para cada uma das proposições.

## Regras de equivalência de dedução para a Lógica Proposicional

As regras de dedução são divididas em dois tipos: regras de equivalência e regras de inferência. Lembrando que duas fbfs são equivalentes, quando todas as combinações possíveis de entradas geram o mesmo resultado de saída para ambas as fbfs, as regras de equivalência serão usadas quando uma fbf (que pode ser uma hipótese ou resultado de uma regra) pode ser substituída por outra fbf, mantendo o resultado lógico.

## Regras de inferência de dedução para a Lógica Proposicional

Além das regras de equivalência, o processo de dedução lógica também possui as regras de inferência. Na inferência, dada uma determinada fbf, ela poderá ser substituída por outra que atenda a regra de inferência. Veja que aqui não é necessário ser uma tautologia (e realmente não será), mas é preciso seguir as regras da inferência.

### Modus Ponens (MP)

A primeira regra de inferência que vamos estudar é chamada Modus Ponens (MP). Essa regra envolve uma implicação e uma conjunção e possui a seguinte estrutura: (P → Q)∧ P → Q . Vejamos um exemplo para ficar mais clara a regra.

Considerando o seguinte argumento: Se João receber seu salário, ele irá ao cinema, vamos separar as proposições P, Q, portanto:

P: João recebe o salário.

Q: João vai ao cinema.

Agora vamos representar cada parte da fórmula de Modus Ponens:

    (P → Q) : Se João receber seu salário, ele irá ao cinema.
    P: João recebe o salário.

Ao fazer a conjunção entre a primeira parte com a segunda, conseguimos inferir a conclusão, pois, se João receber seu salário, ele irá ao cinema E João recebeu o salário, logo podemos inferir (concluir) que João vai ao cinema.

### Modus Tollens

Outra importante regra de inferência é o Modus Tollens (MT). Essa regra, além de envolver uma implicação e uma conjunção, também envolve a negação de uma das proposições. Sua estrutura é dada pela fbf: (P → Q)∧¬Q → ¬P .

Vejamos um exemplo. Considere o seguinte argumento:

Se João desligar o interruptor, então a lâmpada se apaga. Vamos separar as proposições P, Q, portanto:

P: João desliga o interruptor.

Q: A lâmpada apaga.

Agora vamos representar cada parte da fórmula de Modus Tollens:

    (P→ Q) : Se João desligar o interruptor, então a lâmpada se apaga.
    ←Q : A lâmpada não apagou.

Ao fazer a conjunção entre a primeira parte com a segunda, conseguimos inferir a conclusão. Pois, se João desligar o interruptor, a lâmpada se apaga E a lâmpada não se apagou, logo podemos inferir (concluir) que João não desligou o interruptor.

### Silogismo Hipotético (SH)

Outra importante regra é o Silogismo Hipotético (SH). Nessa regra, além de existirem implicações e conjunções nas hipóteses, a conclusão também é uma implicação. Sua estrutura é dada pela fbf:

(P → Q)∧(Q → R) → (P → R) .

Vejamos um exemplo. Considere o seguinte argumento: Se as árvores começam a florir, então começa a primavera. Se começa a primavera, então as árvores dão frutos. Vamos separar as proposições P, Q, R portanto:

P: As árvores começam a florir.

Q: A primavera começa.

R: As árvores dão frutos.

Agora vamos representar cada parte da fórmula de Silogismo Hipotético:

    (P → Q) : Se as árvores começam a florir, então começa a primavera.
    (Q → R) : Se começa a primavera então as árvores dão frutos.

Ao fazer a conjunção entre a primeira parte com a segunda, conseguimos inferir a conclusão. Pois, se as árvores começam a florir, então começa a primavera E se começa a primavera então as árvores dão frutos, logo podemos inferir (concluir) que se as árvores começam a florir, então darão frutos.

    Nas regras de equivalência, as colunas podem ser usadas nos dois sentidos. Já nas regras de inferência, só existe um sentido: a fbf da coluna “De” pode ser substituída pela coluna de “Podemos deduzir”, mas o contrário não é verdade. Em outras palavras, “Ao contrário das regras de equivalência, as regras de inferência não funcionam em ambas as direções” (GERSTING, 2017, p. 27).
