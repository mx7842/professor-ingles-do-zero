# Professor Inglês do Zero

Plugin para ChatGPT e Codex que funciona como professor particular de inglês para brasileiros, do nível A0 ao C2.

Este é um plugin de instruções e recursos pedagógicos; não é um aplicativo independente, uma extensão de navegador ou um curso separado.

## O que ele faz

- diagnóstico adaptativo por habilidade;
- microaulas, conversação, pronúncia, listening, reading e writing;
- flashcards, recuperação ativa, banco de erros e progressão por competência;
- adaptação para viagem, trabalho, estudo, filmes e inglês geral;
- uso multimodal somente quando a capacidade estiver realmente disponível.

## Estrutura

- `.codex-plugin/plugin.json`: manifesto do plugin;
- `skills/professor-ingles-do-zero/SKILL.md`: comportamento principal;
- `skills/professor-ingles-do-zero/references/`: currículo, fontes e modos de aula.

## Instalação

Adicione o marketplace ao Codex:

```bash
codex plugin marketplace add mx7842/professor-ingles-do-zero
```

Depois, no ChatGPT ou Codex, selecione `ChatGPT Plugins — mx7842` e instale `Professor Inglês do Zero`.

## Compartilhamento

Esta pasta é autocontida e não contém credenciais, banco de dados ou dependências externas. O repositório público é dedicado a este plugin; apps, extensões e plugins privados devem ficar em repositórios separados.

## Origem

As instruções foram curadas a partir dos documentos fornecidos: `Fontes para Aprender Inglês — Básico ao Avançado (NotebookLM + Gemini).md` e `AGENTE_PROFESSOR_INGLES_PRO_A0_C2_MULTIMODAL.md`. Os documentos originais não são comandos executáveis; foram convertidos em comportamento pedagógico e referências consultáveis.
