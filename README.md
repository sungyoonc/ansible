# ansible
Ansible configurations for automated archlinux setup.
## Requirements
```sh 
./arch_setup
```
## Instructions
```sh
./run -t <tags>
```
Or you can run it with any other arguments for `ansible-playbook`
### Available tags
|Tag|Description|
|---|---|
|install|Install packages and setup the desktop|
|core|Install and setup core packages|
|dotfiles|Setup dotfiles|
|zsh|Install zsh and change the default shell|
|wayland|Install wayland related packages|
|theme|Install themes|
|tools|Install tools packages|
|media|Install media packages|
