// index.js
function calcularIMC(peso, altura) {
  const imc = peso / (altura * altura);
  return imc.toFixed(2);
}

// Exemplo de uso:
const peso = 90;
const altura = 1.80;
const resultado = calcularIMC(peso, altura);
console.log("Seu IMC é:", resultado);