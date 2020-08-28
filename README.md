## ruby  
  
Setup a ruby development system with rvm  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/ruby/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install ruby
```  

Fedora Based:

```shell
yum install ruby
```  

Arch Based:

```shell
pacman -S ruby
```  

MacOS:  

```shell
brew install ruby
```
  
```shell
mv -fv "$HOME/.config/ruby" "$HOME/.config/ruby.bak"
git clone https://github.com/dfmgr/ruby "$HOME/.config/ruby"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/ruby" target="_blank" rel="noopener noreferrer">ruby wiki</a>  |  
  <a href="https://www.ruby-lang.org" target="_blank" rel="noopener noreferrer">ruby site</a>
</p>  
