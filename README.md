# My-personal-configuration
## 安装nvim(neovim)
ubuntu  
</br>

```bash
sudo spt install nvim -y
```

centos 
</br>

```bash
sudo yum install nvim -y
```
***
## nvim键位更改

先要创建配置文件
</br>

```bash
.config/nvim/init.vim
```
将一下添加到配置文件</br>

```bash
imap jk <ESC>
```
将`ESC`替换为`jk`连续按键，因为常用出入中很少用到`jk`连续
</br>

```bash
nmap <space> :
```

将`space`按键替换为`：`
***
## 安装`vim-plug`
linux
```bash
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
