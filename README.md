# 🎮 LABIRINTITE

**Um jogo de labirinto desenvolvido em linguagem C.**

## 📖 Sobre o projeto

Labirintite é um jogo de terminal desenvolvido em C, no qual o jogador precisa encontrar a saída de um labirinto escuro, utilizando comandos do teclado para se movimentar.

O jogador é representado pelo caractere `@` e possui uma visão limitada ao seu redor, tornando o desafio ainda mais interessante.

O objetivo é explorar o mapa, desviar das paredes e encontrar a saída antes de ficar perdido!

## 🎯 Objetivo do jogo

Encontrar a saída do labirinto, representada pelo caractere `X`, sem atravessar as paredes, representadas por `#`.

## 🕹️ Como jogar

Ao iniciar o programa, será apresentada uma tela com as instruções do jogo.

Depois de pressionar ENTER, o jogador poderá escolher a largura e a altura do labirinto.

Durante o jogo, utilize os seguintes comandos:

| Tecla | Ação |
|:---:|---|
| W | Mover para cima |
| A | Mover para a esquerda |
| S | Mover para baixo |
| D | Mover para a direita |
| Q | Sair do jogo |

**Importante:** É necessário pressionar ENTER após cada movimento.

## 🔎 Elementos do jogo

| Símbolo | Significado |
|:---:|---|
| `@` | Jogador |
| `#` | Parede |
| `X` | Saída |
| ` ` | Caminho livre |

O jogador possui um campo de visão limitado, representado por uma área circular ao seu redor.

## 💻 Tecnologias utilizadas

- Linguagem C
- Biblioteca `stdio.h`
- Biblioteca `stdlib.h`
- Alocação dinâmica de memória
- Matrizes bidimensionais
- Estruturas de repetição e decisão
- Manipulação de entrada pelo teclado

## ⚙️ Requisitos

Para executar o jogo, é necessário ter:

- Um sistema operacional Linux.
- GCC (GNU Compiler Collection).
- Terminal de comandos.

## 🚀 Como executar

### 1. Clone o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 2. Entre na pasta do projeto

```bash
cd labirintite
```

### 3. Compile o código

```bash
gcc labirinto.c -o labirinto
```

### 4. Execute o jogo

```bash
./labirinto
```

## 📐 Configuração do labirinto

O jogador pode escolher as dimensões do labirinto no início da partida.

O tamanho mínimo permitido é de 5x5.

Exemplo:

```text
Digite a largura do labirinto: 15
Digite a altura do labirinto: 15
```

## 🧠 Conceitos de programação aplicados

O desenvolvimento deste projeto permite trabalhar conceitos fundamentais da linguagem C, como:

- Alocação dinâmica de memória com `malloc()`.
- Liberação de memória com `free()`.
- Utilização de matrizes dinâmicas.
- Manipulação de caracteres.
- Estruturas condicionais (`if` e `else`).
- Estruturas de repetição (`for` e `while`).
- Criação e utilização de funções.
- Leitura de dados com `scanf()`.

Projeto desenvolvido como prática de programação em linguagem C.

**LABIRINTITE — Encontre a saída antes que o labirinto encontre você!** 🎮
