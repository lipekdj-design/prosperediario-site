# Contexto do prosperediario-site

## O que é
Site público da página sem rosto Prospere Diário (@prosperediario). Serve para:
- página inicial com os links das redes;
- `privacidade` e `termos`, usados na aprovação dos apps da Meta e do Google (auditoria da API do YouTube, enviada em 03/10/2026);
- `desafio-30-dias`: página de vendas do ebook "30 Dias de Prosperidade" (R$ 9,90 na Kiwify), porta de entrada do funil da Máquina Prospere.

## Onde está
- Vercel: projeto `prosperediario` (time LIPE's projects), domínio `prosperediario.vercel.app`.
- Antes de 26/10/2026 o site era publicado por upload, sem Git. Neste dia virou repositório e as 3 páginas antigas foram copiadas do ar sem mudar o conteúdo (conferido por hash do corpo de cada página); só trocamos o Google Fonts pelas letras do próprio site.

## Decisões
- **Sem Google Fonts:** letras em `/fontes` (woff2 recortadas para português), por LGPD e velocidade.
- **CSP fechada em `'self'`:** o site não carrega nada de fora. Os botões levam ao checkout da Kiwify por link normal.
- **Página de vendas sem truque:** sem depoimento inventado, contador falso ou preço riscado (Código de Defesa do Consumidor).
- **Tom da marca:** mentor calmo, 2ª pessoa, sem promessa de ganho, sem travessão.

## Pendências
- Quando o bot de comentário → direct do Instagram entrar no ar, atualizar `privacidade`: hoje ela diz que a página não lê mensagens nem coleta dados de seguidores.
- Pixel de conversão (Meta) na página de vendas, se for anunciar: exige rever CSP e a política de cookies.
