my custom vim

.vim.tar.gz 放在我邮箱的云盘上

# v2 update
1. 切换到 vim-plug（更现代的方案）
2. 增加了更多插件

## vim-plug 安装与配置
1. 安装vim-plug
```
# Unix/Linux
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
2. 修改.vimrc 
```cp .vimrc_v2 ~/.vimrc
```

3. 打开 Vim 并运行
```
:PlugInstall
```
4. 安装依赖工具包

```
# 对于语法检查
pip install flake8

# 对于代码搜索
sudo apt install ack-grep  # Ubuntu/Debian
brew install ack           # macOS
```
