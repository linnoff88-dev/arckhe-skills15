ï»¿# skills15 ê¢â¬â as 15 skills para o Claude que valem a pena

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


[![skills15](guia/assets/banner.jpg)](https://inematds.github.io/skills15/guia/)

**ê°Å¸â¡Â§ê°Å¸â¡Â· [PortuguêÂªs](README.md) êÂ· ê°Å¸â¡Âºê°Å¸â¡Â¸ [English](README.en.md) êÂ· ê°Å¸â¡Âªê°Å¸â¡Â¸ [EspaêÂ±ol](README.es.md)**

## O que êÂ©

Existem mais de um milhêÂ£o de skills para agentes de IA, e a maioria nêÂ£o serve para nada. Este repositêÂ³rio reêÂºne as **15 que valem a pena** para quem usa o Claude Code (e outros agentes): o problema que cada uma resolve, como funciona por dentro, o comando oficial de instalaêÂ§êÂ£o, um exemplo de pedido e o link para o projeto original. Serve para quem quer escolher **uma** skill para a dor de hoje, sem instalar tudo de uma vez.

## ê°Å¸ââ Guia de uso

Landing + guia com as 15, exemplos e vêÂ­deo: **https://inematds.github.io/skills15/guia/**

## As 15 (da 15êÂª para a 1êÂª)

<!-- tabela -->
| # | Skill | Para quêÂª | ê¢Ëâ¦ 18/10 | Problema que resolve |
|---|---|---|---|---|
| 15 | [NotebookLM](skills/15-notebooklm-py.md) | economia de tokens | 19,8 mil | Quando vocêÂª joga muitos PDFs no Claude, ele lêÂª tudo palavra por palavra e o seu limite de uso acaba rêÂ¡pido. |
| 14 | [I Have ADHD](skills/14-i-have-adhd.md) | respostas | 57,7 mil | O Claude enrola: escreve trêÂªs parêÂ¡grafos antes de dar a resposta que vocêÂª precisava. |
| 13 | [Billion Context](skills/13-billion-context.md) | economia de tokens | 1,9 mil | Em conversa longa, a cada mensagem o modelo relêÂª tudo desde o inêÂ­cio, e isso consome o limite muito rêÂ¡pido. |
| 12 | [Find Skills](skills/12-find-skills.md) | descoberta | 35,5 mil | Existem milhares de skills e vocêÂª nêÂ£o sabe se jêÂ¡ tem uma pronta para o que precisa. |
| 11 | [De-AI Writing](skills/11-de-ai-writing.md) | escrita | ê¢â¬â | Texto com cara de IA ('situado no coraêÂ§êÂ£o da cidade, um testemunho da rica heranêÂ§a cultural') faz o leitor desconfiar e parar de ler. |
| 10 | [Archify](skills/10-archify.md) | diagramas | 85,4 mil | Explicar como funciona uma automaêÂ§êÂ£o, um sistema ou um plano numa reuniêÂ£o, e o cliente sêÂ³ balanêÂ§a a cabeêÂ§a sem entender. |
| 9 | [NanoClaw](skills/09-nanoclaw.md) | assistente | 31 mil | Ter um assistente de IA pessoal no celular sem entregar a sua vida a um programa enorme que ninguêÂ©m entende. |
| 8 | [CLAUDE.md do Karpathy](skills/08-karpathy-claude-md.md) | regras | 220 mil | VocêÂª pede para o Claude mudar uma linha e ele reescreve metade do projeto e ainda inventa recursos que ninguêÂ©m pediu. |
| 7 | [HyperFrames](skills/07-hyperframes.md) | vêÂ­deo | 66,8 mil | Fazer um vêÂ­deo com têÂ­tulo animado, mêÂºsica e cortes leva uma hora num editor, e no fim o tempo ainda fica errado. |
| 6 | [Skills do Matt Pocock](skills/06-mattpocock-skills.md) | cêÂ³digo | 296 mil | O Claude escreve milhares de linhas em minutos e depois vocêÂª passa dias descobrindo o que quebrou, porque ele comeêÂ§ou antes de entender o que vocêÂª queria. |
| 5 | [Career Ops](skills/05-career-ops.md) | carreira | 75,5 mil | Mandar 50 currêÂ­culos e 50 cartas para receber duas respostas. |
| 4 | [Graphify](skills/04-graphify.md) | conhecimento | 128 mil | Notas, PDFs, prints, vêÂ­deos e cêÂ³digo numa mesma pasta, e ninguêÂ©m sabe o que liga com o quêÂª. |
| 3 | [AI Website Cloner](skills/03-ai-website-cloner.md) | web | 37 mil | Refazer um site (fontes, cores, layout) pode levar dias de um designer ou desenvolvedor. |
| 2 | [Anatomy](skills/02-anatomy.md) | visual | 16,1 mil | VocêÂª pergunta como algo funciona e recebe um paredêÂ£o de texto; pergunta de novo e o paredêÂ£o cresce. |
| 1 | [REA (Reverse Engineer Anything)](skills/01-rea.md) | engenharia reversa | 323 mil | VocêÂª vêÂª um recurso no aplicativo de outra pessoa e quer no seu, mas nêÂ£o tem o cêÂ³digo, entêÂ£o chuta e erra. |
<!-- /tabela -->

Estrelas contadas no GitHub em 18/10/2026. A #11 nêÂ£o tem repositêÂ³rio: êÂ© um post do Reddit (a alternativa instalêÂ¡vel êÂ© o [Humanizer](https://github.com/blader/humanizer)).

## Como instalar qualquer uma

O jeito universal: copie o link do repositêÂ³rio, cole no Claude Code e diga **"instale isso para mim"**.

Ou use o instalador deste repo, que sêÂ³ mostra os comandos oficiais (e roda se vocêÂª pedir):

```bash
git clone https://github.com/inematds/skills15.git && cd skills15
./scripts/instalar.sh              # lista as 15
./scripts/instalar.sh 12           # mostra como instalar a #12 (find-skills)
./scripts/instalar.sh 12 --executar  # roda os comandos de terminal da #12
```

> NêÂ£o instale todas. Cada skill a mais êÂ© contexto que o agente carrega e pode disparar sem vocêÂª querer. Escolha a que resolve o seu problema de hoje.

## ConteêÂºdo

| arquivo | o quêÂª |
|---|---|
| `catalogo.json` | as 15 em dados (problema, como funciona, instalaêÂ§êÂ£o, exemplo, cuidado, link) |
| `skills/NN-nome.md` | uma ficha por skill |
| `scripts/instalar.sh` | mostra/roda o comando oficial de cada uma |
| `scripts/gerar.py` | regenera as fichas e a tabela a partir do catêÂ¡logo |
| `tests/run.sh` | checagens do catêÂ¡logo, fichas e guia |
| `guia/` | landing + guia (PT/EN/ES) |

## LicenêÂ§as

Este repositêÂ³rio **nêÂ£o copia** o cêÂ³digo das skills: cada uma continua no projeto original, com a licenêÂ§a dele (a maioria MIT; HyperFrames e Graphify sêÂ£o Apache-2.0; o CLAUDE.md do Karpathy e o billion-context nêÂ£o declaram licenêÂ§a reconhecida pelo GitHub). O texto deste catêÂ¡logo êÂ© MIT.

## No INEMA

- REA (a #1) explicado e testado: https://inematds.github.io/rea-engenharia-reversa/guia/
- Skills do Matt Pocock (a #6) organizadas com Addy e pstack: https://inematds.github.io/trio-skills/guia/
- HyperFrames (a #7) êÂ© o motor dos vêÂ­deos do INEMA: https://inematds.github.io/explicavideos/guia/

Projetos e cursos gratuitos: https://inema.club

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>