// Função para calcular a média aritmética
function calcularMediaAritmetica(notas) {
  const somaNotas = notas.reduce((acumulador, nota) => {
    return acumulador + nota;
  }, 0);

  return somaNotas / notas.length;
}

// Exemplo de utilização
const notas = [7, 8, 9, 6, 7];

const mediaAritmetica = calcularMediaAritmetica(notas);
console.log(`A média aritmética é: ${mediaAritmetica.toFixed(2)}`);
