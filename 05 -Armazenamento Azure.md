# Configurando Armazenamento no Azure | Migração de Dados

Este guia fornece um passo a passo simples para configurar uma Conta de Armazenamento no Azure e preparar a migração de dados.

## Passo a Passo para Configurar Armazenamento no Azure

### 1. Acesse o Portal do Azure 🌐
- Acesse o [Portal do Azure](https://portal.azure.com).
- No painel de navegação, procure por **"Conta de Armazenamento"** e clique em **"Criar"**.

### 2. Configure a Conta de Armazenamento ➕
- **Nome da Conta**: Escolha um nome único para a sua conta de armazenamento (por exemplo: `minhaempresaarmazenamento`).
  
- **Região**: Selecione a região mais próxima de sua localização ou da de seus usuários para garantir melhor performance.

- **Tipo de Conta**: Escolha **"Armazenamento General Purpose v2"** (recomendado para a maioria dos cenários).

- **Replicação**: Selecione o tipo de replicação conforme sua necessidade:
  - **LRS (Locally Redundant Storage)**: Replicação dentro de um único datacenter.
  - Outras opções incluem ZRS (Zone-Redundant Storage), GRS (Geo-Redundant Storage), etc.

### 3. Configurações Avançadas (Opcional)
- Personalize a configuração de segurança, redes virtuais e criptografia, conforme necessário.

### 4. Revisão e Criação
- Revise suas configurações.
- Clique em **"Criar"** para provisionar a nova conta de armazenamento.

## Migração de Dados

Após configurar sua Conta de Armazenamento no Azure, você pode migrar seus dados utilizando várias opções:

### 1. **Azure Storage Explorer**
Ferramenta gráfica que permite gerenciar e mover arquivos para o Azure Storage.

- [Download do Azure Storage Explorer](https://azure.microsoft.com/features/storage-explorer/).

### 2. **AzCopy**
Uma ferramenta de linha de comando para realizar cópias de grandes volumes de dados para o Azure.

- [Guia de uso do AzCopy](https://learn.microsoft.com/azure/storage/common/storage-use-azcopy).

### 3. **Azure Data Box**
Para grandes volumes de dados, o Azure oferece o serviço de hardware Azure Data Box, que facilita o envio físico de seus dados para o datacenter do Azure.

- [Mais informações sobre o Azure Data Box](https://azure.microsoft.com/services/databox/).

## Recursos Úteis
- [Documentação Oficial do Azure Storage](https://learn.microsoft.com/azure/storage/)
- [Preços do Azure Storage](https://azure.microsoft.com/pricing/details/storage/)

---

