# Rodandos Scripts em Python no Windows

https://docs.microsoft.com/pt-br/windows/wsl/install-win10

    notepad.exe .bash_profile

Adicione a seguinte linha no fim do arquivo e salve

    alias python='winpty python.exe'

## Instando WSL

Abra o PowerShell e cole o seguinte comando, espero o computador reiniciar

    Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux


Abra o [Windows Store](https://www.microsoft.com/pt-br/store/b/home)
- Procure pelo Ubuntu
- Escolha obter e depois clique em instalar

Corrigir path do wsl no ubuntu
    
    sudo apt-get install realpath
    060420195274606

