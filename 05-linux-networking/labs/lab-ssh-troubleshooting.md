# SSH Troubleshooting Lab

## Problem
ssh localhost

Result:
Connection refused

Reason:
SSH server was not installed/running.

## Fix
sudo apt update
sudo apt install openssh-server
sudo systemctl start ssh

## Verification
ps aux | grep ssh
ss -tulpn | grep :22
hostname -I

## Learned
- sshd = SSH server
- port 22 = SSH
- systemctl manages services
