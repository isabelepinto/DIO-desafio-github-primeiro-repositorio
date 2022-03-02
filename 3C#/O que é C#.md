# O que é o C#?

- É uma linguagem elegante, orientada a objetos e fortemente tipada;
- A sintaxe do C# é similar a do C,C++ ou Java;
- Suporta os conceitos de encapsulamento, herança e polimorfismo (OO);
- Os programas do C# sao executados no .NET, que inclui:
  - CLR (Common Language Runtime)
  - Conjunto unificado de bibliotecas de classes;
- Atualmente o compilador do C# é o Roslyn;

#### Como funciona?

- O código-fonte escrito em C# é compilado em uma linguagem intermediária (IL)
- O código e os recursos de IL são armazenados no disco em um arquivo executável chamado Assembly, geralmente com uma extensão .exe ou .dll
- Quando o programa C# é executado, o Assembly é carregado no CLR;
- Em seguida o CLR executará a compilação Just In Time (JIT) para converter o código IL em instruções de máquina nativas;
- O CLR nao apenas traduz a linguagem intermediária para linguagem de máquina. **O CLR também executa outros servicos:**
  - Garbage Collector
  - Exception Handler
  - Resources Manager