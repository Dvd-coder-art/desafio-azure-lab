# Desafio Azure - Criação e Configuração de Máquina Virtual
## Introdução
Neste desafio, o objetivo foi criar e configurar uma máquina virtual (VM) na plataforma Microsoft Azure, colocando em prática os conceitos de computação em nuvem que foram abordados até o momento. O processo envolveu o uso de recursos do Azure, como criação de VMs, configuração de rede e integração com outros serviços.

Este repositório contém um guia passo a passo para a criação de uma VM, dicas sobre o uso do Azure e capturas de tela que ilustram as etapas do processo.

## Passos para Criar a Máquina Virtual no Azure
### 1. Acessando o Portal do Azure
Primeiro, acesse o Portal do Azure.

Faça login com sua conta Microsoft ou crie uma nova se necessário.

### 2. Criando a Máquina Virtual
No painel principal, clique em "Criar um recurso".

Selecione "Máquina Virtual" na lista de serviços disponíveis.

Preencha as informações do recurso:

Nome da VM: Escolha um nome único.

Assinatura: Escolha a assinatura ativa.

Grupo de Recursos: Crie um novo grupo ou selecione um existente.

Região: Escolha a região mais próxima para sua VM.

Sistema Operacional: Escolha a versão do Windows ou Linux que você deseja.

Tamanho da VM: Escolha um tipo de máquina adequado (ex: "B1s" para teste).

### 3. Configuração de Rede
Configure a rede virtual (VNet) e sub-rede para sua VM.

Habilite a opção de acesso público (se necessário) e crie ou selecione um grupo de segurança de rede (NSG) para permitir conexões.

### 4. Configuração de Discos e Armazenamento
Escolha o tipo de disco para sua máquina (SSD ou HDD).

Caso necessário, adicione discos adicionais.

### 5. Revisão e Criação
Revise todas as configurações e clique em "Criar".

Após a criação, aguarde alguns minutos até que a VM esteja disponível.

### 6. Conectando-se à Máquina Virtual
Após a criação, você pode se conectar à VM usando RDP (para Windows) ou SSH (para Linux).

Baixe o arquivo RDP ou use as credenciais de SSH para se conectar.

## Dicas e Boas Práticas
Gerenciamento de Custos: Acompanhe os custos da sua VM utilizando o Azure Cost Management.

Segurança: Sempre configure grupos de segurança de rede (NSG) e utilize autenticação multifatorial (MFA) para acessos mais seguros.

Backup: Considere usar o Azure Backup para garantir a segurança dos seus dados.

## Capturas de Tela
Abaixo estão algumas capturas de tela que documentam o processo de criação da máquina virtual:


## Conclusão
Este desafio proporcionou uma compreensão prática do processo de criação e gerenciamento de máquinas virtuais no Azure, além de aprender sobre configurações de rede, discos e segurança na nuvem. Com isso, você estará mais preparado para trabalhar com ambientes de nuvem reais e utilizar os recursos do Azure para implementação de soluções escaláveis.

