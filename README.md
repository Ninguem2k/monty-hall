# 🚪 Problema de Monty Hall – Simulação Interativa

[![Licença: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Simulação interativa do clássico **Problema de Monty Hall**, inspirada na cena do filme *Quebrando a Banca* (21).  
O jogo demonstra, na prática, por que **trocar de porta dobra suas chances** de ganhar o carro.

---

## 📖 O que é o Problema de Monty Hall?

O problema é baseado no programa de televisão americano *Let’s Make a Deal*, apresentado por Monty Hall.

### Cenário
1. O participante escolhe **uma entre três portas**. Atrás de uma delas há um carro; atrás das outras duas, bodes.
2. O apresentador (que sabe onde está o carro) **abre uma das portas não escolhidas**, revelando um bode.
3. O participante tem a opção de **trocar** pela outra porta fechada ou **manter** a escolha inicial.

A matemática mostra que **trocar de porta dá 2/3 de chance de vitória**, enquanto manter dá apenas 1/3.  
Esta simulação permite que você teste essa estratégia na prática.

---

## 🎬 Referência ao filme

A cena do filme *Quebrando a Banca* (21) popularizou o problema, quando o professor (Kevin Spacey) explica a solução ao seu aluno.  
O vídeo da cena está **incorporado** na própria página, para você assistir e relacionar com a simulação.

---

## 🎮 Como funciona o jogo?

### Regras
- Você vê três portas (1, 2 e 3).
- Clique em uma porta para fazer sua escolha inicial.
- O apresentador (o jogo) automaticamente abre uma das outras portas, revelando um bode.
- Agora você deve decidir:
  - **Trocar** de porta (escolher a única porta fechada restante) ou
  - **Manter** sua escolha original.
- O jogo revela o conteúdo de todas as portas e mostra se você ganhou ou perdeu.

### Estatísticas em tempo real
Abaixo do jogo, um painel acumula seus resultados:
- Total de jogos
- Vitórias e derrotas
- Taxa de vitória (%)
- Vitórias quando **trocou** de porta
- Vitórias quando **manteve** a porta

Com o tempo, você verá que a taxa de vitória ao trocar se aproxima de **~66,7%**, comprovando a solução matemática.

---

## 🛠️ Como executar

1. Baixe o arquivo `monty-hall.html`.
2. Abra-o com qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
3. Tudo funciona localmente – não é necessário servidor ou internet (exceto para carregar o vídeo do YouTube).

---

## 🧠 Por que trocar é melhor?

Explicação rápida:

- Inicialmente, a chance de o carro estar atrás da sua porta é **1/3**.
- A chance de estar atrás de uma das outras duas portas é **2/3**.
- Quando o apresentador abre uma dessas duas portas (sempre revelando um bode), aquele **2/3** de chance **concentra-se inteiramente na porta não aberta**.
- Portanto, trocar dá a você essa probabilidade de **2/3** de ganhar.

---

## 📺 Vídeo da cena

O vídeo incorporado na página é da cena do filme *Quebrando a Banca* (em português).  
Caso o vídeo não seja exibido, verifique sua conexão com a internet ou substitua o ID do vídeo no código (`https://www.youtube.com/watch?v=fwoq2ZzLuQo`).

---

## ✨ Tecnologias

- HTML5
- CSS3 (animações 3D, responsividade)
- JavaScript (lógica do jogo, estatísticas)

---

## 📁 Estrutura do arquivo

O projeto é um único arquivo HTML autossuficiente, contendo:
- Todos os estilos CSS embutidos
- Todo o JavaScript embutido
- Sem dependências externas (exceto o vídeo do YouTube)

---

## 📝 Créditos

- Inspirado no filme *21 – Quebrando a Banca* (2008)
- Explicação matemática baseada no clássico problema de Monty Hall
- Ícones por [Font Awesome](https://fontawesome.com/)

---

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e distribuir.

---

Divirta-se e **troque sempre**! 🚗🐐
