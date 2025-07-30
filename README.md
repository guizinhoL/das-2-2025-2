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
