# DesafioConstruindoEsqConceitualDoZero
 Desafio de projeto realizado durante o 'Bootcamp Database Experience', oferecido pela plataforma Digital Innovation One (DIO), em Agosto/2022. O desafio propõe a criação um projeto conceitual de banco de dados, no modelo diagrama entidade-relacionamento estendido, para representar o sistema de controle e gerenciamento de ordens de serviço de uma oficina mecânica.

#### Explicando Soluções
Cada cliente se relaciona com apenas um veículo, e cada veículo se relaciona com uma ordem de serviço. Cada ordem de serviço pode se relacionar com uma ou mais peças; e cada peça pode se relacionar com uma ou mais ordens de serviço. Da mesma forma, um serviço pode estar relacionado a uma ou mais ordens de serviço; e uma ordem de serviço pode estar relacionada (pode conter) mais de um serviço.

Um mecânico pode se relacionar com um ou mais serviços; e um serviço pode ser relacionar com um ou mais mecânicos. A relação entre serviço e mecânico cria uma equipe. Uso o idServiço para inferir qual equipe emitiu e realizou a ordem de serviço, pois o relacionamento Equipe guarda o idServiço e o idMecanico.