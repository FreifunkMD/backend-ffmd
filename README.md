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
### basic

Basic configuration & software installation for all servers.

### ssh

Configures the openssh-server. 

### users

Pulls Admin-SSH-Keys from Git and creates corresponding users.


### docker

Installes docker/-compose.
