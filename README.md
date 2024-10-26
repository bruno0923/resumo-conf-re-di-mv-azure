# resumo-conf-re-di-mv-azure
Configurando recursos e Dimensionamentos em máquinas Virtuais na azure

1. Acessar o Portal da Azure
  * Entre no [Portal Azure](https ://pore fachada 

2. Criar um Novo Recurso de Máquina Virtual
  * "Criar um recurso" .
  * Em seguida, selecione "Virtual Machine" na

Configurar a Máquina Virtual

Preencha as informações básicas:
  * Assinatura : selec
  * Grupo de recursos : crie
  * Nome da VM : d
  * Região : es
  * Opções de disponibilidade : sZona de disponibilidade par
  * Imagem :
  * Tamanho: seStandard_B2s ouD_v3-series , com especific
  
3. Escolher o Tamanho e os Recursos
   
  * Clique em Tamanhoe
  * Série B para ambientes deSérie M p
  
4. Configurar o Armazenamento
   
No painel Disks , escolha
    * HDD padrão paSSD padrão paSSD Premiumpára
Você também pode adicionar discos adicionais para armazenar dados

5. Configurar a Rede

No painel Networking ,
  * Rede virtual (VNet): usar
  * Sub-rede :
  * IP público : crie
  * Grupo de segurança de rede (NSG): contra
    
6. Configurar o Autoescalamento (Auto-Scaling)

Conjuntos de escala de máquina virtual não
Crie um novo Scale Set para a VM e configure:
  * Contagem de instâncias :
  * Condições de autoescala: de
Isso permite que o Azure adicione ou remova instâncias automaticamente com base na carga.

7. Revisar e Criar uma VM
   
Clique em Rever + criarpar
Após confirmar, clique em Criar pa

8. Acessar e Gerenciar a VM
   
Quando a VM estiver pronta, vá até o painel de Máquinas Virtuais .
Você pode iniciar, parar, redimensionar ou conectar-se à VM por SSH (Linux) ou RDP (Windows) e acompanhar o uso de recursos.
