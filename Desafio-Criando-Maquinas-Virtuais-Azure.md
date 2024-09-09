# Passo a Passo para Criar uma Máquina Virtual na Azure

## 1. Iniciar Sessão no Azure
* Vá para https://portal.azure.com e faça login com sua conta.

## 2. Criar um Grupo de Recursos
1. No menu à esquerda, clique em **Grupos de Recursos**.
2. Clique em **Adicionar**.
3. Insira um nome para o grupo de recursos e selecione uma região.
4. Clique em **Revisar + Criar** e depois em **Criar**.

## 3. Criar a Máquina Virtual
1. No menu à esquerda, clique em **Máquinas Virtuais**.
2. Clique em **Adicionar** e depois em **Máquina Virtual**.
3. Preencha os detalhes da instância:
   - **Nome da VM**: Escolha um nome para sua VM.
   - **Região**: Selecione a região desejada.
   - **Imagem**: Escolha o sistema operacional (por exemplo, Windows Server 2022).
   - **Tamanho**: Selecione o tamanho da VM de acordo com suas necessidades.
4. Em **Conta de Administrador**, insira um nome de usuário e uma senha.

## 4. Configurar a Rede
1. Em **Rede**, configure as seguintes opções:
   - **Rede Virtual**: Selecione uma rede virtual existente ou crie uma nova.
   - **Sub-rede**: Selecione uma sub-rede.
   - **Endereço IP Público**: Selecione **Criar novo** para obter um IP público.
   - **Grupo de Segurança de Rede**: Configure as regras de segurança conforme necessário.

## 5. Revisar e Criar
1. Clique em **Revisar + Criar**.
2. Revise todas as configurações e clique em **Criar**.

## 6. Conectar à Máquina Virtual
1. Após a implantação, vá para o recurso da VM.
2. Clique em **Conectar** e selecione **RDP** (para Windows) ou **SSH** (para Linux).
3. Baixe o arquivo RDP ou obtenha as informações de conexão SSH.
4. Conecte-se à VM usando as credenciais configuradas.

## 7. Verificar a Conexão
1. Abra o arquivo RDP baixado e conecte-se à VM.
2. Insira o nome de usuário e a senha configurados.
3. Verifique se a VM está funcionando corretamente.

* Com isso a máquina virtual estará criada.

