# ChatGPT Plugin — Professor Inglês do Zero

Plugin público para ChatGPT e Codex que ensina inglês a brasileiros do nível A0 ao C2.

Este repositório contém um plugin de instruções e recursos pedagógicos. Não é um aplicativo independente nem uma extensão de navegador.

## Instalação

Adicione o marketplace ao Codex:

```bash
codex plugin marketplace add mx7842/professor-ingles-do-zero
```

Depois, no ChatGPT ou Codex, selecione `ChatGPT Plugins — mx7842` e instale `Professor Inglês do Zero`.

## O plugin

- diagnóstico adaptativo por habilidade;
- aulas práticas do A0 ao C2;
- conversação, pronúncia, listening, reading, writing, gramática e vocabulário;
- flashcards, revisão, recuperação ativa e banco de erros;
- adaptação para viagem, trabalho, estudo, filmes e inglês geral.

## Estrutura

```text
.
├── .agents/plugins/marketplace.json
└── plugins/professor-ingles-do-zero/
    ├── .codex-plugin/plugin.json
    ├── assets/icon.png
    └── skills/professor-ingles-do-zero/
```

O marketplace lista somente plugins. Apps, extensões e plugins privados futuros ficarão em repositórios separados, com seus próprios ciclos de publicação e acesso.

## Licença

MIT. O repositório é público para facilitar compartilhamento, cópia e modificação com atribuição.
