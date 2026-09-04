# 🎤 CUE-SHEET — Times Agênticos e Loop Engineering

**HackTown 2026 · 04/09 · 14:30 · TDC Stage (Palco 1) · ETE Santa Rita do Sapucaí - MG**
**Slot: 45 min · Deck: 18 slides (HUD 00–17) · Live coding: Bloco 04, com card de transição (HUD 16)**

---

## ⏱ Mapa de tempo (alvo 45′)

| # | Slide / Momento | Alvo | Acum. | Quem |
| :-: | :-- | :-: | :-: | :-- |
| 00 | Capa — título, 2 frases de abertura | 1′ | 1′ | Ambos |
| 01 | Palestrantes — bio rápida de ambos | 2′ | 3′ | Ambos |
| 02 | Agenda — "cinco blocos, uma tese" | 1′ | 4′ | **Dan** |
| 03 | Mercado — 6 números + ponte "capital chega antes da capacidade" | 3′ | 7′ | Dan |
| 04 | Team Topologies — timeline 2001→2026 + Lei de Conway | 3′ | 10′ | **Jean** |
| 05 | SDLC — do waterfall ao runtime agêntico | 2′ | 12′ | Jean |
| 06 | O que é um Agente — workflow vs. agente + ciclo | 3′ | 15′ | **Dan** |
| 07 | Harness Engineering — definição + cadeia da disciplina | 2′ | 17′ | Dan |
| 08 | Arquitetura Harness — Guias/Sensores/Evals | 3′ | 20′ | Dan |
| 09 | O que é Loop Engineering — stop condition | 2′ | 22′ | **Jean** |
| 10 | Interaction Loops — ⭐ coração da talk | 3′ | 25′ | Jean |
| 11–14 | Triggers: Turn / Goal / Time / Proactive (ritmo, ~30″ cada) | 2′30″ | 27′30″ | **Dan** |
| 15 | Quebras & Mitigação — espelho esquerda→direita + ponte pro demo | 2′30″ | 30′ | **Jean** |
| 16 | Card LIVE — "Padrões no papel não bastam. Demo ao vivo." (voz livre) | 0′30″ | 30′30″ | Ambos |
| — | **LIVE CODING — Bloco 04** (trocar de janela **com o card 16 na tela**) | 11′30″ | 42′ | Dan (demo) · Jean (narração) |
| 17 | Encerramento — **mensagem única**: "Desenhe os loops. Governe com harness. Mantenha o humano no loop." + obrigado | 2′ | 44′ | Ambos |

> ⚠️ Budget de segurança: ~30″ holgados no acumulado (44′30″/45′). Timer da HUD conta 45:00 regressivo — conferir em 25′ (estando no 14/Proactive ou antes, vai bem; além disso, encurtar o demo, não a teoria).

> 🔄 **Negrito** na coluna Quem = início de bloco de voz / handoff entre palestrantes. Trocas: 03→04 (Dan→Jean), 05→06 (Jean→Dan), 08→09 (Dan→Jean), 10→11 (Jean→Dan), 14→15 (Dan→Jean).

---

## 🗣️ Transições prontas

**02 → 03 (mercado):** "Antes do 'como', o 'por quê' — seis números do mercado em 2026."

**05 → 06 (SDLC → agente):** "Se agentes são o próximo salto do SDLC, primeiro precisamos concordar no que é um agente."

**08 → 09 (harness → loop):** "O harness veste o modelo. Mas quem respira — repete, verifica, para — é o loop."

**10 → 11 (interaction → triggers):** "Dois jeitos de girar esse par. Começando pelo trigger mais simples…"

**14 → 15 (proactive → quebras):** "Rotinas sempre-on soam bonitas. Agora, o que acontece quando elas dão errado — e o que as segura."

**15 → 16 (card LIVE):** avançar e deixar a frase cair sobre o card: *"Padrões no papel não bastam…"* → trocar de janela/app **com o card 16 na tela** para não mostrar o desktop.

**LIVE → 17 (retorno):** volta o navegador no card (16), avança pro 17. "Se tudo isso parece promissor, deixem-me ser honesto(a) sobre o preço — e sobre o que não se delega."

---

## 🧯 Plano de resgate ( LIVE )

| Problema | Ação |
| :-- | :-- |
| Demo travando/lenta | Narrar o que *estaria* acontecendo usando o slide 15 como mapa (fraquezas ↔ padrões). Reset 1-clique do cenário. |
| Debug demorado | Pedir paciência 1 vez, se >60″ → abortar e narrar fallback determinístico. |
| Rede/café falha | Deck é 100% local (fontes e imagens offline). Demo é o único componente dependente de rede — decidir ali mesmo se roda ou é narrado. |
| Precisam pausar | `B` = tela de break com cronômetro; `B` de novo para voltar. |
| Timer errado | `R` reinicia os 45:00. `T` pausa/retoma. |

---

## ⌨️ Atalhos rápidos

| Tecla | Ação |
| :-: | :-- |
| `→` `Espaço` `PgDn` / `←` `PgUp` | Avançar / voltar |
| Clique (qualquer área) | Avança (exceto seleção de texto) |
| `T` / `R` | Timer play-pause / reset (45:00) |
| `B` | Tela de break |
| `S` / `G` | Painéis Q&A: Fontes (links) / Glossário — fora da navegação |
| `Esc` | Fecha painéis Q&A (volta exatamente ao slide atual) |
| `D` | Tema claro/escuro (default: preferência do SO) |
| `F` | Fullscreen |
| `Home` / `End` | Primeiro / último slide |

**Kit de palco:** laptop com `presentation.html` aberto no Chromium/Chrome, **wi-fi desligado** para testar ao menos uma vez antes, fullscreen `F`, timer iniciado com `T` logo antes do primeiro slide.

**Q&A pós-slides:** plateia pediu fonte ou o significado de um termo? `S` abre a lista completa de referências citadas (com links; espelha o `docs/REFERENCIAS.md`) e `G` abre o glossário de 18 termos. Os painéis ficam fora da navegação — `Esc` devolve ao slide exato onde a talk estava, sem mover nada.

---

## 📝 Notas de fala pontuais

- **Slide 03 (ponte do mercado):** roteiro oral completo — "O capital chega antes da capacidade. Muito dinheiro sendo investido e ainda assim talentos escassos. Se o gargalo é gente, a alavanca não é contratar, é redesenhar o time para que humanos e agentes amplifiquem uns aos outros." No slide ficou só a síntese ("O capital chega antes da capacidade. Se o gargalo é gente, a alavanca não é contratar — é redesenhar o time.").

- **Slide 15, card HITL/HOTL:** HITL = humano *dentro* do loop (gate de aprovação, ação sensível); HOTL = humano *em cima* do loop (supervisiona, intervém quando necessário — menos intrusivo). Um exemplo basta pra plateia.
- **Slide 16 (fechamento):** recitar as três batidas devagar, uma por linha — "Desenhe os **loops**" / "Governe com **harness**" / "Mantenha o **humano no loop**" — e a seguir a punchline: *automatize o esforço, não a responsabilidade*. Encerrar olhando para a plateia, não para o slide. O detalhe rico (custo, latência, complexidade, julgamento) fica para a conversa de corredor.
- **Ritmo dos triggers (11–14):** ~30″ cada. Se a bagagem de tempo estiver boa, gastar mais no **Goal-based** (evaluator = conceito que costura com harness/evals).
