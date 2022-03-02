# Entendendo as tecnologias .NET

[Slide Aula 2](https://docs.google.com/presentation/d/1FvIKgAR2AAA5q6CWxiUYCRt3UI88OqMP/edit#slide=id.gcb6c659826_0_39)

## Entendendo .NET Framework

- Plataforma atrelada ao Windows inicialmente;
- Possui 2 componentes principais:
  - Common Language Runtime (CLR)
    - mecanismo para gerenciar a execucao das aplicacoes; (Possui o JIT - just in time compiler)
  - Bibliotecas
- Na plataforma, o compilador da linguagem vai compilar para linguagem intermediária (common intermediate language) e, após isso, o JIT entra em acao e, em tempo de execucao, faz a traducao da CIL para o código da máquina;

## Entendendo .NET Core

- É uma plataforma unificada, cruzada: Linuz, Windows, MacOS, modular e com melhor desempenho;
-  .NET = .NET Core + .NET Framework + Xamarin + Mono

## Sobre ASP.NET Core

- Aplicacoes para Web, Internet das Coisas, Backend para mobile;
- Possui funcionalidades para construcao de aplicacoes com renderizacao no servidor;
  - Uso do MVC -> ASP.NET Core MVC
    - Model, View, Controler;
    - Model Binding;
    - Model Validation;
  - Razor Pages e Razor Markup
    - Modelo baseado em páginas - simplificado;
    - Interface e lógica de negócio sao separados, porém na mesma página;
    - Sintaxe de marcacao para inserir código baseado em .NET em páginas WEB = Razor Markup + C# + HTML
  - Tag Helpers
    - Permite que o código do lado do servidor participe da criacao e renderizacao de elementos HTML em arquivos Razor;
    - Desenvolvimento com HTML mais amigável;
    - IntelliSense no ambiente para sintaxe HTML e Razor;
    - Facilita a manutencao do código;
  - Blazor
    - Framework para construir app do lado do cliente, executados com WebAssembly (WASM);
    - Consegue rodar com JavaScript mesmo sendo desenvolvido com C# (interoperabilidade);

## Entendendo Xamarin

- Aplicacoes Mobile;
- Interface nativa em cada plataforma (Android, IOS, MacOS, Windows Apps) e um único código de lógica C# ;
- Criacao de UI em XAML e lógica C# ;
- Biblioteca Xamarin.Essencials;
