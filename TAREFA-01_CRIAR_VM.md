**Passos para a criação de uma máquina virtual no Azure**:

A assinatura já estava previamente selecionada (Azure subscription 1).

Em Grupos de Recursos, criei um novo grupo. Antes, verifiquei que grupos de recursos são coleções de recursos que compartilham o mesmo ciclo de vida, permissões e políticas de gerenciamento.

Defini o nome da máquina virtual como vm01.

Escolhi a região East US.

Na opção de disponibilidade, selecionei "Nenhuma redundância".

Em Tipo de segurança, optei pela configuração padrão.

Para a imagem do sistema operacional, escolhi o Ubuntu Server 24.04 LTS (gratuito).

Mantive a arquitetura como x64.

No tamanho da VM, selecionei a opção Standard_B1 (gratuita).

Para a conta de administrador, deixei as opções padrão:

Usuário: azureuser

Geração de um novo par de chaves públicas SSH (RSA)

Nome do par de chaves: vm01_key

Nas regras de portas de entrada, habilitei apenas a porta 22 (SSH).

No disco do sistema operacional, mantive a imagem padrão: 30 GiB, SSD Premium, sem adicionar discos de dados.

Em Rede, mantive as configurações padrão:

  - VNet: vm01-vnet

  - Sub-rede: 10.0.0.0/24

Demais opções também deixadas como padrão

Por fim, revisei todas as configurações e cliquei em "Revisar e criar".

![image](https://github.com/user-attachments/assets/d24fb23b-c7e2-4ed5-ad17-3d6e0edbe078)

Testado o acesso a VM via SSH.

![image](https://github.com/user-attachments/assets/f5194a33-9c64-4d9d-8c75-44e5db64183f)




