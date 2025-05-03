# Relatório sobre Computação em Nuvem: Conceitos, Características, Produtos e Custos (com foco no AZ-900)
A computação em nuvem revolucionou a forma como empresas e indivíduos acessam e utilizam recursos de tecnologia da informação (TI). Em vez de manter infraestruturas físicas complexas e dispendiosas, a nuvem oferece a capacidade de acessar serviços de computação – como poder de processamento, armazenamento, bancos de dados, software e redes – sob demanda, através da internet. Este relatório explora os conceitos básicos, características, produtos e tipos de custos da computação em nuvem, utilizando o exame AZ-900 (Microsoft Azure Fundamentals) como referência para ilustrar esses pontos.

## Conceitos Básicos da Computação em Nuvem
No cerne da computação em nuvem está a ideia de compartilhamento de recursos computacionais em uma rede. Em vez de cada organização possuir e gerenciar seus próprios servidores e data centers, um provedor de nuvem possui e mantém essa infraestrutura em grande escala. Os clientes, por sua vez, pagam apenas pelos recursos que consomem, em um modelo de pagamento por uso.

# Alguns conceitos fundamentais incluem:

Servidores: Poderosos computadores físicos localizados nos data centers do provedor de nuvem, responsáveis por executar as aplicações e armazenar os dados dos clientes.
Virtualização: Tecnologia que permite criar versões virtuais de recursos de hardware (como servidores, armazenamento e redes), possibilitando o compartilhamento eficiente da infraestrutura física entre múltiplos clientes.
Data Centers: Instalações físicas seguras e altamente disponíveis onde os servidores e outros equipamentos de computação em nuvem estão localizados.
Rede: A conectividade via internet é essencial para acessar os serviços de nuvem. A rede garante a comunicação entre os clientes e a infraestrutura do provedor.
Características Essenciais da Computação em Nuvem
A computação em nuvem possui diversas características distintivas que a tornam atraente para usuários e organizações:

Sob Demanda (On-demand Self-service): Os usuários podem provisionar recursos de computação (como servidores e armazenamento) de forma autônoma e em tempo real, sem a necessidade de interação humana com o provedor de serviços.
Amplo Acesso à Rede (Broad Network Access): Os serviços de nuvem estão acessíveis através de uma rede (geralmente a internet) utilizando diversos dispositivos, como laptops, tablets e smartphones.
Pool de Recursos (Resource Pooling): Os recursos de computação do provedor são agrupados para atender a múltiplos consumidores utilizando um modelo multi-inquilino, com recursos dinamicamente alocados e realocados de acordo com a demanda.
Elasticidade Rápida (Rapid Elasticity): A capacidade de provisionar e liberar recursos de forma elástica, tanto para cima (escalar verticalmente ou horizontalmente) quanto para baixo, de acordo com a demanda. Isso oferece grande flexibilidade e otimiza custos.
Serviço Medido (Measured Service): O uso dos recursos é monitorado, controlado e reportado, proporcionando transparência e permitindo que os clientes paguem apenas pelo que consomem.
Produtos e Serviços de Computação em Nuvem (Exemplos do Azure AZ-900)
Os provedores de nuvem oferecem uma vasta gama de produtos e serviços categorizados em diferentes modelos de serviço:

Infraestrutura como Serviço (IaaS): Fornece recursos computacionais fundamentais, como máquinas virtuais, armazenamento, redes e sistemas operacionais. O cliente tem controle sobre o sistema operacional, armazenamento e aplicações, mas não gerencia a infraestrutura física subjacente.
Exemplos no Azure: Máquinas Virtuais (Virtual Machines), Rede Virtual (Virtual Network), Armazenamento (Storage Accounts).
Plataforma como Serviço (PaaS): Oferece um ambiente para desenvolvimento, execução e gerenciamento de aplicações. O provedor gerencia a infraestrutura (servidores, armazenamento, redes) e o cliente se concentra no desenvolvimento e gerenciamento de suas aplicações.
Exemplos no Azure: Serviço de Aplicativo (App Service), Azure SQL Database, Azure Kubernetes Service (AKS).
Software como Serviço (SaaS): Fornece aplicações de software prontas para uso, acessíveis através da internet. O provedor gerencia toda a infraestrutura e o software, e o cliente simplesmente utiliza a aplicação.
Exemplos no Azure (e em geral): Microsoft 365, Dynamics 365.
Além desses modelos principais, existem outros serviços importantes, como:

Computação sem Servidor (Serverless Computing): Permite executar código sem a necessidade de gerenciar servidores. O provedor gerencia a infraestrutura e escala os recursos automaticamente com base na demanda.
Exemplos no Azure: Azure Functions, Azure Logic Apps.
Inteligência Artificial e Machine Learning (AI/ML): Oferece ferramentas e serviços para desenvolver e implantar soluções de IA e aprendizado de máquina.
Exemplos no Azure: Azure Machine Learning, Azure Cognitive Services.
Bancos de Dados: Variedade de serviços de banco de dados gerenciados, incluindo relacionais (SQL) e NoSQL.
Exemplos no Azure: Azure Cosmos DB, Azure Database for PostgreSQL.
Segurança: Serviços para proteger os recursos e dados na nuvem.
Exemplos no Azure: Azure Security Center, Azure Sentinel.
Tipos de Custos na Computação em Nuvem
A estrutura de custos na computação em nuvem geralmente é baseada no modelo de pagamento por uso, mas pode variar dependendo do serviço e do provedor. Alguns dos tipos de custos mais comuns incluem:

Computação: Custo das instâncias de máquinas virtuais ou da capacidade de processamento utilizada por outros serviços (como funções serverless). Geralmente cobrado por hora ou por segundo de uso.
Armazenamento: Custo para armazenar dados na nuvem, que pode variar dependendo da quantidade de dados, da frequência de acesso e do tipo de armazenamento (por exemplo, armazenamento de alta performance vs. armazenamento de arquivo).
Rede: Custo da transferência de dados para fora da nuvem (egress). A transferência de dados para dentro da nuvem (ingress) geralmente é gratuita. Também pode haver custos associados a serviços de rede específicos, como balanceadores de carga e gateways de VPN.
Bancos de Dados: Custo dos serviços de banco de dados gerenciados, que pode ser baseado na capacidade provisionada, no armazenamento utilizado e no número de transações.
Largura de Banda: Custo da quantidade de dados transferidos através da rede em um determinado período.
Licenças: Custo de licenças de software que podem ser necessárias para executar certas aplicações na nuvem.
Os provedores de nuvem, como a Microsoft Azure, oferecem calculadoras de preços para ajudar os clientes a estimar os custos de seus recursos na nuvem. É importante entender os diferentes modelos de preços e otimizar o uso dos recursos para controlar os gastos.

# Conclusão
A computação em nuvem oferece uma abordagem flexível, escalável e econômica para a utilização de recursos de TI. Compreender os conceitos básicos, as características essenciais, os diversos produtos e serviços disponíveis (como os exemplificados pelo AZ-900 no Azure) e os diferentes tipos de custos é fundamental para aproveitar ao máximo os benefícios da nuvem. Ao adotar a computação em nuvem, as organizações podem inovar mais rapidamente, reduzir custos operacionais e focar em suas atividades principais, deixando a complexidade da infraestrutura para os provedores de nuvem. O exame AZ-900 serve como um excelente ponto de partida para quem busca solidificar seu conhecimento fundamental sobre os princípios da computação em nuvem e os serviços oferecidos pela Microsoft Azure.
