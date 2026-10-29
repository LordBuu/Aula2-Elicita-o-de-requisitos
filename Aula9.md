# Atividade 9 - Casos de Uso

**Sistema:** Pedidos de uma lanchonete.

**Atores:**
- Cliente
- Atendente
- Sistema de Pagamento

**Casos de uso:**
- Realizar pedido
- Consultar pedido
- Confirmar pagamento
- Preparar pedido
- Entregar pedido

## Especificação: Realizar Pedido

**Ator:** Cliente.

**Descrição:** Permite ao cliente fazer um pedido na lanchonete.

**Gatilho:** Cliente deseja comprar um produto.

**Pré-condição:** O sistema está funcionando e há produtos cadastrados.

**Pós-condição:** Pedido registrado no sistema.

### Fluxo principal
1. Cliente escolhe os produtos.
2. Sistema calcula o valor.
3. Cliente confirma o pedido.
4. Sistema registra o pedido.

### Fluxo alternativo
**Quando:** Um produto está indisponível.

1. Sistema informa a indisponibilidade.
2. Cliente escolhe outro produto.
3. Retorna à escolha dos produtos.

### Exceção
**Quando:** O sistema apresenta erro ao salvar o pedido.

1. Sistema informa o erro.
2. Pedido não é confirmado.
3. Cliente pode tentar novamente.