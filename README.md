# Bash - Wiki

## Transferencia de arquivos via ssh

- Exportar
```
scp <file_name> user@endereço:~/
```

- Importar
```
scp user@endereço:~/ ~/
```



## Instalação do YAY
```
sudo pacman -S git go
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
```



## Instalação de ferramentas Xilinx
```
yay -S digilent.adept.runtime digilent.adept.utilities
```
- !!! Embora seja possível instalar o Xilinx ISE Webpack pelo Yay, é preferível não faze-lo.

