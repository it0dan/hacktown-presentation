# 🚀 Times Agênticos e Loop Engineering — HackTown 2026

> **Da squad ágil ao loop agêntico — como estruturar times quando parte da equipe também são agentes.**

Repositório oficial de apoio e apresentação do **HackTown 2026** (Santa Rita do Sapucaí - MG).

---

## 📌 Visão Geral

À medida que os agentes de Inteligência Artificial evoluem de assistentes de código para membros ativos na execução de tarefas complexas, a estrutura tradicional das equipes de tecnologia precisa ser repensada. 

Esta apresentação aborda a transição das **Squads Ágeis** e **Team Topologies** para as **Squads Agênticas**, introduzindo os conceitos de **Harness Engineering** e **Loop Engineering** para garantir previsibilidade, governança e alto desempenho na era da IA autônoma.

---

## 🗣️ Palestrantes

| Palestrante | Função & Bio | Tags / Especialidade |
| :--- | :--- | :--- |
| **Dan (Danilo Amaral)** | **Solutions Architect @ Sensedia**<br/>À frente da direção de IA do time de Soluções. AI Champion e membro do comitê técnico do TDC — constrói pontes entre arquitetura agêntica e prática de engenharia. | `Agentic Architecture` `Harness Engineering` |
| **Jean** | **Liderança Dev @ Sensedia**<br/>Lidera pessoas e times de desenvolvimento na Sensedia. Traz a visão de gestão e liderança para dentro da conversa sobre agentes — como esses times mudam quando parte da equipe também executa. | `Team Topologies` `Liderança de Squads` |

---

## 🗺️ Agenda & Status dos Blocos da Apresentação

### 1. Contexto Geral & Histórico `[CONCLUÍDO]`
- **Mercado de IA em 2026:** Investimentos globais, déficit de talentos de tecnologia e o paradoxo do ROI em GenAI (95% dos pilotos travados em Proof of Concept).
- **Evolução do Design de Times:** Do Manifesto Ágil (2001) e Spotify Model (2012) ao **Team Topologies** (2019) e **Topologies para Agentes** (2026).
- **Ciclo de Vida do Software (SDLC):** De Waterfall e Agile/DevOps até **Platform Engineering** e a integração de runtime agêntico no ciclo produtivo.

### 2. A Era Agêntica & Arquitetura Harness `[CONCLUÍDO]`
- **O que é um Agente de IA:** Diferença entre Workflow determinístico vs. Agentes autônomos.
- **O Loop Fundamental do Agente:** `Percebe ➔ Raciocina ➔ Age ➔ Observa` (repetindo até atingir o objetivo).
- **Fórmula Central:** $$\text{Agente} = \text{Modelo} + \text{Harness}$$
- **Componentes do Harness:**
  - **Guias (Feedforward):** Prompts, especificações, contratos de API, schemas e contexto em tempo real.
  - **Sensores (Feedback):** Traces de observabilidade, guardrails determinísticos, LLM-as-Judge e HITL (Human-in-the-Loop).
  - **Evals:** Validação contínua da assertividade do agente transformando falhas em novos contextos.

---

### ⏳ Blocos Pendentes (Em Desenvolvimento)

- ⏳ **3. Loop Engineering:** Tipos de loop (*Inner Loop*, *Outer Loop*, *Multi-Agent Loop*), autonomia controlada, stopping conditions, circuit breakers e auto-recuperação de contexto.
- ⏳ **4. Live Coding:** Demonstração prática com Squad Agêntica (*Dev Agent*, *Tester Agent* e *Human-in-the-Loop*) reagindo a mudanças regulatórias em tempo real.
- ⏳ **5. Considerações & Futuro:** Reestruturação de times (*Stream-aligned*, *Platform*), governança, redução de carga cognitiva e a transição para *Graph Engineering* (A2A).

---

## ⌨️ Atalhos da Apresentação (`presentation.html`)

Ao abrir [`presentation.html`](file:///home/daniloamaral/Desktop/hacktown-2026/hacktown-presentation/presentation.html) no navegador:

| Tecla / Atalho | Ação |
| :---: | :--- |
| `➡️` / `Espaço` / `PgDn` | Avança para o próximo slide |
| `⬅️` / `PgUp` | Volta para o slide anterior |
| `Home` / `End` | Vai para o primeiro / último slide |
| `T` | Inicia / Pausa o Cronômetro HUD (45 min) |
| `R` | Reinicia o Cronômetro |
| `B` | Tela de Pausa / Break |
| `D` | Alterna entre Modo Escuro 🌙 e Claro ☀️ |
| `F` | Alterna modo Tela Cheia (*Fullscreen*) |

---

## 📂 Estrutura do Repositório

```text
.
├── presentation.html         # Apresentação oficial em slides HTML/CSS/JS (Blocos 1 e 2)
├── README.md                 # Guia do projeto, agenda e status dos blocos pendentes
├── assets/
│   └── speakers/             # Fotos e especificações visuais dos palestrantes
│       ├── dan.jpg
│       ├── jean.jpg
│       └── README.md
└── docs/
    └── REFERENCIAS.md        # Artigos, pesquisas e fontes bibliográficas da talk
```

---

## 🚀 Como Executar

1. Clone ou baixe este repositório.
2. Abra [`presentation.html`](file:///home/daniloamaral/Desktop/hacktown-2026/hacktown-presentation/presentation.html) diretamente em qualquer navegador moderno.

---

## 📄 Licença

Este projeto é disponibilizado sob os termos da licença constante no arquivo [`LICENSE`](file:///home/daniloamaral/Desktop/hacktown-2026/hacktown-presentation/LICENSE).
