Objetivo:
Refine o modelo apresentado acrescentando os seguintes pontos:

Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
Entrega – Possui status e código de rastreio;

Resolução

Foi acrescentado mais duas tabelas, pessoa física e pessoa jurídica. Esse modelo é flexível 
e fácil de expandir, permitindo que você relacione tanto Pessoa Física quanto Pessoa Jurídica
indiretamente a outras entidades do sistema, através da superclasse Cliente.

Mais uma tabela "Forma de pagamento" foi acrescentada ao banco de dados e seu respectivo campo foi acrescentado na tabela "Pedido".

Quanto a estrega, acrescentei os campos "Data da entrega" e "código de rastreio".

