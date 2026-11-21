# skills15 â€” as 15 skills para o Claude que valem a pena

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


[![skills15](guia/assets/banner.jpg)](https://inematds.github.io/skills15/guia/)

**ðŸ‡§ðŸ‡· [PortuguÃªs](README.md) Â· ðŸ‡ºðŸ‡¸ [English](README.en.md) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](README.es.md)**

## O que Ã©

Existem mais de um milhÃ£o de skills para agentes de IA, e a maioria nÃ£o serve para nada. Este repositÃ³rio reÃºne as **15 que valem a pena** para quem usa o Claude Code (e outros agentes): o problema que cada uma resolve, como funciona por dentro, o comando oficial de instalaÃ§Ã£o, um exemplo de pedido e o link para o projeto original. Serve para quem quer escolher **uma** skill para a dor de hoje, sem instalar tudo de uma vez.

## ðŸ“– Guia de uso

Landing + guia com as 15, exemplos e vÃ­deo: **https://inematds.github.io/skills15/guia/**

## As 15 (da 15Âª para a 1Âª)

<!-- tabela -->
| # | Skill | Para quÃª | â˜… 18/10 | Problema que resolve |
|---|---|---|---|---|
| 15 | [NotebookLM](skills/15-notebooklm-py.md) | economia de tokens | 19,8 mil | Quando vocÃª joga muitos PDFs no Claude, ele lÃª tudo palavra por palavra e o seu limite de uso acaba rÃ¡pido. |
| 14 | [I Have ADHD](skills/14-i-have-adhd.md) | respostas | 57,7 mil | O Claude enrola: escreve trÃªs parÃ¡grafos antes de dar a resposta que vocÃª precisava. |
| 13 | [Billion Context](skills/13-billion-context.md) | economia de tokens | 1,9 mil | Em conversa longa, a cada mensagem o modelo relÃª tudo desde o inÃ­cio, e isso consome o limite muito rÃ¡pido. |
| 12 | [Find Skills](skills/12-find-skills.md) | descoberta | 35,5 mil | Existem milhares de skills e vocÃª nÃ£o sabe se jÃ¡ tem uma pronta para o que precisa. |
| 11 | [De-AI Writing](skills/11-de-ai-writing.md) | escrita | â€” | Texto com cara de IA ('situado no coraÃ§Ã£o da cidade, um testemunho da rica heranÃ§a cultural') faz o leitor desconfiar e parar de ler. |
| 10 | [Archify](skills/10-archify.md) | diagramas | 85,4 mil | Explicar como funciona uma automaÃ§Ã£o, um sistema ou um plano numa reuniÃ£o, e o cliente sÃ³ balanÃ§a a cabeÃ§a sem entender. |
| 9 | [NanoClaw](skills/09-nanoclaw.md) | assistente | 31 mil | Ter um assistente de IA pessoal no celular sem entregar a sua vida a um programa enorme que ninguÃ©m entende. |
| 8 | [CLAUDE.md do Karpathy](skills/08-karpathy-claude-md.md) | regras | 220 mil | VocÃª pede para o Claude mudar uma linha e ele reescreve metade do projeto e ainda inventa recursos que ninguÃ©m pediu. |
| 7 | [HyperFrames](skills/07-hyperframes.md) | vÃ­deo | 66,8 mil | Fazer um vÃ­deo com tÃ­tulo animado, mÃºsica e cortes leva uma hora num editor, e no fim o tempo ainda fica errado. |
| 6 | [Skills do Matt Pocock](skills/06-mattpocock-skills.md) | cÃ³digo | 296 mil | O Claude escreve milhares de linhas em minutos e depois vocÃª passa dias descobrindo o que quebrou, porque ele comeÃ§ou antes de entender o que vocÃª queria. |
| 5 | [Career Ops](skills/05-career-ops.md) | carreira | 75,5 mil | Mandar 50 currÃ­culos e 50 cartas para receber duas respostas. |
| 4 | [Graphify](skills/04-graphify.md) | conhecimento | 128 mil | Notas, PDFs, prints, vÃ­deos e cÃ³digo numa mesma pasta, e ninguÃ©m sabe o que liga com o quÃª. |
| 3 | [AI Website Cloner](skills/03-ai-website-cloner.md) | web | 37 mil | Refazer um site (fontes, cores, layout) pode levar dias de um designer ou desenvolvedor. |
| 2 | [Anatomy](skills/02-anatomy.md) | visual | 16,1 mil | VocÃª pergunta como algo funciona e recebe um paredÃ£o de texto; pergunta de novo e o paredÃ£o cresce. |
| 1 | [REA (Reverse Engineer Anything)](skills/01-rea.md) | engenharia reversa | 323 mil | VocÃª vÃª um recurso no aplicativo de outra pessoa e quer no seu, mas nÃ£o tem o cÃ³digo, entÃ£o chuta e erra. |
<!-- /tabela -->

Estrelas contadas no GitHub em 18/10/2026. A #11 nÃ£o tem repositÃ³rio: Ã© um post do Reddit (a alternativa instalÃ¡vel Ã© o [Humanizer](https://github.com/blader/humanizer)).

## Como instalar qualquer uma

O jeito universal: copie o link do repositÃ³rio, cole no Claude Code e diga **"instale isso para mim"**.

Ou use o instalador deste repo, que sÃ³ mostra os comandos oficiais (e roda se vocÃª pedir):

```bash
git clone https://github.com/inematds/skills15.git && cd skills15
./scripts/instalar.sh              # lista as 15
./scripts/instalar.sh 12           # mostra como instalar a #12 (find-skills)
./scripts/instalar.sh 12 --executar  # roda os comandos de terminal da #12
```

> NÃ£o instale todas. Cada skill a mais Ã© contexto que o agente carrega e pode disparar sem vocÃª querer. Escolha a que resolve o seu problema de hoje.

## ConteÃºdo

| arquivo | o quÃª |
|---|---|
| `catalogo.json` | as 15 em dados (problema, como funciona, instalaÃ§Ã£o, exemplo, cuidado, link) |
| `skills/NN-nome.md` | uma ficha por skill |
| `scripts/instalar.sh` | mostra/roda o comando oficial de cada uma |
| `scripts/gerar.py` | regenera as fichas e a tabela a partir do catÃ¡logo |
| `tests/run.sh` | checagens do catÃ¡logo, fichas e guia |
| `guia/` | landing + guia (PT/EN/ES) |

## LicenÃ§as

Este repositÃ³rio **nÃ£o copia** o cÃ³digo das skills: cada uma continua no projeto original, com a licenÃ§a dele (a maioria MIT; HyperFrames e Graphify sÃ£o Apache-2.0; o CLAUDE.md do Karpathy e o billion-context nÃ£o declaram licenÃ§a reconhecida pelo GitHub). O texto deste catÃ¡logo Ã© MIT.

## No INEMA

- REA (a #1) explicado e testado: https://inematds.github.io/rea-engenharia-reversa/guia/
- Skills do Matt Pocock (a #6) organizadas com Addy e pstack: https://inematds.github.io/trio-skills/guia/
- HyperFrames (a #7) Ã© o motor dos vÃ­deos do INEMA: https://inematds.github.io/explicavideos/guia/

Projetos e cursos gratuitos: https://inema.club

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>