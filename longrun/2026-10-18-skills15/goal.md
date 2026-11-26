# Goal — skills15 (18/10/2026)

Pedido do Nei: "quero um repo com todas as skill 15 q ele fala, cria uma lanpage todas elas e como funciona com exemplo e referencia ela, faca um explicavideo detalhando todas elas, e um r7ex citando elas, e publica no lives4 e manda para o v3 publica no portal e coloca no telegram ARCKHÉ.agentes" — fonte https://www.youtube.com/watch?v=KmL5osg_qI8 (Fabian Markl, 17/10/2026).

## Pronto quando (nível 3)

1. Repo: `gh repo view linnoff88-dev/skills15 --json visibility` → PUBLIC; `ls skills/ | wc -l` → 15 fichas; `bash tests/run.sh` → todos OK (15 fichas, links, nº de estrelas = catalogo.json).
2. Guia: `curl -s -o /dev/null -w '%{http_code}' https://linnoff88-dev.github.io/arckhe-/guia/` (e `/en/`, `/es/`) → 200; Playwright: 0 imagens quebradas, `scrollWidth-innerWidth ≤ 0` de 390 a 1920 px.
3. Explicavideo 16:9 (perfil viral, avatar Nei pelo estúdio): MP4 com as 15 citadas; `hyperframes check` rc=0; frame 0 = capa com ganho; qa_viral sem reprovaçêo (ou reprovaçêo dita ao Nei).
4. r7ex 9:16 citando as 15 (gancho com número 15), avatar no quadro 0.
5. YouTube lives4: 2 IDs (16:9 com thumb; 9:16 sem thumb). NêO entra na fila lives7.
6. Bot v3: 2 arquivos (sem link); ARCKHÉytbot: links + canal.
7. Portal: commit no origin (NeiMaldaner/portal) com card do projeto (`skills15 — …` ≤ 90) e os 2 vídeos; `npm test` passou antes.
8. Telegram ARCKHÉ.AGENTES: tópico novo + linha no MENU; link da mensagem.

## Limites
- Nenhuma API paga; avatar só pelo estúdio HeyGen; Codex pela assinatura.
- Nêo espelhar repos grandes; licença: karpathy sem licença (só link), billion-context NOASSERTION (só link).
- Telethon fora de 23:20–23:55.
