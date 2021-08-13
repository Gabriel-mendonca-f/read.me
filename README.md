# **[COMPILADORES] Q3-2021**
# *Entrega de Projeto --ProjLang--*

Conteúdos
=================

<!--ts-->
   * [Descrição do projeto](#descrição-do-projeto)
   * [Itens obrigatórios](#itens-obrigatórios-)
   * [Itens opcionais](#itens-opcionais-)
   * [Comandos e funções](#comandos-e-funções-)
   * [Exemplo de código](#exemplo-de-código-%EF%B8%8F)

<!--te-->


Descrição do Projeto 📋
====================
A linguagem ProjLang foi desenvolvida como projeto final para a disciplina Compiladores Q2-2021

Criada com o auxílio da ferramenta ANTLR 4 (versão antlr-4.5-complete), e possúi destino final a linguagem Java

Itens obrigatórios ✅
==================
- [X] 2 tipos de variáveis (String,Double)
- [X] possuir if-else
- [X] 1 estrutura de repetição (while)
- [X] verificar atribuição de variáveis (erro semântico) - compatibilidade de tipos
- [X] operações de entrada e saída (leia e escreva)
- [X] aceitar números decimais
- [X] verificar se a variável foi ou não declarada
- [X] verificar se a variável declarada foi ou não utilizada
- [X] linguagem de destino: Java

Itens opcionais 💡
===============
- [X] compatibilidade de tipos em expressões comparativas
- [X] repetição do-while
- [X] indicação do tempo de compilação 
- [X] repetição for

Comandos e funções 🔧
==================

|Função                                    |Comando
|------------------------------------------|--------|
|início do código:                         |programa
|fim do código:                            |fimprog
|para a declaração de variáveis numéricas: |numero
|para a declaração de palavras (strings):  |texto
|para ler uma entrada a                    |leia(a)
|operação de adição de a por b:            |a + b
|operação de subtração de a por b:         |a - b
|operação de multiplicação de a por b:     |a * b
|operação de divisão de a por b:           |a / b
|comparatico a maior que b:                |a > b

Exemplo de código 🖥️
=================
->  
 
    programa
      numero a, b, c, d, i;
      texto t1;

      leia(a);
      leia(b);

      a = 1+2*3/b;

      se (a < b ) {
        escreva (a);
      }
      senao {
        escreva(b);
      }	

      t1 = "testing";

        repetir (i=0; i<3; i=i+1) {
          escreva(a);
        }

        escreva(t1);

    fimprog;
