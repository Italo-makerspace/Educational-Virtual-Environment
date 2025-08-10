Educational Virtual Environment
===============================

Introduction
------------

This project aims to create a virtual environment for educational purposes, enabling the execution of software such as MySQL, Node.js, and Python. The activity integrates concepts from **Operating Systems**, **Computer Networks**, **Requirements Gathering**, and **Programming Logic**. The project involves researching components to build a computer with a maximum cost of R$ 5,000.00, configuring a virtual machine, and installing a free Linux distribution chosen based on compatibility and ease of use.

Requirements Gathering
----------------------

### Requirements for the Physical Computer

-   **Processor (CPU):** Good performance for multitasking.

-   **RAM:** Ideally 8GB (depending on the budget).

-   **Storage:** SSD for better performance.

-   **Other:** Motherboard, power supply, etc.

-   **Maximum Budget:** R$ 5,000.00 (approx. $925 USD)

### Requirements for the Virtual Machine

-   **Memory:** 4096 MB

-   **CPU:** 6 Processors

-   **Storage:** 2.00 GB

-   **Network:** NAT

Component Research and Budgeting
--------------------------------

*Note: USD prices are approximate and based on an exchange rate of 1 USD = 5.40 BRL.*

### Processor (CPU)

-   **AMD Ryzen 5 5600G**

    -   Approximate Price: R$ 1,000.00 (approx. $185 USD)

    -   Justification: The Ryzen 5 5600G is a 6-core, 12-thread processor with excellent multitasking performance and good energy efficiency, suitable for applications like MySQL, Node.js, and Python.

    -   [Link to Processor](https://www.kabum.com.br/produto/134233/processador-amd-ryzen-5-5600g-4-4ghz-box "null")

### RAM

-   **Corsair Vengeance LPX, 32GB (2x16GB) 3200MHz DDR4 CL16**

    -   Approximate Price: R$ 700.00 (approx. $130 USD)

    -   Justification: The 32GB kit offers more than enough memory for multitasking in a development environment, allowing the simultaneous execution of multiple services like MySQL and Node.js.

    -   [Link to RAM](https://www.kabum.com.br/produto/102852/memoria-corsair-vengeance-lpx-32gb-2x16gb-3200mhz-ddr4-cl16-preto "null")

### Storage (SSD)

-   **SanDisk Plus SSD - 500GB, NVMe, M.2 2280**

    -   Approximate Price: R$ 330.00 (approx. $61 USD)

    -   Justification: An NVMe SSD offers excellent read and write speeds, ideal for the performance of the operating system and applications.

    -   [Link to SSD](https://www.kabum.com.br/produto/120003/ssd-sandisk-plus-500gb-nvme-m-2-2280 "null")

### Motherboard

-   **ASRock B450M Steel Legend Micro ATX AM4**

    -   Approximate Price: R$ 600.00 (approx. $111 USD)

    -   Justification: The ASRock B450M offers good performance with support for the Ryzen 5 5600G processor, has good connectivity options, and is a great choice in terms of cost-effectiveness.

    -   [Link to Motherboard](https://www.kabum.com.br/produto/129076/placa-mae-asrock-b450m-steel-legend-micro-atx-am4 "null")

### Power Supply

-   **MSI MAG A850GL PCIE5, 850W, 80 Plus Gold, Full Modular**

    -   Approximate Price: R$ 600.00 (approx. $111 USD)

    -   Justification: A high-quality power supply with 850W, 80 Plus Gold efficiency, and PCIe 5 certification, ensuring stability and safety for the system.

    -   [Link to Power Supply](https://www.kabum.com.br/produto/103273/fonte-msi-mag-a850gl-pcie5-850w-80-plus-gold-full-modular "null")

### Keyboard

-   **Redragon Lakshmi Keyboard, Brown Switch, 60% Layout, ABNT2**

    -   Approximate Price: R$ 300.00 (approx. $56 USD)

    -   Justification: A compact and efficient keyboard with Brown mechanical switches, ideal for gaming and productivity. The ABNT2 layout is compatible with the Brazilian standard.

    -   [Link to Keyboard](https://www.kabum.com.br/produto/117801/teclado-gamer-redragon-lakshmi-switch-brown-layout-60-abnt2 "null")

### Mouse

-   **Redragon Cobra Chroma M711 Mouse**

    -   Approximate Price: R$ 100.00 (approx. $19 USD)

    -   Justification: A cost-effective mouse with an ergonomic design and a precise sensor for development and gaming applications.

    -   [Link to Mouse](https://www.kabum.com.br/produto/119024/mouse-redragon-cobra-chroma-m711 "null")

### Monitor

-   **AOC 24G2E1 23.8" 1920 x 1080 100 Hz Monitor**

    -   Approximate Price: R$ 1,100.00 (approx. $204 USD)

    -   Justification: A monitor with good resolution and a 100 Hz refresh rate, offering a smoother and more comfortable visual experience for work.

    -   [Link to Monitor](https://www.kabum.com.br/produto/122345/monitor-aoc-24g2e1-23-8-1920-x-1080-100-hz "null")

### Total: R$ 4,730.00 (approx. $876 USD)

Configuration
-------------

-   **Processor:** AMD Ryzen 5 5600G

-   **RAM:** Corsair Vengeance LPX 32GB (2x16GB) 3200MHz DDR4

-   **Storage (SSD):** SanDisk Plus 500GB NVMe M.2

-   **Motherboard:** ASRock B450M Steel Legend Micro ATX AM4

-   **Power Supply:** MSI MAG A850GL 850W 80 Plus Gold

-   **Keyboard:** Redragon Lakshmi Switch Brown 60% Layout ABNT2

-   **Mouse:** Redragon Cobra Chroma M711

-   **Monitor:** AOC 24G2E1 23.8" 100Hz

Operating System Choice
-----------------------

After comparing several Linux distributions, the choice was **Ubuntu 22.04.5 LTS (Jammy Jellyfish)**, due to its compatibility and ease of use.

Linux Installation Manual on VirtualBox
---------------------------------------

### Prerequisites

-   **VirtualBox:** Download and install the latest version from [VirtualBox](https://www.virtualbox.org/ "null").

-   **Linux ISO Image:** Download the Ubuntu ISO image from [Ubuntu Download](https://ubuntu.com/download "null").

### Step-by-Step

#### 1\. Installing VirtualBox

1.  Go to the VirtualBox website and download the version for your operating system.

2.  Follow the provided installation instructions.

3.  After installation, open **VirtualBox**.

#### 2\. Creating the Virtual Machine

1.  **Click "New":**

    -   **Name:** VM-EDUCU

    -   **Type:** Linux

    -   **Version:** Ubuntu 22.04.5 LTS (Jammy Jellyfish)
![Image](https://github.com/italo-makerspace/Educational-Virtual-Environment/blob/main/1.png?raw=true)

2.  **Memory Configuration:**

    -   Allocate **4096 MB** of RAM to the virtual machine.
![Image](https://github.com/italo-makerspace/Educational-Virtual-Environment/blob/main/2.png?raw=true)

3.  **Virtual Hard Disk Creation:**

    -   Select the **Create a virtual hard disk now** option.

    -   Choose the disk file type **VDI (VirtualBox Disk Image)**.

    -   Select the **Dynamically allocated** option for the disk size (e.g., **2 GB**).
![Image](https://github.com/italo-makerspace/Educational-Virtual-Environment/blob/main/3.png?raw=true)

#### 3\. Network Configuration

![Image](https://github.com/italo-makerspace/Educational-Virtual-Environment/blob/main/4.png?raw=true)

1.  Select the created virtual machine and click on **Settings**.

2.  Go to the **Network** tab and configure it as **NAT**.

![Image](https://github.com/italo-makerspace/Educational-Virtual-Environment/blob/main/5.png?raw=true)

#### 4\. Installation Disk Configuration

1.  Go to the virtual machine settings and navigate to the **Storage** tab.

2.  Select the **optical drive** option and add the downloaded Ubuntu ISO image.

#### 5\. Starting the Ubuntu Installation

1.  **Start the Virtual Machine:**

    -   Click **Start** to load Ubuntu from the ISO.

2.  **Step-by-Step Installation:**

    -   Select your preferred language.

    -   Choose keyboard settings.

    -   Configure the network and installation.

    -   If prompted, connect to the internet for updates.

```
mysql --version
node -v
python3 --version

```

Final Considerations
--------------------

### Lessons Learned

Several important lessons were learned in this project, both on the hardware side and in the configuration and use of virtual environments. The main lessons include:

1.  **Hardware Component Selection:**

    -   Choosing the right components is crucial for building a balanced system within a limited budget. It was important to understand the performance and compatibility needs between the **AMD Ryzen 5 5600G** and the **Corsair Vengeance LPX 32GB**, ensuring good performance for multitasking and development without exceeding the budget.

2.  **Virtual Machine Configuration:**

    -   Configuring the virtual environment was a valuable step in understanding how to allocate resources efficiently, such as memory and CPU cores. Additionally, it was necessary to configure internet access and other resources to install the operating system and required software.

    -   The choice of **Ubuntu 22.04.5 LTS** proved to be correct due to its ease of use and large community support, which facilitated the entire process.

3.  **Software Installation and Testing:**

    -   Installing and testing tools like **MySQL**, **Node.js**, and **Python** in a virtual machine helped in understanding how different environments can be used to run applications effectively.

    -   Although **Docker** was not explored in the project, it is a good alternative for managing software versions and creating isolated environments, which would be a good practice for the future.

### Suggestions for Improvement

Although the project was successfully completed, there are always areas for improvement. Some suggestions include:

1.  **Consider Using Docker or Containers:**

    -   Using **Docker** or other containerization tools could be a more efficient way to create isolated development environments, in addition to making the configuration process faster and more flexible. This would allow for greater control over software versions and better scalability.

2.  **Increase RAM or Storage:**

    -   Although the budget was respected, it would be interesting to consider expanding the RAM to 16GB or more, depending on the environment's demand. Additionally, increasing the SSD capacity (e.g., to 1TB) could provide more flexibility for storing larger projects.

3.  **Improve Network and Connectivity:**

    -   The network configuration could be optimized, for example, by using **Bridged** networking for more direct internet access. This would help improve the virtual machine's performance, especially for tasks requiring higher bandwidth.

4.  **Automate the Installation Process:**

    -   Automating the installation and configuration process could be a significant improvement. Using tools like **Ansible** or **Terraform** to create and configure environments automatically would make the process more efficient and consistent, which would be useful, especially in educational environments with multiple users.

5.  **Experiment with Other Linux Distributions:**

    -   Although **Ubuntu** met the project's needs well, exploring other Linux distributions, such as **Fedora** or **Debian**, could be interesting to understand their differences and advantages over Ubuntu. This would help expand knowledge about operating system options.

6.  **Implement Backup and Recovery Solutions:**

    -   Implementing a backup solution for virtual environments and operating systems would be an important measure to ensure data protection. This is especially relevant in educational projects, where data loss can negatively affect the progress of activities.
