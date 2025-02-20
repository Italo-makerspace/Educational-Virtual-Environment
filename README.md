# Ambiente Virtual Educacional

## Introdução

Este projeto tem como objetivo criar um ambiente virtual para fins educacionais, que possibilite a execução de softwares como MySQL, Node.js e Python. A atividade integra conceitos de **Sistemas Operacionais**, **Redes de Computadores**, **Levantamento de Requisitos** e **Lógica de Programação**. No projeto, será realizada a pesquisa de componentes para a montagem de um computador com custo máximo de R$ 5.000,00, a configuração de uma máquina virtual e a instalação de uma distribuição Linux gratuita, escolhida com base na compatibilidade e facilidade de uso.

---

## Levantamento de Requisitos

### Requisitos para o Computador Físico

- **Processador (CPU):** Bom desempenho para multitarefa.
- **Memória RAM:** Idealmente 8GB (conforme o orçamento).
- **Armazenamento:** SSD para melhor desempenho.
- **Outros:** Placa-mãe, fonte de alimentação, etc.
- **Orçamento Máximo:** R$ 5.000,00

### Requisitos para a Máquina Virtual

- **Memória:** 4096 MB
- **CPU:** 6 Processadores
- **Armazenamento:** 2,00 GB
- **Rede:** NAT
---

## Pesquisa e Orçamento de Componentes

### Processador (CPU)

- **AMD Ryzen 5 5600G**
  - Preço aproximado: R$ 1.000,00
  - Justificativa: O Ryzen 5 5600G é um processador de 6 núcleos e 12 threads com ótimo desempenho para multitarefa e boa eficiência energética, adequado para aplicações como MySQL, Node.js e Python.
  - [Link para Processador](https://www.kabum.com.br/produto/134233/processador-amd-ryzen-5-5600g-4-4ghz-box)

### Memória RAM

- **Corsair Vengeance LPX, 32GB (2x16GB) 3200MHz DDR4 CL16**
  - Preço aproximado: R$ 700,00
  - Justificativa: O kit de 32GB oferece mais do que o suficiente para multitarefa em um ambiente de desenvolvimento, permitindo a execução simultânea de vários serviços como MySQL e Node.js.
  - [Link para Memória RAM](https://www.kabum.com.br/produto/102852/memoria-corsair-vengeance-lpx-32gb-2x16gb-3200mhz-ddr4-cl16-preto)

### Armazenamento (SSD)

- **SSD Sandisk Plus - 500GB, NVMe, M.2 2280**
  - Preço aproximado: R$ 330,00
  - Justificativa: SSD NVMe oferece excelente velocidade de leitura e gravação, ideal para o desempenho do sistema operacional e dos aplicativos.
  - [Link para SSD](https://www.kabum.com.br/produto/120003/ssd-sandisk-plus-500gb-nvme-m-2-2280)

### Placa-Mãe

- **ASRock B450M Steel Legend Micro ATX AM4**
  - Preço aproximado: R$ 600,00
  - Justificativa: A ASRock B450M oferece boa performance com suporte para o processador Ryzen 5 5600G, possui boas opções de conectividade e é uma boa escolha em termos de custo-benefício.
  - [Link para Placa-Mãe](https://www.kabum.com.br/produto/129076/placa-mae-asrock-b450m-steel-legend-micro-atx-am4)

### Fonte de Alimentação

- **MSI MAG A850GL PCIE5, 850W, 80 Plus Gold, Full Modular**
  - Preço aproximado: R$ 600,00
  - Justificativa: Fonte de alimentação de alta qualidade com 850W, eficiência 80 Plus Gold e certificação PCIe 5, que garante estabilidade e segurança para o sistema.
  - [Link para Fonte](https://www.kabum.com.br/produto/103273/fonte-msi-mag-a850gl-pcie5-850w-80-plus-gold-full-modular)

### Teclado Gamer

- **Teclado Gamer Redragon Lakshmi, Switch Brown, Layout 60%, ABNT2**
  - Preço aproximado: R$ 300,00
  - Justificativa: Teclado compacto e eficiente, com switches mecânicos tipo Brown, ideal para jogos e produtividade. O layout ABNT2 é compatível com o padrão brasileiro.
  - [Link para Teclado](https://www.kabum.com.br/produto/117801/teclado-gamer-redragon-lakshmi-switch-brown-layout-60-abnt2)

### Mouse Gamer

- **Mouse Redragon Cobra Chroma M711**
  - Preço aproximado: R$ 100,00
  - Justificativa: Mouse com bom custo-benefício, com design ergonômico e sensor preciso para aplicações de desenvolvimento e jogos.
  - [Link para Mouse](https://www.kabum.com.br/produto/119024/mouse-redragon-cobra-chroma-m711)

### Monitor

- **Monitor AOC 24G2E1 23.8″ 1920 x 1080 100 Hz**
  - Preço aproximado: R$ 1.100,00
  - Justificativa: Monitor com boa resolução e taxa de atualização de 100 Hz, oferecendo uma experiência visual mais fluida e confortável para o trabalho.
  - [Link para Monitor](https://www.kabum.com.br/produto/122345/monitor-aoc-24g2e1-23-8-1920-x-1080-100-hz)
 
  #### Total: R$4730,00

---

## Escolha do Sistema Operacional

Após comparar diversas distribuições Linux, a escolha recaiu sobre o **Ubuntu 22.04.5 LTS (Jammy Jellyfish)**, devido à sua compatibilidade e facilidade de uso.

---

## Manual de Instalação do Linux no VirtualBox

### Pré-requisitos

- **VirtualBox:** Baixe e instale a versão mais recente do [VirtualBox](https://www.virtualbox.org/).
- **Imagem ISO do Linux:** Faça o download da imagem ISO do Ubuntu em [Ubuntu Download](https://ubuntu.com/download).

---

### Passo a Passo

#### 1. Instalação do VirtualBox

1. Acesse o site do VirtualBox e baixe a versão para o seu sistema operacional.
2. Siga as instruções de instalação fornecidas.
3. Após a instalação, abra o **VirtualBox**.

#### 2. Criação da Máquina Virtual


1. **Clique em "Novo":**
   - **Nome:** VM-EDUCU
   - **Tipo:** Linux
   - **Versão:** Ubuntu 22.04.5 LTS (Jammy Jellyfish)
   
![Imagem](https://github.com/Italo-makerspace/Montagem-de-Ambiente-Virtual/blob/main/1.png?raw=true)

2. **Configuração de Memória:**
   - Alocar **4096 MB** de memória RAM para a máquina virtual.
  
![Imagem](https://github.com/Italo-makerspace/Montagem-de-Ambiente-Virtual/blob/main/2.png?raw=true)

4. **Criação do Disco Rígido Virtual:**
   - Selecione a opção **Criar disco rígido agora**.
   - Escolha o tipo de arquivo de disco **VDI (VirtualBox Disk Image)**.
   - Selecione a opção **dinâmico** para o tamanho do disco (por exemplo, **2 GB**).
  
![Imagem](https://github.com/Italo-makerspace/Montagem-de-Ambiente-Virtual/blob/main/3.png?raw=true)

#### 3. Configuração de Rede

1. Selecione a máquina virtual criada e clique em **Configurações**.
2. Acesse a aba **Rede** e configure como **NAT** 

#### 4. Configuração do Disco de Instalação

1. Acesse as configurações da máquina virtual e vá até a aba **Armazenamento**.
2. Selecione a opção de **unidade óptica** e adicione a imagem ISO do Ubuntu baixada.

#### 5. Iniciando a Instalação do Ubuntu

1. **Inicie a Máquina Virtual:**
   - Clique em **Iniciar** para carregar o Ubuntu a partir da ISO.
   
2. **Instalação Passo a Passo:**
   - Selecione o idioma de preferência.
   - Escolha as configurações de teclado.
   - Configure a rede e a instalação.
   - Se solicitado, conecte à internet para atualizações (opcional).

```bash
mysql --version
node -v
python3 --version
```
---

## Considerações Finais

### Lições Aprendidas

Neste projeto, várias lições importantes foram tiradas, tanto na parte do hardware quanto na configuração e uso de ambientes virtuais. As principais lições incluem:

1. **Escolha dos Componentes de Hardware:**
   - A escolha dos componentes certos é fundamental para montar um sistema equilibrado dentro de um orçamento limitado. Foi importante entender as necessidades de desempenho e compatibilidade entre o **AMD Ryzen 5 5600G** e a **Corsair Vengeance LPX 32GB**, garantindo uma boa performance para multitarefa e desenvolvimento sem ultrapassar o orçamento.

2. **Configuração da Máquina Virtual:**
   - A configuração do ambiente virtual foi uma etapa valiosa para entender como alocar recursos de maneira eficiente, como memória e núcleos de CPU. Além disso, foi necessário configurar o acesso à internet e outros recursos para instalar o sistema operacional e os softwares necessários.
   - A escolha do **Ubuntu 22.04.5 LTS** se mostrou acertada devido à facilidade de uso e grande suporte da comunidade, o que facilitou todo o processo.

3. **Instalação e Testes de Softwares:**
   - A instalação e testes de ferramentas como **MySQL**, **Node.js** e **Python** em uma máquina virtual ajudaram a entender como diferentes ambientes podem ser usados para rodar aplicativos de forma eficaz.
   - Embora o uso de **Docker** não tenha sido explorado no projeto, ele é uma boa alternativa para gerenciar versões de software e criar ambientes isolados, o que seria uma boa prática para o futuro.
  
--- 

### Sugestões de Melhoria

Apesar do projeto ter sido concluído com sucesso, sempre existem áreas para melhorar. Algumas sugestões incluem:

1. **Considerar o Uso de Docker ou Containers:**
   - O uso de **Docker** ou outras ferramentas de containerização poderia ser uma forma mais eficiente de criar ambientes isolados para desenvolvimento, além de tornar o processo de configuração mais rápido e flexível. Isso permitiria maior controle sobre as versões dos softwares e uma melhor escalabilidade.

2. **Aumentar a Memória RAM ou Armazenamento:**
   - Embora o orçamento tenha sido respeitado, seria interessante considerar a ampliação da memória RAM para 16GB ou mais, dependendo da demanda do ambiente. Além disso, aumentar a capacidade do SSD (por exemplo, para 1TB) poderia proporcionar mais flexibilidade para armazenar projetos maiores.

3. **Melhorar a Rede e Conectividade:**
   - A configuração de rede poderia ser otimizada, por exemplo, utilizando redes **Bridge** para um acesso mais direto à internet. Isso ajudaria a melhorar a performance da máquina virtual, especialmente para tarefas que exigem maior largura de banda.

4. **Automatizar o Processo de Instalação:**
   - A automação do processo de instalação e configuração poderia ser uma melhoria importante. Utilizar ferramentas como **Ansible** ou **Terraform** para criar e configurar ambientes automaticamente tornaria o processo mais eficiente e consistente, o que seria útil, especialmente em ambientes educacionais com múltiplos usuários.

5. **Experimentar Outras Distribuições Linux:**
   - Embora o **Ubuntu** tenha atendido bem às necessidades do projeto, explorar outras distribuições Linux, como **Fedora** ou **Debian**, pode ser interessante para entender suas diferenças e vantagens em relação ao Ubuntu. Isso ajudaria a expandir o conhecimento sobre as opções de sistemas operacionais.

6. **Implementar Soluções de Backup e Recuperação:**
   - Implementar uma solução de backup para ambientes virtuais e sistemas operacionais seria uma medida importante para garantir a proteção dos dados. Isso é especialmente relevante em projetos educacionais, onde a perda de dados pode afetar negativamente o andamento das atividades.
  
https://drive.google.com/file/d/1HNyJmnUlyzWilSpRo0wHW__ILilnd4ea/view?usp=drive_link
https://drive.google.com/file/d/1rnceFe2qzh-qZshZMv-WEstpSY1ABYlI/view?usp=drive_link
https://drive.google.com/file/d/1aYFJ1YVX5na-tJOKt-ubmfL9M6R3Uh_X/view?usp=drive_link
https://drive.google.com/file/d/10gpKvrtkkc1ZZizuKejrjMCjpQzAXnif/view?usp=drive_link

