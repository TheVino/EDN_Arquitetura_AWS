# Projeto de Migração para a Nuvem - Empresa TechInfo LTDA

## Visão Geral do Projeto

**Projeto:**  
A Empresa TechInfo LTDA, uma grande varejista online, está enfrentando dificuldades com a escalabilidade e a disponibilidade de seu sistema atual de TI. Com o aumento das transações online e a expansão de seus serviços digitais, a empresa decidiu migrar para uma solução de nuvem para melhorar a performance, a segurança e a flexibilidade de sua infraestrutura.

**Objetivo do Projeto:**  
Migrar a infraestrutura de TI da Empresa TechInfo LTDA para a nuvem, implementando uma solução escalável e segura que suporte o crescimento futuro e melhore a experiência do cliente.

**Papéis específicos:**  
- **Líder de projeto**: Vinicius
- **Arquiteto de solução**: Paulo Sergio
- **Engenheiro de nuvem**: Abraão
- **Especialista em segurança**: Marina 🙂
- **Analista de dados**: Luane

**Problemas enfrentados pelo cliente:**
- Itens não vão para o carrinho ou não conseguem finalizar a compra.
- Clientes são “deslogados” de tempo em tempo quando logados.

## Plano de Migração para AWS

### 📝 Planejamento e Avaliação Inicial
- **Avaliação da Infraestrutura Atual:** Analisar todos os componentes da infraestrutura atual da Empresa TechInfo LTDA, incluindo servidores, banco de dados, rede, armazenamento, etc.
  
- **Identificação de Requisitos de Performance e Escalabilidade:** Determinar as necessidades atuais e futuras em termos de tráfego, transações e capacidade de armazenamento.

- **Análise de Segurança:** Avaliar os requisitos de segurança atuais e identificar as melhores práticas de segurança da AWS.
  - **Especialista em Segurança:** Garantir a proteção robusta dos dados, sistemas, acessos, infra e migração da Empresa TechInfo LTDA. 
    - Avaliar os riscos da migração (senhas e chaves de acesso dentro do código ou desprotegidas)
    - Implementar medidas de segurança adequadas (firewalls, ACLs, grupos de segurança) 
    - Monitorar atividades maliciosas e responder a incidentes de segurança de forma rápida
    - Cultivar uma política de segurança nos colaboradores (não expor cartões de acesso, base de código, não comprometer os dispositivos usados na rede, ...)

### 🖥️ Design da Arquitetura na AWS
- **Escolha das Regiões e Zonas de Disponibilidade:** Selecionar as regiões da AWS que melhor atendem às necessidades geográficas e de latência da Empresa TechInfo LTDA.

- **Design de Rede:** Configurar VPC, sub-redes, gateways, VPN e IPs elásticos.

- **Implementação de Segurança:** Utilizar serviços como AWS Identity and Access Management (IAM), AWS Key Management Service (KMS) para gerenciamento de chaves, e configurar grupos de segurança para controlar o acesso.

- **Escolha de Serviços Gerenciados:** Utilizar serviços gerenciados da AWS sempre que possível, como Amazon RDS para banco de dados, Amazon Elastic Load Balancing para balanceamento de carga, Amazon CloudFront para CDN (Content Delivery Network).

### 📦 Migração de Dados e Aplicações
- **Planejamento da Migração:** Dividir a migração em fases, começando com workloads menos críticos e progredindo para os mais críticos.

- **Ferramentas de Migração:** Utilizar ferramentas como AWS Database Migration Service para migração de banco de dados e AWS Server Migration Service para máquinas virtuais.

- **Testes e Validação:** Realizar testes completos após cada fase de migração para garantir que todas as aplicações estejam funcionando corretamente na nova infraestrutura.

### 🔧 Implementação e Otimização Contínua
- **Monitoramento e Otimização:** Configurar monitoramento utilizando AWS CloudWatch para monitorar métricas de performance, logs e eventos operacionais. Utilizar AWS Trusted Advisor para otimizar custos, performance e segurança.

- **Backup e Recuperação:** Implementar políticas de backup utilizando AWS Backup e testar regularmente os procedimentos de recuperação de desastres.

- **Escalonamento Automático:** Configurar Auto Scaling para ajustar dinamicamente a capacidade de acordo com demandas variáveis.

### 📚 Treinamento e Gestão de Mudança
- **Capacitação da Equipe:** Providenciar treinamento para a equipe de TI da Empresa TechInfo LTDA sobre as novas tecnologias e práticas na AWS.

- **Gestão de Mudança:** Implementar um plano de gestão de mudança para garantir uma transição suave e minimizar impactos no negócio.

### 🔍 Revisão e Ajuste
- **Revisão Pós-Migração:** Realizar revisões periódicas para avaliar a performance, custos e segurança da nova infraestrutura na AWS. Ajustar a arquitetura conforme necessário para otimizar recursos e melhorar a experiência do usuário.

- **Análise de resultados:** Analisar os resultados do histórico de vendas e satisfação dos clientes antes e após a migração. Conhecendo assim os clientes e produtos, para poder adequar a infraestrutura aos resultados obtidos.

Implementando esse plano de migração para a AWS, a Empresa TechInfo LTDA estará posicionada para suportar seu crescimento futuro, melhorar a experiência do cliente e garantir um ambiente de TI seguro e escalável.


 ## Arquitetura montada
![Diagrama AWS](https://github.com/user-attachments/assets/e1d85333-928c-44fd-9a36-e7ea130ef6f1)
