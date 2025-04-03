### Este documento foi elaborado a partir de exercícios previamente resolvidos na plataforma Beecrowd, com o auxílio de Inteligência Artificial para a organização e estruturação dos tópicos abordados.

# Funções Java Utilizadas nos Códigos

## 1. `Scanner`
### Classe `Scanner`
- **`Scanner s = new Scanner(System.in);`**
  - Cria um objeto `Scanner` para leitura de entradas do usuário.

- **`s.nextInt();`**
  - Lê um valor inteiro digitado pelo usuário.

- **`s.nextDouble();`**
  - Lê um valor decimal (ponto flutuante) digitado pelo usuário.

- **`s.nextLine();`**
  - Lê uma linha completa de entrada do usuário.

## 2. Operadores Matemáticos

- **Soma (`+`)**
  - Exemplo: `int soma = A + B;`
  - Realiza a soma de dois valores inteiros.

- **Multiplicação (`*`)**
  - Exemplo: `double media = (((A*3.5)+(B*7.5))/11);`
  - Realiza a multiplicação de valores.

- **Divisão (`/`)**
  - Exemplo: `double consumo_medio = (X/Y);`
  - Divide um valor pelo outro e retorna o resultado.

- **Módulo (`%`)**
  - Exemplo: `dias = (N % 365) % 30;`
  - Retorna o resto da divisão entre dois números.

## 3. Classe `Math`
- **`Math.abs(x);`**
  - Retorna o valor absoluto de `x`. //valor que não contem - e +
  - Exemplo: `Math.abs(a-b);`

- **`Math.sqrt(x);`**
  - Calcula a raiz quadrada de `x`.
  - Exemplo: `distancia = Math.sqrt((Math.pow(x2-x1,2)) + (Math.pow(y2-y1,2)));`

- **`Math.pow(base, expoente);`**
  - Calcula a potência de `base` elevada ao `expoente`.
  - Exemplo: `Math.pow(x2-x1,2);`

## 4. Conversão de Tipos
- **`Integer.parseInt(String);`**
  - Converte uma string para um inteiro.
  - Exemplo: `a = Integer.parseInt(dados_separados[0]);`

- **`Float.parseFloat(String);`**
  - Converte uma string para um número de ponto flutuante (float).
  - Exemplo: `x1 = Float.parseFloat(dados_separados[0]);`

## 5. Manipulação de Strings
- **`String.split(" ");`**
  - Divide uma string em um array de substrings com base no espaço (`" "`).
  - Exemplo: `String[] dados_separados = entrada.split(" ");`

## 6. Formatação de Saída
- **`String.format("%.5f", valor);`**
  - Formata um número de ponto flutuante para exibir 5 casas decimais.
  - Exemplo: `System.out.println("MEDIA = " + String.format("%.5f", media));`

- **`System.out.printf("%.4f\n", valor);`**
  - Imprime um valor formatado com 4 casas decimais.
  - Exemplo: `System.out.printf("%.4f\n", distancia);`

## 7. Entrada e Saída de Dados
- **`System.out.println(valor);`**
  - Exibe o valor e pula para a próxima linha.
  - Exemplo: `System.out.println(resultado_final + " eh o maior");`

- **`System.out.print(valor);`**
  - Exibe o valor sem pular de linha.
  - Menos comum nos exemplos dados, mas pode ser usado para saídas mais controladas.

Essas funções e métodos são fundamentais para manipulação de dados em Java e ajudam a resolver problemas de forma eficiente!
