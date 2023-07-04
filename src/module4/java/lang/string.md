# Classe `String`

A classe `String` em Java representa uma sequência de caracteres. Ela é uma das classes mais utilizadas na linguagem e fornece diversos métodos para manipulação e processamento de strings.

Alguns dos métodos mais comumente usados da classe `String` são:

## Manipulação de Strings
- `length()`: retorna o número de caracteres da string.
- `charAt(int index)`: retorna o caractere na posição especificada.
- `substring(int beginIndex)`: retorna uma nova string a partir do índice especificado.
- `substring(int beginIndex, int endIndex)`: retorna uma nova string do intervalo especificado.
- `concat(String str)`: concatena a string atual com a string especificada.
- `replace(char oldChar, char newChar)`: substitui todas as ocorrências de um caractere por outro.
- `toLowerCase()`: converte todos os caracteres da string para minúsculas.
- `toUpperCase()`: converte todos os caracteres da string para maiúsculas.

## Busca e Comparação
- `indexOf(String str)`: retorna o índice da primeira ocorrência da string especificada.
- `lastIndexOf(String str)`: retorna o índice da última ocorrência da string especificada.
- `contains(CharSequence sequence)`: verifica se a string contém a sequência especificada.
- `equals(Object obj)`: verifica se a string é igual ao objeto especificado.
- `startsWith(String prefix)`: verifica se a string começa com o prefixo especificado.
- `endsWith(String suffix)`: verifica se a string termina com o sufixo especificado.

## Conversão e Formatação
- `valueOf(...)`: converte outros tipos de dados em strings.
- `trim()`: remove espaços em branco no início e no final da string.
- `split(String regex)`: divide a string em substrings com base em um delimitador.
- `format(String format, Object... args)`: formata a string de acordo com um padrão especificado.

A classe `String` é imutável, ou seja, uma vez criada, seu conteúdo não pode ser alterado. No entanto, as operações de manipulação e processamento de strings retornam novas strings com os resultados desejados.

Em resumo, a classe `String` é essencial para o trabalho com texto em Java. Ela fornece uma ampla gama de métodos para manipular, buscar, comparar, converter e formatar strings, permitindo a construção de aplicações poderosas e flexíveis.
