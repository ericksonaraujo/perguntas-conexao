# Conexão — Jogo de Perguntas

PWA instalável para iOS e Android.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub (pode ser privado ou público)
2. Faça upload de todos os arquivos desta pasta para a raiz do repositório
3. Vá em **Settings → Pages**
4. Em **Source**, selecione `Deploy from a branch`
5. Escolha a branch `main` e a pasta `/ (root)`
6. Clique em **Save**
7. Aguarde ~1 minuto — o app estará disponível em `https://seu-usuario.github.io/nome-do-repositório`

## Como instalar no celular

### iPhone (Safari)
1. Abra o link no Safari
2. Toque no botão de compartilhar (□↑)
3. Toque em **"Adicionar à Tela de Início"**

### Android (Chrome)
1. Abra o link no Chrome
2. Toque no menu (⋮)
3. Toque em **"Adicionar à tela inicial"** ou aguarde o banner automático

## Estrutura de arquivos

```
/
├── index.html       ← app principal
├── manifest.json    ← configuração do PWA
├── sw.js            ← service worker (cache offline)
└── icons/
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-180.png  ← ícone para iPhone
    ├── icon-192.png
    ├── icon-384.png
    └── icon-512.png
```
