[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tro2Z-6l)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23170901&assignment_repo_type=AssignmentRepo)
# Lab 01: Lógica de Programação com Blockly 🐢

Bem-vindo(a) à sua atividade prática de Lógica Computacional! Siga os passos abaixo para completar o desafio.

**Nome do Aluno:** [Preencha seu nome aqui]
**Matrícula:** [Preencha sua matrícula]
---

## 🎯 Objetivo
Demonstrar capacidade de resolução de problemas algorítmicos completando o **Nível 10** do jogo da Tartaruga (Turtle). 

## 📝 Instruções

**Passo 1: Jogue e Resolva**

Acesse o jogo da Tartaruga no [Blockly Games](https://blockly.games/turtle) e complete as etapas até vencer o **nível 10**.

**Passo 2: Registre sua Solução**

Tire um screenshot (captura de tela) da sua solução final (mostrando os blocos que você usou para passar do nível 10). Faça o upload (envio) dessa imagem **dentro da pasta /imagens** que já existe neste repositório.

**Passo 3: Explique sua Estratégia**

Escreva um pequeno texto explicando qual foi a sua linha de raciocínio e a estratégia que você usou para resolver o nível 10.
*(Exemplo: "Criei uma função para desenhar uma estrela, depois usei um loop para repetir essa função 3 vezes girando 120 graus.")*

**Passo 4: Pergunta Desafio**

Olhando para os blocos que você usou para resolver o jogo no nível 10, imagine que o problema mudou. A sua nova missão agora é desenhar um **hexágono regular** (uma figura geométrica de 6 lados iguais) e repetir esse hexágono **4 vezes**, formando um padrão circular (como as pétalas de uma flor).

**Sem precisar montar os blocos** no jogo, responda por escrito:
* **A)** Quantas repetições o seu loop principal (que desenha o hexágono) precisaria ter e qual seria o ângulo (em graus) que a tartaruga deve virar a cada linha desenhada?
* **B)** Depois de desenhar um hexágono completo, qual deve ser o ângulo de giro (em graus) antes de começar a desenhar o próximo hexágono, para que os 4 fiquem distribuídos igualmente em um círculo completo?
* **C)** Explique brevemente qual foi a lógica (ou o cálculo) que você usou para descobrir os ângulos das questões A e B.

---

## ✍️ Suas Respostas

*(Edite este arquivo e escreva suas respostas dos Passos 3 e 4 aqui embaixo. Lembre-se de colocar a imagem do Passo 2 dentro da pasta **/imagens** deste repositório)*

## 2. Evidência Visual (Screenshot)
*Suba o screenshot da sua solução final (onde aparece "Você resolveu este nível!") para a pasta **/imagens** deste repositório.*

## 3. Estratégia Utilizada
*Explique com suas palavras como você resolveu o problema. Qual foi a lógica?*

Nivel 9- Desenhar 3 estrelas pequenas com uma lua minguante no lado inferior esquerdo da tela.

Desenhando as 3 estrelas:


Para que a estrela se feche corretamente utilizamos um loop de 5 vezes para cada linha da estrela, o cursor deve girar 144° em cada vértice. Esse giro de 144 graus resulta em um ângulo interno agudo de 36 graus nas pontas da estrela.

A função acima repete-se 3 vezes para criar o conjunto de 3 estrelas, entre o desenho de uma estrela e outra, utiliza-se os comandos Pen Up e Pen Down  para reiniciar o desenho na nova posição com 150 de distancia de uma verticie em linha reta para outra. Isso garante que as estrelas fiquem distribuídas, em formato de triângulo, sem linhas de conexão.

fazendo a lua lua minguante:

Fora dos dois primeiros loops damos uma distancia de 100 da ultima estrela feita. Fazemos um 3 loop de 360 repetições desenhando linhas com distancia de 1 grau uma da outra da cor branca, quando for executado formara um circulo 100% branco.

Desta vez faremos a mesma coisa porem com a cor preta porem, deve ser dada uma distancia de 20 para cima na diagonal do centro original do primeiro circulo, ao ser executado este segundo círculo apaga parte do primeiro, resultando em uma silhueta de lua minguante.

## 4. Desafio:
**A)** o loop que desenha o hexagono deve possuir 6 repeticoes para cada linha que sera feita, com a distancia de 120 graus entre elas na parte interna, assim colocamos o angulo de 60 graus na parte exterior para se feito o desenho.
  
**B)** para que os 4 fiquem distribuidos como petalas de uma flor em um circulo completo o angulo de curva em relacao a uma reta tem que ser de 90 graus os distribuindo de forma igual.
  
**C)** questao A: um hexagono possui 120 no seu algulo interno, uma reta possui um angulo de 180 se subtrairmos os angulos possuimos 60 graus que e qual deve ser utilizado para poder deixar os 120 graus internos do hexagono.

questao B:o angulo de 90 graus possibilita que os 4 hexagonos desenhados formem um circulo completo em relacao a um ponto central comum. 360/90=4 possui espaco de 90 graus de forma igual para os 4 hexagonos caso o valor for maior ou menos que 90 o circulo nao vai ser completo.


---
