## ruby  
  
Setup a ruby development system with rvm  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/casjay-dotfiles/ruby/raw/master/install.sh)"
```
Manual install:
  
requires:    
```
apt install req ruby
```  
```
yum install req ruby
```  
```
pacman -S req ruby
```  
  
```
mv -fv "$HOME/.config/ruby" "$HOME/.config/ruby.bak"
git clone https://github.com/casjay-dotfiles/ruby "$HOME/.config/ruby"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/ruby" target="_blank">ruby wiki</a>  |  
  <a href="https://www.ruby-lang.org" target="_blank">ruby site</a>
</p>  
    
