# Laptop  
Install instructions for setting up a new development workstation.

1. Download and install [XCode 7 from the App Store](https://itunes.apple.com/us/app/xcode/id497799835?mt=12)
2. Create a github.com directory inside your home directory -- use the {user,organization}/project structure
3. Clone and run [DiyahM/sprout-wrap](https://github.com/DiyahM/sprout-wrap) to setup base development apps and settings
4. Install MacVim
```
brew install macvim --with-lua
```
5. Set zsh as login shell
```
chsh -s $(which zsh)
```
6. Install Oh My Zsh
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
7. Clone [thoughtbot/dotfiles](https://github.com/thoughtbot/dotfiles)
9. Install rcm
```
brew tap thoughtbot/formulae
brew install rcm
```
10. Clone [DiyahM/dotfiles](https://github.com/DiyahM/dotfiles)
11. Install dotfiles
```
env RCRC=$HOME/github.com/DiyahM/dotfiles/rcrc rcup
```
12. Install RVM
```
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
\curl -sSL https://get.rvm.io | bash -s stable --ruby
```
13. Install [Heroku CLI](https://toolbelt.heroku.com/)

