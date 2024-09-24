## Passos para Criar uma Conta de Armazenamento

1. **Acesse o Portal do Azure**
   - Vá para o Portal do Azure.

2. **Navegue até Contas de Armazenamento**
   - No menu à esquerda, selecione **Contas de Armazenamento**.

3. **Criar uma Nova Conta de Armazenamento**
   - Clique em **+ Criar**.
   - Preencha os detalhes necessários:
     - **Assinatura**: Selecione sua assinatura do Azure. ( Standard ou Premium[cenários de baixa latência] )
     - **Grupo de Recursos**: Escolha um grupo de recursos existente ou crie um novo.
     - **Nome da Conta de Armazenamento**: Insira um nome único para sua conta de armazenamento.
     - **Região**: Selecione a região onde deseja criar a conta de armazenamento.
     - **Desempenho**: Escolha entre Standard ou Premium.
     - **Replicação**: Selecione a opção de replicação desejada (LRS, GRS, RA-GRS, etc.).

4. **Configurações Adicionais**
   - Configure as opções adicionais conforme necessário, como segurança, rede e tags.

5. **Revisar e Criar**
   - Revise suas configurações e clique em **Criar**.

# Como Criar um Compartilhamento de Arquivos no Azure

## Passos para Criar um Compartilhamento de Arquivos

1. **Acesse o Portal do Azure**
   - Vá para o Portal do Azure.

2. **Navegue até a Conta de Armazenamento**
   - No menu à esquerda, selecione **Contas de Armazenamento**.
   - Selecione a conta de armazenamento onde deseja criar o compartilhamento de arquivos.

3. **Criar um Compartilhamento de Arquivos**
   - No menu de serviço, em **Armazenamento de Dados**, selecione **Compartilhamentos de Arquivos**.
   - Clique em **+ Compartilhamento de Arquivo**.
   - Preencha os detalhes necessários:
     - **Nome**: Insira um nome para o compartilhamento de arquivos.
     - **Camada de Acesso**: Escolha a camada de acesso (Transação otimizada, Hot, Cool, etc.).

4. **Configurações Adicionais**
   - Configure as opções adicionais conforme necessário, como cota de armazenamento e políticas de backup.

5. **Criar o Compartilhamento**
   - Clique em **Criar** para finalizar a criação do compartilhamento de arquivos.

## Montar o Compartilhamento de Arquivos no Windows

1. **Obter o Script de Conexão**
   - No portal do Azure, navegue até o compartilhamento de arquivos que você criou.
   - Selecione **Conectar**.
   - Escolha a letra da unidade que deseja usar e copie o script de conexão.

2. **Executar o Script no Windows**
   - Abra o **PowerShell** no seu computador.
   - Cole e execute o script de conexão copiado.


# Como Criar um Compartilhamento de Arquivos no Azure

## Passos para Criar um Compartilhamento de Arquivos

1. **Acesse o Portal do Azure**
   - Vá para o Portal do Azure.

2. **Navegue até a Conta de Armazenamento**
   - No menu à esquerda, selecione **Contas de Armazenamento**.
   - Selecione a conta de armazenamento onde deseja criar o compartilhamento de arquivos.

3. **Criar um Compartilhamento de Arquivos**
   - No menu de serviço, em **Armazenamento de Dados**, selecione **Compartilhamentos de Arquivos**.
   - Clique em **+ Compartilhamento de Arquivo**.
   - Preencha os detalhes necessários:
     - **Nome**: Insira um nome para o compartilhamento de arquivos.
     - **Camada de Acesso**: Escolha a camada de acesso (Transação otimizada, Hot, Cool, etc.).

4. **Configurações Adicionais**
   - Configure as opções adicionais conforme necessário, como cota de armazenamento e políticas de backup.

5. **Criar o Compartilhamento**
   - Clique em **Criar** para finalizar a criação do compartilhamento de arquivos.

## Montar o Compartilhamento de Arquivos no Windows

1. **Obter o Script de Conexão**
   - No portal do Azure, navegue até o compartilhamento de arquivos que você criou.
   - Selecione **Conectar**.
   - Escolha a letra da unidade que deseja usar e copie o script de conexão.

2. **Executar o Script no Windows**
   - Abra o **PowerShell** no seu computador.
   - Cole e execute o script de conexão copiado.
