# MDTools :unlock:
> Pequeno programa em Python para facilitar os cálculos da disciplina de Matemática Discreta.

## Utilização

Para correr o programa, `python3 MDTools.py`

## Funcionalidades

#### Algoritmo FFT ####

        A) Ver algortimo

#### Algoritmo RSA ####

        B) Descobrir inverso de e mod (p-1)*(q-1)
        C) Fazer módulos rapidamente
        D) Obter soma em base 2 de número
        E) Ver algoritmo RSA - Trabalho ainda em progresso!

#### Congruências ####

        F) Máximo Divisor Comum
        G) Simplificar congruências
        H) Coeficientes de Bézout
        I) Equações Diofantinas

#### Calendários ####

        J) Juliano
        K) Gregoriano
        L) Pascoa Juliana
        M) Pascoa Gregoriana (step by step)

#### Grafos ####

        N) Noções Básicas
        O) Teoremas
        P) Algoritmo de Fleury

## RSA (Teoria)

RSA é um algoritmo de criptografia de dados, que deve o seu nome a três professores do Instituto de Tecnologia de Massachusetts (MIT), Ronald Rivest, Adi Shamir e Leonard Adleman, fundadores da actual empresa RSA Data Security, Inc., que inventaram este algoritmo — até a data (2008) a mais bem sucedida implementação de sistemas de chaves assimétricas, e fundamenta-se em teorias clássicas dos números. É considerado dos mais seguros, já que mandou por terra todas as tentativas de quebrá-lo. Foi também o primeiro algoritmo a possibilitar criptografia e assinatura digital, e uma das grandes inovações em criptografia de chave pública.

> _O servidor e o cliente geram as suas chaves públicas e privadas. O servidor envia para o cliente sua_ **_chave pública_**_, e o cliente
> envia para o servidor sua_ **_chave pública_**_._
> 
> _O cliente criptografa seus dados com a_ **_chave pública_** _(do servidor),_  _e envia para o servidor._
> 
> _O servidor descriptografa os dados com a sua_ **_chave privada_**_._
> 
> _O servidor criptografa o que será enviado para o cliente com a_ **_chave pública_** _do cliente, e envia para o cliente._
>
>_O cliente consegue, por fim, descriptografar o retorno do servidor, com sua_ **_chave privada_**_._


