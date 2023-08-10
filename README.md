# Revisao para o Exame Amazon Certificação AWS Cloud Practitioner CLF-C01


## Conceitos de Cloud

### O que é _Cloud Computing?_

- Cloud computing é o fornecimento de recursos de computação, como servidores, armazenamento e serviços, através da internet, permitindo escalabilidade e pagamento conforme o uso.

***Vantagens***
- As vantagens do cloud computing incluem escalabilidade sob demanda, pagamento conforme o uso, flexibilidade na alocação de recursos, redundância e recuperação de dados aprimoradas, além de permitir o acesso remoto e colaboração eficiente.

###  Tipos de serviços em cloud computing
1. >***IaaS (Infraestrutura como Serviço)***: Fornecimento de recursos de infraestrutura virtual, como servidores, redes e armazenamento, permitindo controle e configuração detalhados.

1. >***PaaS (Plataforma como Serviço)***: Oferta de uma plataforma de desenvolvimento e implantação, incluindo ambiente de execução e ferramentas, simplificando a criação de aplicativos.

1. >***SaaS (Software como Serviço)***: Disponibilização de aplicativos de software pela internet, sem necessidade de instalação local, geralmente com pagamento por assinatura.

1. >***FaaS (Função como Serviço)***: Execução de funções individuais em resposta a eventos, permitindo desenvolvimento orientado a eventos sem gerenciar a infraestrutura.

1. >***CaaS (Contêiner como Serviço)***: Entrega de plataformas de contêiner, como Docker, para facilitar a implantação e gerenciamento de aplicativos em contêineres.

1. >***DaaS (Dados como Serviço)***: Fornecimento de acesso a serviços de gerenciamento e análise de dados através da nuvem, simplificando o processamento e análise de grandes conjuntos de dados.

1. >***MBaaS (Backend como Serviço)***: Oferecimento de serviços de back-end para aplicativos móveis, incluindo armazenamento de dados, autenticação e notificações.

### Modelos de implantação em cloud computing

1. >***Nuvem Pública***: Recursos são fornecidos por provedores de nuvem a várias organizações e usuários públicos através da internet. A infraestrutura é compartilhada e gerenciada pelo provedor.

1. >***Nuvem Privada***: Recursos são dedicados a uma única organização e geralmente hospedados em data centers internos ou em instalações de terceiros. Oferece maior controle sobre segurança e personalização.

1. >***Nuvem Híbrida***: Combinação de nuvem pública e privada, permitindo a migração de cargas de trabalho entre ambas. Proporciona flexibilidade para atender às necessidades variáveis de recursos e segurança.

1. >***Nuvem Comunitária***: Recursos são compartilhados por várias organizações com interesses e requisitos comuns, visando a colaboração e o compartilhamento de recursos de maneira mais restrita.


## Serviços dentro da AWS


1. >***Computação***:
    >> * Amazon EC2 (Elastic Compute Cloud): Máquinas virtuais escaláveis na nuvem.
    > 
    >> * AWS Lambda: Execução de código sem provisionamento de servidores.

1. >***Armazenamento***:
    >> * Amazon S3 (Simple Storage Service): Armazenamento de objetos escalável.
    > 
    >> * Amazon EBS (Elastic Block Store): Armazenamento persistente para instâncias EC2.

1. >***Banco de Dados***:
   >> * Amazon RDS (Relational Database Service): Bancos de dados relacionais gerenciados.
   >  
   >> * Amazon DynamoDB: Banco de dados NoSQL totalmente gerenciado.

1. >***Rede***:
   >> * Amazon VPC (Virtual Private Cloud): Rede isolada e personalizável.
   >  
   >> * Amazon CloudFront: CDN (Content Delivery Network) para distribuição de conteúdo.

1. >***Análise de Dados***:
   >> * Amazon Redshift: Data warehouse para análise de dados.
   >  
   >> * Amazon EMR (Elastic MapReduce): Processamento e análise de big data.

1. >***IA e Aprendizado de Máquina***:
   >> * Amazon SageMaker: Plataforma para desenvolvimento e implantação de modelos de ML.
   >  
   >> * Amazon Rekognition: Serviço de análise de imagem e vídeo.

1. >***Segurança***:
   >> * AWS IAM (Identity and Access Management): Gerenciamento de identidades e acesso.
   >  
   >> * AWS WAF (Web Application Firewall): Proteção de aplicativos web contra ameaças.

1. >***DevOps***:
   >> * AWS CodePipeline: Automação de pipelines de entrega contínua.
   >  
   >> * AWS CodeDeploy: Implantação automatizada de aplicativos.

1. >***Internet das Coisas (IoT)***:
   >> * AWS IoT Core: Plataforma para conectar dispositivos IoT à nuvem.
   >  
   >> * AWS IoT Greengrass: Extensão da nuvem para dispositivos IoT locais.

### As responsabilidades são divididas da seguinte forma

- >***AWS Responsibility (Responsabilidade da AWS):***
A AWS é responsável pela segurança da infraestrutura subjacente, como data centers, servidores físicos e redes globais.
Isso inclui a proteção física dos data centers, manutenção da disponibilidade da plataforma e serviços, e segurança dos serviços oferecidos.

- >***Customer Responsibility (Responsabilidade do Cliente):***
Os clientes são responsáveis pela segurança dos dados, configuração correta dos recursos e uso adequado dos serviços.
Isso inclui a configuração e gerenciamento de permissões de acesso, segurança de aplicativos e sistemas operacionais, proteção de dados e configurações de rede.

### Infraestrutura global da AWS

- A infraestrutura global da AWS (Amazon Web Services) é uma rede de data centers e recursos de computação distribuídos em todo o mundo, projetada para fornecer serviços em nuvem altamente disponíveis, escaláveis e confiáveis. Essa infraestrutura global permite que os clientes implantem seus aplicativos e serviços em regiões geográficas diversas, proporcionando benefícios como baixa latência, alta disponibilidade e recuperação de desastres.

1. >***Regiões***: São áreas geográficas distintas que contêm várias zonas de disponibilidade. Cada região é isolada para melhorar a resiliência em caso de problemas regionais.

1. >***Zonas de Disponibilidade***: São data centers isolados fisicamente dentro de uma região. Cada zona de disponibilidade é conectada por redes de baixa latência e alta largura de banda.

1. >***Data Centers***: Os data centers da AWS são construídos com foco em segurança, escalabilidade e eficiência energética. Eles são distribuídos globalmente para garantir a redundância e a capacidade de lidar com falhas.

1. >***Edge Locations***: São pontos de presença em cidades ao redor do mundo, usados para armazenar em cache conteúdo estático e acelerar a distribuição de conteúdo por meio da CDN (Content Delivery Network) da AWS, chamada CloudFront.

1. >***Rede Global***: A AWS opera uma rede global de alta capacidade que conecta suas regiões, zonas de disponibilidade e edge locations. Isso ajuda a garantir baixa latência e alta velocidade de transferência de dados.

1. >***Disponibilidade e Resiliência***: A infraestrutura global da AWS é projetada para oferecer alta disponibilidade e tolerância a falhas. Os serviços podem ser distribuídos em várias zonas de disponibilidade para aumentar a resiliência.

### Regiões da AWS

- A AWS (Amazon Web Services) opera diversas regiões geográficas ao redor do mundo, cada uma delas contendo várias zonas de disponibilidade. Cada região é um cluster de data centers que estão geograficamente próximos e conectados (por um raio max de 100km) por uma rede de alta velocidade.


- Cada região é projetada para ser independente, com suas próprias instâncias de serviços da AWS, e oferece alta disponibilidade. Dentro de cada região, as zonas de disponibilidade são separadas fisicamente, permitindo redundância e resiliência adicionais.

1. >***Américas***:
   >> Leste dos EUA (Norte da Virgínia)
   >
   >> Leste dos EUA (Ohio)
   >
   >> Oeste dos EUA (Norte da Califórnia)
   >
   >> Oeste dos EUA (Oregon)
   >
   >> Canadá (Central)

1. >***Europa***:
   >> UE (Irlanda)
   >
   >> UE (Londres)
   >
   >> UE (Frankfurt)
   >
   >> UE (Paris)
   >
   >> UE (Milão)

1. >***Ásia-Pacífico***:
   >> Ásia-Pacífico (Tóquio)
   >> Ásia-Pacífico (Cingapura)
   >
   >> Ásia-Pacífico (Sydney)
   >
   >> Ásia-Pacífico (Mumbai)
   >
   >> Ásia-Pacífico (Seul)
   >
   >> Ásia-Pacífico (Hong Kong)

1. >***América do Sul***:
   >> América do Sul (São Paulo)

1. >***África***:
   >> África (Cidade do Cabo)
   
###  Zonas de Disponibilidade

- As Zonas de Disponibilidade (Availability Zones) da AWS são unidades de infraestrutura isoladas e fisicamente separadas dentro de uma região. Cada Zona de Disponibilidade é projetada para ser altamente resiliente e independente, com sua própria infraestrutura de energia, resfriamento e rede. A ideia por trás das Zonas de Disponibilidade é fornecer aos clientes da AWS uma maneira de construir aplicativos altamente disponíveis e tolerantes a falhas, aproveitando a redundância entre as Zonas.

- >***Isolamento Físico***: Cada Zona de Disponibilidade é composta por um ou mais data centers separados, que são projetados para suportar falhas independentes. Isso garante que problemas em uma Zona não afetem as outras.

- >***Redundância***: Distribuir aplicativos ou recursos em várias Zonas de Disponibilidade oferece uma maior resiliência, pois mesmo que uma Zona de Disponibilidade sofra uma interrupção, os outros recursos podem continuar operando.

- >***Baixa Latência***: As Zonas de Disponibilidade dentro de uma região estão interconectadas por uma rede de alta velocidade e baixa latência, o que facilita a replicação de dados e a comunicação entre elas.

- >***Failover e Recuperação***: Ao projetar aplicativos em várias Zonas de Disponibilidade, é possível implementar estratégias de failover e recuperação de desastres para manter a disponibilidade do serviço em caso de falhas.

- >***Seleção de Zonas***: Ao implantar recursos na AWS, você pode escolher em qual Zona de Disponibilidade deseja provisionar esses recursos, ou permitir que a AWS escolha automaticamente a Zona mais adequada.

- >***SLA de Disponibilidade***: A AWS oferece um Service Level Agreement (SLA) de disponibilidade para cada região, com base nas Zonas de Disponibilidade, garantindo uma alta porcentagem de tempo de atividade para os serviços.


### Zonas Locais

- Zonas locais da AWS são um tipo de implantação de infraestrutura que coloca computação, armazenamento, banco de dados e outros serviços selecionados da AWS próximos a grandes centros populacionais e industriais.


### AWS Wavelength

- O AWS Wavelength é um serviço da AWS que estende a infraestrutura da AWS para as bordas das redes de telecomunicações. Ele permite que aplicativos e serviços sejam implantados diretamente nos pontos de presença de operadoras de telecomunicações, proporcionando baixa latência e alta conectividade para dispositivos móveis e usuários finais.


- O AWS Wavelength é uma solução que visa atender às crescentes demandas por baixa latência em aplicações modernas que dependem de interações em tempo real. Ele permite que as organizações aproveitem a escala e a flexibilidade da infraestrutura da AWS, ao mesmo tempo em que entregam uma experiência de usuário mais rápida e responsiva. 

**Principais características do AWS Wavelength**:

- >***Baixa Latência***: O AWS Wavelength coloca os recursos da AWS próximos aos locais onde os usuários finais ou dispositivos móveis estão, reduzindo significativamente a latência nas comunicações entre esses dispositivos e os serviços na nuvem.

- >***Implantação Direta***: O serviço permite que os aplicativos sejam implantados diretamente nos pontos de presença das operadoras, evitando a necessidade de rotear os dados para longe da rede de telecomunicações.

- >***Suporte a 5G***: O AWS Wavelength é projetado para funcionar com redes 5G, aproveitando as altas velocidades e a capacidade das redes móveis de próxima geração.

- >***Casos de Uso***: O AWS Wavelength é especialmente útil para aplicativos que requerem baixa latência, como jogos em nuvem, realidade aumentada/virtual, streaming de vídeo ao vivo, aplicações de IoT (Internet das Coisas) e muito mais.

- >***Parcerias com Operadoras***: A AWS colabora com várias operadoras de telecomunicações para disponibilizar o AWS Wavelength em seus pontos de presença, permitindo a integração direta entre a infraestrutura da AWS e a rede de telecomunicações.


### AWS Outspots

- Basicamente a AWS, colocando os equipamentos dela e as conexões rápidas dentro de data centers de terceiros, dentro de empresas que precisam isso ou dentro de locais que têm uma região de cobertura muito boa.


## IAM

- O AWS IAM (**_Identity and Access Management_**) é um serviço da Amazon Web Services que permite controlar quem pode acessar quais recursos na nuvem da AWS. Ele define permissões para usuários, grupos e papéis, garantindo a segurança e a conformidade dos dados e serviços na nuvem.

- >***Usuários***:
   >>Usuários são indivíduos ou processos que precisam acessar recursos na AWS.
   >
   >>Cada usuário tem credenciais únicas (nome de usuário e senha) para fazer login na conta da AWS.
   >
   >>As permissões são concedidas diretamente aos usuários para determinar o que eles podem fazer.

- >***Grupos***:
   >>Grupos são coleções de usuários que compartilham as mesmas permissões.
   >
   >>Em vez de atribuir permissões individualmente, você atribui políticas aos grupos, simplificando a administração.
   >
   >>Isso é útil para categorizar usuários com funções semelhantes e aplicar permissões consistentes.

- >***Roles***:
   >>Roles são usados para conceder permissões temporárias a entidades confiáveis.
   >
   >>São frequentemente usados por serviços ou aplicativos que precisam acessar recursos em nome deles, sem compartilhar credenciais.
   >
   >>Roles podem ser assumidos por serviços internos da AWS ou por serviços externos.

- >***Políticas***:
   >>Políticas são documentos JSON que definem as permissões.
   >
   >>Elas especificam quais ações são permitidas ou negadas em recursos específicos.
   >
   >>Políticas podem ser anexadas a usuários, grupos e papéis para controlar o acesso.


## EC2 -  _Elastic (Computing Cloud)²_ 

- Amazon EC2 (Elastic Compute Cloud) é um serviço de computação em nuvem oferecido pela AWS que permite provisionar e gerenciar servidores virtuais na nuvem. EC2 é um dos principais serviços da AWS e oferece uma forma escalável e flexível de executar cargas de trabalho em máquinas virtuais, conhecidas como "instâncias EC2".


***Principais características do Amazon EC2***:

1. >***Instâncias EC2***: São as unidades de processamento do Amazon EC2. Você pode escolher entre várias configurações de instâncias, como tamanho da CPU, quantidade de memória e armazenamento.

1. >***Escalabilidade***: As instâncias EC2 podem ser escaladas verticalmente (aumentando o tamanho) ou horizontalmente (adicionando mais instâncias) para lidar com variações de carga.

1. >***Seleção de Sistema Operacional***: Você pode escolher entre diversos sistemas operacionais, como Amazon Linux, Windows Server, Ubuntu, entre outros.

1. >***Tipos de Instância***: A AWS oferece diversos tipos de instâncias otimizados para diferentes casos de uso, como computação geral, memória intensiva, armazenamento otimizado e mais.

1. >***Opções de Armazenamento***: EC2 oferece opções de armazenamento variadas, incluindo armazenamento local, Amazon EBS (Elastic Block Store) e armazenamento em instâncias.

1. >***Segurança***: As instâncias EC2 podem ser isoladas em uma rede privada virtual (VPC), permitindo controle total sobre a rede e a segurança.

1. >***Opções de Preços***: EC2 oferece opções de preços flexíveis, incluindo instâncias sob demanda, reservadas e spot instances (ofertas de instâncias ociosas com preços mais baixos).

1. >***Recursos Avançados***: EC2 oferece recursos avançados, como Load Balancing (balanceamento de carga), Auto Scaling (escalabilidade automática) e Elastic IP (endereços IP estáticos).


***User Data***

- O _"User Data"_ (Dados do Usuário) é um conceito utilizado na EC2 e em outras instâncias de máquinas virtuais para automatizar tarefas de configuração durante a inicialização. Quando você inicia uma instância EC2, pode fornecer um script ou conjunto de comandos chamado _"User Data"_, que será executado automaticamente quando a instância for iniciada pela primeira vez.


***Principais pontos sobre _"User Data"_***

1. >***Automação de Configuração***: O _"User Data"_ permite automatizar a configuração da instância EC2 no momento da inicialização, sem a necessidade de intervenção manual.

1. >***Scripts e Comandos***: O _"User Data"_ normalmente consiste em scripts, comandos ou instruções em shell que são executados sequencialmente.

1. >***Exemplos de Uso***: O _"User Data"_ pode ser usado para instalar software, atualizar pacotes, configurar servidores web, baixar arquivos, configurar variáveis de ambiente, entre outros.

1. >***Ambientes Escaláveis***: O _"User Data"_ é especialmente útil em ambientes de Auto Scaling, onde novas instâncias são criadas ou substituídas conforme necessário.

1. >***Formatação de Dados***: Geralmente, o _"User Data"_ é fornecido em texto simples ou codificado em base64, dependendo da plataforma e das necessidades.

1. >***Exemplo Prático***: Um exemplo simples de uso seria fornecer um script que configura um servidor web Apache e hospeda um site específico assim que a instância EC2 é iniciada.


### AWS Batch

- O AWS Batch é um serviço da AWS que permite executar facilmente cargas de trabalho de processamento em lote na nuvem. Ele gerencia automaticamente a escalabilidade, o provisionamento de recursos e a execução de tarefas em lote, tornando mais eficiente o processamento de grandes volumes de dados.


- O AWS Batch é particularmente útil para cargas de trabalho que exigem processamento de dados em lote, como análises de big data, transformações de dados, renderização de vídeo, simulações e muito mais.



***Principais características do AWS Batch***:

1. >***Agendamento e Gerenciamento***: O AWS Batch permite agendar e gerenciar a execução de tarefas em lote, como processamento de dados, análises, transformações, entre outros.

1. >***Escalabilidade Automática***: O serviço ajusta automaticamente a quantidade de recursos necessários para executar as tarefas em lote, otimizando o desempenho e economizando custos.

1. >***Tarefas em Lote***: As tarefas em lote são unidades discretas de trabalho que podem ser processadas de forma independente, como contêineres Docker ou scripts.

1. >***Integração com Outros Serviços***: O AWS Batch se integra com outros serviços da AWS, como Amazon S3, Amazon DynamoDB e Amazon ECS (Elastic Container Service), para facilitar o processamento de dados.

1. >***Fila de Trabalho***: O AWS Batch utiliza uma fila de trabalho para agendar e gerenciar tarefas, permitindo a priorização e o controle sobre a execução.

1. >***Definição de Recursos***: Você pode definir os recursos necessários para suas tarefas, como a quantidade de CPU, memória e armazenamento.

1. >***Monitoramento e Logging***: O AWS Batch fornece métricas e registros para acompanhar o status e o desempenho das tarefas em lote.


### AWS LightSail

- O Amazon Lightsail é um serviço simplificado de computação em nuvem oferecido pela AWS. Ele é projetado para facilitar o processo de lançamento e gerenciamento de aplicativos e sites, especialmente para usuários que estão começando com a nuvem e não possuem experiência técnica avançada. O Lightsail oferece uma maneira fácil de iniciar rapidamente recursos de infraestrutura sem a complexidade de outros serviços da AWS.


- O Amazon Lightsail é uma opção popular para indivíduos, pequenas empresas e equipes de desenvolvimento que buscam uma maneira rápida e descomplicada de começar a usar a computação em nuvem da AWS. É uma escolha especialmente útil para projetos menores que não exigem toda a complexidade de configuração e gerenciamento que outros serviços da AWS oferecem.


***Principais características do Amazon Lightsail***:

1. >***Simplicidade***: O Lightsail oferece uma interface de usuário simples e intuitiva, tornando mais fácil a implantação de aplicativos e sites.

1. >***Opções Predefinidas***: Ele fornece planos predefinidos que incluem recursos como instâncias de máquinas virtuais, armazenamento em bloco, bancos de dados e serviços de rede.

1. >***Fácil Implantação***: Com apenas alguns cliques, você pode lançar aplicativos, sites ou bancos de dados preconfigurados.

1. >***Gerenciamento Simplificado***: O Lightsail automatiza tarefas de gerenciamento, como backups, monitoramento e escalabilidade, para reduzir a carga de trabalho.

1. >***Integração com Serviços AWS***: Embora seja simplificado, o Lightsail pode ser integrado a outros serviços da AWS, permitindo escalabilidade e expansão futura.

1. >***Precificação Transparente***: Os preços são fixos e previsíveis, o que facilita o planejamento financeiro.

1. >***Variedade de Aplicações***: O Lightsail pode ser usado para hospedar sites, blogs, aplicativos web, aplicativos móveis, entre outros.

1. >***Atualização para AWS***: Se suas necessidades crescerem, é possível migrar facilmente do Lightsail para outros serviços da AWS sem grandes mudanças na arquitetura.


### ECS 

- O Amazon Elastic Container Service (Amazon ECS) é um serviço de orquestração de contêineres oferecido pela AWS. Ele permite implantar, gerenciar e dimensionar aplicativos em contêineres Docker de maneira eficiente na nuvem. O ECS facilita a execução de aplicativos distribuídos e baseados em microserviços usando a tecnologia de contêineres.


- O Amazon ECS é adequado para arquiteturas de aplicativos baseados em contêineres, como microserviços, em que vários componentes podem ser implantados, gerenciados e dimensionados independentemente. Ele ajuda a simplificar o processo de implantação de contêineres, permitindo que os desenvolvedores se concentrem mais no código e menos na infraestrutura.

***Principais características do Amazon ECS***:

1. >***Contêineres Docker***: O ECS permite empacotar e executar aplicativos em contêineres Docker, proporcionando isolamento e portabilidade para suas cargas de trabalho.

1. >***Orquestração de Contêineres***: Ele automatiza a implantação e o gerenciamento de contêineres em clusters de máquinas virtuais EC2 (ou usando o serviço AWS Fargate).

1. >***Clusters***: Os clusters do ECS são grupos de instâncias EC2 (ou tarefas do Fargate) onde os contêineres são executados.

1. >***Tarefas e Serviços***: No ECS, você define tarefas que contêm uma ou mais definições de contêineres. Os serviços garantem que um número específico de tarefas esteja sempre em execução.

1. >***Integração com Outros Serviços***: O ECS integra-se a serviços como Amazon EC2, Amazon ECR (Elastic Container Registry), Amazon VPC (Virtual Private Cloud) e Amazon CloudWatch.

1. >***Escalabilidade***: O ECS facilita a escalabilidade horizontal de aplicativos, ajustando automaticamente o número de tarefas em execução.

1. >***Gerenciamento de Recursos***: Ele gerencia recursos de infraestrutura, como provisionamento, balanceamento de carga, monitoramento e escalabilidade.

1. >***Integração com Ferramentas***: O ECS trabalha bem com ferramentas populares de orquestração de contêineres, como Docker Compose e Kubernetes.


### ECS Cluster com Instâncias EC2

- Um ECS cluster é um grupo lógico de instâncias EC2 que são usadas para executar contêineres.


- Você precisa provisionar e gerenciar as instâncias EC2 por conta própria, incluindo escalabilidade, atualizações e segurança.


- O ECS permite que você configure um cluster usando instâncias EC2, onde os contêineres são implantados nas instâncias que compõem o cluster.


- Você tem controle total sobre o ambiente de hospedagem, incluindo personalizações de sistema operacional e configurações de rede.

### AWS Fargate

- O AWS Fargate é uma opção de execução para o ECS (e também para o Amazon EKS), que remove a necessidade de gerenciar instâncias EC2.


- Com o Fargate, você não precisa se preocupar com a infraestrutura subjacente. Em vez disso, a AWS cuida do provisionamento e da administração da infraestrutura.


- O Fargate permite que você defina tarefas (conjuntos de contêineres) e as execute sem precisar gerenciar as instâncias que as hospedam.


- Isso torna a execução de contêineres mais abstrata, focando apenas nos recursos de aplicativos em vez da infraestrutura.

### Resumo ECS

- Um ECS cluster é um grupo de instâncias EC2 que você gerencia manualmente para executar contêineres, enquanto o AWS Fargate é uma opção gerenciada pelo AWS que permite executar contêineres sem a necessidade de provisionar ou gerenciar instâncias EC2. A escolha entre essas opções depende das suas necessidades de controle sobre a infraestrutura e da preferência por abstrair ou gerenciar mais os recursos de hospedagem.