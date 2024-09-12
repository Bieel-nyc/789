// index.js
function calcularIMC(peso, altura) {
  const imc = peso / (altura * altura);
  return imc.toFixed(2);
}

// Exemplo de uso:
const peso = 70;
const altura = 1.75;
const resultado = calcularIMC(peso, altura);
console.log("Seu IMC é:", resultado);
