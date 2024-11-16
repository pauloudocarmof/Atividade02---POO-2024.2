# Atividade02---POO-2024.2

1) 
     Dinâmica: O tipo da variável é definido em tempo de execução.
     Estática: O tipo é definido em tempo de compilação.
2)
     Pode causar erros difíceis de detectar, como operações inválidas em tipos inesperados.

3)
   x = "10"  
  print(x + 5)  # Gera erro pois "10" é string.

4) Em C, tipos diferentes podem ser implicitamente convertidos, levando a resultados inesperados:
int x = 10;  
float y = x / 4;

5) Não é considerada fraca, pois aceitar inteiros e floats em number é uma escolha de design, não uma fraqueza da tipagem.

6)  

const name = "Ely";
const paymentTime = 120.56;
const preferredLanguage = "TypeScript";

const message = `${name}
My payment time is ${paymentTime}
and
my preferred language is ${preferredLanguage}`;

console.log(message);


