# Infraestrutura Local vs AWS

Muitos serviços da AWS têm análogos no espaço e na terminologia tradicionais 
de TI. Essa comparação lado a lado mostra como os produtos e os serviços da 
AWS se relacionam com uma infraestrutura tradicional. Quase tudo o que você 
quer fazer com um data center tradicional está disponível na AWS.
Legenda:
•
ACL (ACLs)
•
Amazon Elastic Block Store (Amazon EBS)
•
Amazon Elastic File Store (Amazon EFS)
•
Imagem de máquina da Amazon (Amazon Machine Image, AMI)
•
Amazon Relational Database Service (Amazon RDS)
•
Amazon Simple Storage Service (Amazon S3)
•
AWS Identity and Access Management (IAM)
•
Armazenamento de conexão direta (Direct
-
attached storage, DAS)
•
Listas de controle de acesso à rede (Network access control lists, ACLs)
•
Armazenamento conectado à rede (Network
-
attached storage, NAS)
•
Sistema de gerenciamento de banco de dados relacional (Relational 
database management system, RDBMS)

Rede de área de armazenamento  (Storage area network, SAN)

## O que são Serviços Web?

Um serviço web é qualquer software disponibilizado pela Internet ou em redes 
privadas (intranet). Um serviço web usa um formato padronizado para 
solicitação e resposta de uma interação de interface de programação de 
aplicativo (API). Por exemplo, podem ser usados formatos como Extensible 
Markup Language (XML) ou JavaScript Object Notation (JSON). Não está 
vinculado a nenhum sistema operacional ou linguagem de programação. Um 
serviço web é autodescrito por meio de um arquivo de definição de interface e 
é detectável.

## O que é a AWS?

A AWS é um provedor de serviços de nuvem seguro que oferece diversos 
serviços para ajudar as empresas a dimensionar e a crescer. Esses produtos são 
entregues por meio da Internet. Dessa forma, você tem acesso sob demanda a 
recursos de computação, armazenamento, rede, banco de dados e outros 
recursos de TI necessários para seus projetos. Você também tem as 
ferramentas para gerenciá
-
los.
Os serviços da AWS se enquadram em diferentes categorias, e cada categoria 
contém um ou mais serviços. É possível selecionar os serviços que deseja nessas 
diferentes categorias para criar suas soluções.
Legenda:
•
Realidade aumentada (AR)
•
Realidade virtual (VR)

## Solução Simples

Por exemplo, suponha que você está construindo um aplicativo de banco de 
dados. Seus clientes podem estar enviando dados para suas instâncias do 
Amazon Elastic Compute Cloud (Amazon EC2), que é um serviço da categoria 
Computação
. Esses servidores do EC2 fazem lote dos dados em incrementos de 
1 minuto. Eles adicionam um objeto por cliente ao Amazon Simple Storage 
Service (Amazon S3), o serviço de armazenamento da AWS que você escolheu 
usar. É possível usar um banco de dados não relacional, como o Amazon 
DynamoDB, para alimentar o aplicativo. Por exemplo, é possível usá
-
lo para 
construir um índice para encontrar todos os objetos, de um cliente específico, 
que foram coletados em um período específico. É possível executar esses 
serviços em uma Amazon Virtual Private Cloud (Amazon VPC), que é um serviço 
da categoria de Redes.
Esse exemplo simples mostra que é possível selecionar serviços web de 
diferentes categorias e usá
-
los em conjunto para construir uma solução. (Nesse 
caso, a solução é um aplicativo de banco de dados.) Entretanto, as soluções que 
você constrói também podem ser bastante complexas.

## Serviços AWS

O serviço que você selecionar depende dos seus objetivos empresariais e dos 
requisitos de tecnologia. No exemplo anterior, a solução usou o Amazon EC2 
como serviço de Computação. Entretanto, o Amazon EC2 é apenas um dos 
muitos serviços de computação que a AWS oferece. Veja a seguir algumas 
outras ofertas de Computação da AWS que podem ser selecionadas para uso 
nos exemplos de casos de uso:
•
Amazon EC2
: você quer ter controle total sobre seus recursos de 
computação da AWS.
•
AWS Lambda
: você quer executar seu código e não gerenciar ou provisionar 
servidores.
•
AWS Elastic Beanstalk
: você quer um serviço que implante, gerencie e 
dimensione aplicativos web para você.
•
Amazon Lightsail
: você precisa de uma plataforma em nuvem leve para um 
aplicativo web simples. 
•
AWS Batch
: você precisa executar centenas de milhares de cargas de 
trabalho em lote.
•
AWS Outposts
: você quer executar a infraestrutura da AWS em seu data 
center no local.
•
Amazon Elastic Container Service
(Amazon ECS), 
Amazon Elastic Kubernetes 
Service
(Amazon EKS) ou 
AWS Fargate
: você quer implementar uma 
arquitetura de microsserviços ou de contêineres

## Escolher um Serviço

O serviço que você selecionar depende dos seus objetivos empresariais e dos 
requisitos de tecnologia. No exemplo anterior, a solução usou o Amazon EC2 
como serviço de Computação. Entretanto, o Amazon EC2 é apenas um dos 
muitos serviços de computação que a AWS oferece. Veja a seguir algumas 
outras ofertas de Computação da AWS que podem ser selecionadas para uso 
nos exemplos de casos de uso:
•
Amazon EC2
: você quer ter controle total sobre seus recursos de 
computação da AWS.
•
AWS Lambda
: você quer executar seu código e não gerenciar ou provisionar 
servidores.
•
AWS Elastic Beanstalk
: você quer um serviço que implante, gerencie e 
dimensione aplicativos web para você.
•
Amazon Lightsail
: você precisa de uma plataforma em nuvem leve para um 
aplicativo web simples. 
•
AWS Batch
: você precisa executar centenas de milhares de cargas de 
trabalho em lote.
•
AWS Outposts
: você quer executar a infraestrutura da AWS em seu data 
center no local.
•
Amazon Elastic Container Service
(Amazon ECS), 
Amazon Elastic Kubernetes 
Service
(Amazon EKS) ou 
AWS Fargate
: você quer implementar uma 
arquitetura de microsserviços ou de contêineres

•
VMware Cloud on AWS
: você tem uma plataforma de virtualização de 
servidor no local e quer migrá
-
la para a AWS

## Serviços mais usados

A variedade de serviços da AWS pode ser intimidadora no início da jornada para 
a nuvem. Esse curso se concentra em alguns dos serviços mais comuns em 
categorias específicas. As categorias de serviço incluem: Computação; 
Armazenamento; Banco de dados; Redes e entrega de conteúdo; Segurança, 
identidade e conformidade; Gerenciamento e governança; e Gerenciamento de 
custos da AWS

## Como interagir com a AWS?

Você pode estar se perguntando como acessar a ampla variedade de serviços 
oferecidos pela AWS. É possível criar e gerenciar recursos na nuvem AWS de 
três maneiras:
•
Console de gerenciamento da AWS: o console é uma interface gráfica 
avançada para a maioria dos recursos que a AWS oferece. (Observação: 
ocasionalmente, os recursos novos ainda não têm todas as capacidades 
incluídas no console na data de lançamento inicial.) Para acesso móvel, é 
possível usar o aplicativo móvel AWS Console para visualizar rapidamente os 
recursos da AWS a qualquer momento, em qualquer lugar.
•
AWS Command Line Interface (AWS CLI): a AWS CLI oferece um conjunto de 
utilitários que podem ser iniciados a partir de um script de comandos no 
Linux, macOS ou Microsoft Windows.
•
Kits de Desenvolvimento de Software (SDKs): a AWS oferece pacotes que 
permitem acessar a AWS em várias linguagens de programação populares. 
Esses pacotes facilitam o uso da AWS em aplicativos existentes. Eles 
também permitem criar aplicativos que implantam e monitoram sistemas 
complexos inteiramente por meio de código.

## AWS Cloud Adoption Framework (AWS CAF)

A jornada de adoção da nuvem de cada organização é única. Entretanto, para 
qualquer organização migrar o portfólio de TI para a nuvem com êxito, três 
elementos 
–
pessoas, processos e tecnologia 
–
devem estar alinhados. O AWS 
Cloud Adoption Framework (AWS CAF) ajuda as organizações a desenvolver 
planos eficientes e eficazes para a jornada de adoção da nuvem.
A orientação e as práticas recomendadas para a estrutura ajudam você a 
construir uma abordagem abrangente para lidar com a computação em nuvem 
na sua organização e em todo o ciclo de vida da TI. Essas diretrizes ajudam 
cada unidade da sua organização a atualizar habilidades, adaptar processos 
existentes e introduzir processos novos. Dessa forma, é possível aproveitar ao 
máximo os serviços oferecidos pela computação em nuvem. 
O AWS CAF divide o processo complexo de planejamento de uma migração 
para a nuvem em partes gerenciáveis denominadas 
perspectives  (perspectivas)
. 
Essas perspectivas representam áreas essenciais de foco que abrangem 
pessoas, processos e tecnologia. Em geral, as perspectivas de negócios, pessoas 
e governança se concentram nas capacidades do negócio. As perspectivas de 
plataforma, segurança e operações se concentram em recursos técnicos.

---

# Conclusões da Aula

<div align=center>
    <img src="assets/img/conclusao-01.png">
</div>

Exemplos das principais conclusões dessa lição:
•
A AWS é um provedor de serviços de nuvem. A AWS oferece um amplo 
conjunto de produtos globais baseados na nuvem, chamados de 
serviços
, 
projetados para trabalhar em conjunto.
•
A AWS oferece inúmeras categorias de serviços, e cada categoria tem muitos 
serviços para escolher.
•
Escolha um serviço com base em seus objetivos empresariais e requisitos de 
tecnologia.
•
É possível interagir com os serviços da AWS de três maneiras diferentes.
•
Use a Documentação da AWS como seu principal recurso para obter ajuda.