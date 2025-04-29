# Entendendo sobre Segurança e Identidade na Azure

Segurança e identidade são componentes críticos na plataforma Azure.

Principais conceitos e ferramentas:

  - Microsoft Entra ID - Anteriormente conhecido como Active Directory do Azure (Azure AD), é uma solução de gerenciamento de identidade e acesso da Microsoft que ajuda organizações a proteger e gerenciar identidades em ambientes locais e de nuvem.
    - Funcionalidades:
      - Autenticação: Verifica a identidade de um usuário para garantir que ele é quem diz ser.
      - Autorização: Determina quais recursos o usuário tem permissão para acessar.
      - MFA (Autenticação Multifator): Adiciona uma camada extra de segurança ao exigir mais de um método de autenticação (senha + SMS, por exemplo).
      - 
  - RBAC (Role-Based Access Control) - Método de controle de acesso que atribui permissões aos usuários com base em suas funções dentro de uma organização. O Controle de Acesso Baseado em Funções permite que você gerencie permissões de acesso aos recursos do Azure.
      - Funções integradas - Funções predefinidas que atendem a muitas necessidades comuns de segurança.
      - Funções personalizadas - Capacidade de definição de permissões específicas para cada usuário ou aplicação.
        
  -  Azure Security Center - Ferramenta de gerenciamento unificada que aprimora a postura de segurança dos seus datacenters. Oferece recomendações de segurança com base em melhores práticas e monitora continuamente os recursos para garantir que eles estão configurados corretamente.
      - Avaliação de vulnerabilidade - Detecta vulnerabilidades nos seus recursos e sugere como corrigi-las.
      - Ameaças em tempo real - Monitora atividades suspeitas nos recursos do Azure e oferece alertas em tempo real.
      - 
  - Microsoft Defender for Cloud - É uma ferramenta cloud native, com configurações específicas para, por exemplo, trazer recomendações de segurança (com notas, recurso DevOps Security), sendo benéfico para a área de software, multicloud e híbrido.

    ![image](https://github.com/user-attachments/assets/3e59c262-2255-4b2b-95e7-ca419467d4e5)

  - Azure Sentinel - Uma visão geral do que está acontecendo em seu ambiente e conectar os pontos que podem estar relacionados ao mesmo incidente de segurança.

      ![image](https://github.com/user-attachments/assets/ce5aa915-d5a3-4ab5-aab0-e3c00a2ea1ca)



