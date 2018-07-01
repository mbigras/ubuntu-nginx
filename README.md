# Ubuntu NGINX

> Install NGINX on a Vagrant Box

## Links

* https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-ubuntu-16-04

## Usage example

```
vagrant up
ansible all -m ping
ansible-playbook main.yml
curl -sI 192.168.11.10 | head -n1 | tee /dev/tty | pbcopy
HTTP/1.1 200 OK
vagrant destroy -f
```
