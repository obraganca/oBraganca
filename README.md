<p align="center">
  <img src="https://raw.githubusercontent.com/oBraganca/oBraganca/main/assets/header.svg" alt="Thayllon Bragança — superfície 3D de uma função objetivo com a trajetória de um Iterated Local Search" width="100%">
</p>

<p align="center">
  <a href="https://obraganca.github.io/curriculum/"><img src="https://img.shields.io/badge/Currículo-b4501c?style=for-the-badge&logo=readme&logoColor=white" alt="Currículo"></a>
  <a href="https://www.linkedin.com/in/thayllonbraganca/"><img src="https://img.shields.io/badge/LinkedIn-1d6b67?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:thayllonbraganca@gmail.com"><img src="https://img.shields.io/badge/E--mail-47433c?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"></a>
  <img src="https://img.shields.io/badge/Aberto_a_oportunidades-1d6b67?style=for-the-badge" alt="Aberto a oportunidades">
</p>

<br>

Transformo problemas de decisão em modelos matemáticos e os resolvo com o método adequado: **programação inteira mista** quando o exato é viável; **heurísticas e metaheurísticas** quando a escala exige.

```cpp
struct Resultado { const char* metodo; double gap_pct; double tempo_s; };

struct Thayllon final {
    // ── formação ─────────────────────────────────────────────────────
    static constexpr auto curso    = "Matemática Computacional @ UFMG";
    static constexpr auto pesquisa = "Otimização combinatória @ Pesquisa Operacional";

    // ── caixa de ferramentas ─────────────────────────────────────────
    enum class Exato      { PLIM, Gurobi, CPLEX };
    enum class Heuristico { ILS, VNS, RVND, MCTS, Lookahead };
    static constexpr std::array linguagens{ "C++", "Python" };

};
```

## 🔥 Em destaque

<p align="center">
  <img src="https://raw.githubusercontent.com/oBraganca/oBraganca/main/assets/opthyrrigated.svg" alt="optHyrrigated — ILS+RVND atinge o ótimo em soja (7,9 s), milho (7,4 s) e algodão (13,6 s) e fica a 0,08% do ótimo na cana-de-açúcar, com 540 dias (158,5 s)" width="100%">
</p>

**optHyrrigated** · C++ — irrigação por pivô central. Construtiva Lookahead, quatro vizinhanças do domínio combinadas via RVND dentro de um ILS, e um vetor de margem hídrica que verifica a viabilidade de cada movimento em O(1).

**Alocação de tarefas com aceitação de pedidos** — ILS com busca local substitute/drop, sequenciamento via RVND e integração com o modelo exato (EILS) em ambiente multiperíodo.

## 📄 Publicações

| | Trabalho | Evento | Ano |
|:-:|:--|:--|:-:|
| 📄 | **Aplicação do ILS-RVND para o Problema de Irrigação utilizando Pivô Central**<br><sub>T. R. B. de Almeida, P. L. A. Munhoz · ótimo em 3 de 4 instâncias, gap de 0,08% na maior, em menos de 3 min</sub> | LVIII SBPO | 2026 |
| 📝 | **ILS e EILS para o problema de alocação de tarefas com aceitação de pedidos em ambiente multiperíodo**<br><sub>T. R. B. de Almeida et al.</sub> | em preparação | 2026 |

## 🧰 Ferramentas

<p>
  <img src="https://img.shields.io/badge/C++-1d6b67?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Python-1d6b67?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Gurobi-b4501c?style=for-the-badge" alt="Gurobi">
  <img src="https://img.shields.io/badge/CPLEX-b4501c?style=for-the-badge&logo=ibm&logoColor=white" alt="CPLEX">
  <img src="https://img.shields.io/badge/NumPy-47433c?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Pandas-47433c?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Jupyter-47433c?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/LaTeX-47433c?style=for-the-badge&logo=latex&logoColor=white" alt="LaTeX">
  <img src="https://img.shields.io/badge/Git-47433c?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Linux-47433c?style=for-the-badge&logo=linux&logoColor=white" alt="Linux">
</p>

## 📈 Atividade

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=oBraganca&hide_border=true&background=121518&ring=55b5ab&fire=e2804b&currStreakNum=ebe5d9&currStreakLabel=e2804b&sideNums=ebe5d9&sideLabels=8c867a&dates=8c867a&stroke=2a3036">
    <img alt="Sequência de contribuições" src="https://streak-stats.demolab.com?user=oBraganca&hide_border=true&background=f5f0e6&ring=1d6b67&fire=b4501c&currStreakNum=1d1b18&currStreakLabel=b4501c&sideNums=1d1b18&sideLabels=7a7366&dates=7a7366&stroke=dcd3c2">
  </picture>
</p>

<p align="center"><sub><i>Ad optimum, per vicinitates.</i></sub></p>
