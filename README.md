## Tutorial de Sistema virtual Linux

![sistema_linux](https://github.com/user-attachments/assets/f80d6792-87fe-40b9-af08-7a909e96eeaf)



## Passo 1: Baixe e instale o VirtualBox

- Acesse o site oficial do VirtualBox :
https://www.virtualbox.org/


- Baixe o VirtualBox .

- Escolha a versão para Windows Hosts .
- Instalar o VirtualBox :

- Execute o arquivo baixado.
- Siga o assistente de instalação, mantendo as opções padrão.
- Clique em Instalar e, quando solicitado, permita a instalação de drivers.
- Finalize a instalação clicando em Concluir .



## Passo 2: Baixe a ISO do Linux

- Escolha uma distribuição Linux, como:

- Ubuntu : ubuntu.com/download .​​
- Fedora : getfedora .org .
- Linux Mint : linuxmint.com/download.php .​​
- Baixe o arquivo ISO correspondente:

- se de escolher a versão para arquitetura verifique 64 bits .

## Passo 3: Configurar uma máquina virtual
- Abra o VirtualBox :

![sistema_1](https://github.com/user-attachments/assets/8b565934-6feb-4238-b65f-46472b736938)


- Clique no botão Novo .
Configure uma nova máquina virtual :

- Nome : Insira o nome da máquina virtual (ex.: Ubuntu).
- Tipo : Selecione Linux .
- Versão : Escolha a versão do Linux correspondente à ISO (ex.: Ubuntu 64 bits).
- Clique em Avançar .
- Definir a memória RAM :

![sistema_2](https://github.com/user-attachments/assets/73ffef92-4ec2-41b7-bf7c-7c0077f23b63)


- Recomenda-se pelo menos 2 GB (2048 MB) , mas 4 GB ou mais é o ideal.
- Clique em Avançar .
- Crie um disco rígido virtual :

- Escolha Crie um disco rígido virtual agora e clique em Criar .
- Selecione o tipo de disco como VDI (VirtualBox Disk Image) e clique em Next .
- Escolha alocado dinamicamente .
- Defina o tamanho do disco virtual (ex.: 20 GB) e clique em Criar .

## Passo 4: Conecte a ISO do Linux



- Selecione a máquina virtual criada e clique em Configurações .
- Vá para a aba Armazenamento :
- Clique no ícone do CD vazio no Controlador IDE .
- À direita, clique no ícone do disco com uma seta e selecione Escolher um arquivo de disco .
- Localize e selecione o arquivo ISO baixado.
- Clique em OK para salvar as configurações.

## Passo 5: Iniciar a instalação do Linux

![sistema_4](https://github.com/user-attachments/assets/97c8780f-127e-486b-ad30-956e7f11a03e)


- Na interface do VirtualBox, clique na máquina virtual criada e selecione Iniciar .
A máquina virtual irá inicializar com o arquivo ISO.
- Siga as etapas do instalador do Linux:
- Escolha o idioma.
- Clique em Instalar (Instalar Linux/Ubuntu/etc.).
Configure o teclado, fuso horário e outras opções.
- Para o particionamento, escolha Apagar disco e instale (não se preocupe, isso afeta apenas a máquina virtual).
- Siga as instruções até concluir a instalação.
- Após a instalação, reinicie a máquina virtual.


## Passo 6: Finalizar e usar o Linux

Com CD(Opcional)
Após reiniciar, remova um ISO:
Vá em Dispositivos > Drives Ópticos > Remover disco do drive .

Sem CD
Aproveite sua nova instalação do Linux!

Aproveite sua nova instalação do Linux!

