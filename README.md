# 💻 Azure Virtual Machines – Desafio de Laboratório

Este repositório faz parte de um laboratório prático com o objetivo de consolidar conhecimentos sobre a criação e o uso de Máquinas Virtuais (VMs) na **Microsoft Azure**, utilizando o **Portal do Azure**.

---

## 🚀 Benefícios de Usar Máquinas Virtuais na Azure

As Máquinas Virtuais da Azure oferecem uma infraestrutura flexível, escalável e segura para execução de sistemas operacionais e aplicativos. Abaixo, listamos os principais benefícios:

### ✅ Implantação Rápida
Você pode criar e configurar uma VM em poucos minutos pelo **Portal do Azure**, escolhendo entre diversas imagens pré-configuradas (como Windows Server, Ubuntu, etc.).

### ✅ Flexibilidade de Configuração
É possível ajustar recursos como CPU, memória, disco e rede de acordo com as necessidades da aplicação, com facilidade de redimensionamento posterior.

### ✅ Acesso Remoto
Após a criação, a VM pode ser acessada remotamente por RDP (Windows) ou SSH (Linux), permitindo administração e uso como um computador tradicional.

### ✅ Integração com Outros Serviços Azure
As VMs se integram facilmente com redes virtuais, balanceadores de carga, discos gerenciados, Azure Monitor, entre outros.

### ✅ Disponibilidade e Redundância
Com opções como zonas de disponibilidade e escalonamento, é possível garantir alta disponibilidade e resiliência para cargas de trabalho críticas.

---

## 🧭 Passo a Passo: Criar uma Máquina Virtual (VM) no Azure

A seguir, o guia rápido para criar uma VM com Windows pelo Portal do Azure:

### 1. Acessar o Portal
Acesse o [Portal do Azure](https://portal.azure.com) com sua conta.

### 2. Criar um Novo Recurso
- Clique em **"Criar um recurso"**.
- Selecione **"Máquina virtual"**.

### 3. Configurar Informações Básicas
- **Assinatura** e **Grupo de Recursos**: selecione ou crie um novo.
- **Nome da VM**: defina um nome para a máquina virtual.
- **Região**: escolha a localização (ex: Brasil Sul).
- **Imagem**: selecione uma imagem do sistema operacional (ex: Windows Server 2022).
- **Tamanho**: escolha a especificação de hardware da VM.
- **Usuário administrador**: defina nome de usuário e senha.

### 4. Regras de Entrada
- Permita **porta 3389 (RDP)** para acesso remoto via Área de Trabalho Remota.

### 5. Discos e Rede
- Selecione as opções de disco padrão (geralmente SSD Premium ou Padrão).
- Mantenha as configurações de rede padrão (rede virtual e IP público automático).

### 6. Revisar e Criar
- Clique em **"Revisar + criar"**.
- Verifique as configurações e clique em **"Criar"**.

### 7. Conectar-se à VM
- Após a implantação, vá até o recurso da VM.
- Clique em **"Conectar"** → **"RDP"**.
- Baixe o arquivo `.rdp` e abra para acessar a VM com as credenciais criadas.

---

## 📚 Documentação Oficial

- [Início Rápido: Criar uma máquina virtual do Windows no Portal do Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)

---

## 🧠 Dicas Finais

- Lembre-se de **parar ou excluir a VM** após o uso, para evitar cobranças desnecessárias.
- Explore o **Azure Monitor** e as **métricas de desempenho** da VM após a criação.
- Teste também VMs com **Linux**, que seguem um processo semelhante de criação.

---

📬 **Dúvidas ou sugestões?** Abra uma issue neste repositório!
