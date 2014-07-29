 Code Craft - BasicTools
=========================

> [Aeon Digital](http://www.aeondigital.com.br)
>
> rianna@aeondigital.com.br


**Code Craft** é um conjunto de soluções front-end e outras server-side para a construção de aplicações web.
Tais soluções aqui apresentadas são a minha forma de compartilhar com a `comunidade online` parte do que aprendi 
(e continuo aprendendo) nos foruns, sites, blogs, livros e etc. assim como na experiência adquirida no contato
direto com profissionais e estudantes que, como eu, amam o universo `Web Developer` e nunca se dão por satisfeitos 
com seu nível atual de conhecimento.


## C.C. - BasicTools

Esta biblioteca traz um conjunto de métodos básicos que possívelmente serão úteis para escrever
outras bibliotecas, widgets e aplicações javascript.


### Verificação de Tipos.

* `TypeOf`                          : Retorna o Tipo do Objeto informado.
* `IsNotNullValue`                  : Verifica se o valor informado é qualquer um diferente de undefined, null ou '' .
* `IsObject`                        : Verifica se o objeto passado é do tipo 'object'.
* `IsBoolean`                       : Verifica se o objeto passado é do tipo 'boolean'.
* `IsNumber`                        : Verifica se o objeto passado é do tipo 'number'.
* `IsInteger`                       : Verifica se o objeto passado é do tipo 'number' e se é inteiro.
* `IsString`                        : Verifica se o objeto passado é do tipo 'string'.
* `IsDate`                          : Verifica se o objeto passado é do tipo 'Date'.
* `IsArray`                         : Verifica se o objeto passado é do tipo 'Array'.
* `IsJSON`                          : Verifica se o objeto passado é do tipo 'JSON'.
* `IsFunction`                      : Verifica se o objeto passado é do tipo 'function'.


### Formatação de Strings.

* `Trim`                            : Remove espaços em branco no inicio e no final da string.
* `ReplaceAll`                      : Substitui toda ocorrência de determinada string por uma outra definida.
* `RemoveChars`                     : Remove da string todas as ocorrências da cadeia de caracteres informado.


### Conversão de Tipos.

O objeto `TryParse` traz algums métodos que permitem tentar a conversão dos objetos passados.
O comportamento padrão de todos os métodos abaixo é o de retornar o valor original do objeto passado
caso a conversão não seja possível.

* `TryParse.ToBoolean`              : Converte o tipo do valor passado para 'boolean'.
* `TryParse.ToNumber`               : Converte o tipo do valor passado para 'number'.
* `TryParse.ToInteger`              : Converte o tipo do valor passado para um 'number integer'.
* `TryParse.ToFloat`                : Converte o tipo do valor passado para um 'float number'.
* `TryParse.ToDate`                 : Converte o tipo do valor passado para um objeto 'date'.


### Manipulação de Objetos.

* `InitiSet`                        : Caso o objeto a ser testado não tenha sido iniciado, retorna o valor padrão.
* `DynamicSort`                     : Permite ordenar um array de objetos a partir da indicação de uma de suas propriedades.
* `CloneObject`                     : Clona um objeto completamente.
* `GetFieldType`                    : Identifica o tipo de campo do elemento passado.


**Importante**

Tenha em mente que em algumas vezes, neste e em outros projetos **Code Craft** optou-se de forma consciênte em 
não utilizar uma ou outra *regra de otimização* dos artefatos de software quando foi percebida uma maior vantagem para
a equipe de desenvolvimento em flexibilizar tal ponto do que extritamente seguir todas as regras de otimização.


### Compatibilidade

Não é intenção deste nem de outros projetos do conjunto de soluções **Code Craft** em manter 
compatibilidade com navegadores antigos (IE8<).


________________________________________________________________________________________________________________________



## Licença

Para este e outros projetos **Code Craft** é utilizada a [Licença GNUv3](LICENCE.md).