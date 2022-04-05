Para ativar o pagamento MB WAY no Shopify dever� seguir o procedimento abaixo:

1 - Criar um Pagamento Manual (Settings/Payment Providers) com a seguinte informa��o:

- No nome do pagamento colocar MB WAY (obrigat�rio)
- Nas defini��es adicioniais colocar o seguinte texto (recomendado):

"Pagamento por MB WAY.

Nota: Se optar por este m�todo de pagamento dever� estar registado com o seu n�mero de telem�vel associado ao MB WAY."

- Nas instru��es do pagamento colocar o seguinte texto (recomendado):

"Por favor confirme na sua aplica��o MB WAY a autoriza��o do pagamento."

2 - Configurar as defini��es de Chechout (Settings/Checkout)

- No separador Form options na op��o (Shipping address phone number) escolher uma das seguintes op��es (Optional ou Required). 
Nota: Se escolher Hidden o cliente n�o ter� possibilidade de introduzir o n�mero de telem�vel que ser� usado no envio do pedido de pagamento MB WAY.

- No separador Order processing, no campo Additional scripts, copiar o conte�do do ficheiro "checkout-MBWAY-config.txt", ou "checkout-MBWAY-with-callback-config.txt", conforme pretender ou n�o a activa��o de callback, para dentro da caixa. Caso j� tenha pagamentos MULTIBANCO ativo, ter� que acrescentar no final do c�digo existente.

No c�digo existente dever� substituir a tag [MBWAYKEY] pela sua MBWAY KEY (sem os par�nteses rectos) fornecida pela ifthenpay no formato AAA-000000. Poder� encontr�-la no seu contrato. N�o confundir com a chave de acesso ao backoffice.





	


	
