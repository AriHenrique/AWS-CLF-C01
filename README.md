# Revisao para o Exame Amazon Certificação AWS Cloud Practitioner CLF-C01

### O que é _Cloud Computing?_

- Cloud computing é o fornecimento de recursos de computação, como servidores, armazenamento e serviços, através da internet, permitindo escalabilidade e pagamento conforme o uso.

### Vantagens
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


### Serviços dentro da AWS


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

- As Zonas de Disponibilidade (Availability Zones) da Amazon Web Services (AWS) são unidades de infraestrutura isoladas e fisicamente separadas dentro de uma região. Cada Zona de Disponibilidade é projetada para ser altamente resiliente e independente, com sua própria infraestrutura de energia, resfriamento e rede. A ideia por trás das Zonas de Disponibilidade é fornecer aos clientes da AWS uma maneira de construir aplicativos altamente disponíveis e tolerantes a falhas, aproveitando a redundância entre as Zonas.

- >***Isolamento Físico***: Cada Zona de Disponibilidade é composta por um ou mais data centers separados, que são projetados para suportar falhas independentes. Isso garante que problemas em uma Zona não afetem as outras.

- >***Redundância***: Distribuir aplicativos ou recursos em várias Zonas de Disponibilidade oferece uma maior resiliência, pois mesmo que uma Zona de Disponibilidade sofra uma interrupção, os outros recursos podem continuar operando.

- >***Baixa Latência***: As Zonas de Disponibilidade dentro de uma região estão interconectadas por uma rede de alta velocidade e baixa latência, o que facilita a replicação de dados e a comunicação entre elas.

- >***Failover e Recuperação***: Ao projetar aplicativos em várias Zonas de Disponibilidade, é possível implementar estratégias de failover e recuperação de desastres para manter a disponibilidade do serviço em caso de falhas.

- >***Seleção de Zonas***: Ao implantar recursos na AWS, você pode escolher em qual Zona de Disponibilidade deseja provisionar esses recursos, ou permitir que a AWS escolha automaticamente a Zona mais adequada.

- >***SLA de Disponibilidade***: A AWS oferece um Service Level Agreement (SLA) de disponibilidade para cada região, com base nas Zonas de Disponibilidade, garantindo uma alta porcentagem de tempo de atividade para os serviços.


### Zonas Locais

- Zonas locais da AWS são um tipo de implantação de infraestrutura que coloca computação, armazenamento, banco de dados e outros serviços selecionados da AWS próximos a grandes centros populacionais e industriais.


### AWS Wavelength

- O AWS Wavelength é um serviço da Amazon Web Services (AWS) que estende a infraestrutura da AWS para as bordas das redes de telecomunicações. Ele permite que aplicativos e serviços sejam implantados diretamente nos pontos de presença de operadoras de telecomunicações, proporcionando baixa latência e alta conectividade para dispositivos móveis e usuários finais.


- O AWS Wavelength é uma solução que visa atender às crescentes demandas por baixa latência em aplicações modernas que dependem de interações em tempo real. Ele permite que as organizações aproveitem a escala e a flexibilidade da infraestrutura da AWS, ao mesmo tempo em que entregam uma experiência de usuário mais rápida e responsiva. 

**Principais características do AWS Wavelength**:

- >***Baixa Latência***: O AWS Wavelength coloca os recursos da AWS próximos aos locais onde os usuários finais ou dispositivos móveis estão, reduzindo significativamente a latência nas comunicações entre esses dispositivos e os serviços na nuvem.

- >***Implantação Direta***: O serviço permite que os aplicativos sejam implantados diretamente nos pontos de presença das operadoras, evitando a necessidade de rotear os dados para longe da rede de telecomunicações.

- >***Suporte a 5G***: O AWS Wavelength é projetado para funcionar com redes 5G, aproveitando as altas velocidades e a capacidade das redes móveis de próxima geração.

- >***Casos de Uso***: O AWS Wavelength é especialmente útil para aplicativos que requerem baixa latência, como jogos em nuvem, realidade aumentada/virtual, streaming de vídeo ao vivo, aplicações de IoT (Internet das Coisas) e muito mais.

- >***Parcerias com Operadoras***: A AWS colabora com várias operadoras de telecomunicações para disponibilizar o AWS Wavelength em seus pontos de presença, permitindo a integração direta entre a infraestrutura da AWS e a rede de telecomunicações.


### AWS Outspots

- Basicamente a AWS, colocando os equipamentos dela e as conexões rápidas dentro de data centers de terceiros, dentro de empresas que precisam isso ou dentro de locais que têm uma região de cobertura muito boa.
