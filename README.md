[README.md](https://github.com/user-attachments/files/24952249/README.md)
# Aether Quest: Terminal-Based RPG

![C](https://img.shields.io/badge/Language-C-blue.svg)
![Status](https://img.shields.io/badge/Status-Completed-green.svg)
![Academic](https://img.shields.io/badge/Project-Academic-orange.svg)

**Aether Quest** é um jogo de RPG (Role-Playing Game) desenvolvido inteiramente em linguagem **C** para execução via terminal. Este projeto foi concebido como parte integrante da avaliação da disciplina de **Algoritmos e Programação Estruturada** durante o primeiro período do curso de **Engenharia de Software**.

O objetivo principal do desenvolvimento foi aplicar conceitos fundamentais de programação estruturada, manipulação de estruturas de dados (`structs`), controle de fluxo, lógica condicional e geração de números aleatórios para criar uma experiência de jogo interativa e dinâmica.

---

## 🎮 Funcionalidades Principais

| Funcionalidade | Descrição |
| :--- | :--- |
| **Sistema de Batalha** | Combate por turnos com mecânicas de ataque, defesa e uso de itens especiais. |
| **Gestão de Inventário** | Coleta de itens únicos ao derrotar inimigos, com descrições detalhadas e efeitos variados. |
| **Dificuldade Dinâmica** | Três níveis de dificuldade (Fácil, Normal, Difícil) que escalam o dano dos inimigos. |
| **Inimigos Únicos** | Encontros com criaturas mitológicas como Dragões, Fênix e Hidras, cada um com comportamentos especiais. |
| **Narrativa Imersiva** | Introdução em ASCII Art e ambientação textual que guia o jogador pelo mundo de Aether. |

---

## 🛠️ Tecnologias e Conceitos Aplicados

O projeto foi construído utilizando os seguintes pilares da Engenharia de Software inicial:

*   **Estruturas de Dados:** Uso de `typedef struct` para modelagem de personagens (Jogador e Inimigos) e itens.
*   **Modularização:** Organização do código em funções específicas para facilitar a manutenção e legibilidade.
*   **Lógica de Jogo:** Implementação de algoritmos de embaralhamento (*Shuffle*) para garantir que cada jornada seja única.
*   **Interatividade:** Manipulação de entrada e saída padrão (`stdio.h`) com tratamento de erros para escolhas do usuário.
*   **Portabilidade:** Macros para limpeza de tela compatíveis com sistemas **Windows** e **Unix/Linux**.

---

## 🚀 Como Executar

Para rodar o jogo localmente, você precisará de um compilador C (como o GCC).

1.  **Clonar o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/aether-quest-rpg.git
    ```
2.  **Compilar o código:**
    ```bash
    gcc projeto_terminal_based_RPG.c -o aether_quest
    ```
3.  **Executar o jogo:**
    ```bash
    ./aether_quest
    ```
    *(Nota: Em sistemas Windows, pode ser necessário ajustar a codificação do terminal para UTF-8, o que já é tratado internamente pelo código via `SetConsoleOutputCP(65001)`).*

---

## 📚 Contexto Acadêmico

Este repositório documenta minha evolução como desenvolvedor no início da graduação. O código reflete o aprendizado de **Programação Estruturada**, focando em:
*   Boas práticas de nomenclatura de variáveis.
*   Comentários explicativos para lógica complexa.
*   Interface de usuário baseada em texto (TUI) intuitiva.

> "A simplicidade é o último grau de sofisticação." — Leonardo da Vinci (Filosofia aplicada ao desenvolvimento deste projeto).

---

**Desenvolvido por:** Gabriel Sá Teles
**Instituição:** UniGoiás
**Curso:** Engenharia de Software - Feito no 1º Período
