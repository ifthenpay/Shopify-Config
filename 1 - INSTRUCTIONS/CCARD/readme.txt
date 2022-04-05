Para ativar o pagamento por CARTÃO DE CRÉDITO no Shopify deverá seguir o procedimento abaixo:

1 - Criar um Pagamento Manual (Settings/Payment Providers) com a seguinte informação:

- No nome do pagamento colocar CARTÃO DE CRÉDITO (obrigatório)
- Nas definições adicionais colocar o seguinte texto (recomendado):

Pagamento por Cartão de Crédito através da gateway da ifthenpay

- Instruções de pagamento:

Conclua o pagamento da sua compra utilizando o cartão de crédito


2 - Configurar as definições de Chechout (Settings/Checkout)

- No separador Order processing, no campo Additional scripts, copiar o conteúdo do ficheiro "checkout-CCARD-config.txt".

No código existente deverá substituir a tag [GATEWAY_KEY] pela Gateway Key fornecida pela ifthenpay (sem os parênteses rectos) no formato XXXX-000000. Caso não tenha a Gateway Key solicite-nos. Não confundir com a chave de acesso ao backoffice.