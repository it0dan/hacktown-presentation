# 🎤 CUE-SHEET — Times Agênticos e Loop Engineering

**HackTown 2026 · 04/09 · 14:30 · TDC Stage (Palco 1) · ETE Santa Rita do Sapucaí - MG**
**Slot: 45 min · Deck: 17 slides (HUD 00–16) · Live coding: Bloco 04, sem slide dedicado**

---

## ⏱ Mapa de tempo (alvo 45′)

| # | Slide / Momento | Alvo | Acum. | Quem |
| :-: | :-- | :-: | :-: | :-- |
| 00 | Capa — título, 2 frases de abertura | 1′ | 1′ | ________ |
| 01 | Palestrantes — bio rápida de ambos | 2′ | 3′ | ________ |
| 02 | Agenda — "cinco blocos, uma tese" | 1′ | 4′ | ________ |
| 03 | Mercado — 6 números + ponte "capital chega antes da capacidade" | 3′ | 7′ | ________ |
| 04 | Team Topologies — timeline 2001→2026 + Lei de Conway | 3′ | 10′ | ________ |
| 05 | SDLC — do waterfall ao runtime agêntico | 2′ | 12′ | ________ |
| 06 | O que é um Agente — workflow vs. agente + ciclo | 3′ | 15′ | ________ |
| 07 | Harness Engineering — definição + cadeia da disciplina | 2′ | 17′ | ________ |
| 08 | Arquitetura Harness — Guias/Sensores/Evals | 3′ | 20′ | ________ |
| 09 | O que é Loop Engineering — stop condition | 2′ | 22′ | ________ |
| 10 | Interaction Loops — ⭐ coração da talk | 3′ | 25′ | ________ |
| 11–14 | Triggers: Turn / Goal / Time / Proactive (ritmo, ~30″ cada) | 2′30″ | 27′30″ | ________ |
| 15 | Quebras & Mitigação — espelho esquerda→direita + ponte pro demo | 2′30″ | 30′ | ________ |
| — | **LIVE CODING — Bloco 04** (entrar **imediatamente** após 15) | 12′ | 42′ | ________ |
| 16 | Encerramento — **mensagem única**: "Desenhe os loops. Governe com harness. Mantenha o humano no loop." + obrigado | 2′ | 44′ | ________ |

> ⚠️ Budget de segurança: ~30″ holgados no acumulado (44′30″/45′). Timer da HUD conta 45:00 regressivo — conferir em 25′ (estando no 14/Proactive ou antes, vai bem; além disso, encurtar o demo, não a teoria).

---

## 🗣️ Transições prontas

**02 → 03 (mercado):** "Antes do 'como', o 'por quê' — seis números do mercado em 2026."

**05 → 06 (SDLC → agente):** "Se agentes são o próximo salto do SDLC, primeiro precisamos concordar no que é um agente."

**08 → 09 (harness → loop):** "O harness veste o modelo. Mas quem respira — repete, verifica, para — é o loop."

**10 → 11 (interaction → triggers):** "Dois jeitos de girar esse par. Começando pelo trigger mais simples…"

**14 → 15 (proactive → quebras):** "Rotinas sempre-on soam bonitas. Agora, o que acontece quando elas dão errado — e o que as segura."

**15 → LIVE (frase de entrada):** *"Padrões no papel não bastam. Vamos ver isso rodando de verdade — uma squad agêntica respondendo a uma demanda real, agora mesmo."* → trocar de janela/app **antes de virar o slide** (ou colapsar o navegador) para não mostrar o desktop.

**LIVE → 16 (retorno):** volta o navegador no HUD, avança pro 16. "Se tudo isso parece promissor, deixem-me ser honesto(a) sobre o preço — e sobre o que não se delega."

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
| `D` | Tema claro/escuro (default: preferência do SO) |
| `F` | Fullscreen |
| `Home` / `End` | Primeiro / último slide |

**Kit de palco:** laptop com `presentation.html` aberto no Chromium/Chrome, **wi-fi desligado** para testar ao menos uma vez antes, fullscreen `F`, timer iniciado com `T` logo antes do primeiro slide.

---

## 📝 Notas de fala pontuais

- **Slide 15, card HITL/HOTL:** HITL = humano *dentro* do loop (gate de aprovação, ação sensível); HOTL = humano *em cima* do loop (supervisiona, intervém quando necessário — menos intrusivo). Um exemplo basta pra plateia.
- **Slide 16 (fechamento):** recitar as três batidas devagar, uma por linha — "Desenhe os **loops**" / "Governe com **harness**" / "Mantenha o **humano no loop**" — e a seguir a punchline: *automatize o esforço, não a responsabilidade*. Encerrar olhando para a plateia, não para o slide. O detalhe rico (custo, latência, complexidade, julgamento) fica para a conversa de corredor.
- **Ritmo dos triggers (11–14):** ~30″ cada. Se a bagagem de tempo estiver boa, gastar mais no **Goal-based** (evaluator = conceito que costura com harness/evals).
