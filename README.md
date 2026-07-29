# Tapete AR — Tapetes São Carlos

Visualizador de tapetes em realidade aumentada, acessível direto pelo celular via browser.

## Como usar

1. Abra o link do Vercel no celular
2. Selecione o arquivo `.glb` do tapete
3. Toque em **Abrir AR**
4. Aponte a câmera pro chão até aparecer o anel dourado
5. Toque pra posicionar o tapete
6. **1 dedo** → rotacionar · **2 dedos (pinça)** → escalar

## Compatibilidade

| Dispositivo | Suporte |
|---|---|
| Android + Chrome + ARCore | ✅ Completo |
| iOS 15+ Safari | ✅ AR Quick Look |
| Desktop | ❌ Sem AR |
| Firefox | ❌ Sem WebXR |

## Tech

- HTML/CSS/JS puro — sem build, sem dependências instaladas
- [Three.js r128](https://threejs.org/) via CDN
- WebXR Hit Test API (Android)
- AR Quick Look (iOS)
- Deploy via Vercel (static)

## Deploy

```bash
git clone https://github.com/<seu-user>/tapete-ar-viewer
cd tapete-ar-viewer
# abra index.html no browser ou faça deploy no Vercel
```
