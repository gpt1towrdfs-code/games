# games

Coleção de jogos e experimentos web em arquivo único (HTML + JS), prontos para rodar direto no navegador.

| Jogo | Pasta | Descrição |
| --- | --- | --- |
| Santa Muerta Stories | [`santa-muerta-stories/`](santa-muerta-stories/index.html) | Sandbox de crime em mundo aberto 3D (React + Three.js): direção, tiros, missões, loja de armas e trânsito. |
| Rick Sanchez — Visualizador 3D | [`rick-sanchez-3d/`](rick-sanchez-3d/index.html) | Visualizador de modelos 3D (Three.js) com órbita, zoom e upload de arquivos `.glb` / `.gltf`. |

A página inicial ([`index.html`](index.html)) é um menu que leva a cada jogo.

## Como rodar

**Local:** abra o `index.html` de cada pasta no navegador (ou sirva com `python3 -m http.server`).

**GitHub Pages:** em *Settings → Pages*, escolha **Deploy from a branch** → branch `main` → pasta `/ (root)`.
O site fica em `https://gpt1towrdfs-code.github.io/games/`.

## Estrutura

```
.
├── index.html                  # menu inicial
├── santa-muerta-stories/
│   └── index.html
└── rick-sanchez-3d/
    └── index.html
```

Cada jogo é autocontido; apenas as fontes vêm do Google Fonts e, no visualizador 3D, as bibliotecas Three.js vêm de CDN.
