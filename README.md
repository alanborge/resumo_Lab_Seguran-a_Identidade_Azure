# Microsoft Entra ID e Active Directory em Nuvem

O **Microsoft Entra ID** (antigo *Azure Active Directory*) é a solução de **identidade e gerenciamento de acessos em nuvem da Microsoft**.  
Ele possibilita a integração com ambientes **on-premise** e o gerenciamento centralizado de **usuários, grupos, permissões e segurança**.

---

## 🔗 Integração com Active Directory On-Premise
Para empresas que já possuem **Active Directory local**, o ideal é manter a autenticação em **ambos os ambientes** (on-premise e nuvem).

A integração é feita através do **Microsoft Entra Connect**, que permite:

- Sincronizar **usuários e senhas** para a nuvem.  
- Apenas contas sincronizadas têm suas senhas migradas.  
- Contas criadas diretamente no Entra ID **não retornam** para o AD local.  

---

## 👥 Gerenciamento de Usuários
No Entra ID é possível:

- Visualizar informações detalhadas:  
  - Última data de sincronização  
  - Endereço IP utilizado  
  - Região de acesso  

- **Exclusão e restauração de contas**  
  - Usuários excluídos permanecem em **"Usuários Excluídos"** por até **30 dias**.  
  - Nesse período, podem ser restaurados. Após isso, a exclusão é permanente.  

- **Self-Service Password Reset (SSPR)**  
  - Usuários podem redefinir suas próprias senhas.  
  - Reduz demandas para a equipe de TI.  

- **Criação de contas**  
  - Usuários internos  
  - Usuários externos/visitantes  
  - Importação em massa via arquivo **CSV**  

---

## 🛡️ Microsoft Entra Roles & Administrators
- Permite atribuir **permissões granulares** através de **roles** (funções) e administradores.  
- Não inclui criação ou exclusão de usuários, apenas gerenciamento.  
- Para recursos avançados, é necessário licenciamento **P1** ou **P2**.  

---

## 🔄 Microsoft Entra Connect
Ferramenta que possibilita:

- **Sincronização de usuários** do AD On-Premise para a nuvem, garantindo identidade unificada.  
- Configuração de **domínios personalizados (Custom Domain Names)** para uso do domínio corporativo.  

---

## 📊 Monitoramento e Saúde do Serviço
O **Health Preview** oferece:

- Métricas de SLA, autenticações e níveis de serviço.  
- Monitoramento de **thresholds** e desempenho das autenticações.  

---

## 🔑 Controle de Acessos a Recursos (RBAC)
- Permite controle via **Role-Based Access Control (RBAC)**.  
- Permissões podem ser aplicadas em nível de **Resource Group** ou herdadas.  
- Requer atenção para evitar permissões excessivas.  

---

## 🛡️ Microsoft Defender for Cloud
Ferramenta de segurança que oferece:

- Avaliação da **postura de segurança** da organização.  
- Recomendações para **Microsoft** e outros provedores de nuvem.  
- Integração com **DevOps Security** (GitHub, GitLab).  
- Envio de alertas para:  
  - 📧 E-mail  
  - 💬 Slack  
  - 💬 Microsoft Teams  

- Monitoramento de:  
  - Bancos de dados  
  - Máquinas virtuais  
  - Armazenamento (*Storage*)  
  - Contêineres  
  - APIs e Web Services  

> ⚠️ Alguns recursos exigem licenciamento adicional. A camada **Foundation CSPM** é gratuita e cobre funcionalidades básicas.

---

## ✅ Conclusão
O **Microsoft Entra ID** centraliza **identidades e segurança em nuvem**, trazendo benefícios como:

- Autenticação híbrida  
- Gestão de usuários e permissões  
- Recuperação e redefinição de senhas  
- Monitoramento de acessos e SLAs  
- Segurança integrada com **Microsoft Defender for Cloud**  

Essa solução facilita o trabalho das equipes de TI, melhora a experiência dos usuários e fortalece a postura de segurança organizacional.  
