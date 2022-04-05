Para ativar o pagamento PAYSHOP no Shopify dever� seguir o procedimento abaixo:

1 - Criar um Pagamento Manual (Settings/Payment Providers) com a seguinte informa��o:

- No nome do pagamento colocar PAYSHOP (obrigat�rio)
- Nas defini��es adicioniais colocar o seguinte texto (recomendado):

"Pagamento por refer�ncia PAYSHOP em Agentes Payshop, Loja CTT ou Postos de Correio"

- Nas instru��es de pagamento colocar o seguinte texto (recomendado):
"Para pagar a sua refer�ncia diriga-se a um Agente Payshop, Loja CTT ou Posto de Correio"

2 - Configurar as defini��es de Chechout (Settings/Checkout)

- No separador Order processing, no campo Additional scripts, copiar o conte�do do ficheiro "checkout-PAYSHOP-config.txt", ou "checkout-PAYSHOP-with-callback-config.txt", conforme pretender ou n�o a activa��o de callback, para dentro da caixa.

No c�digo existente dever� substituir a tag [PAYSHOP_KEY] pela sua PAYSHOP KEY (sem os par�nteses rectos) fornecida pela ifthenpay no formato XXX-000000. Poder� encontr�-la no seu contrato. N�o confundir com a chave de acesso ao backoffice.

Se pretender validade na refer�ncia indique o n�mero de dias no par�metro validade=[DIAS], se n�o pretender data de validade passe o valor vazio. 





	


	
