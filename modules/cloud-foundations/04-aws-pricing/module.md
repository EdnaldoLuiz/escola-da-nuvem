# Modelo de Preço da AWS

Há três fatores fundamentais de custo com a AWS: computação, armazenamento e transferência de dados de saída. Essas características variam um pouco dependendo do produto da AWS e do modelo de preço escolhidos. Na maioria dos casos, você não será cobrado pela transferência de dados de entrada ou pela transferência de dados entre outros serviços da AWS na mesma Região da AWS. No entanto, é importante verificar as taxas de transferência de dados antes de começar a usar o serviço da AWS. A transferência de dados de saída é agregada entre serviços e cobrada de acordo com a taxa de transferência de dados de saída. Essa cobrança é exibida no relatório mensal como "Transferência de dados para fora da AWS".

## Como Você Paga pela AWS?

A filosofia subjacente ao modelo de preço da AWS é pagar pelo que usar. Ao final de cada mês, você paga pelo que realmente consumiu. É possível iniciar ou parar de usar um produto a qualquer momento, sem a necessidade de contratos de longo prazo. A AWS oferece diversos serviços de computação em nuvem, onde você paga exatamente pela quantidade de recursos que utiliza. Esse modelo de preço por estilo de consumo inclui:

- **Pagamento Conforme o Uso**
  - Com a AWS, você paga apenas pelos serviços consumidos, sem grandes despesas iniciais. Isso elimina a necessidade de investir recursos caros em infraestrutura dispendiosa, como compra de servidores, licenças de software ou aluguel de instalações.

- **Pague Menos ao Fazer Reserva**
  - Para serviços como Amazon EC2 e Amazon RDS, é possível investir em capacidade reservada e economizar significativamente em relação à capacidade sob demanda equivalente. As instâncias reservadas estão disponíveis em três opções para maximizar suas economias.

- **Pague Menos Usando Mais**
  - Com a AWS, você obtém descontos com base no volume, beneficiando-se de economias substanciais à medida que a utilização aumenta. Alguns serviços, como o Amazon S3, oferecem preços em camadas, onde você paga menos por GB à medida que usa mais.

## Nível Gratuito AWS

A AWS oferece um nível gratuito para novos clientes por até um ano. Esse nível gratuito é aplicável a serviços específicos, permitindo experimentar e usar os serviços da AWS com limites de uso gratuitos.

## Calculadora AWS

A calculadora de preço da AWS é uma ferramenta útil para estimar a fatura mensal da AWS. Com ela, é possível adicionar, modificar e remover serviços para recalcular automaticamente as cobranças mensais estimadas. A calculadora incorpora uma ampla variedade de cálculos de preço em todos os serviços e Regiões da AWS, oferecendo estimativas detalhadas e exemplos de uso comum.

## Local vs. Nuvem

A comparação entre uma infraestrutura no local e em nuvem envolve como essas opções são implantadas e gerenciadas. A infraestrutura no local requer investimentos significativos em hardware, instalações e equipe de manutenção, enquanto a nuvem oferece pagamento conforme o uso, facilidade de escalabilidade e previsibilidade nos custos.

## Considerações sobre o TCO

O custo total de propriedade (TCO) é uma métrica importante para comparar soluções de nuvem e no local. Com a nuvem, a maioria dos custos é inicial e transparente, facilitando a comparação de custos e a tomada de decisão sobre a melhor opção de implantação.

# Conclusões da Aula

<div align=center>
    <img src="assets/img/conclusao-01.png">
</div>

Resumindo, embora o número e os tipos de serviços oferecidos pela AWS tenham aumentado, a nossa filosofia de preço não mudou. No final de cada mês, você paga apenas pelo que usar e pode começar ou parar de usar um produto a qualquer momento, sem a necessidade de contratos de longo prazo.

A melhor maneira de estimar os custos é analisar as características fundamentais de cada serviço da AWS, estimar o uso de cada característica e mapear esse uso para os preços publicados no site. A estratégia de modelo de preço do serviço oferece a flexibilidade de escolher os serviços necessários para cada projeto e pagar apenas pelo que usar. É possível usar a calculadora de preço da AWS para obter estimativas de custo de serviços da AWS e avaliar o total de uma solução da AWS, respectivamente.

Alguns serviços da AWS não incorrem em cobranças, incluindo:

- Amazon VPC
- AWS Elastic Beanstalk
- AWS CloudFormation
- IAM
- Amazon EC2 Auto Scaling
- AWS OpsWorks
- Cobrança consolidada

Embora os serviços não incorram em cobranças, os recursos que eles provisionam não são gratuitos. Além disso, você não é cobrado pela transferência de dados de entrada ou entre serviços na mesma Região. No entanto, os custos de transferência de dados de saída são definidos em camadas.