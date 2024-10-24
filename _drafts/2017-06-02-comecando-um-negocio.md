---
layout: post
published: false
mathjax: false
featured: false
comments: false
imagefeature: penguin.jpg
title: Coloque o pé na água antes de mergulhar
headline: >-
  Teste o seu mercado antes de qualquer coisa. Mas teste de verdade. Isto irá
  lhe poupar tempo e dinheiro. 
description: Começando um negócio
modified: '2017-06-03'
categories: personal
---
Esta deve ser a orientação mais importante que todo empreendedor de primeira viagem escuta de pessoas mais experientes; e também é a mais mal compreendida. Afinal, parece meio obvio. "Antes de dedicar meu tempo e dinheiro a um empreendimento é obvio que devo verificar, da melhor forma que conseguir, quais são as chances de sucesso dessa empreitada". Ainda assim é comum que o empreendedor de primeira viagem leve mais tempo que o desejado para entender em profundidade o que isto significa.

Na [AulaViva](https://aulvaviva.com.br) não foi diferente. E olha que eu e o Marcelo somos bastante cuidadosos. Para minimizar problemas decidimos seguir o livro [*The Startup Owner's Manual*](https://www.amazon.com/Startup-Owners-Manual-Step-Step-ebook/dp/B009UMTMKS/ref=tmm_kin_swatch_0?_encoding=UTF8&qid=1496616813&sr=8-1), do Steve Blank. Esse cara é fera. Ele é o criador do *Customer Development*, metodologia para a criação de startups e novos empreendimentos, que é ensinada nas maiores universidades americanas e seguida por boa parte das startups do vale do silício. Esta metodologia surgiu como alternativa ao método tradicional de desenvolvimento de novos produtos, mais adequado a situações em que o modelo de negócios é desconhecido. Aliás esta é a regra quando se trata de Startups. E não poderia ser diferente, já que esta é própria definição de startup, *uma organização temporária projetada para **buscar** um modelo de negócios repetível e escalável*. Se tiver interesse no livro, recomendo o e-book em inglês, que além de mais barato, está livre dos diversos erros de tradução para o Português que chegam a comprometer o entendimento da versão traduzida.

Voltando ao assunto, é de suma importância para seu sucesso que você valide o problema que se propõe a resolver e a solução proposta pela sua startup. Isto irá evitar que se gaste tempo e dinheiro desenvolvendo algo que não tem mercado ou que não resolve o problema da forma correta. Isto parece bem simples no papel, mas na hora de colocar em prática certamente várias dúvidas surgirão. Como fazer essa validação? Que história é essa de validar as hipóteses através de experimentos? O que são esses experimentos? Como interpretar os resultados? Um resultado negativo significa que algo deve ser alterado no modelo de negócios, mas o que? Existe a possibilidade do experimento ter sido mal elaborado ou mal executado e o do resultado ser um falso negativo?

Seguindo a metodologia *Custumer Development*, citada acima, podemos dividir as empresas em quatro quadrantes. Num dos eixos temos o tipo do produto: físico e não-físico (software, ações, seguro, serviços, etc). No outro eixo temos o tipo do canal de vendas: físico e digital (web, dispositivo móvel). Neste momento você pode estar se perguntando: mas o que isto tem a ver com o assunto do post? Tem tudo a ver! Na medida em que seu canal de vendas e seu produto deixam de ser físicos, a forma de validar seu problema/solução mudam. Você pode obter feedback de potenciais clientes rapidamente e tem a oportunidade de se adaptar com agilidade. E nestas circunstâncias é bom que você seja ágil. Seu concorrentes serão... Isto também permitirá que você entenda seus clientes a um custo mais baixo que aquele necessário a empresas totalmente físicas.

Para ser objetivo e prático, irei focar em empresas com produtos não-físicos e canal de vendas digital. Isto me permitirá mostrar na prática como validar o problema utilizando um hotsite

Já as validações bem sucedidas trazem conforto e a certeza de estar no caminho certo. Mas é justamente aí que está o perigo! Novamente pode haver algum problema com o experimento. E o problema mais comum é confundir manifestações de interesse em sua ideia com fit de mercado. E isto é bastante tentador na fase inicial de uma startup, pois o que mais se quer é a confirmação das hipóteses sobre os clientes para iniciar o desenvolvimento e vendas. O que acaba passando despercebido é que a única validação que realmente importa é um potencial cliente colocar a mão no bolso para adquirir o que você oferece.

Antes disso acontecer, diversos motivos podem impedir que a venda se concretize. Por exemplo, o problema que você se propõe a resolver pode não ser prioritário para o potencial cliente, o custo total de aquisição e implantação do seu produto pode não estar previsto no orçamento da empresa com a qual você está negociando, a adoção do seu produto pela empresa pode exigir uma ligeira mudança de cultura o que normalmente gera insegurança por parte dos envolvidos, a situação econômica do país pode não estar favorável a investimentos, a manifestação de interesse no seu produto pode ser um falso positivo causado pelo desconforto do brasileiro em desagradar, etc.

E como fazer então? Você precisa testar se o problema que sua empresa se propõe a resolver bem como a solução adotada são suficientemente importantes para fazer seu cliente colocar a mão no bolso. Para lhe ajudar nesta empreitada irei lhe ensinar, num próximo artigo, a fazer um hotsite utilizando o Jekyll. Você irá utilizar o hotsite para apresentar pela primeira vez sua proposta de valor para potenciais clientes e verificar se eles se importam suficientemente com isto a ponto de você seguir a diante.

Mas não basta apenas ter o hotsite. Você precisa hospedá-lo em algum lugar, trazer potencias clientes até ele e gerar dados que te permitam saber se sua proposta de valor foi bem aceita. Por isto irei lhe ensinar a hospedá-lo no [S3](https://aws.amazon.com/pt/s3/) da Amazon, a fazer o SEO - *search engine optimization*, configurá-lo para ter alta disponibilidade usando [CloudFront](https://aws.amazon.com/pt/cloudfront/) da Amazon e a configurar https e cache usando o [CloudFlare](https://www.cloudflare.com/br/). Com estas ferramentas você poderá fazer um MVP low-fidelity para testar suas hipóteses e verificar se a sua grande ideia de negócios tem futuro como está ou se vai precisar de adaptações. Fique ligado!

MVP -> teste de hipóteses
low-fidelity
high-fidelity

Exemplo: Feedback de clientes de salão de cabelereiro

Conversa: Maior problema: retenção de clientes -> falta de feedback negativo

Solução: App para feedback do cliente.

Hipótese 1:

Hipótese 1: Havendo oportunidade o cliente do salão dará feedback espontaneamente
Experimento 1: Formulário em papel para preenchimento pelo cliente disponível na recepção (MVP low-fidelity)
