# República dos Pastéis — Homepage

Site estático simples e responsivo para divulgação da pastelaria.

## Como usar

- Abra o arquivo `index.html` no navegador.
- Para publicar, envie estes arquivos para um serviço de hospedagem estática (Vercel, GitHub Pages, Netlify ou servidor próprio).

## Personalização

- Logo: substitua `assets/img/logo.png` pelo seu arquivo (PNG/SVG) mantendo o nome.
- Imagens: as seções usam imagens do Unsplash como placeholders. Troque as URLs diretamente no `index.html` ou defina suas próprias imagens locais.
- Cores: ajuste variáveis no topo de `assets/css/styles.css` (por exemplo `--primary`).
- Preços: os preços exibidos no preview são "a partir de" e servem de exemplo. Edite os valores na seção "Nosso Cardápio" dentro do `index.html`.
- Links: os botões "Faça já o seu pedido" e "Ver Cardápio Completo" apontam para `https://republicadospasteis.vercel.app`. Atualize se necessário.
- WhatsApp: o link usa `https://wa.me/5579981575934`. Altere o número se precisar.

## Estrutura

- `index.html` — Estrutura principal da página.
- `assets/css/styles.css` — Estilos e responsividade.
- `assets/js/main.js` — Menu mobile e UX.
- `assets/img/` — Coloque aqui a logo e futuras imagens locais.

## SEO & Acessibilidade

- Metatags Open Graph para melhor preview em redes sociais.
- Elementos com `aria-label` e textos alternativos nas imagens.

## Licenças

- As imagens de exemplo são referências do Unsplash e devem ser substituídas por imagens próprias. Verifique direitos de uso antes de publicar.
