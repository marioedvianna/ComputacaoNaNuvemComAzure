# Tutorial: Configurando uma Instância de Banco de Dados na Azure

## 1. Iniciar Sessão no Portal do Azure
1. Acesse o Portal do Azure.
2. Faça login com sua conta da Microsoft.

## 2. Criar um Grupo de Recursos (Se necessário)
1. No menu à esquerda, clique em **Grupos de Recursos**.
2. Clique em **Criar**.
3. Insira um nome para o grupo de recursos(Caso não tenha criado siga os seguintes passos:
    ) e selecione uma região.
4. Clique em **Revisar + Criar** e depois em **Criar**.

## 3. Criar um Servidor de Banco de Dados
1. No menu à esquerda, clique em **Banco de Dados SQL**.
2. Clique em **Criar**.
3. Preencha os detalhes do servidor:
   - **Nome do Servidor**: Escolha um nome único.
   - **Localização**: Selecione a região desejada.
   - **Método de Autenticação**: Escolha entre autenticação SQL ou Azure AD.
   - **Nome de Usuário e Senha**: Defina as credenciais de administrador.

## 4. Configurar o Banco de Dados
1. Após criar o servidor, clique em **Adicionar Banco de Dados**.
2. Preencha os detalhes do banco de dados:
   - **Nome do Banco de Dados**: Escolha um nome para o banco de dados.
   - **Plano de Serviço**: Selecione o plano de serviço (por exemplo, Básico, Standard, Premium).
   - **Tamanho**: Defina o tamanho e a capacidade do banco de dados.

## 5. Configurar a Rede
1. Em **Configurações de Rede**, configure as seguintes opções:
   - **Regras de Firewall**: Adicione regras de firewall para permitir o acesso ao banco de dados.
   - **Rede Virtual**: Se necessário, configure a rede virtual para o banco de dados.

## 6. Revisar e Criar
1. Clique em **Revisar + Criar**.
2. Revise todas as configurações e clique em **Criar**.

## 7. Conectar ao Banco de Dados
1. Após a implantação, vá para o recurso do banco de dados.
2. Clique em **Configurações** e depois em **Propriedades** para obter a string de conexão.
3. Use a string de conexão no seu aplicativo ou ferramenta de gerenciamento de banco de dados (por exemplo, SQL Server Management Studio, Azure Data Studio).

## 8. Verificar a Conexão
1. Abra a ferramenta de gerenciamento de banco de dados.
2. Insira a string de conexão e as credenciais configuradas.
3. Verifique se a conexão foi estabelecida com sucesso e se o banco de dados está acessível.

