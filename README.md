# prosperediario-site

Site público do Prospere Diário (@prosperediario): página inicial, política de privacidade, termos de uso e a página de vendas do ebook "30 Dias de Prosperidade".

- No ar: https://prosperediario.vercel.app
- Página de vendas: https://prosperediario.vercel.app/desafio-30-dias
- Checkout (Kiwify): https://pay.kiwify.com.br/3ICab1J

## Como é feito

HTML e CSS puros, sem build e sem pacote npm. As letras (DM Serif Display, Inter e Space Mono, licença OFL) ficam em `/fontes`, sem Google Fonts. `vercel.json` liga URLs limpas e os cabeçalhos de segurança.

## Variáveis de ambiente

Nenhuma. O site não guarda nem coleta dados; o pagamento é todo na Kiwify.

## Como publicar

1. Ramo novo, mudança, push: a Vercel gera a prévia.
2. PNG da prévia para o Lipe aprovar.
3. Com o OK, juntar no `main`: publica em produção.
