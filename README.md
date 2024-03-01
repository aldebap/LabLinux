# Lab de Open Source/Linux (Impacta)

Repositório com material de apoio ao curso _Lab de Open Source/Linux da Impacta_

Opções para rodar o Linux:

- **VirtualBox**

O virtual Box (<https://www.virtualbox.org/>) é um virtualizador gratuíto que permite instalar e
executar qualquer sistema operacional independente do sistema operacional da máquina hospedeira.
Ou seja, é possivel instalar e executar o Linux se o seu sistema operacional é o Windows ou o
MacOS.
Para simplificar o Lab, disponibilizei uma imagem já instalada com o xUbuntu
(<https://xubuntu.org/>) no seguinte link:
[Imagem xUbuntu](https://drive.google.com/file/d/1LGldbsi4lOIx61B7LrrTRvsjwNf2k8JG/view?usp=sharing)
Ao executar essa imagem, utilize o seguinte usuário e senha: impacta / lablinux24

- **WSL**

Windows Subsystem for Linux (WSL) é uma funcionalidade do Windows 10 que permite instalar e executar
o Linux como se fosse uma apllicação Windows.
O WSl pode ser instalado via linha de comando (PowerShell) como Administrador:

```powershell
wsl --install

wsl --install -d Ubuntu-20.04
```

- **Linux Online**

Em últimos casos, é possível rodar o Arch Linux diretamente de um navegador web por meio do seguinte
link: [Arch](http://copy.sh/v86/?profile=archlinux).
Mesmo funcionando razoavelmente bem, a quantidade de recusros disponíveis é mais limitada do que as
opções anteriores.

Independente do sistema operacional, é possível estabelecer uma conexão de rede com uma máquina
Linux.
Caso você esteja utilizando o Windows, baixe e utilize o Putty (<https://putty.org/>), um cliente de
_ssh_ e telnet para conectar-se remotamente ao Linux.
