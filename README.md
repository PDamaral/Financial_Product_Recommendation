# Financial Product Recommendation
Recommendation of financial products according to the client's profile, considering the level of trust and minimum support - Unsupervisioned (PT-BR)

## Objetivo
Conforme proposto pela IBM :” O desafio consiste de agregar as bases destas instituições proporcionadas pelo novo ambiente do Open Finance, realizar o tratamento dos dados e desenvolver modelos de recomendação de produtos a partir do uso de algoritmos como os de Regras de Associação, considerando uma confiança na regra de 80% e um suporte mínimo de 10% com no máximo 5 antecedentes.”
## Resumo do Desenvolvimento
Unificando as bases de dados fornecidas, sendo cada base de uma empresa diferente contendo dados de cada cliente, após a unificação e feita a analise exploratória univariada e bivariada. Não realizada nenhuma transformação e aplicado o modelo APRIORI de aprendizado de maquina, conforme solicitado utilizando 80% de confiança e 10% de suporte mínimo com ate 5 antecedentes. Com o resultado aplicado a um dataframe e filtrado para que existam 3 ou menos recomendações e aplicado no conjunto de dados resposta.

## Conclusão
Por fazer parte da maratona Behind the code 2021 o tempo de desenvolvimento do projeto foi bem curto, sendo feito em apenas 4 dias, apesar do tempo curto foi um grande aprendizado realizar um projeto não supervisionado entendendo seu conceito e a utilização de uma de suas bibliotecas de aprendizado de maquina.

Em vista do negocio quanto mais acurado forem as recomendações melhor sera aplicada a força de trabalho para que o produto certo chegue ao cliente certo evitando assim desgastes por ambas as partes (empresa/vendedor e cliente), também possível tomar decisões estratégicas para promover determinado produto ou descontinua-lo em vista da quantidade/qualidade de clientes que o mesmo possa abranger.

