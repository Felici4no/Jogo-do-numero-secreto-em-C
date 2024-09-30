# Jogo de Adivinhação

Este é um jogo de adivinhação em C, no qual o jogador deve adivinhar um número secreto gerado aleatoriamente entre 0 e 100. O jogador escolhe o nível de dificuldade, que determina a quantidade de tentativas, e ao longo do jogo, os pontos vão sendo deduzidos conforme a distância entre o chute e o número secreto.

## Descrição

- O jogador escolhe entre três níveis de dificuldade: fácil, médio e difícil.
- O programa gera um número secreto aleatório.
- A cada tentativa, o jogador deve chutar um número e o programa informa se o chute foi maior ou menor que o número secreto.
- Se o jogador acertar, o programa exibe uma mensagem de vitória e a pontuação final.
- Caso o jogador não acerte até o final das tentativas, uma mensagem de derrota é exibida.

## Níveis de Dificuldade

1. **Fácil**: 20 tentativas.
2. **Médio**: 15 tentativas.
3. **Difícil**: 6 tentativas.

## Regras

- O jogador não pode chutar números negativos.
- A pontuação começa em 1000 e é reduzida conforme a diferença entre o chute e o número secreto. Quanto mais próximo do número secreto, menos pontos são perdidos.
- Ao acertar o número, o jogo termina e a pontuação é exibida.
- Se o jogador não acertar após todas as tentativas, o jogo exibe uma mensagem de derrota.

## Exemplo de uso

Entrada do usuário:

```
Qual o nivel de dificuldade?
(1) Facil (2) Medio (3) Dificil

Escolha: 1
-> Tentativa 1 de 20
Chute um numero: 50
Seu chute foi maior do que o numero secreto!

-> Tentativa 2 de 20
Chute um numero: 25
Seu chute foi menor do que o numero secreto!
```

## Como executar o programa

1. Compile o programa usando um compilador de C, como o GCC:
   ```bash
   gcc -o jogo_adivinhacao jogo_adivinhacao.c
   ```

2. Execute o arquivo gerado:
   ```bash
   ./jogo_adivinhacao
   ```

3. Escolha o nível de dificuldade e comece a jogar.

## Requisitos

- Um compilador C (GCC, Clang, etc.).
- Sistema operacional compatível com a execução de programas C.

## Autor

Felici4no
