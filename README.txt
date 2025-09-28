# Infinity Pet — Projeto Next.js pronto para build

## Como usar (passo a passo simples)
1) No Windows, abra **Prompt de Comando** (CMD).
2) Rode:
   cd /d "C:\Users\biel_\OneDrive\Imagens\SITE INFINITTY"
   (ou copie esta pasta para C:\site\infinity e use essa pasta)
3) Entre na pasta deste projeto (a mesma onde está este README), e rode:
   npm ci
   npm run build
4) Será criada a pasta **out**. No Netlify, faça **Deploy manual** enviando **apenas** o ZIP da pasta `out`.

## Observação sobre ícones (Remix Icons)
Se seus componentes usam classes `ri-*` (ex.: `ri-whatsapp-line`), inclua no `<head>` do `app/layout.tsx`:
<link href="https://cdn.jsdelivr.net/npm/remixicon@4.3.0/fonts/remixicon.css" rel="stylesheet" />
