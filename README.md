# EV+ Detector App

App simples para analisar prints de jogos de futebol e detectar EV+ (Expected Value positivo) usando seus critérios.

---

## Funcionalidades

- Recebe prints do jogo (placar, minuto, estatísticas).  
- Usa OCR (`pytesseract`) para ler os dados do print.  
- Calcula EV+ baseado nos critérios:
  - Gol(es) no HT ≥ 1
  - Taxa EV ≥ 70%
  - Probabilidade de ≥1 gol no 2º tempo ≥ 80%
- Mostra resultado direto na tela: ⚡ EV+ detectado ou ❌ Não atende.

---

## Estrutura do repositório
