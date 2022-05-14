# Proposição

Proposição é uma sentença declarativa que pode ser classificada como verdadeira ou falsa, jamais ambas ao mesmo tempo. Ou seja, não pode haver dúvida quanto à classificação da sentença. Também podemos dizer que trata-se de uma classificação binária, pois só existem dois resultados possíveis: V ou F, ou ainda 1 ou 0.

Segundo Gersting (2017), podemos utilizar letras maiúsculas do alfabeto para representar as proposições, portanto a partir de agora adotaremos essa notação para representar as proposições. Por exemplo:

-   A: Quinze é menor que vinte.
-   B: Todos os italianos são europeus.

Segundo Bispo e Castanheira (2011, p. 4), toda proposição deve seguir três princípios básicos:

-   Princípio da Identidade: “Toda proposição é idêntica a si mesma”. Ou seja, sendo P uma proposição: P é P.
-   Princípio da Não Contradição: “Uma proposição não pode ser verdadeira e falsa ao mesmo tempo”. Sendo P uma proposição tem-se: não (P e não P).
-   Princípio do Terceiro excluído: “Toda proposição ou é verdadeira ou é falsa, não existindo um terceiro valor que ela possa assumir”. Sendo P uma proposição tem-se: P ou não P.

## Classificação das proposições

As proposições podem ser classificadas como simples ou compostas. A proposição será simples quando existir uma única afirmação na frase. Por outro lado, uma proposição é composta quando for constituída de, pelo menos, duas proposições simples “ligadas” por um conectivo lógico, também chamado de conector lógico, conectivo proposicional ou operação lógica. (BISPO; CASTANHEIRA, 2011).

## Conectivos

Essas “palavras” usadas para unir as proposições simples são os conectivos (ou conectores) lógicos e influenciam a valoração de uma proposição composta. Os conectivos disponíveis para fazer a conexão são: (i) e, (ii) ou, (iii) não, (iv) se... então, (v) se, e somente se. (BISPO; CASTANHEIRA, 2011).

### Conectivo lógico de conjunção - e

Vamos começar estudando o conectivo lógico “e”, que também pode ser visto na literatura escrito em inglês AND ou ainda por meio do seu símbolo ⋀ . Essa operação lógica é chamada conjunção e sua valoração será verdadeira somente quando ambas as proposições simples forem verdadeiras. Resumindo, se A e B forem proposições simples verdadeiras, a proposição composta A ⋀ B (lê-se “A e B”) será verdadeira.

### Conectivo lógico de disjunção – ou (inclusivo)

Outro conector muito utilizado tanto na Lógica Formal, quanto na computacional é “ou” que também pode ser visto na literatura escrito em inglês OR ou ainda por meio do seu símbolo Ú . Essa operação lógica é chamada de disjunção e seu operador lógico pode ser utilizado de duas formas distintas: inclusivo ou exclusivo. Veremos nesta aula a forma inclusiva do operador.

O operador lógico de disjunção usado na forma inclusiva terá sua valoração falsa somente quando ambas as proposições simples forem falsas. Resumindo, se A e B forem proposições simples falsas, a proposição composta A ⋁ B (lê-se “A ou B”) será falsa, nos demais casos a valoração é verdadeira.

### Conectivo lógico de disjunção – ou (exclusivo)

Observe:

R: João é estudante ou é trabalhador.

S: João é Paulista ou é Carioca.

A proposição R representa uma disjunção inclusiva, pois João pode ser estudante e também trabalhador. Já a proposição S é uma disjunção exclusiva, pois João não pode ser Paulista e Carioca, ele só pode ser um dos dois.

Segundo Souza (2016), a disjunção inclusiva é representada pelo símbolo ⋁, ou seja, a proposição R, pode ser escrita como A⋁B . Já a disjunção exclusiva é representada pelo símbolo V, ou seja, a proposição S pode ser escrita como CVD.

### Operador lógico de negação – não

Os operadores lógicos de conjunção e disjunção são binários, ou seja, juntam duas expressões para formar uma nova proposição. O operador lógico de negação é unário, ou seja, ele não junta duas proposições, ele age sobre uma única proposição (que pode ser resultado de uma operação binária). A palavra usada para fazer a negação é o não que também pode ser visto na literatura em inglês NOT, ou ainda de forma simbólica como ~ , ←, ‘ . Os dois primeiros símbolos são usados antes da letra que representa a proposição, já o terceiro é usado depois da letra.

Por exemplo, as expressões:

~ A , ←B , C’ representam as negações das proposições A, B, C.

A operação lógica de negação troca o valor-verdade da proposição. Ou seja, se a proposição é verdadeira, quando acompanhada do operador de negação passará a ser falsa; por outro lado, se ela for falsa passará a ser verda- deira.

A negação pode ser aplicada ao resultado de uma outra operação, como por exemplo, ∼ (A ∧ B) . Nesse caso o resultado da conjunção será invertido.

### Conectivo condicional (Implicação lógica) – se... então

Dadas as proposições simples A, B, elas formam uma condicional (ou implicação lógica) se for possível construir a estrutura: se A, então B (BISPO; CASTANHEIRA, 2011). A primeira proposição é chamada antecedente, e a segunda consequente. A condicional significa que a verdade da primeira proposição implica a verdade da segunda proposição (GERSTING, 2017). O símbolo usado para representar a implicação lógica é o → , logo a regra se A, então B, pode ser escrita como A → B .

### Conectivo Bicondicional – se, e somente se

Dadas as proposições simples A, B, elas formam uma bicondicional se for possível construir a estrutura: A se, e somente se, B (BISPO; CASTANHEIRA, 2011). O símbolo usado para representar esse conectivo é o ↔ , então a expressão A se, e somente se, B, pode ser expressa simbolicamente por A ↔ B . Vejamos um exemplo.

Considere as proposições a seguir:

P: Lucas receberá o dinheiro.

Q: Lucas completará o trabalho.

S: A ↔ B .

A proposição S, deve ser traduzida como “Lucas receberá o dinheiro se, e somente se, completar o trabalho”.

Segundo Gersting (2017), o bicondicional é um atalho para a expressão lógica: (A → B)∧(B → A) .

Nessa expressão temos a conjunção entre o resultado de duas condicionais que alteram seus antecedentes e consequentes. Para ficar mais claro, usando as proposições P, Q criadas anteriormente, dizer que “Lucas receberá o dinheiro se, e somente se, completar o trabalho” é o mesmo que dizer “Se Lucas receber o dinheiro então completará o trabalho e se Lucas completar o trabalho então receberá o dinheiro”. Como podemos observar, o bicondicional resume a sentença, facilitando até mesmo a compreensão.

A valoração do conectivo bicondicional será verdadeira quando o valor--lógico das duas proposições forem iguais, tanto para verdadeiro como para falso.

Ou seja, V ↔V = V e F ↔ F =V .

### Suencia dos conectiovs

Assim como os operadores matemáticos, os conectivos lógicos também possuem ordem de precedência, sendo ela:

1. Para conectivos dentro de vários parênteses, efetuam-se primeiro as expressões dentro dos parênteses mais internos.
2. Negação (← ).
3. Conjunção e disjunção ( ⋀ , ⋁ ).
4. Condicional (→ ).
5. Bicondicional (↔).
