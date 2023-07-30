# ansible
My ansible configurations for automating setup. It is intended for Endeavour OS. (Or any other arch based distributions.)
## Requirements
```sh 
$ ansible-galaxy collection install -r requirements.yml
```
## Instructions
```sh
$ ./run -t <tags>
```
Or you can run it with any other arguments for `ansible-playbook`
