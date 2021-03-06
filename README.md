## Description 
Repositório exclusivo para realizar a matéria de compiladores na instituição CEFET-MG

## Compiladores x Interpretadores 
Basicamente, um compilador é um programa (ou um conjunto deles) como qualquer outro, porém seu objetivo principal é o de traduzir todas as suas linhas de código para outra linguagem – normalmente, uma de alto nível para outra de baixo nível (Assembly ou linguagem de máquina). Delphi, Rust, C++ e Swift figuram na lista de compiladas.

Um interpretador também é um programa, mas, ao contrário do compilador, ele não converte o código todo para linguagem de máquina de uma vez. Ele executa diretamente cada instrução, passo a passo. MATLAB, Lisp, Perl e PHP são apontadas como interpretadas.

Em suma, a grande diferença está na forma de execução. Enquanto um compilador analisa todo o código a fim de traduzi-lo de uma vez (muitas vezes, o resultado é um arquivo executável ou uma biblioteca), o interpretador faz esse trabalho de conversão aos poucos, sempre que uma declaração ou função é executada, por exemplo.

Como resultado, linguagens compiladas tendem a executarem mais rapidamente, visto que sua aplicação já está toda convertida em linguagem de máquina. Por outro lado, em códigos muito extensos pode haver um maior tempo de espera para iniciar a real execução da aplicação. Já as linguagens compiladas perdem um pouco de performace, visto que elas são compiladas/interpretadas linha a linha no momento da execução. Porém para códigos muito extensos é possivel visualizar a real execução da aplicação em bem menos tempo em relação a outras aplicação desenvolvidas com linguagens compiladas.


# Análise Lexica
## Introductio
Na ciência da computação, análise léxica, lexing ou tokenização é o processo de converter uma sequência de caracteres (como em um programa de computador ou página da web) em uma sequência de tokens (strings com um significado atribuído e, portanto, identificado). Um programa que realiza análise lexical pode ser denominado lexer, tokenizer, ou scanner, embora scanner também seja um termo para o primeiro estágio de um lexer. Um lexer geralmente é combinado com um analisador, que juntos analisam a sintaxe de linguagens de programação, páginas da Web e assim por diante.

## Description
O suposto diretório trata a análise Léxica de uma linguagem de programção. Para tal feito, foi elaborado um 'compilador' em python e um código em c++ que simula uma calculadora simples. Como explicado na introdução, a ideia do compilador é separar todo o código em categorias de token que façam sentido para o contexto da linguagem. As categoria abordadas no código são:
1. reserved: São um conjunto de palavras reservadas (tem funções definidas dentro da linguagem - if, else, while...)
2. assignment: Operadores de atribuição da linguagem (=, <<)
3. delimiters: Delimitam o inicio ou fim de algo dentro da linguagem ({,},(,),[,])
4. operator: São responsaveis por realizar operações matematicas dentro da linguagem
5. comparation: São responsaveis por realizar operações logicas
6. literal: São um conjunto de caracteres delimitados por aspas (são normalmente textos ou strings - "my-text")
7. number: São valores numericos definidos pelo dominio Real.


## References
<a href="https://imasters.com.br/desenvolvimento/metodos-de-traducao-interpretador-x-compilador#:~:text=Enquanto%20um%20compilador%20analisa%20todo,fun%C3%A7%C3%A3o%20%C3%A9%20executada%2C%20por%20exemplo.">Compilador x Interpretador<a>
<a href="https://pt.wikipedia.org/wiki/An%C3%A1lise_l%C3%A9xica">Analise Lexica<a>