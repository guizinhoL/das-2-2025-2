# das-2-2025-2

guia de boas praticas da aws https://aws.amazon.com/pt/architecture/well-architected/

Um arquiteto de nuvem é um profissional de TI que projeta, implementa e gerencia a arquitetura de sistemas e aplicações baseadas em nuvem. Ele atua como um elo entre as necessidades de negócio de uma empresa e as soluções tecnológicas disponíveis nas plataformas de nuvem (como AWS, Azure, Google Cloud, entre outras).

Requisitos para um Arquiteto de Nuvem
Para se tornar um arquiteto de nuvem eficaz, é preciso ter uma combinação de habilidades técnicas e interpessoais. Alguns dos requisitos essenciais incluem:

Conhecimento Profundo de Plataformas de Nuvem: Dominar uma ou mais das principais plataformas de nuvem (AWS, Azure, Google Cloud) é fundamental. Isso inclui entender seus serviços, modelos de precificação, melhores práticas de segurança, conformidade e como otimizar custos.

Compreensão de Arquiteturas Distribuídas: Ter conhecimento sobre como projetar sistemas escaláveis, resilientes e tolerantes a falhas em ambientes distribuídos.

Habilidades de Programação e Scripting: Embora não seja um desenvolvedor full-time, um arquiteto de nuvem se beneficia de familiaridade com linguagens como Python, Go, Java ou Node.js, e ferramentas de scripting para automação (Terraform, CloudFormation, Ansible).

Segurança da Informação: Entender os princípios de segurança em nuvem, controle de acesso, criptografia, proteção de dados e como implementar arquiteturas seguras.

Redes: Conhecimento sólido em redes (TCP/IP, DNS, VPNs, firewalls, balanceamento de carga) e como elas funcionam em um ambiente de nuvem.

Containers e Orquestração: Experiência com tecnologias de contêineres como Docker e sistemas de orquestração como Kubernetes é cada vez mais importante.

Bancos de Dados: Compreender diferentes tipos de bancos de dados (relacionais, NoSQL) e suas aplicações em arquiteturas de nuvem.

DevOps e Cultura de Automação: Familiaridade com práticas de DevOps, CI/CD (Integração Contínua/Entrega Contínua) e automação de infraestrutura.

Habilidades de Comunicação e Liderança: Capacidade de se comunicar efetivamente com equipes técnicas e não técnicas, liderar discussões sobre design e influenciar decisões.

Resolução de Problemas: Ser capaz de identificar e resolver problemas complexos relacionados à infraestrutura e aplicações em nuvem.

Planejamento
O planejamento é a fase inicial e crucial no trabalho de um arquiteto de nuvem. É aqui que se define a estratégia para a migração ou criação de soluções em nuvem. Essa etapa envolve:

Análise de Requisitos de Negócio: Entender as necessidades e objetivos da empresa. O que se espera alcançar com a nuvem? Redução de custos, escalabilidade, agilidade, inovação?

Avaliação da Infraestrutura Existente (On-Premise): Se for uma migração, mapear e entender a infraestrutura atual, aplicações, dependências e cargas de trabalho.

Definição de Objetivos Técnicos: Estabelecer metas claras para a arquitetura de nuvem, como desempenho, segurança, conformidade, alta disponibilidade e recuperação de desastres.

Seleção de Plataforma de Nuvem: Escolher a plataforma de nuvem mais adequada (AWS, Azure, GCP ou uma abordagem multi-cloud) com base nos requisitos técnicos e de negócio.

Estimativa de Custos: Calcular os custos esperados da infraestrutura e serviços em nuvem, considerando otimização de custos e modelos de precificação.

Roadmap e Cronograma: Criar um plano detalhado de como a migração ou implantação será executada, incluindo fases e prazos.

Definição de Padrões e Melhores Práticas: Estabelecer diretrizes para o design, segurança e operação das soluções em nuvem.

Pesquisa
A pesquisa é um processo contínuo e vital para um arquiteto de nuvem, tanto antes quanto durante e após a implementação. Ela envolve:

Exploração de Novas Tecnologias e Serviços: A nuvem é um ambiente em constante evolução. Arquitetos precisam estar sempre atualizados com os novos serviços, recursos e tendências lançados pelas provedoras de nuvem.

Análise de Casos de Uso e Referências: Estudar como outras empresas e projetos resolveram desafios semelhantes na nuvem, buscando por arquiteturas de referência e padrões de design.

Comparação de Soluções: Avaliar diferentes opções de serviços e ferramentas para determinar qual se encaixa melhor nos requisitos do projeto (ex: qual tipo de banco de dados, qual serviço de contêiner, etc.).

Avaliação de Ferramentas e Frameworks: Pesquisar e testar ferramentas para automação, monitoramento, segurança e gestão de custos em nuvem.

Estudo de Regulamentações e Conformidade: Manter-se atualizado sobre as regulamentações de dados (LGPD, GDPR, HIPAA, etc.) e os requisitos de conformidade que afetam as soluções em nuvem.

Testes de Prova de Conceito (PoC): Realizar pequenos experimentos e PoCs para validar tecnologias, designs e abordagens antes de uma implementação em larga escala.

Construção
A fase de construção é onde o plano e a pesquisa se materializam em uma infraestrutura e aplicações em nuvem funcionais. Isso geralmente envolve:

Implementação da Infraestrutura como Código (IaC): Utilizar ferramentas como Terraform, AWS CloudFormation, Azure Resource Manager ou Google Cloud Deployment Manager para provisionar e gerenciar a infraestrutura de forma automatizada e repetível.

Configuração de Redes e Segurança: Implementar a arquitetura de rede (VPCs/VNets, sub-redes, tabelas de rotas, firewalls, grupos de segurança) e configurar as políticas de segurança e controle de acesso.

Implantação de Aplicações: Migrar ou implantar as aplicações na nuvem, configurando servidores, contêineres, funções serverless e serviços de banco de dados.

Configuração de Monitoramento e Logs: Implementar soluções de monitoramento (métricas, logs, traces) para garantir a visibilidade do desempenho e saúde da infraestrutura e aplicações.

Implementação de CI/CD: Configurar pipelines de Integração Contínua e Entrega Contínua para automatizar o processo de construção, teste e implantação de código.

Otimização e Refinamento: Ajustar a arquitetura e as configurações com base nos resultados de testes de desempenho, segurança e custos.

Documentação: Criar documentação detalhada da arquitetura, configurações e procedimentos operacionais.



Testes: Realizar testes de ponta a ponta, incluindo testes de carga, segurança, resiliência e recuperação de desastres.


## 6 pilares aws 

 pilar da exelencia 

 "Run and monitor systems that deliver business value."

Explicação: Isso significa que é essencial não apenas colocar sistemas em funcionamento, mas também monitorá-los ativamente para garantir que eles estejam realmente entregando o valor esperado para o negócio. É sobre acompanhar o desempenho, a disponibilidade e a eficácia das soluções.

"Continually improve supporting processes and procedures." (Destacado em amarelo)

Explicação: Enfatiza a importância da melhoria contínua. Os processos e procedimentos que dão suporte à operação dos sistemas devem ser revisados e aprimorados constantemente. Isso pode envolver otimização, automação, ou ajuste para novas necessidades.

"View the entire workload as code."

Explicação: Refere-se à prática de Infraestrutura como Código (IaC). A ideia é que toda a infraestrutura e configuração dos sistemas sejam definidas em arquivos de código, permitindo automação, versionamento, reusabilidade e consistência, como se fossem um software.

Em resumo, o pilar de Excelência Operacional busca garantir que os sistemas sejam executados de forma eficaz, que os processos de apoio sejam constantemente aprimorados e que a infraestrutura seja gerenciada como código para maior eficiência e controle.





pilar da segurança 




"Implement a strong Identity foundation." (Destacado em laranja)

Explicação: Este é o ponto mais importante ou inicial do pilar de segurança. Refere-se à necessidade de estabelecer uma base robusta para o gerenciamento de identidades e acessos. Isso envolve garantir que apenas as pessoas e serviços autorizados possam acessar os recursos, utilizando práticas como o princípio do privilégio mínimo, autenticação multifator (MFA) e gerenciamento de permissões.

"Maintain traceability."

Explicação: Significa que você deve ser capaz de rastrear e auditar todas as ações e eventos que ocorrem em seu ambiente de nuvem. Isso é crucial para investigações de segurança, conformidade e para entender quem fez o quê, quando e onde. Ferramentas de log e auditoria são fundamentais aqui.

"Apply security at all layers."

Explicação: Enfatiza a segurança em profundidade. A segurança não deve ser aplicada apenas em um único ponto, mas em todas as camadas da arquitetura, desde a rede (firewalls, grupos de segurança), computação (segurança de máquinas virtuais, contêineres), armazenamento (criptografia de dados) até a aplicação e o código.

"Implement risk management and mitigation strategies."

Explicação: Refere-se à prática proativa de identificar, avaliar e mitigar riscos de segurança. Isso envolve ter um plano para lidar com ameaças potenciais, implementar controles de segurança e ter estratégias de resposta a incidentes para minimizar o impacto de qualquer violação.

Em suma, o pilar de Segurança foca em criar uma base sólida de identidade e acesso, garantir a capacidade de auditar e rastrear ações, aplicar segurança em todas as camadas da infraestrutura e ter estratégias robustas para gerenciar e mitigar riscos.


## Aula 6/08


https://aws.amazon.com/pt/about-aws/global-infrastructure/

elastic comput cloud


contend delivery network

IaaS Paas SaaS

impossible travel - camada de seguraça

iam serviço global de segurança a  prate de autenticação e orientação

privilegio minimo da as permissoes necessarias

client side encryption -             criptografia no lado do cliente primeiro criptografa so o outro lado consegue encriptografar o cliente é reponsavel pela criptografia nãoo fornecedor de serviço

server side encryptio

#aula 13\8

- identity based policies: 

Attached to: Users, groups, or roles.

Focus: Defines the permissions of an identity.

Answers the question: "What can this identity do?"

Example: A policy attached to a "Developers" group that allows them to create and manage EC2 instances but denies them access to S3 buckets.



- resorce based polites:

Attached to: Resources (e.g., S3 buckets, SQS queues).

Focus: Defines who has access to a specific resource.

Answers the question: "Who can access this resource?"

Example: A policy on an S3 bucket that allows read-only access to a specific AWS account, enabling cross-account data sharing.

#aula 20\08

-block storage:
Como funciona: Oferece volumes brutos de armazenamento que são anexados a um servidor.

Acesso: Acessado pelo sistema operacional como se fosse um disco local.

Ideal para: Bancos de dados, sistemas de arquivos de alto desempenho (como em máquinas virtuais) e aplicações que exigem baixa latência e alta performance de leitura/escrita. É a base para a computação tradicional.

Analogia: Peças de LEGO. Você recebe um monte de blocos (peças) e pode construir o que quiser com eles (um sistema de arquivos, um banco de dados, etc.).



- File share:

Como funciona: Oferece volumes brutos de armazenamento que são anexados a um servidor.

Acesso: Acessado pelo sistema operacional como se fosse um disco local.

Ideal para: Bancos de dados, sistemas de arquivos de alto desempenho (como em máquinas virtuais) e aplicações que exigem baixa latência e alta performance de leitura/escrita. É a base para a computação tradicional.

Analogia: Peças de LEGO. Você recebe um monte de blocos (peças) e pode construir o que quiser com eles (um sistema de arquivos, um banco de dados, etc.).

- Object Store

Como funciona: Armazena dados como objetos em um espaço de endereço plano (bucket).

Acesso: Acessado via APIs web (HTTP/HTTPS) usando seu identificador único.

Ideal para: Armazenar grandes volumes de dados não estruturados, como fotos, vídeos, backups, logs, dados de sites estáticos e datasets para Big Data e IA. É altamente escalável e durável.

Analogia: Um serviço de manobrista (valet). Você entrega seu carro (objeto) e recebe um ticket (identificador único). Você não precisa saber em qual vaga o carro está estacionado; basta apresentar o ticket e o manobrista o trará de volta para você.


Resumo geral:

O que é? Um serviço para guardar e recuperar qualquer quantidade de dados, a qualquer hora, de qualquer lugar na web.

Conceitos Principais:

Buckets: São os "contêineres" onde você armazena seus dados. O nome de um bucket precisa ser único globalmente (em toda a AWS). Pense neles como a "raiz" do seu armazenamento.

Objetos: São os arquivos (fotos, vídeos, backups, etc.) e seus metadados. Cada objeto tem uma chave única (um nome/caminho) dentro de um bucket.

Durabilidade e Disponibilidade: O S3 foi projetado para uma durabilidade de 99,999999999% (onze noves), o que significa que se você armazenar 10 milhões de objetos, pode esperar perder um único objeto a cada 10.000 anos, em média. Ele replica automaticamente seus dados em múltiplas instalações físicas para protegê-los contra falhas.

#Dia 03\09

Serviços Computacionais da AWS (EC2 - Elastic Compute Cloud)
Pense no Amazon EC2 como um serviço que permite "alugar" computadores virtuais na nuvem da Amazon. Em vez de comprar e manter servidores físicos, você pode criar, configurar e rodar esses servidores virtuais (chamados de instâncias) em minutos, pagando apenas pelo tempo que os utiliza.

Com certeza! Aqui está uma explicação detalhada sobre os principais conceitos do serviço de computação da AWS, o EC2.

Serviços Computacionais da AWS (EC2 - Elastic Compute Cloud)
Pense no Amazon EC2 como um serviço que permite "alugar" computadores virtuais na nuvem da Amazon. Em vez de comprar e manter servidores físicos, você pode criar, configurar e rodar esses servidores virtuais (chamados de instâncias) em minutos, pagando apenas pelo tempo que os utiliza.

O "Elástico" no nome significa que você pode aumentar (scale up) ou diminuir (scale down) a capacidade computacional facilmente, conforme a sua necessidade. Precisa de mais 100 servidores para um evento de marketing? Você os cria. O evento acabou? Você os desliga e para de pagar.

Função Principal: Prover capacidade de computação segura e redimensionável na nuvem para rodar praticamente qualquer tipo de aplicação.

Amazon Machine Images (AMI)
Uma AMI é o "molde" ou o "template" usado para criar suas instâncias EC2. Ela é uma imagem de disco pré-configurada que contém:

Sistema Operacional: Como Amazon Linux, Ubuntu, Windows Server, etc.

Software e Aplicações: Você pode criar uma AMI com seu servidor web, banco de dados ou qualquer outro software já instalado e configurado.

Configurações e Permissões: Todas as configurações de inicialização e permissões associadas.

 (Burstable - Ex: t2.micro, t3.medium): Uso geral e baixo custo. Ideais para aplicações com picos de uso, como sites de baixo tráfego, blogs e ambientes de desenvolvimento. Elas acumulam "créditos de CPU" para usar quando precisam de mais performance.

m (General Purpose - Ex: m5.large): Equilíbrio entre CPU, memória e rede. São os "canivetes suíços" da AWS, ótimos para servidores web, microsserviços e bancos de dados de pequeno a médio porte.

c (Compute Optimized - Ex: c5.xlarge): Otimizadas para CPU. Têm muito poder de processamento e são ideais para aplicações que exigem muito do processador, como processamento em lote, edição de vídeo, machine learning e servidores de games.

r (Memory Optimized - Ex: r5.large): Otimizadas para Memória RAM. Perfeitas para aplicações que processam grandes volumes de dados na memória, como bancos de dados de alta performance, caches (Redis, Memcached) e análise de Big Data.

g (GPU - Ex: g4dn.xlarge): Equipadas com placas de vídeo (GPUs) da NVIDIA. Usadas para inteligência artificial, machine learning, renderização gráfica e aplicações científicas.

Tipos de Storage (Armazenamento)

Com certeza! Aqui está uma explicação detalhada sobre os principais conceitos do serviço de computação da AWS, o EC2.

Serviços Computacionais da AWS (EC2 - Elastic Compute Cloud)
Pense no Amazon EC2 como um serviço que permite "alugar" computadores virtuais na nuvem da Amazon. Em vez de comprar e manter servidores físicos, você pode criar, configurar e rodar esses servidores virtuais (chamados de instâncias) em minutos, pagando apenas pelo tempo que os utiliza.

O "Elástico" no nome significa que você pode aumentar (scale up) ou diminuir (scale down) a capacidade computacional facilmente, conforme a sua necessidade. Precisa de mais 100 servidores para um evento de marketing? Você os cria. O evento acabou? Você os desliga e para de pagar.

Função Principal: Prover capacidade de computação segura e redimensionável na nuvem para rodar praticamente qualquer tipo de aplicação.

Amazon Machine Images (AMI)
Uma AMI é o "molde" ou o "template" usado para criar suas instâncias EC2. Ela é uma imagem de disco pré-configurada que contém:

Sistema Operacional: Como Amazon Linux, Ubuntu, Windows Server, etc.

Software e Aplicações: Você pode criar uma AMI com seu servidor web, banco de dados ou qualquer outro software já instalado e configurado.

Configurações e Permissões: Todas as configurações de inicialização e permissões associadas.

Analogia: Pense em uma AMI como a "imagem de fábrica" do seu celular ou o arquivo de instalação (.iso) de um sistema operacional. Você usa essa imagem base para criar quantas cópias (instâncias) idênticas precisar, economizando um tempo enorme de instalação e configuração. A AWS fornece muitas AMIs prontas, e você também pode criar e customizar as suas.

Tipos de Instâncias
A AWS oferece centenas de "modelos" de servidores virtuais, chamados Tipos de Instâncias. Cada tipo é otimizado para uma finalidade diferente, equilibrando recursos como CPU, memória RAM, armazenamento e capacidade de rede.

As famílias mais comuns são:

t (Burstable - Ex: t2.micro, t3.medium): Uso geral e baixo custo. Ideais para aplicações com picos de uso, como sites de baixo tráfego, blogs e ambientes de desenvolvimento. Elas acumulam "créditos de CPU" para usar quando precisam de mais performance.

m (General Purpose - Ex: m5.large): Equilíbrio entre CPU, memória e rede. São os "canivetes suíços" da AWS, ótimos para servidores web, microsserviços e bancos de dados de pequeno a médio porte.

c (Compute Optimized - Ex: c5.xlarge): Otimizadas para CPU. Têm muito poder de processamento e são ideais para aplicações que exigem muito do processador, como processamento em lote, edição de vídeo, machine learning e servidores de games.

r (Memory Optimized - Ex: r5.large): Otimizadas para Memória RAM. Perfeitas para aplicações que processam grandes volumes de dados na memória, como bancos de dados de alta performance, caches (Redis, Memcached) e análise de Big Data.

g (GPU - Ex: g4dn.xlarge): Equipadas com placas de vídeo (GPUs) da NVIDIA. Usadas para inteligência artificial, machine learning, renderização gráfica e aplicações científicas.

A escolha do tipo de instância correto é fundamental para garantir a performance da sua aplicação e otimizar os custos.

Tipos de Storage (Armazenamento)
Quando você cria uma instância EC2, precisa de um lugar para armazenar o sistema operacional e seus dados. Existem duas opções principais:

1. EBS (Elastic Block Store)
O que é: Um volume de armazenamento em rede, como um "HD externo de alta performance" que você anexa à sua instância.

Persistência: Os dados no EBS persistem (são mantidos) mesmo que a instância EC2 seja desligada ou encerrada. Você pode desanexar um volume EBS de uma instância e anexá-lo a outra, como se estivesse trocando um HD de computador.

Uso: Ideal para armazenar o sistema operacional, bancos de dados, arquivos de aplicações e qualquer dado que precise sobreviver ao ciclo de vida da instância. É a opção padrão e mais recomendada.

Tipos: Existem vários tipos de EBS, como gp2/gp3 (SSD de uso geral), io1/io2 (SSD de altíssima performance) e st1 (HDD otimizado para dados acessados com frequência).


2. Instance Store (Armazenamento de Instância)
O que é: Discos físicos que estão diretamente conectados ao computador host que roda a sua instância EC2.

Persistência: Os dados no Instance Store são temporários (efêmeros). Se a instância for parada, hibernada ou encerrada, TODOS OS DADOS SÃO PERDIDOS permanentemente.

Uso: Ideal para dados temporários que não precisam ser mantidos, como cache, buffers, ou dados que são replicados em outras instâncias. A grande vantagem é a velocidade, pois oferece latência extremamente baixa.

Analogia: Pense no EBS como um HD/SSD principal e no Instance Store como uma memória RAM muito rápida, mas que se apaga quando a energia acaba.

Acesso via SSH (Secure Shell)
SSH é o protocolo padrão para acessar e administrar servidores Linux de forma segura pela linha de comando. Para se conectar a uma instância EC2 Linux, você usa um par de chaves criptográficas:

Chave Pública: Fica armazenada na instância EC2. Você a seleciona no momento da criação da instância.

Chave Privada: Fica com você, armazenada de forma segura no seu computador (um arquivo com extensão .pem ou .ppk). Ela é o seu "segredo" para provar sua identidade.



#Dia 10\09

Tipos de Storage (EBS vs. Instance Store)
Quando você cria uma máquina virtual (instância) na AWS, precisa de um local para armazenar dados. As duas principais opções são EBS e Instance Store, e a principal diferença entre elas é a persistência dos dados



EBS (Elastic Block Store
Persistência: Os dados são permanentes. Se você desligar ou destruir a instância, os dados no volume EBS continuam intactos. Você pode até desconectar o volume de uma instância e conectá-lo em outra.

Uso Ideal: É a escolha padrão para a grande maioria dos casos, como armazenar o sistema operacional, bancos de dados, servidores de aplicação e qualquer dado que precise ser durável e seguro.

Flexibilidade: Você pode redimensionar o volume e alterar seu tipo (mais rápido ou mais barato) a qualquer momento.

Instance Store 

Persistência: Os dados são temporários (efêmeros). Se a instância for desligada ou terminada, todos os dados são apagados permanentemente.

Uso Ideal: Perfeito para dados que não precisam ser guardados, como caches, arquivos temporários, ou para partes de um sistema distribuído que já possui replicação (como alguns bancos de dados NoSQL). Sua principal vantagem é a velocidade e a latência extremamente baixa.

Amazon EFS (Elastic File System) 📂
O EFS é um sistema de arquivos de rede simples, elástico e totalmente gerenciado para ser usado com instâncias Linux.

Protocolo: Usa o protocolo NFS (Network File System), padrão no mundo Linux.

Elasticidade: O armazenamento cresce e diminui automaticamente conforme você adiciona ou remove arquivos. Você não precisa provisionar um tamanho específico.

Uso Ideal: Perfeito para sistemas de gerenciamento de conteúdo (como WordPress), diretórios "home" de usuários compartilhados, e aplicações que precisam de um sistema de arquivos compartilhado e escalável para instâncias Linux.


Amazon FSx 🗂️
O Amazon FSx é uma família de sistemas de arquivos gerenciados para diferentes necessidades. Os dois mais comuns são:

FSx for Windows File Server: Como o nome diz, é um servidor de arquivos Windows completo na nuvem.

Protocolo: Usa o protocolo SMB (Server Message Block), padrão do Windows.

Recursos: Suporta tudo o que você espera de um servidor de arquivos Windows, incluindo integração com Active Directory, permissões NTFS e shadow copies.

Uso Ideal: Perfeito para compartilhar arquivos entre instâncias EC2 Windows, aplicações .NET e migrar servidores de arquivos corporativos para a nuvem.

FSx for Lustre: Um sistema de arquivos de altíssimo desempenho, otimizado para computação pesada.

Uso Ideal: Cargas de trabalho como machine learning, análise de dados em grande escala e renderização de vídeo, onde a velocidade de leitura e escrita é crucial.


EC2 Windows
A AWS permite que você crie instâncias EC2 não apenas com Linux, mas também com diversas versões do Microsoft Windows Server. O funcionamento é muito parecido com o de uma instância Linux, mas com algumas diferenças importantes.

AMI: Você seleciona uma AMI (Amazon Machine Image) de Windows Server (ex: 2019, 2022) ao criar a instância.

Custos: O custo de uma instância Windows é um pouco maior, pois inclui o valor da licença do sistema operacional da Microsoft.

Acesso: Em vez de usar SSH (linha de comando), o acesso a instâncias Windows é feito principalmente através do RDP (Remote Desktop Protocol). Isso abre uma interface gráfica completa do Windows, exatamente como se você estivesse sentado na frente do servidor.

Autenticação: Para se conectar, a AWS usa o mesmo par de chaves (.pem) que você usa para Linux, mas de uma forma diferente. Você usa sua chave privada para descriptografar a senha de Administrador inicial, que a AWS gera aleatoriamente para você. Depois de obter a senha, você se conecta via RDP com o usuário "Administrator" e essa senha.
