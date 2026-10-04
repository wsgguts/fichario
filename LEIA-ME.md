# Fichário de Estudo (PWA)

Conteúdo: `index.html`, `manifest.json`, `sw.js`, `jspdf.umd.min.js` e a pasta `icons/`. Mantenha tudo junto, na mesma pasta.

## Publicar de graça no GitHub Pages
1. Crie um repositório público no GitHub (ex.: `fichario`).
2. Envie todos os arquivos desta pasta para a raiz do repositório (Add file > Upload files).
3. Em Settings > Pages, escolha "Deploy from a branch", branch `main`, pasta `/ (root)`, e salve.
4. Em 1 a 2 minutos o endereço fica disponível: `https://SEU-USUARIO.github.io/fichario/`.

(O Netlify Drop também serve: arraste a pasta em app.netlify.com/drop.)

## Instalar no Android
1. Abra o endereço no Chrome do celular.
2. Menu ⋮ > "Instalar app" (ou "Adicionar à tela inicial").
3. O Fichário passa a abrir em tela cheia e funciona sem internet.

## Gerar o APK
1. Abra https://www.pwabuilder.com e cole o endereço publicado.
2. Em "Package for stores", escolha Android e baixe o pacote. Ele inclui o APK (para instalar direto) e o AAB (para a Play Store).
3. Para instalar o APK, permita "Instalar apps de fontes desconhecidas" no Android.

## Suas fichas
As fichas ficam guardadas no navegador de cada aparelho. O app instalado tem armazenamento próprio.
Para levar as fichas da versão antiga: Arquivo > Baixar backup na versão antiga, depois Arquivo > Restaurar backup no app novo.
Faça backup de vez em quando.

## Atualizar o app
Altere os arquivos no repositório e, em `sw.js`, troque `fichario-v1` por `fichario-v2` para o celular baixar a nova versão.
