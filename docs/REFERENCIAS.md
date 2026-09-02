# 📚 Referências & Fontes de Pesquisa — Times Agênticos & Loop Engineering

Este documento compila a bibliografia, pesquisas de mercado, frameworks e artigos de referência utilizados na palestra **"Times Agênticos e Loop Engineering"** no **HackTown 2026**.

---

## 📊 1. Dados & Pesquisas de Mercado

- **Gartner (2026):** *Global IT & AI Spending Forecast* — projeção de US$ 2,59 tri de investimento global em IA em 2026 (alta de 47% em relação a 2025).
- **Brasscom / Valor Econômico (2026):** *Relatório de Talentos em Tecnologia no Brasil* — déficit acumulado de 530 mil profissionais de TI até 2026.
- **IDC (2026):** *Latin America Artificial Intelligence Ecosystem Report* — mercado de IA no Brasil atingindo US$ 4,2 bilhões (41,7% da América Latina).
- **S&P Global (2026):** *Enterprise AI Adoption Survey* — 42% das empresas abandonaram a maioria das iniciativas de IA em 2025 por falta de governança e ROI.
- **MIT NANDA (2025):** *GenAI ROI & Pilot Failure Rate Study* — 95% dos pilotos de GenAI corporativos não entregam ROI mensurável sem um Harness adequado.
- **Korn Ferry:** *Global Talent Crunch Study* — projeção de 85 milhões de vagas de tecnologia sem profissionais qualificados no mundo até 2030.

---

## 🏗️ 2. Arquitetura de IA & Agentes

- **Anthropic (Dez/2024):** [*Building Effective Agents*](https://www.anthropic.com/research/building-effective-agents) — Guia de referência sobre workflows, agentes, loops de pensamento e padrões de orquestração.
- **Thoughtworks / Martin Fowler:** [*Harness Engineering*](https://www.thoughtworks.com/) — Birgitta Böckeler sobre como envolver LLMs com Guias, Sensores e Evals.
- **Google Cloud AI Whitepaper (2024):** [*Agents: Reasoning and Action in LLMs*](https://cloud.google.com/) — Fundamentos de loops de raciocínio (ReAct, Percebe-Raciocina-Age-Observa).
- **Model Context Protocol (MCP):** Especificação para integração padronizada de ferramentas e contextos a modelos de IA.

---

## 🔁 3. Loop Engineering (Bloco 03)

- **Claude/Anthropic (30/jun/2026):** [*Loop engineering: getting started with loops*](https://claude.com/blog/getting-started-with-loops) — Delba de Oliveira & Michael Segner. Define loops como "agentes repetindo ciclos de trabalho até uma condição de parada". Tipos por trigger/stop: *Turn-based*, *Goal-based* (`/goal`), *Time-based* (`/loop`, `/schedule`), *Proactive*. Turn caps, evaluator model, dynamic workflows.
- **Claude/Anthropic (18/jun/2026):** [*Steering Claude Code: CLAUDE.md, skills, hooks, rules, subagents*](https://claude.com/blog/steering-claude-code-skills-hooks-rules-subagents-and-more) — Michael Segner. Matriz de mecanismos de controle (autoridade vs. custo de contexto); guardrails determinísticos via hooks/permissions/managed settings; skills e hooks como blocos de construção de agent loops.
- **LangChain (16/jun/2026):** [*The Art of Loop Engineering*](https://www.langchain.com/blog/the-art-of-loop-engineering) — Sydney Runkle. A "pilha" de 4 loops aninhados: *Agent*, *Verification*, *Event-driven*, *Hill climbing*. Loopcraft (swyx), traces, LLM-as-judge, human-in-the-loop.
- **swyx / Latent Space:** [*loopcraft: the art of stacking loops*](https://www.latent.space/) — conceito de empilhar e estender loops para construir agentes mais eficazes (citado pela LangChain).
- **Anthropic (26/nov/2025):** [*Effective harnesses for long-running agents*](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents) — Justin Young. Failure modes: one-shotting, premature completion, marcar features sem testar. Solução: initializer + coding agent, feature list JSON, progress file, git commits, init.sh.
- **Anthropic (24/mar/2026):** [*Harness design for long-running application development*](https://www.anthropic.com/engineering/harness-design-for-long-running-application-development) — Prithvi Rajasekaran. Failure modes: loss of coherence, context anxiety, self-evaluation bias. Solução generator-evaluator (inspirada em GANs), planner-generator-evaluator, context resets vs. compaction.
- **Anthropic (29/set/2025):** [*Effective context engineering for AI agents*](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents) — Context rot, attention budget, minimal viable context, compaction, structured note-taking, sub-agents.
- **Anthropic (08/abr/2026):** [*Scaling Managed Agents: Decoupling the brain from the hands*](https://www.anthropic.com/engineering/managed-agents) — Session/harness/sandbox, harness assumptions que ficam stale, context anxiety, security boundary, wake/getSession para recuperação.
- **Claude/Anthropic (29/set/2025):** [*Building agents with the Claude Agent SDK*](https://claude.com/blog/building-agents-with-the-claude-agent-sdk) — Loop gather → action → verify → repeat; verificação (rules/lint, visual, LLM-as-judge); compaction.

---

## 👥 4. Design de Organização & Metodologias

- **Skelton, M. & Pais, M. (2019):** *Team Topologies: Organizing Business and Technology Teams for Fast Flow*. IT Revolution Press.
  - 4 Tipos de Time: *Stream-aligned*, *Enabling*, *Complicated-subsystem*, *Platform*.
  - 3 Modos de Interação: *Collaboration*, *X-as-a-Service*, *Facilitating*.
- **Melvin Conway (1967):** *Lei de Conway* ("Organizações projetam sistemas que refletem suas estruturas de comunicação") e o *Inverse Conway Maneuver*.
- **Manifesto Ágil (2001):** *Agile Software Development Manifesto*.

---

## 🎨 5. Identidade Visual da Apresentação

- **Brand:** Sensedia (Light Theme por padrão com opções de Dark Theme Purple Rain).
- **Tipografia:** `Montserrat` (Títulos e Corpo) e `Roboto Mono` (Tags, Timers, HUD e Código).
- **Cores Oficiais:**
  - Light: `#8241B0` (Sensedia Purple), `#5C2E7D` (Primary Accent), `#EA5B0C` (Sensedia Orange).
  - Dark: `#2B163B` (Dark Purple), `#DAA9FC` (Bright Highlight), `#FF7D4A` (High Orange).
