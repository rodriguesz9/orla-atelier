# Orla Atelier

Joalheria conceitual com fotografia, seleção de peças e FAQ nativo.

**Demonstração:** [Abrir Orla Atelier](https://robertrodrigues.vercel.app/demos/orla/)

## Stack

HTML, CSS e JavaScript. Build com Node.js, sem dependências de runtime.

## Executar

Requer Node.js22+ e Python3 para o servidor local. Não precisa instalar dependências.

```sh
npm run build
npm run preview
```

Abra http://127.0.0.1:4173. `dist/` pode ser hospedada como site estático, inclusive em um subdiretório.

## Estrutura

- HTML/CSS/JavaScript na raiz ou em `src/`.
- `public/` ou `src/art/`: mídia local.
- `build.mjs`: empacotamento independente e reproduzível.

## Acessibilidade e verificação

Navegação por âncoras, foco visível, textos alternativos e respeito a `prefers-reduced-motion`. Interações essenciais usam controles nativos quando aplicável. Revisado em320,390,768 e1440px; sem substituir testes em aparelhos físicos ou leitores de tela.

## Créditos e limites

Fotografias de acervo Pexels: Leeloo, Lum3n e colaboradores. Ver PHOTO-SOURCES.md.

Estudo de portfólio por Robert Rodrigues. Não representa contratação, operação comercial ou afiliação a marcas externas. Sem pagamentos, cadastro ou reservas reais. Nenhum depoimento ou resultado comercial é apresentado como real. Créditos de terceiros devem ser preservados; este repositório não concede direitos adicionais sobre mídia de terceiros.
