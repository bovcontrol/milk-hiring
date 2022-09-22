# Desafio para desenvolvedor backend


Olá dev, tudo bem?


A Bovcontrol tem como missão digitalizar a pecuária, trabalhamos coletando e analisando dados para assim aumentar a produtividade, eficiência e rentabilidade do agronegócio.


Para conseguir alcançar esse objetivo nos tornamos um time multidisciplinar, onde diferentes habilidade combinadas nos faz crescer para o futuro que almejamos.

Buscamos pessoas que sejam engajadas com nosso objetivo, que sejam criativas e àvidas por criar soluções que causam impacto na sociedade, desenvolvedores que vão além do código, que consigam entender as dores de nossos parceiros e que ajudem a pensar, desenvolver e implantar soluções.



## Como realizar o teste

Crie um repositório no seu Github e envie para ele a solução para o desafio proposto neste documento.


O teste deverá ser realizado usando Nodejs e MongoDB.


## Cenário do problema a ser solucionado

Considere o cenário onde há N fazendeiros que produzem leite e entregam sua produção para uma fábrica de processamento.

O objetivo neste cenário é ter um registro do volume de leite entregue e o preço recebido em cada mês por litro de leite, bem como o montante recebido para a produção mensal.

Para cada semestre do ano o preço do litro de leite é computado usando diferentes regras:


|Critério| Primeiro semestre - Jan a Jun | Segundo semestre - Jul a Dez |
|---|:---:|---|
|Preço base por litro| R$ 1,80| R$ 1,95|
|Custo por KM até 50KM| R$ 0,05 | |
|Custo por KM acima de 50KM| R$ 0,06 | |
|Bônus p/ produção acima de 10.000 L| |R$ 0,01|

A regra para computar o preço do litro de leite é:

Preço = (Volume do mês * Preço base) - (Custo por KM * distância da fazenda até a fábrica) + (Bônus p/ produção * litros entregues no mês)

Considerando as regras descritas, crie uma API com os seguintes recursos:
- cadastro de fazenda e fazendeiro;
- cadastro da produção de leite diário, em litros;
- consulta do volume de leite entregue para cada dia e a média mensal, dado um fazendeiro e um mês de parâmetro;
- consulta do preço do litro de leite pago ao fazendeiro, dado um código de fazendeiro e um mês de parâmetro. Apresentar o preço no formato numérico brasileiro e inglês;
- consulta do preço do litro de leite pago para cada mês do ano, dado um fazendeiro e um ano de parâmetro. Apresentar o preço no formato numérico brasileiro e inglês;



## O que iremos avaliar

O objetivo do teste é permitir que possamos conhecer um pouco sobre suas habilidades técnicas de desenvolvimento, como o conhecimento e aplicação de conceitos que vão além da codificação, como organização da aplicação em camadas de responsabildade, escalabilidade e manuntenibilidade.

Critérios específicos que iremos avaliar:

- nível de conhecimento da linguagem;
- aplicação de conceitos de orientação a objetos (herança, polimorfismo, composição, encapsulamento);
- aplicação de conceitos de padrões de projeto (criação, estrutura e comportamento);
- aplicação de conceitos de API REST;
- qualidade do código; Esperamos código sem/ou baixo acoplamento, alta coesão, nomes de classes, métodos e funções claros e condizentes com o que representem ou realizam;
- separação em camadas da aplicação; Esperamos visualizar as camadas da aplicação de forma bem definida (requisição, validação, controllers, dto, caso de uso, entidades, objetos de valor, serviços de domínio, serviços de aplicação, repositório, infraestrutura, etc);
- escalabilidade do projeto;
- manutenibilidade (facilidade de adição de novos recursos, alteração nos que existem, facilidade de depuração, testes);
- estrutura de dados;

## Dúvidas

Caso tenha dúvidas sobre o entendimento do problema, não hesite em perguntar, é importante que o cenário esteja claro em sua mente antes de resolvê-lo.

Iremos te ajudar a entender o problema sempre que precisar, só precisa perguntar :).
