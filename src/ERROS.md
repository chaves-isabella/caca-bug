Durante a análise do código, o primeiro erro identificado foi um construtor incompleto, provocado pela ausência do this. na atribuição dos dados. A solução aplicada foi adicionar o this. aos atributos dentro do próprio construtor.

Outro problema encontrado foi um cálculo incorreto no método aumentarSalario, em que o valor do percentual estava sendo somado diretamente ao salário, sem o cálculo prévio da porcentagem. A correção foi feita dividindo o percentual por 100 e somando o valor resultante ao salário.
