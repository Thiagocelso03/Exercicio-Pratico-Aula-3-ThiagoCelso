EXERCÍCIO PRÁTICO RÁPIDO

Aluno: Thiago Celso Souto Da Silva Data: 13-10-2025

Complete o código abaixo:

Typescript

// 1. Crie um tipo literal para cor com: "vermelho", "azul", "verde"

type _Cor_ \= "vermelho" | "azul" | "verde";

// 2. Crie um tipo Carro com:

// - marca (string, readonly)

// - modelo (string)

// - cor (do tipo Cor acima)

// - ano? (opcional, number)

type _Carro_ \= {

readonly marca: _string_; modelo: _string_;

cor: _Cor_; ano?: _number_;

};

// 3. Crie uma função Generic que retorne o primeiro elemento de um array

function primeiro<_T_\>(_arr_: _T_\[\]): _T_ | _undefined_ { return _arr_\[0\];

}