# Conceitos

- **GNU:** é o sistema operacional baseado no Unix. Uma coleção de muitos programas: apps, bibliotecas, ferramentas etc. Junto com o Linux (kernel) é instituido o SO completo GNU/Linux.

<br/>

- **Kernel:** é o nucleo do SO, componente responsavel por ligar os aplicativos e o processamento. Ele controla todas as principais funções do hardware!

<br/>

- **Virtualização:** criar uma versão virtual de algo, uma VM! 

<br/>

- **SystemD:** conjunto de softwares básicos que gerencia e fornece serviços para iniciar o resto do sistema. (init)

<br/>

- **FirmWare:** classe de software padrão e obrigatorio do sistema para funcionamento, mais baixo nível!

<br/>

- **BIOS/UEFI:** é a bios, atualmente só existe UEFI, mas pode ser iniciada como uma bios. 

<br/>

- **MBR/GPT:** são os discos, sendo o MBR da antiga bios e o GPT do UEFI. MBR é limitado a 4 partições (mas tem como dividr uma partição em mais), já o GPT é "ilimitado".

<br/>

- **VPN:** é uma ligação privada e segura entre dois "pontos", ela trafega pela internet pública mas com uma proteção de criptografia. 

<br/>

- **PAM:** um mediador entre o serviço e a autenticação a fim de garantir um nível de segurança entre as operações.

<br/>

- **GPG:** criptografia

    - **Simétrica**: um chave única para criptografar e descriptografar.
    - **Assimetrica:** par de chaves, criptografa com uma chave publica e descriptografa usando outra chave. As chaves são "ligadas".
    - **Hash:** código fixo de certo dado, usado para verificar/mapear. Qualquer alteração no dado modifica o Hash!

<br/>

- **BootLoader:** é um gerenciador que inicializa o SO.

    - **GRUB** e **SystemD** são exemplos.

<br/>

- **Logs:** são registros de eventos relevantes que acontecem no sistema. É usado para verificar mensagens de erro, quando há algo errado é lá que vai tá a informação.
