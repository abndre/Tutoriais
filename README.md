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
