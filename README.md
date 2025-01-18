## 🌐 Alcance Global: Uma Jornada de E-commerce na Nuvem com AWS ☁️

<p align="center">
  <img src="Imagens\Arquitetura_aws.png" width="1000" alt="Diagrama da Arquitetura do Projeto Alcance Global" />
</p>

### Olá! 👋

Este é o repositório do projeto **Alcance Global**, desenvolvido para o trabalho de conclusão de curso da **Escola da Nuvem**. Embarcamos em uma aventura para construir uma infraestrutura de e-commerce escalável, segura e eficiente na AWS. Se você é apaixonado por cloud e desafios, veio ao lugar certo! 😉

### 🎯 Nosso Objetivo

Nosso foco principal foi criar uma arquitetura robusta para uma startup de e-commerce, a **Nova Tech**, com os seguintes objetivos:

-   **Escalabilidade:** Garantir que a aplicação possa lidar com picos de tráfego sem problemas.
-   **Segurança:** Proteger os dados da aplicação e dos usuários contra ameaças.
-   **Otimização de Custos:** Utilizar os recursos da AWS de forma eficiente para manter os custos sob controle.
-   **Alta Disponibilidade:** Assegurar que a aplicação esteja sempre disponível para os clientes.

### 🚀 A Arquitetura

A imagem acima mostra nossa arquitetura final. Utilizamos uma combinação de serviços AWS para garantir que o projeto atenda aos requisitos da Nova Tech.

Algumas das tecnologias chave incluem:

*   **Rede e DNS Global:**
    *   **Amazon Route 53:** Para DNS global e roteamento de tráfego inteligente.
    *   **VPC Multi-AZ:** Configuração para alta disponibilidade.

*   **Aplicação e Escalabilidade:**
    *   **Elastic Load Balancing (ELB):** Distribuição de tráfego para várias instâncias EC2.
    *   **EC2 com Auto Scaling:** Escalabilidade automática baseada na demanda.

*   **Distribuição de Conteúdo Global:**
    *   **Amazon CloudFront:** CDN para baixa latência na entrega de conteúdo.

*   **Banco de Dados e Cache:**
    *   **Amazon RDS com Auto Scaling:** Banco de dados relacional com escalabilidade.
    *   **Amazon DynamoDB:** Banco de dados NoSQL para dados de sessão e alta disponibilidade.
    *   **Amazon ElastiCache:** Cache para melhorar a performance do banco de dados.
    *   **Amazon S3:** Armazenamento de arquivos estáticos e backups.
    *   **EBS (Elastic Block Store):** Armazenamento persistente para EC2.

*   **Segurança:**
    *   **MFA e AWS Cognito:** Gerenciamento de acesso e autenticação multifator.
    *   **AWS WAF e Shield:** Proteção contra ataques DDoS e vulnerabilidades.
    *   **KMS (Key Management Service):** Gerenciamento de chaves de criptografia.
    *   **AWS GuardDuty:** Monitoramento de ameaças e segurança dos dados.

*   **Monitoramento e Automação:**
    *   **Amazon CloudWatch e Alarms:** Monitoramento de saúde da infraestrutura e alarmes.
    *   **CloudTrail:** Auditoria de ações e monitoramento do desempenho da aplicação.
    *   **AWS CloudFormation:** Automação do provisionamento e configuração da infraestrutura.

### 📊 Estimativa de Custos

Com base na nossa arquitetura, estimamos um custo inicial de **635,80 USD**, um custo mensal de **466,66 USD**, e um custo total de **6.235,72 USD** para 12 meses.

*   [Link para calculadora de custos AWS](https://calculator.aws/#/estimate?id=c1c5210ac1e6c6bc7d7b3148e0c993230981c1bf)

### 🛠️ Como Clonar o Repositório

Para começar a explorar nosso projeto, siga estes passos:

1.  **Clone o repositório:**

    ```bash
    git clone https://github.com/bhnunes/AlcanceGlobalEDN.git
    ```
2.  **Acesse o diretório do projeto:**

    ```bash
    cd AlcanceGlobalEDN
    ```

### 🧑‍💻 Nossa Equipe

Conheça os membros da equipe que tornaram este projeto possível:

*   **Heryvelton - Líder de Time:** [/heryvelton](https://www.linkedin.com/in/heryvelton)
*   **Bruno Henrique Nunes - Arquiteto:** [/brunohenriquenunes](https://www.linkedin.com/in/brunohenriquenunes)
*   **Letícia Lucena - Especialista Cloud:** [/leticialucena](https://www.linkedin.com/in/leticialucena/)
*   **David Antônio - Especialista Cloud:** [/davidantonio](https://www.linkedin.com/in/davidantonio)
*   **Rodrigo Thomaz Gerber - Especialista Segurança Cloud:** [/rodrigothomazgerber](https://www.linkedin.com/in/rodrigothomazgerber/)

<p align="center">
  <img src="Imagens\team.PNG" width="600" alt="Equipe Alcance Global" />
</p>


### ❓ Dúvidas ou Sugestões?

Se você tiver alguma dúvida, sugestão ou quiser colaborar, sinta-se à vontade para entrar em contato! Adoraríamos ouvir suas ideias! 😄

---

**🚀 Juntos, vamos construir o futuro da nuvem!** 💪🏼
