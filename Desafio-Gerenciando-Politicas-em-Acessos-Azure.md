# Gerenciando Politicas em Acessos Azure

## Portal de Confiança do Serviço

O Portal de Confiança do Serviço Azure é um site oficial da Microsoft onde você encontra informações detalhadas sobre a segurança e a privacidade dos serviços da nuvem Azure. É como um "rosto" da segurança da Azure, mostrando aos clientes, parceiros e reguladores que a Microsoft leva a sério a proteção dos dados.

### Como acessar Portal de Confiança do Serviço?

acesse [Portal de Confiança do Serviço](https://servicetrust.microsoft.com/) . Algumas informações estarão legíveis sem necessidade de login, já outras somente com login.

## Microsoft Purview

O Microsoft Purview é uma plataforma abrangente de gerenciamento de informações que visa ajudar as organizações a descobrir, classificar, proteger e gerenciar seus dados de forma mais eficiente e segura. Essa solução unificada oferece uma série de ferramentas e recursos para auxiliar na governança de dados, garantindo que as informações sejam utilizadas de maneira adequada e em conformidade com as regulamentações.

### Principais Funcionalidades do Microsoft Purview:

- **Descoberta de Dados:** Identifica e categoriza dados em toda a organização, incluindo dados estruturados e não estruturados, em diversas fontes como Microsoft 365, Azure e outros sistemas.
- **Classificação de Dados:** Aplica etiquetas e classificações aos dados com base em sua sensibilidade e valor, facilitando a gestão de riscos e o cumprimento de políticas.
- **Proteção de Dados:** Implementa medidas de segurança para proteger dados confidenciais, como prevenção de perda de dados (DLP) e criptografia.
- **Gerenciamento do Ciclo de Vida dos Dados:** Auxilia na retenção, preservação e exclusão de dados de acordo com as políticas da organização e as leis aplicáveis.
- **Conformidade:** Facilita o cumprimento de regulamentações como GDPR, HIPAA e outras, fornecendo ferramentas para rastrear e gerenciar o acesso aos dados.
- **Governança de Dados:** Permite definir e aplicar políticas de dados, assegurando que as informações sejam utilizadas de forma consistente e em conformidade com as diretrizes da organização.

### Benefícios do Microsoft Purview:

- **Visibilidade:** Oferece uma visão completa dos dados da organização, facilitando a tomada de decisões informadas.
- **Segurança:** Protege os dados confidenciais da organização contra ameaças internas e externas.
- **Conformidade:** Auxilia no cumprimento das obrigações legais e regulatórias.
- **Eficiência:** Automatiza muitos processos de gerenciamento de dados, reduzindo o trabalho manual.
- **Escalabilidade:** Adapta-se a organizações de todos os tamanhos e complexidades.

### Como criar uma conta no Microsoft Purview


1. **Acesse o Portal do Azure**
   - Vá para o Portal do Azure.

2. **Pesquisar Microsoft Purview**
   - No menu de pesquisa, digite "Microsoft Purview" e selecione a opção correspondente.

3. **Criar uma Nova Conta**
   - Clique em **+ Criar** para iniciar o processo de criação de uma nova conta do Microsoft Purview.

4. **Configurar a Conta**
   - Na guia **Noções Básicas**, preencha os seguintes detalhes:
     - **Assinatura**: Selecione a assinatura do Azure onde deseja criar a conta.
     - **Grupo de Recursos**: Escolha um grupo de recursos existente ou crie um novo.
     - **Nome da Conta**: Insira um nome único para a conta do Microsoft Purview.
     - **Região**: Selecione a região onde deseja criar a conta.

5. **Configurações Adicionais**
   - Configure as opções adicionais conforme necessário, como **Tipo de Identidade** e **Acesso à Rede Pública**.

6. **Revisar e Criar**
   - Revise todas as configurações e clique em **Criar** para finalizar a criação da conta.


## Bloqueio de Recursos no Azure

O bloqueio de recursos é uma funcionalidade de segurança do Azure que permite proteger recursos críticos, impedindo que sejam excluídos ou modificados acidentalmente. 

**Por que usar bloqueios de recursos?**
* Evitar exclusões acidentais.
* Proteger recursos críticos.
* Garantir a conformidade com políticas.

**Como criar um bloqueio:**

1. **Acesse o Portal do Azure:**
   * Faça login em https://portal.azure.com/.

2. **Localize o recurso:** Navegue até o recurso que deseja proteger.

3. **Configure o bloqueio:**
   * No painel do recurso, vá para "Bloqueios".
   * Clique em "Adicionar bloqueio".
   * **Tipos de bloqueio:**
     * **ReadOnly:** Impede modificações, permite leitura.
     * **CanNotDelete:** Impede exclusão.
   * Selecione o tipo desejado e adicione um nome e descrição.

4. **Salve o bloqueio:** Clique em "Salvar".

**Dicas adicionais:**
* **Bloqueios em grupos de recursos:** Aplique bloqueios a grupos de recursos para proteger vários recursos de uma vez.
* **Azure Blueprints:** Utilize blueprints para aplicar bloqueios de forma consistente em várias implantações.
* **Política do Azure:** Combine bloqueios com políticas do Azure para um controle mais granular.


## Gerenciamento de Políticas no Azure

As políticas do Azure são regras definidas que determinam quais tipos de recursos podem ser criados ou modificados em sua assinatura.

**Por que usar políticas?**
* Garantir a conformidade com normas e regulamentos.
* Melhorar a segurança da sua infraestrutura.
* Otimizar os custos.

**Criando uma nova política:**

1. **Acesse o Portal do Azure:** https://portal.azure.com/
2. **Navegue para 'Azure Policy':** Encontre e selecione **Azure Policy** no menu.
3. **Crie uma nova definição:**
   * Selecione **Definitions** e clique em **New Policy Definition**.
   * **Defina os critérios:** Escolha o tipo de recurso, propriedades e condições.
   * **Defina a ação:** Escolha a ação a ser tomada se a política for violada (negar, advertir, etc.).
4. **Aplique a política:**
   * Vá para **Assignments**.
   * Clique em **Assign Policy**.
   * Selecione a política criada.
   * **Defina o escopo:** Escolha onde a política será aplicada (assinatura, grupo de recursos, iniciativa).
   * **Ative a política:** Marque a opção para ativar a política.
5. **Revise e salve:** Clique em **Create**.

**Dicas:**
* Utilize iniciativas para gerenciar políticas em larga escala.
* Explore os diferentes tipos de critérios e ações disponíveis.
* Monitore o cumprimento das políticas regularmente.
