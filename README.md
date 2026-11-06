# Diagnóstico dos pedidos de delivery em 2024

> Análise da operação, das avaliações dos clientes e da relação de chuva e cupons com os pedidos para apoiar o planejamento de 2025.

## 1. Pergunta de negócio

A diretoria do aplicativo de delivery solicitou um diagnóstico dos pedidos de 2024 para apoiar o planejamento de 2025. A análise investiga três frentes: operação das entregas, comportamento e avaliações dos clientes, e a relação de chuva e cupons com os pedidos.

**Perguntas que guiam a análise**

1. Em quais horários e dias da semana se concentram os pedidos?
2. Em dias de chuva, as entregas demoram mais em cada cidade?
3. Como a avaliação varia conforme o tempo de entrega?
4. O valor dos pedidos com cupom difere do valor dos pedidos sem cupom dentro de cada tipo de cozinha?
5. Como o volume diário de pedidos e o uso de cupons em julho se comparam aos demais meses?

## 2. Dados

- **Fonte** — `delivery_pedidos.csv`, base simulada fornecida no módulo DS-PY-018.
- **Período e escopo** — pedidos de 2024 em São Paulo, Rio de Janeiro e Belo Horizonte.
- **Tamanho da base original** — 8.058 linhas e 18 colunas, conforme o enunciado.
- **Unidade de observação** — um pedido.