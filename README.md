### myemacs
```sh
sudo apt install silversearcher-ag ispell global 
sudo pip install --upgrade "jedi>=0.9.0" "json-rpc>=1.8.1" "service_factory>=0.1.5" flake8 hy autoflake
```
### when brower c code. create GTAGS first.
```
#refer to https://github.com/syl20bnr/spacemacs/tree/master/layers/%2Btags/gtags
```
### install font
```
git clone --depth 1 --branch release https://github.com/adobe-fonts/source-code-pro.git ~/.fonts/adobe-fonts/source-code-pro
fc-cache -f -v ~/.fonts/adobe-fonts/source-code-pro
```
### install spacemacs
```
git clone --depth 1 https://github.com/syl20bnr/spacemacs ~/.emacs.d

#first boot
emacs --insecure
```
### install emacs
```
sudo apt-get update
sudo apt-get install emacs
```
