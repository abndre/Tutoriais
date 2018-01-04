# Tutoriais

##Virtual Box Linux

Tive sempre o problema com ubuntu no virutal box, adicionar o usuário para ter acesso as pastas compartilhadas:

```bash
sudo adduser username vboxsf
```

onde username é o usuário da maquina virtual.

Encurtar caminho pasta terminal linux:

user normal
```bash
PS1="${debian_chroot:+($debian_chroot)}\[\033[01;34m\]\W \[\033[32m\]\$\[\033[00m\] "
```

sudo
```bash
PS1="${debian_chroot:+($debian_chroot)}\[\033[01;34m\]\W \[\033[31m\]\$\[\033[00m\] "
```
https://www.vivaolinux.com.br/dica/Customizando-o-BASH


#PycharmTips

For retaining objects/ classes/ functions/ variables even after execution you will have to change the Interpreter Option in Run> Edit Configuration> Interpreter Option, you have to add -i there. I still don't know about code completion in the console.

With '-i' is possible interactive console in pycharm, the problem you nedd make is all time.
