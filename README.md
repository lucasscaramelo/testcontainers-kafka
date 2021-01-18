# TestContainers com Kafka

Kafka  tem como objetivo fornecer uma  plataforma unificada, de alta capacidade e baixa latência para tratamento de dados em tempo real.

O Apache Kafka é baseado no commit log, ele permite que os usuários inscrevam-se e publiquem dados para qualquer número de sistemas ou aplicações em tempo real.

Com TestContainers, criaremos uma imagem do Kafka a partir do docker para efetuar uma rotina determinada de testes automazidas que ao seu final de execução, matará todos os containers executados.
