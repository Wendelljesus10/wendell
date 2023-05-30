# wendell
Modelo EER
Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
"Achei melhor criar duas entidades onde elas enviam suas FK, para caso uma das escolhas anule a outra. Ex: Pessoa sendo Física e utilizando CPF, na tabela Cliente a Fk Jurídica fica nula."

Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
"Criei outras entidadades como exemplo de formas de pagamentos, pois achei que nesse modelo a representação ficaria melhor. Deixando a entender que possa entrar outros meios de pagamentos, que não coloquei para não ficar muita coisa, mas poderia entrar pagamentos por terceiros, como: Mercado Pago, Paypal, TED."

Entrega – Possui status e código de rastreio;
"Entrega deixei dentro do pedido, pois tirando em base um modelo de ecommerce que atuo, acredito que não precise de outra entidade."
