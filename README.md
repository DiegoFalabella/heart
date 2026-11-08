# Verme do coração — infográficos animados

Infográficos animados (Lottie) para a matéria "Uma doença silenciosa, histórias diferentes: o impacto do verme do coração na vida dos cães" (O TEMPO, editoria Pets). Tudo fica hospedado aqui no GitHub Pages; na matéria só entra o código do iframe.

- Prévia da matéria: https://diegofalabella.github.io/heart/
- Embed 1 (ciclo): https://diegofalabella.github.io/heart/embed/ciclo.html
- Embed 2 (guia do tutor): https://diegofalabella.github.io/heart/embed/guia.html

## Códigos para colar na matéria

Use no mesmo lugar onde hoje está cada embed do Genially.

**Embed 1 — no lugar do Genially "Ciclo da dirofilariose"**

```html
<iframe src="https://diegofalabella.github.io/heart/embed/ciclo.html" title="Infográfico animado: ciclo da dirofilariose" width="640" height="800" loading="lazy" scrolling="no" style="display:block;width:100%;max-width:640px;height:auto;aspect-ratio:4/5;border:0;margin:24px auto;"></iframe>
```

**Embed 2 — no lugar do Genially "Verme do coração: o que os tutores precisam saber"**

```html
<iframe src="https://diegofalabella.github.io/heart/embed/guia.html" title="Infográfico animado: verme do coração, o que os tutores precisam saber" width="640" height="800" loading="lazy" scrolling="no" style="display:block;width:100%;max-width:640px;height:auto;aspect-ratio:4/5;border:0;margin:24px auto;"></iframe>
```

## Se o sistema cortar o atributo `style`

Se o iframe aparecer com tamanho fixo (640 × 800) ou cortado no celular, use esta versão com um bloco em volta, que mantém a proporção 4:5:

```html
<div style="max-width:640px;margin:24px auto;"><div style="position:relative;padding-top:125%;"><iframe src="https://diegofalabella.github.io/heart/embed/ciclo.html" title="Infográfico animado: ciclo da dirofilariose" loading="lazy" scrolling="no" style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;"></iframe></div></div>
```

(Para o guia, troque `ciclo.html` por `guia.html` e o título.)

## Arquivos

- `embed/` — páginas que os iframes carregam
- `lottie/` — os arquivos de animação

Atenção: os embeds dependem deste repositório. Não apague nem renomeie o repositório, a pasta `embed/` ou a pasta `lottie/`, senão os infográficos somem da matéria.
