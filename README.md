# ansible-pi

![](https://raw.github.com/motdotla/ansible-pi/master/ansible-pi.jpg)

Quickly setup your Raspberry Pi - particularly WIFI settings.

There is a [complete guide to setting up your raspberry pi without a keyboard and mouse](http://sendgrid.com/blog/complete-guide-set-raspberry-pi-without-keyboard-mouse/) that goes along with this repo.

## Installation

Clone and setup the ansible script.

```
git clone https://github.com/motdotla/ansible-pi.git
cd ansible-pi
```

Edit the `hosts` files.

Deploy using [ansible](http://www.ansible.com) (install instructions for ansible are in [requirements](#requirements) below).

```
ansible-playbook playbook.yml -i hosts --ask-pass --become
```

## Requirements

[Ansible](http://www.ansible.com/) is required.
