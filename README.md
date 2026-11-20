# ⌚ Timeback — o jogo do tempo
**VOLTA NO TEMPO** · jogo em pixel art · Desenvolvido por Felipe

## ▶ Jogar
**https://frjfelipe-droid.github.io/Timeback---o-jogo-do-tempo/**

Funciona no celular e no PC. Use fones de ouvido.

- **iPhone:** abra o link no Safari → Compartilhar → "Adicionar à Tela de Início" (vira app, tela cheia, funciona offline).
- **Android:** abra no Chrome → menu ⋮ → "Instalar app". Ou baixe o APK em **Actions → Gerar APK Android → Artifacts**.
- **PC:** teclado (setas, Z/Enter = A, X = B, C = relógio, P = pausa, F = tela cheia) ou controle.

## A história
Lucas vive o mesmo dia todo dia, até comprar um relógio que o leva de volta a 2005. Lá, além de reencontrar a vida que queria, ele pode:
- jogar a **final do interclasse** de futsal e voltar no tempo quando errar;
- descobrir **quem é o diretor** da escola;
- procurar **o menino que sumiu** dentro de uma casa assombrada.

Suas escolhas — e seus silêncios — mudam o final. 3 finais.

## Estrutura
- `www/` — o jogo (um único `index.html`) + modo app (manifest, service worker, ícones)
- `android/`, `ios/` — projetos nativos (Capacitor)
- `.github/workflows/` — publica o site e gera o APK automaticamente
