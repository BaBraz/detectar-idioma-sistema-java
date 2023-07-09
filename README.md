# Detectar Idioma do Sistema em Java

Este projeto em Java demonstra como detectar o idioma do sistema em que o programa está sendo executado.

## Como funciona

O programa utiliza a classe `Locale` da biblioteca Java `java.util` para obter o idioma padrão do sistema. A classe `Locale` representa informações de localização, incluindo idioma, país e variantes.

No método principal (`main`), o código obtém o `Locale` padrão do sistema através do método `Locale.getDefault()`. Em seguida, utiliza o método `getDisplayLanguage()` para obter o nome legível do idioma representado pelo `Locale`.

A mensagem "O idioma do sistema é o {idioma}." é exibida no console, onde {idioma} é o nome do idioma detectado.

## Pré-requisitos

- Java SDK instalado
- Ambiente de desenvolvimento Java (por exemplo, Eclipse, IntelliJ IDEA)

## Executando o programa

1. Clone este repositório em sua máquina local.
2. Abra o projeto em seu ambiente de desenvolvimento Java.
3. Compile e execute o arquivo `IdiomaSistema.java`.
4. O idioma do sistema será exibido no console.

Sinta-se à vontade para explorar o código fonte para entender o funcionamento em detalhes.
