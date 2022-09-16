## TRABALHO EM GRUPO - FIAP

Integrantes: 

Daphyne Vitorino,

Flávia Sorati,

Maysa Gonçalves,

Miguel Cardoso,

Tati Alvarenga



##  PROBLEMA I - TABUADA

Demonstração do console do código fonte do repositório:

<img width="374" alt="ex1" src="https://user-images.githubusercontent.com/94724021/190700434-0dd3c1cf-72bf-49e1-b289-5107e0f943d1.png">

## PROBLEMA II - EXPRESSÕES REGULARES

CEP: 01311-100

CPF: 333.111.222-00

CNPJ: 12.321.123/0001-02

RG: 22.455.213-2

EMAIL: email@fiap.com.br

--------------------------------

Expressão regular onde o formato **123.456.abc.def** seja válido, porém **2123.456.abc.def** também pode ser válido.

-------------------------------

**Resolução**

CEP: /^[0-9]{5}\-[0-9]{3}$/,

CPF: /^[0-9]{3}\.[0-9]{3}\.[0-9]{3}\-[0-9]{2}$/,

CNPJ: /^[0-9]{2}\.[0-9]{3}\.[0-9]{3}\/[0-9]{4}\-[0-9]{2}$/,

RG: /^[0-9]{2}\.[0-9]{3}\.[0-9]{3}\-[0-9]{1}$/,

E-MAIL: /^[a-z0-9._]+@[a-z0-9]+\.[a-z]+\.[a-z]+$/i;

--------------------------------

/^[0-9]{3,4}\.[0-9]{3}\.[a-z]{3}\.[a-z]{3}$/i



