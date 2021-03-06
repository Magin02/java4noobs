<h1>Declaração de váriaveis</h1>

As váriaveis são formas de armazenar algo na memória do computador, que, podem ser reutilizadas durante o código. Elas são de extrema importância e sua <a href="#"> tipagem</a> também. 

Quando se declara uma váriavel você coloca o tipo dela antes (int, float, double, string, char), o nome que não pode ser um nome reservado da linguagem (como por exemplo os nomes dos tipos de váraiveis), não pode conter números no inicio nem acentuações. Após isso coloca-se um "=" para dizer que o valor que vem a frente é atribuido a váriavel, lê-se recebe;

```java
    public class Variaveis {
        public static void main(String args[]) {
            //tipo nome = valor;
            int nome = 10; //Exemplo básico.
        }
    }
```

Os código abaixo demonstrarão a implementação de variáveis.




```java
public class VariaveisInteiras {
    public static void main(String args[]) {
        int numero1 = 3; //variavél inteira com o nome de "numero1" recebe o valor de 3.

        int nome = 4; //variavél inteira com o nome de "nome" recebe o valor de 4.

        int idadeAluno = 15; //variável inteira com o nome de "idadeAluno" recebe o valor de 15.

        System.out.println("O valor da váriavel de numero1 é " + numero1 + " e a nome é " + nome); //estou mostrando no terminal o os valores das variaveis, para mostrar elas, você quebra a STRING finalizando, coloca um "+" e depois o nome da váriavel.

        System.out.println("A idade do aluno é de " + idadeAluno + " anos.");
    }
}
```

```java
public class VariaveisFlutuantes{
    public static void main(String args[]) {
        double numero1 = 2.3; //variável de ponto flutuate (no caso double) com o nome de "numero1" recebe o valor de 2.3.

        float nome = (float)4.2; //variável de ponto flutuate (no caso double) com o nome de "nome" recebe o valor de 4.2.

        double mediaIdades = 13.5; //variável de ponto flutuate (no caso float) de nome "mediaIdades" recebe o valor de 13.5.

        System.out.println("O valor da váriavel de numero1 é " + numero1 + " e a numero2 é " + nome); //estou mostrando no terminal o os valores das variaveis, para mostrar elas, você quebra a STRING finalizando, coloca um "+" e depois o nome da váriavel.

        System.out.println("A media de idades da turma é de " + mediaIdades ".");
    }
}
```
```java
    public class VariaveisBooleanas {
        public static void main(String args[]) {
            boolean ehMaior = true; //variável booleana (que é somente true ou false, de nome "ehMaior" recebe o valor de verdadeiro).

            boolean nome = false; //variável booleana (que é somente true ou false, recebe o valor de verdadeiro).

            boolean mediaDeIdadesMaiorQueDez = true;

            System.out.println("O valor da váriavel de nome ehMaior é " + ehMaior + " e a nome é " + nome);//estou mostrando no terminal o os valores das variaveis, para mostrar elas, você quebra a STRING finalizando, coloca um "+" e depois o nome da váriavel.

            System.out.println("A media de idades é maior que dez? Resposta: " + mediaDeIdadesMaiorQueDez);
        }
    }
```

```java
    public class VariaveisChar {
        public static void main(String args[]) {
            char letra = 'j'; //variável char de nome "letra" recebe o valor de j.

            char nome = 'n'; //variável char com nome "nome" recebe o valor de n.

            char primeiraLetraDoAlfabeto = 'a';

            System.out.println("O valor da váriavel de nome letra é " + letra + " e a nome é " + nome);//estou mostrando no terminal o os valores das variaveis, para mostrar elas, você quebra a STRING finalizando, coloca um "+" e depois o nome da váriavel.

            System.out.println("A primeira letra do alfabeto é: " + primeiraLetraDoAlfabeto);

        }
    }
```

```java
    public class VariaveisString {
        public static void main(String args[]) {
            String nomeAluno = "Paulo Oliveira"; //variavel String de nome "nomeAluno" recebe o valor de Paulo Oliveira.

            String nome = "Valor"; //variável de nome "nome" recebe o valor de Valor

            System.out.println("O valor da váriavel de nome letra é " + letra + " e a nome é " + nome);//estou mostrando no terminal o os valores das variaveis, para mostrar elas, você quebra a STRING finalizando, coloca um "+" e depois o nome da váriavel.

        }
    }
```

Nós podemos juntar todas as váriaveis para compor o programa mais completo. Veja abaixo um exemplo.

```java
    public class VariaveisJuntas {
        public static void main(String args[]) {
            String nomeAluno = "Paulo Oliveira";
            int idadeDoAluno = 15;
            double mediaIdades = 13.5;
            boolean alunoTemIdadeAcimaDaMedia = true;

            System.out.println("O aluno de nome " + nomeAluno + " com idade de "+ idadeDoAluno + " anos tem idade acima da media? " + alunoTemIdadeAcimaDaMedia);

        }
    }
```

As variáveis tem várias peculiaridades, você não consegue sobrepor elas, por exemplo, criar duas váriaveis com o mesmo nome. Por exemplo:

```java
    public class Variaveis {
        public static void main(String args[]) {
            //tipo nome = valor;
            int nome = 10; //Exemplo básico.
            int nome = 15; //Exemplo básico.

            //OBS: ESSE PROGRAMA GERA ERRO.

        }
    }
```

Esse tipo de programa geraria um erro.

Ou também utilizar acentos, caracteres especiais e numeros no inicio.

```java
    public class Variaveis {
        public static void main(String args[]) {
            //tipo nome = valor;
            int !nome = 10; //Exemplo básico.
            int 1nome = 15; //Exemplo básico.
            int nomé = 1245; //Exemplo básico.

            //OBS: ESSE PROGRAMA GERA ERRO.
        }
    }
```

É uma ótima pratica colocar nomes que fazem sentido para as váriaveis, no exemplo de classe VariaveisJuntas, utilizei os nomes com semântica, nos demais, foi para exemplo. Siga a ideia dele.