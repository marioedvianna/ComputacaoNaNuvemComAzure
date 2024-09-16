# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

## Passo 1: Acessar o Portal do Azure
1. Acesse o Portal do Azure e faça login com suas credenciais.
2. No painel, procure por **Máquinas Virtuais** ou clique em **Criar Recurso** para iniciar a criação de uma nova VM.

## Passo 2: Criar a Máquina Virtual
1. Selecione uma assinatura e um grupo de recursos existente ou crie um novo.
2. Defina o nome da VM e escolha a região mais próxima dos seus usuários para obter melhor performance.
3. Selecione o sistema operacional desejado (Windows ou Linux) e a imagem correspondente.
4. Defina as credenciais de login:
   - Para Windows: nome de usuário e senha.
   - Para Linux: utilize chaves SSH para uma conexão mais segura.

## Passo 3: Configurar o Tamanho da Máquina Virtual
1. O tamanho da VM define a quantidade de CPU, memória e armazenamento temporário disponível.
2. Escolha o tamanho que melhor se ajuste à sua carga de trabalho:
   - **Tamanhos Gerais**: Adequado para aplicações comuns e balanceadas.
   - **Tamanhos Otimizados para Memória**: Ideal para bancos de dados e aplicações com alta demanda de RAM.
   - **Tamanhos Otimizados para Computação**: Recomendado para cargas que exigem alto poder de processamento.
3. **Dimensionamento Manual**: Escolha o tamanho de VM que atende às suas necessidades atuais. O Azure Advisor pode sugerir ajustes baseados em desempenho.
4. **Dimensionamento Automático**: Configure a autoescala para que o Azure ajuste automaticamente o número de instâncias com base na demanda. Isso é ideal para cargas de trabalho que variam ao longo do tempo.

## Passo 4: Configurar o Armazenamento
1. Na aba de **Discos**, selecione o tipo de disco mais adequado para sua VM:
   - **SSD Premium**: Recomendado para aplicações de alta performance e ambientes de produção.
   - **SSD Padrão**: Um meio-termo, para cargas moderadas.
   - **HDD Padrão**: Ideal para cargas com baixo custo e menor exigência de desempenho.
2. Adicione discos adicionais, se necessário, para separar dados de aplicação ou backups.

## Passo 5: Configurar a Rede
1. Na aba de **Rede**, associe a VM a uma Rede Virtual (VNet) existente ou crie uma nova.
2. Configure as seguintes opções:
   - **Sub-redes**: Defina sub-redes para segmentar a rede.
   - **Grupos de Segurança de Rede (NSG)**: Configure regras de segurança para controlar o tráfego de rede.
   - **IP Público**: Atribua um endereço IP público, se necessário, para acesso externo.

## Passo 6: Revisar e Criar
1. Clique em **Revisar + Criar**.
2. Revise todas as configurações e clique em **Criar** para iniciar a implantação da VM.

## Passo 7: Gerenciar e Dimensionar a VM
1. Após a implantação, vá para o recurso da VM no portal do Azure.
2. Para redimensionar a VM:
   - Navegue até **Tamanho** no menu à esquerda.
   - Escolha um novo tamanho de VM com base nas necessidades de CPU e memória.
   - Clique em **Redimensionar**.
3. Para configurar a autoescala:
   - Navegue até **Autoescala** no menu à esquerda.
   - Clique em **+ Adicionar uma regra**.
   - Defina as condições, como métrica (CPU, memória) e ação (escalar verticalmente ou horizontalmente).
   - Defina os parâmetros da ação, como o número máximo de instâncias e a quantidade de incremento.


A configuração de recursos e dimensionamento em máquinas virtuais do Azure é um processo fundamental para garantir o sucesso de suas aplicações na nuvem