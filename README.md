# uk8 Training

This repository contains the source files needed to follow the k8s training series:

* Session 1: Docker 101
* Session 2: Kubernet by examples

## Playing with playbooks

### Requeriments

[Installation guide ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

### How to run 
```
* $ ansible-playbook build-images-playbook.yml
```

```
* $ ansible-playbook run-containers-playbook.yml
```

## Playing with tmuxp

### Requeriments

* [tmux](https://github.com/tmux/tmux)
* [tmuxp](https://github.com/tmux-python/tmuxp)

### How to run 

```
tmuxp load tmuxp.yml
```

## TODOs

* use `docker_image` on `build-images-playbook.yml`
* use `docker_container` on `run-containers-playbook.yml`

# Credits
[Learn Kubernetes in Under 3 Hours: A Detailed Guide to Orchestrating Containers](https://medium.freecodecamp.org/learn-kubernetes-in-under-3-hours-a-detailed-guide-to-orchestrating-containers-114ff420e882)
