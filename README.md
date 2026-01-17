# Sorteador de Números

Este projeto é uma aplicação web simples desenvolvida para praticar lógica de programação com JavaScript. O objetivo é sortear números aleatórios únicos dentro de um intervalo definido pelo usuário.

## 📝 Funcionalidades

- **Definição de Intervalo:** O usuário pode escolher o número inicial ("Do número") e o número final ("Até o número") do sorteio.
- **Quantidade Personalizada:** É possível definir quantos números serão sorteados dentro do intervalo.
- **Sorteio sem Repetição:** A lógica implementada verifica e garante que os números sorteados não se repitam.
- **Controle de Estado:** O botão "Reiniciar" é habilitado ou desabilitado visualmente conforme o fluxo da aplicação.

## 🚀 Como Usar

1. Insira a **quantidade** de números que deseja obter.
2. Insira o valor mínimo no campo **"Do número"**.
3. Insira o valor máximo no campo **"Até o número"**.
4. Clique no botão **"Sortear"**.
5. Os números sorteados aparecerão na tela.
6. Para realizar um novo sorteio, clique em **"Reiniciar"**.

## 💻 Tecnologias

- **JavaScript:** Lógica principal (`app.js`) para manipulação do DOM e geração de números aleatórios.
- **HTML/CSS:** Estrutura e estilo da página (implícito).

## ⚠️ Observações sobre o Código

O arquivo principal `app.js` contém as seguintes funções:
- `sortear()`: Captura os inputs, valida a unicidade e exibe os resultados.
- `obterNumeroAleatorio(min, max)`: Gera um número inteiro aleatório inclusivo.
- `alterarStatusBotao()`: Alterna a classe CSS do botão de reiniciar.
- `reiniciar()`: Limpa os campos e reseta a aplicação.
