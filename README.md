# Ambiente Virtual Educacional

## Introdução
Este projeto tem como objetivo criar um ambiente virtual para fins educacionais, que possibilite a execução de softwares como MySQL, Node.js e Python. A atividade integra conceitos de Sistemas Operacionais, Redes de Computadores, Levantamento de Requisitos e Lógica de Programação. Nele, você pesquisará componentes para a montagem de um computador com custo máximo de R$ 5.000,00, configurará uma máquina virtual e instalará uma distribuição Linux gratuita, escolhida com base na compatibilidade e facilidade de uso.

## Levantamento de Requisitos

### Requisitos para o Computador Físico
- **Processador (CPU):** Bom desempenho para multitarefa.
- **Memória RAM:** Idealmente 8GB (conforme o orçamento).
- **Armazenamento:** SSD para melhor desempenho.
- **Outros:** Placa-mãe, fonte de alimentação, etc.
- **Orçamento Máximo:** R$ 5.000,00

### Requisitos para a Máquina Virtual
- **Memória:** 4096
- **CPU:** 6 Processadores
- **Armazenamento** 2,00 GB
- **Rede:** Configuração via NAT ou Bridge para acesso à internet

## Pesquisa e Orçamento de Componentes
- **Exemplo de Link para Processador:** [Processador X](#)
- **Exemplo de Link para Memória RAM:** [Memória Y](#)
- *(Inclua aqui os demais componentes com seus respectivos links e justificativas de escolha)*

## Escolha do Sistema Operacional
Após comparar distribuições Linux....

## Manual de Instalação do Linux no VirtualBox

### Pré-requisitos
- **VirtualBox:** Baixe e instale a versão mais recente do [VirtualBox](https://www.virtualbox.org/).
- **Imagem ISO do Linux:** Faça o download da imagem ISO do Ubuntu em [Ubuntu Download](https://ubuntu.com/download).

### Passo a Passo

#### 1. Instalação do VirtualBox
- Acesse o site do VirtualBox e baixe a versão para seu sistema operacional.
- Siga as instruções de instalação fornecidas.
- Após a instalação, abra o VirtualBox.

#### 2. Criação da Máquina Virtual
1. **Clique em "Novo":**
   - **Nome:**VM-EDUCU
   - **Tipo:**Linux
   - **Versão:**Ubuntu 22.04.5 LTS (Jammy Jellyfish)

2. **Configuração de Memória:**
   - ...

3. **Criação do Disco Rígido Virtual:**
   - ......
   - ......
   - ......

#### 3. Configuração de Rede
- Selecione a máquina virtual criada e clique em "Configurações".
- ......
- ......

#### 4. Configuração do Disco de Instalação
- .......
- .......

#### 5. Iniciando a Instalação do Ubuntu
1. **Inicie a Máquina Virtual:**
   - ...........

2. **Instalação Passo a Passo:**
   - ......
   - ......
   - Se solicitado, conecte à internet para atualizações (opcional).

#### 6. Pós-Instalação e Testes
- Após a instalação, a máquina virtual reiniciará.
- Faça login com as credenciais criadas.
- Abra o terminal e verifique a instalação dos softwares executando os seguintes comandos:
  ```bash 
  mysql --version
  node -v
  python3 --version
