# explicacao

O cálculo do CPF é feito com dois dígitos verificadores, calculados a partir dos 9 primeiros números do documento. O primeiro dígito é gerado aplicando o algoritmo de módulo 11 aos 9 primeiros dígitos, e o segundo dígito é obtido do mesmo modo, mas usando os 9 primeiros dígitos mais o primeiro verificador. 
Cálculo do primeiro dígito verificador
Multiplique os 9 primeiros dígitos por pesos de 10 a 2, da esquerda para a direita.
Some os resultados das multiplicações.
Divida a soma por 11 e guarde o resto.
Subtraia o resto de 11. Se o resultado for 10 ou 11, o dígito é 0; caso contrário, o resultado é o dígito. 

O validador sabe se o CPF é válido comparando os dígitos verificadores calculados com os dígitos reais do CPF. Se forem iguais, é válido; se forem diferentes, é inválido.




