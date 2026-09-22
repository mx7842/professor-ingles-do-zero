# ChatGPT Plugin — Professor Inglês do Zero

Plugin público para ChatGPT e Codex que ensina inglês a brasileiros do nível A0 ao C2.

Este repositório contém um plugin de instruções e recursos pedagógicos. Ele não é um aplicativo independente nem uma extensão de navegador.

## Instalação

Adicione o marketplace ao Codex:

```bash
codex plugin marketplace add mx7842/professor-ingles-do-zero
```

Depois, abra o diretório de plugins do ChatGPT/Codex, selecione `ChatGPT Plugins — mx7842` e instale `Professor Inglês do Zero`.

## O plugin

O Professor Inglês do Zero oferece:

- diagnóstico adaptativo por habilidade;
- aulas práticas do A0 ao C2;
- conversação, pronúncia e listening;
- reading, writing, gramática e vocabulário;
- flashcards, revisão, recuperação ativa e banco de erros;
- adaptação para viagem, trabalho, estudo, filmes e inglês geral;
- uso responsável de áudio, imagens e web quando essas capacidades estiverem disponíveis.

## Estrutura

```text
.
├── .agents/plugins/marketplace.json
└── plugins/professor-ingles-do-zero/
    ├── .codex-plugin/plugin.json
    ├── assets/icon.png
    └── skills/professor-ingles-do-zero/
```

O marketplace lista somente plugins. Aplicativos e extensões ficarão em repositórios próprios, com seus própriorio ciclos de publicação e acesso.

## Compartilhamento e privacidade

Este repositório é público. Plugins privados futuros não devem ser adicionados aqui; cada um deverá usar um repositório privado separado e um marketplace restrito.

## Origem

O conteõdo pedagógico foi curado a partir dos documentos fornecidos para este projeto e mantém referências externas de CEFR, British Council, Cambridge, VOA, Oxford e materiais educacionais abertos.
