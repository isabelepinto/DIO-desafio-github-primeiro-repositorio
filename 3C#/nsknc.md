## Métodos

[Docs Métodos](https://docs.microsoft.com/pt-br/dotnet/csharp/programming-guide/classes-and-structs/methods)

Os métodos que manipulam cadeias de caracteres retornam novos objetos de cadeia de caracteres, em vez de fazer modificações no local.  O uso de um método retorna uma nova cadeia de caracteres, mas **não altera a mensagem original**. _Diferentemente das PROPRIEDADES_;

- O método precisa finalizar com ( ); pois é dentro do parênteses que irá realizar a função;

  - string sayHello = "Hello World!"; 

  - Console.WriteLine(sayHello);

  - _sayHello = sayHello.Replace("Hello", "Greetings");_

  - Console.WriteLine(sayHello);

  - - Console.WriteLine(sayHello.ToUpper()); 
    - Console.WriteLine(sayHello.ToLower());

[Exemplos de Métodos C#](https://docs.microsoft.com/pt-br/dotnet/csharp/tour-of-csharp/tutorials/hello-world?tutorial-step=5)

- Lembrando que a variável pode armazenar o método, exemplo:
  - _sayHello = sayHello.Replace("Hello", "Greetings");_
  - É a mesma coisa de criar uma variável  _string substituir = sayHello.Replace("Hello", "Greetings");_ e depois Console.WriteLine(substituir);

#### Números

- **Para números inteiros int, o resultado também será inteiro.**
- No caso, podemos usar o método % para verificar qual o resto da divisão:

- ```
  int a = 7;
  int b = 4;
  int c = 3;
  int d = (a + b) / c;
  int e = (a + b) % c;
  Console.WriteLine($"quotient: {d}");
  Console.WriteLine($"remainder: {e}");
  
  quotient: 3
  remainder: 2
  ```

- _O tipo numérico `double` representa um número de ponto flutuante de precisão dupla. Esses termos podem ser novidade para você. Um número de **ponto flutuante** é útil para representar números não integrais que podem ser muito grandes ou pequenos em magnitude. A **precisão dupla** é um termo relativo que descreve os números de dígitos binários usados para armazenar o valor. O número de **precisão dupla** tem duas vezes o número de dígitos binários como **uma única precisão**. Em computadores modernos, é mais comum usar precisão dupla que números de precisão única. Números de **precisão única** são declarados usando a `float` palavra-chave. Vamos explorar._

- Há um outro tipo para aprender: o `decimal` tipo. O tipo `decimal` tem um intervalo menor, mas precisão maior do que `double`:

  - double a = 1.0;
    double b = 3.0;
    Console.WriteLine(a / b);

    ```
    double a = 1.0;
    double b = 3.0;
    Console.WriteLine(a / b);
    
    decimal c = 1.0M;
    decimal d = 3.0M;
    Console.WriteLine(c / d);
    
    0.333333333333333
    0.3333333333333333333333333333
    ```



# Reference Type and Valeu Type

[Slide Aula Dio](https://docs.google.com/presentation/d/1tuJDTzT3PenfsEE2_GG6UEGhT9HxvtqX/edit#slide=id.p1)

[Repositorio GitHub da Aula](https://github.com/ricardovicentini/Reference-Type-And-Value-Type)
