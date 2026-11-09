# Site demonstrativo — Pão da Vida

Site estático em HTML, CSS e JavaScript, preparado para publicar pelo GitHub Pages. A página inicial foi ajustada para seguir a referência visual: cabeçalho, hero com foto, quatro categorias, localização, faixa de destaques, chamada para WhatsApp e rodapé.

## Antes de publicar

Esta é uma demonstração comercial. As imagens de produtos foram geradas como referências visuais; substitua-as por fotos reais autorizadas pela padaria. O símbolo de trigo é uma marcação provisória em SVG; troque pelo logo oficial. Confirme com o responsável o telefone, endereço, categorias de produtos e textos antes de publicar. Não foram inventados horários nem preços.

Os dados de contato usados neste rascunho vieram de listagens públicas e precisam ser confirmados pela empresa:

- Telefone: `(45) 3096-4920`
- Endereço: Rua Xavantes, 1168 — Santa Cruz, Cascavel — PR, 85806-020

Os botões do WhatsApp apontam para esse mesmo número. Confirme que ele está ativo no WhatsApp Business; se a padaria usar outro número, substitua o destino em `index.html`, `cardapio/index.html` e `contato/index.html`. O cartão de localização e os links de endereço abrem a busca correspondente no Google Maps.

## Publicar no GitHub Pages

1. Extraia o ZIP. Para abrir localmente, abra o arquivo `index.html`; os links entre páginas apontam diretamente aos arquivos `index.html` das pastas.
2. Crie um repositório no GitHub e envie **o conteúdo desta pasta** para a raiz do repositório (incluindo `index.html`, `cardapio/`, `contato/` e `assets/`).
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**, escolha `main` e `/ (root)`, e salve.
5. Aguarde o endereço do GitHub Pages aparecer nessa tela.
6. Depois de conhecer o endereço final, atualize `sitemap.xml` e `robots.txt` para usar o endereço exato publicado. O domínio próprio é opcional e deve ser configurado separadamente.

## Editar dados e aparência

- `assets/css/styles.css`: cores, espaçamento, tipografia e layout responsivo.
- `assets/img/hero-demo.webp`: foto ilustrativa principal; substitua por uma foto licenciada e aprovada.
- `assets/img/categorias-demo.webp`: mosaico ilustrativo usado nos cartões de categoria.
- `assets/img/marca-provisoria.svg`: símbolo temporário; substitua pelo logo autorizado.
- `index.html`, `cardapio/index.html` e `contato/index.html`: conteúdo, títulos SEO e descrições.

Os links para telefone e mapa ficam nos HTMLs. Atualize todos se a empresa confirmar dados diferentes. Não publique a demonstração como site oficial sem aprovação expressa da empresa e revisão do conteúdo.

## Estrutura

```text
.
├── index.html
├── cardapio/index.html
├── contato/index.html
├── assets/
│   ├── css/styles.css
│   ├── js/main.js
│   ├── img/
│   └── icons/favicon.svg
├── robots.txt
└── sitemap.xml
```
