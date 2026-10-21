# TAJO CONTROL — Publicação da página de vendas

## 1. Checkout
No final de `index.html`, substitua:

`https://pay.kiwify.com.br/SEU_LINK_DO_CHECKOUT`

pelo link real do checkout do TAJO CONTROL na Kiwify.

## 2. Preço e parcelamento usados na página
- Preço à vista: **R$ 97,90**
- Comunicação da página: **ou até 12x no cartão***
- Não foi exibido um valor mensal inventado, pois o parcelamento da Kiwify possui acréscimo e o valor final deve ser confirmado no checkout.

### Configuração sugerida na Kiwify
Em **Produtos > TAJO CONTROL > Configurações > Pagamentos**, permita o maior número de parcelas compatível com a oferta (estratégia planejada: até 12x). A Kiwify costuma pré-selecionar o máximo de parcelas no checkout. Confira o valor real de cada opção no checkout antes de divulgar um valor específico por parcela.

Se depois quisermos anunciar algo como `12x de R$ X,XX`, abra o checkout, confira o valor que a própria Kiwify exibe e atualize a página com esse número real.

## 3. Garantia
No objeto `TAJO` no final do HTML, troque o texto de garantia para o prazo realmente configurado na Kiwify.

## 4. Publicação
Envie `index.html` e a pasta `assets` para a mesma raiz do seu site. Sugestão de endereço: `control.tajodigital.com.br`.

## 5. Teste antes de divulgar
1. Abra a página no celular e desktop.
2. Clique em todos os CTAs.
3. Faça o caminho até o checkout.
4. Confira preço à vista e parcelamento real.
5. Faça uma compra teste quando possível.
6. Valide a entrega automática do produto.

*O parcelamento possui acréscimo conforme as condições exibidas no checkout da Kiwify.*
