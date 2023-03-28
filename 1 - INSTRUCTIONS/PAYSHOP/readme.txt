Para ativar o pagamento PAYSHOP no Shopify deverá seguir o procedimento abaixo:

1 - Criar um Pagamento Manual (Settings/Payment Providers) com a seguinte informação:

- No nome do pagamento colocar PAYSHOP (obrigatório)
- Nas definições adicioniais colocar o seguinte texto (recomendado):

"Pagamento por referência PAYSHOP em Agentes Payshop, Loja CTT ou Postos de Correio"

- Nas instruções de pagamento colocar o seguinte texto (recomendado):
"Para pagar a sua referência diriga-se a um Agente Payshop, Loja CTT ou Posto de Correio"

2 - Configurar as definições de Chechout (Settings/Checkout)

- No separador Order processing, no campo Additional scripts, copiar o conteúdo do ficheiro "Checkout-config.txt", para dentro da caixa.

No código existente deverá substituir a tag [PAYSHOP_KEY] pela sua PAYSHOP KEY (sem os parênteses rectos) fornecida pela ifthenpay no formato XXX-000000. Poderá encontrá-la no seu contrato. Não confundir com a chave de acesso ao backoffice.

Se pretender validade na referência indique o número de dias no parâmetro validade=[DIAS], se não pretender data de validade passe o valor vazio. 





	


	
