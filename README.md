### myemacs
```sh
sudo apt install silversearcher-ag ispell
sudo pip install --upgrade "jedi>=0.9.0" "json-rpc>=1.8.1" "service_factory>=0.1.5"
sudo pip install flake8
sudo pip install hy
```
### when brower c code. create GTAGS first.
```
 gtags --gtagslabel=ctags
```
### install font
```
git clone --depth 1 --branch release https://github.com/adobe-fonts/source-code-pro.git ~/.fonts/adobe-fonts/source-code-pro
fc-cache -f -v ~/.fonts/adobe-fonts/source-code-pro
```
### install spacemacs
```
git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d
```
