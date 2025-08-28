# Criando uma máquina virtual Windows no Azure

## 1. Configurar a VM
Primeiro tive que configurar a máquina virtual que eu queria, que era o **Windows Server 2025**.  
Coloquei o nome de `myVM`, cadastrei um usuário e uma senha, e habilitei a porta **RDP (3389)**.

---

## 2. Conectando a máquina
Após fazer a configuração e criar a VM, cliquei em **Conectar**, baixei o arquivo `.rdp` e depois abri ele na minha máquina utilizando o usuário e senha configurados no início.

---

## 3. Dentro da VM
Dentro da VM, abri o **PowerShell** e rodei o seguinte comando:

```powershell
Install-WindowsFeature -Name Web-Server -IncludeManagementTools
```

## 4. Deletando os recursos
Para não gastar créditos, deletei minha VM e seus recursos, já que foram utilizados apenas para aprendizado.
