# Configurando Recursos e Dimensionamento em Máquinas Virtuais na Azure

Este guia descreve o processo de configuração de recursos e dimensionamento de máquinas virtuais (VMs) na Azure, para garantir um uso eficiente dos recursos de computação.

## Sumário

1. [Pré-requisitos](#pré-requisitos)
2. [Criando uma Máquina Virtual na Azure](#criando-uma-máquina-virtual-na-azure)
3. [Dimensionando Máquinas Virtuais](#dimensionando-máquinas-virtuais)
4. [Configurando Recursos de Máquina Virtual](#configurando-recursos-de-máquina-virtual)
5. [Dimensionamento Vertical e Horizontal](#dimensionamento-vertical-e-horizontal)
6. [Monitoramento de Utilização](#monitoramento-de-utilização)
7. [Conclusão](#conclusão)

---

## Pré-requisitos

- Uma conta na **Azure** com permissões adequadas para criar e gerenciar recursos.
- **Azure CLI** ou **Azure Portal** configurados.
- Familiaridade com conceitos de **computação em nuvem** e **máquinas virtuais**.

## Criando uma Máquina Virtual na Azure

1. Acesse o **Azure Portal** e vá até a seção "Máquinas Virtuais".
2. Clique em "Criar" e selecione "Máquina Virtual".
3. Preencha as informações básicas:
   - **Nome da VM**: Nome da sua máquina virtual.
   - **Região**: Selecione a região que melhor atende às suas necessidades.
   - **Tamanho da VM**: Escolha o tipo e o tamanho de acordo com os requisitos de processamento e memória.
4. Selecione as opções de **sistema operacional**, **rede**, e **armazenamento** de acordo com suas necessidades.

### Exemplo usando Azure CLI

az vm create \
  --resource-group MeuGrupoDeRecursos \
  --name MinhaVM \
  --image UbuntuLTS \
  --size Standard_B1s \
  --admin-username meuUsuario \
  --generate-ssh-keys



## Dimensionando Máquinas Virtuais
O dimensionamento de uma máquina virtual na Azure se refere ao ajuste da capacidade de recursos de CPU e memória para atender a demandas variáveis. Existem dois tipos principais de dimensionamento: Vertical e Horizontal.

Alterando o Tamanho da Máquina Virtual
Acesse o Azure Portal e selecione sua máquina virtual.
No painel lateral, clique em "Tamanho" (Size).
Selecione o novo tamanho da VM com base nos recursos necessários (CPU, memória, etc.).
Clique em "Redimensionar".
