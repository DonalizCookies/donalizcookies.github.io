# Dona Liz · App de pedidos do cliente

Página onde o cliente escolhe os cookies, monta o carrinho e envia o pedido.
O pedido chega no app da Dona Liz (painel de estoque) na hora.

**Link para os clientes:** https://otavio512.github.io/donaliz-pedidos/

- Cardápio, combos (a partir de quarta) e 5% de desconto nos sabores para pedidos de segunda e terça.
- Retirada e entrega de quinta a sábado, com corte às 18h. Horários, períodos, datas fechadas,
  taxas por bairro e Pix são configurados no painel (Ajustes → Pedidos pelo app do cliente).
- O cliente não precisa de cadastro: informa nome e WhatsApp. "Meus pedidos" fica salvo no navegador dele.
- `firestore.rules` tem as regras de segurança do Firestore (cole em Firestore Database → Regras).

Cada envio para a branch `main` publica a página de novo pelo GitHub Actions.
