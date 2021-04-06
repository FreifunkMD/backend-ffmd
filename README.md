# backend-ffmd

Configuration and Ansible for the FreifunkMD backend.

## Usage

### Preparation

Install the requirements by running
```bash
ansible-galaxy install -r requirements.yml
```


## Requirements

```bash
sshd
```

## Roles
### system-basic

Basic configuration & software installation for all servers.

### service-ssh

Configures the openssh-server. 

### users

Pulls Admin-SSH-Keys from Git and creates corresponding users.


### system-docker

Installes docker/-compose.
