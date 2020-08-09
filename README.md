## Prérequis

* HomeBrew 

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

* Ansible 

```
brew install ansible
```

## How to execute 

```
ansible-playbook playbook.yml
```


## Create Trash Kube 

```
k3d cluster create trash --api-port 6550 --servers 3 --agents 3 --port 8080:80@loadbalancer --wait
```

### Some demo here : 

```
https://github.com/iwilltry42/k3d-demo
```