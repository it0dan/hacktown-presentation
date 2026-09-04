# 🚀 Times Agênticos e Loop Engineering — HackTown 2026

> **Da squad ágil ao loop agêntico — como estruturar times quando parte da equipe também são agentes.**

Repositório oficial de apoio e apresentação do **TDC Stage no HackTown 2026** (04/09/2026 · 14:30 · Palco 1 · ETE - Santa Rita do Sapucaí - MG).

---

## 📌 Visão Geral

À medida que os agentes de Inteligência Artificial evoluem de assistentes de código para membros ativos na execução de tarefas complexas, a estrutura tradicional das equipes de tecnologia precisa ser repensada. 

Esta apresentação aborda a transição das **Squads Ágeis** e **Team Topologies** para as **Squads Agênticas**, introduzindo os conceitos de **Harness Engineering** e **Loop Engineering** para garantir previsibilidade, governança e alto desempenho na era da IA autônoma.

**Tese central:** quando agentes entram no ciclo de vida de desenvolvimento, o diferencial não é velocidade — é **redesenhar os loops de interação humano↔agente**; e fazer isso de forma confiável exige harness. Times agênticos são essa **arquitetura de loops**, não uma cultura.

---

## 🗣️ Palestrantes

| Palestrante | Função & Bio | Tags / Especialidade |
| :--- | :--- | :--- |
| **Dan (Danilo Amaral)** | **Arquiteto de Soluções @ Sensedia**<br/>Pai, da música, dos animais. Arquiteto de Soluções especialista em integrações e estratégia de inteligência artificial, auxilia clientes a alcançar o resultado desejado habilitando ecossistemas digitais e potencializando negócios através de práticas de integração modernas. Palestrante e criador de conteúdo nas horas vagas, integra o comitê técnico do TDC. | `Agentic Architecture` `Harness Engineering` |
| **Jean** | **Líder de Times @ Sensedia**<br/>Profissional de tecnologia e desenvolvedor há 10 anos, com 5 anos de experiência em liderança de equipes de tecnologia, arquitetura, integração e inteligência artificial. Atua com foco em cultura, agilidade, formação de líderes técnicos e mentoria para desenvolvimento e realocação profissional. | `Squad Leadership` `Product Engineering` |

---

## 🗺️ Agenda & Status dos Blocos da Apresentação

### 1. Contexto Geral & Histórico `[CONCLUÍDO]`
- **Mercado de IA em 2026:** Investimentos globais, déficit de talentos de tecnologia e o paradoxo do ROI em GenAI (95% dos pilotos travados em Proof of Concept).
- **Evolução do Design de Times:** Do Manifesto Ágil (2001) e Spotify Model (2012) ao **Team Topologies** (2019) e **Topologies para Agentes** (2026).
- **Ciclo de Vida do Software (SDLC):** De Waterfall e Agile/DevOps até **Platform Engineering** e a integração de runtime agêntico no ciclo produtivo.

### 2. A Era Agêntica & Arquitetura Harness `[CONCLUÍDO]`
- **O que é um Agente de IA:** Diferença entre Workflow determinístico vs. Agentes autônomos.
- **O Loop Fundamental do Agente:** `Percebe ➔ Raciocina ➔ Age ➔ Observa` (repetindo até atingir o objetivo).
- **Fórmula Central:** `Agente = Modelo + Harness`
- **Componentes do Harness:**
  - **Guias (Feedforward):** Prompts, especificações, contratos de API, schemas e contexto em tempo real.
  - **Sensores (Feedback):** Traces de observabilidade, guardrails determinísticos, LLM-as-Judge e HITL (Human-in-the-Loop).
  - **Evals:** Validação contínua da assertividade do agente transformando falhas em novos contextos.

---

### 3. Loop Engineering `[CONCLUÍDO]`
- **O que é Loop Engineering:** Loops como agentes repetindo ciclos até uma condição de parada; por que projetar o loop (não só o harness) é essencial.
- **Interaction Loops:** o ponto de virada — o loop de interação humano ↔ agente (o coração da talk).
- **Tipos de Loop por Trigger:** *Turn-based*, *Goal-based*, *Time-based*, *Proactive* (Claude).
- **Quebras & Mitigação (slide unificado):** à esquerda, onde o loop quebra — *Infinite/Doom loop*, *Goal drift*, *Context rot*; à direita, o que segura — separar quem faz de quem julga, guardrails determinísticos e HITL/HOTL. Ponte direta para o live coding.

### 4. Live Coding — o Squad como prova viva da tese `[CONCLUÍDO — card de transição (HUD 16) + demo]`
- **Card de transição (HUD 16):** mensagem hero única — "Padrões no papel não bastam. Demo ao vivo." — com as garantias de palco em microtexto (reset 1-clique, fallback determinístico, observabilidade). Do card sai-se direto para o editor.
- **Ao vivo:** Squad Agêntica de 6 especialistas (SDD Refinement, Architect, Backend, Frontend, QA e SRE) operando sobre a **Astronomy Shop (otel-demo)** — pilha de 4 loops (agent, verification, event-driven, hill-climbing) coordenados por um grafo de estados.
- **Falado durante a demo (sem slide):** momento HITL (aprovar/rejeitar com feedback) e garantias de palco (reset 1-clique, fallback determinístico, observabilidade ao vivo).

### 5. Encerramento `[CONCLUÍDO — mensagem única]`
- **Uma mensagem para levar:** Desenhe os *loops*. Governe com *harness*. Mantenha o *humano no loop*.
- **Punchline:** automatize o esforço, não a responsabilidade.

---

## ⌨️ Atalhos da Apresentação (`presentation.html`)

Ao abrir [`presentation.html`](./presentation.html) no navegador:

| Tecla / Atalho | Ação |
| :---: | :--- |
| `Clique` | Avança para o próximo slide |
| `➡️` / `Espaço` / `PgDn` / `⬇️` | Avança para o próximo slide |
| `⬅️` / `PgUp` / `⬆️` | Volta para o slide anterior |
| `Home` / `End` | Vai para o primeiro / último slide |
| `T` | Inicia / Pausa o Cronômetro HUD (45 min) |
| `R` | Reinicia o Cronômetro |
| `B` | Tela de Pausa / Break |
| `S` | Tela de Fontes & Referências (painel Q&A — links para as fontes citadas) |
| `G` | Tela de Glossário (painel Q&A — 18 termos da talk) |
| `Esc` | Fecha os painéis Q&A (`S`/`G`) |
| `D` | Alterna entre Modo Escuro 🌙 e Claro ☀️ |
| `F` | Alterna modo Tela Cheia (*Fullscreen*) |

---

## 📂 Estrutura do Repositório

```text
.
├── presentation.html         # Apresentação oficial em slides HTML/CSS/JS (18 slides, Blocos 1 a 5)
├── README.md                 # Guia do projeto, agenda dos blocos e atalhos
├── assets/
│   ├── fonts/                # Fontes locais (offline-proof): Montserrat e Roboto Mono (variáveis)
│   └── speakers/             # Fotos e especificações visuais dos palestrantes
│       ├── dan.jpg
│       ├── jean.jpg
│       └── README.md
└── docs/
    ├── CUE-SHEET.md          # Mapa de palco: ordem, tempos, transições e resgates
    └── REFERENCIAS.md        # Artigos, pesquisas e fontes bibliográficas da talk
```

---

## 🚀 Como Executar

1. Clone ou baixe este repositório.
2. Abra [`presentation.html`](./presentation.html) diretamente em qualquer navegador moderno.

---

## 📄 Licença

Este projeto é disponibilizado sob os termos da licença constante no arquivo [`LICENSE`](./LICENSE).
