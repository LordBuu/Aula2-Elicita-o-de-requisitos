# Atividade 7 - Event Storming

**Domínio:** Lanchonete

**Atores:** Cliente e Atendente.

**Comandos:**
- Fazer pedido
- Confirmar pagamento
- Preparar pedido

**Eventos:**
- Pedido criado
- Pagamento aprovado
- Pedido preparado
- Pedido entregue

**Agregado:** Pedido.

**Políticas:**
- Quando o pagamento for aprovado, o pedido é enviado para a cozinha.
- Quando o pedido estiver preparado, o cliente é avisado.

**Hotspots:**
- E se o pagamento for recusado?
- E se faltar algum produto?

**Fluxo:** Cliente faz o pedido, o pagamento é aprovado, a cozinha prepara o pedido e o atendente realiza a entrega.