# Página de divulgação — Ryan Rodrigues

Página única (HTML + CSS, sem build) com os três planos: Biosite, Site simples e Site completo.

## Estrutura

```
index.html          página completa
assets/             prints dos sites e imagem de divulgação (1080x1350)
.nojekyll           evita o processamento do Jekyll no GitHub Pages
```

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub (público).
2. Envie o **conteúdo** desta pasta para a raiz do repositório (Add file > Upload files, arrastando `index.html`, a pasta `assets` e o `.nojekyll`).
3. Vá em Settings > Pages, escolha "Deploy from a branch", branch `main`, pasta `/ (root)`, e salve.
4. Em cerca de 1 a 2 minutos a página fica em `https://SEU-USUARIO.github.io/SEU-REPOSITORIO/`.

## Prévia do link no WhatsApp e Facebook

No `index.html`, a tag `og:image` tem um endereço de exemplo. Depois de publicar, troque `SEU-USUARIO` e `SEU-REPOSITORIO` pelo endereço real, para o link aparecer com a imagem `assets/divulgacao.png`. Se o WhatsApp ou o Facebook mostrarem uma prévia antiga, cole o link no Depurador de Compartilhamento do Facebook para atualizar.

## O que editar

- Número e mensagem do WhatsApp: procure por `5521973544768`.
- Preços e textos dos planos: seção `plans` do `index.html`.
- Sites de exemplo: links da classe `sample` e links dos prints.
