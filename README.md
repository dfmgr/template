## NAME  
  
DESCRIBE  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/NAME/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install req
```  

Fedora Based:

```shell
yum install req
```  

Arch Based:

```shell
pacman -S req
```  

MacOS:  

```shell
brew install req
```
  
  
```shell
mv -fv "$HOME/.config/NAME" "$HOME/.config/NAME.bak"
git clone https://github.com/dfmgr/NAME "$HOME/.config/NAME"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/NAME" target="_blank">NAME wiki</a>  |  
  <a href="NAME" target="_blank">NAME site</a>
</p>  
