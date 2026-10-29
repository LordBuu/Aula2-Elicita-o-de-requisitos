# Atividade 8 - BPMN

**Processo:** Pedido em uma lanchonete.

**Piscinas:** Cliente e Lanchonete.

**Raias da lanchonete:** Atendente e Cozinha.

**Fluxo do processo:**

1. Início: cliente faz o pedido.
2. Atendente registra o pedido.
3. Gateway exclusivo: produto disponível?
4. Se não, pedido cancelado.
5. Se sim, confirmar pedido.
6. Gateway paralelo: conferir pagamento e preparar pedido.
7. Após as duas tarefas, avisar que está pronto.
8. Cliente retira o pedido.
9. Fim: pedido entregue.

**Mensagem entre piscinas:** Cliente envia o pedido e recebe a confirmação de que está pronto.