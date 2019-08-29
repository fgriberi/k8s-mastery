# k8s Training

This repository contains the source files needed to follow the k8s training series:

* Session 1: Docker 101
* Session 2: Kubernet by examples

## Docker 101

### Playing with tmuxp

#### Requeriments

* [tmux](https://github.com/tmux/tmux)
* [tmuxp](https://github.com/tmux-python/tmuxp)

#### How to run the Sentimental Analyser without docker

```
$ tmuxp load tmuxp.yml
```

### Playing with playbooks

#### Requeriments

[Installation guide ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

#### How to build the images
```
$ ansible-playbook build-images-playbook.yml
```

#### How to run the containers
```
$ ansible-playbook run-containers-playbook.yml
```

### TODOs

* use `docker_image` on `build-images-playbook.yml`
* use `docker_container` on `run-containers-playbook.yml`

## k8s 101
TODO

# Credits
[rinormaloku-k8s-mastery](https://github.com/rinormaloku/k8s-mastery)
