# Exercícios sobre Strings

1. Crie uma classe chamada StringUtils com os seguintes métodos estáticos:

- **String formataAtributo(String atributo)**: atributos iniciam com letra minúscula e devem estar no formato camelCase; Ex: *"quantidade de questoes"* ==> *"quantidadeDeQuestoes"*

- **String formataMetodo(String metodo)**: métodos iniciam com letra minúscula e devem estar no formato camelCase; Ex: *"get quantidade de questoes"* ==> *"getQuantidadeDeQuestoes"*

- **String formataClasse(String classe)**: classes iniciam com letras maiúsculas devem estar no formato camelCase; Ex: *"formatador de identificadores"* ==> *"FormatadorDeIdentificadores"*

- **String ordenaStrings(String palavra1, String palavra2)**: retorna uma única String, com as 2 palavras separadas por espaço mas em ordem lexicográfica; Ex: *"chevrolet fiat"* ==> *"chevrolet* e *fiat"*; *"volkswagen ford"* ==> *"ford volkswagen"*; *"honda honda"* ==> *"honda honda"*

- **boolean ehPalindromo(String palavra)**: retorna verdadeiro se a palavre é um palíndromo; Ex: *"arara"* ==> *true*.

- **String transformaParaCaixaAlta(String palavra)**: retornar palavra com letras maiúsculas; Ex: *"PhUlaNo dEtHal"* ==> *"PHULANO DETHAL"*

- **int contaVogais(String frase)**: informa a quantidade de vogais na frase; Ex: *"In God We Trust"* ==> *4*

- **String removeEspacosSuperfluos(String frase)**: retornar uma versão da frase digitada sem espaços supérfluos; Ex: *" Hay que endurecerse,    pero  sin perder la   ternura   jamás    "* ==> *"Hay que endurecerse, pero sin perder la ternura jamás"*

- **int[] ocorrencias(String frase, String subPalavra)**: retorna todas as ocorrência (índices) da subpalavra dentro da frase; Ex: *"O doce perguntou para o doce, qual o doce mais doce?"* ==> *[2, 24, 37, 47]*

- **int binarioPraDecimal(String binario)**: transforma a String binario para sua representação em decimal; Ex: *"101110010"* ==> *370*; *"1100110011"* ==> *819*

- **int getQtdadePalavras(String frase)**: retorna a quantidade de palavras separadas por espaço na frase; Ex: *"programar é muito fácil"* ==> *4*

- **int[] histogramaLetras(String texto)**: retorna um array com um histograma de letras (sem diferenciar maiúsculas de minúsculas) de um texto. Ex: *"the quick brown fox jumps over the lazy dog*" ==> *[1, 1, 1, 1, 3, 1, 1, 2, 1, 1, 1, 1, 1, 1, 4, 1, 1, 2, 1, 2, 2, 1, 1, 1, 1, 1]* (perceba que o índice 0 representa A, 1 representa B, e daí por diante) 

2. Explique qual a diferença entre criar uma String das seguintes formas: 
- *String nome = "Eduardo";*
- *String nome = new String("Eduardo");*

3. Explique como funciona o String pool.

4. O que acontece toda vez que uma String é modificada? Considere o exemplo a seguir para embasar sua resposta.
```java
String nome = "Eduardo";
nome += "de Lucena";
nome += "Falcao";
```

5. Como a classe StringBuilder pode ajudar a tornar o código anterior mais eficiente? 

Agradecimentos ao prof Bruno de Brito por ceder este material de exercícios sobre Strings.