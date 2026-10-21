# JESEG Engenharia — versão para tráfego frio Meta Ads

## O que foi entregue
Landing page responsiva com imagens ilustrativas geradas por IA, formulário que prepara atendimento via WhatsApp, termos de privacidade preliminares, seção de dores B2B, catálogo de categorias sujeito a confirmação e rastreamento opcional por Pixel com consentimento.

## OBRIGATÓRIO antes de veicular anúncios
1. Confirmar todos os serviços, local de atendimento e alegações comerciais com a empresa. Não afirmar que as imagens são funcionários ou instalações reais da JESEG: são ilustrativas geradas por IA.
2. Em `index.html`, definir `SITE_CONFIG.whatsapp` como o número COMPROVADO da JESEG no formato `55DDDNÚMERO`. Sem ele, formulário não recebe nem envia leads.
3. Preencher o `SITE_CONFIG.metaPixelId` com o ID real do Pixel e verificar funcionamento no Test Events. O evento `WhatsAppOpenAttempt` significa apenas intenção/abertura; NÃO é lead recebido.
4. Revisar `privacidade.html` junto da empresa, incluindo identificação do controlador, contato e bases legais; adicionar política final antes de anunciar.
5. Testar em celular, clicar em TODOS os CTAs, abrir WhatsApp e confirmar envio. Testar links de privacidade, consentimento, carregamento e página de erro.
6. Subir no Vercel / hospedagem estática e testar URL pública com HTTPS, política da Meta, pixel e domínio verificado.
7. Para mensurar leads efetivamente recebidos, conectar CRM ou endpoint de coleta e usar evento `Lead` apenas após entrega confirmada.

## Deploy
Publicar a pasta `jeseg-site` como site estático. `index.html` é a entrada e `assets/*.webp` contém todas as imagens.

## Observação
O site original `jesegengenharia.com.br` não respondeu à tentativa de consulta (502). A lista exata de serviços não foi verificada, por isso a cópia evita listar normas, laudos ou resultados específicos como serviços garantidos.

## Atualização V3 — 20/10/2026
As imagens em `assets/hero.webp`, `vistoria.webp`, `documentacao.webp` e `treinamento.webp` foram substituídas pelo conjunto visual mais recente e compactadas em WebP. Ilustrações IA, NÃO representam profissionais/serviços prestados comprovadamente. Verificar adequação dos cenários industriais à realidade da JESEG.


## V5 — cases e fotos reais
- Cases Rock in Rio, The Town, FIAT e Suvinil foram apresentados com registros reais fornecidos pelo cliente, em WebP.
- Sem rostos substituídos ou experiências inventadas.
- O conteúdo não presume relação contratual direta com as marcas.
- Confirme o escopo preciso de cada participação antes de liberar campanhas.
- Valide contatos, Pixel e LGPD antes de anunciar.
