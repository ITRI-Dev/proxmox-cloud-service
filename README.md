# Proxmox VM Service
## Prerequisites
* Ask [kevinjan](mailto:kaiyuan.jan@itri.org.tw) to require Proxmox web/terminal login username and passwd.
* You can clone a new vm from Proxmox Ubuntu-2204-base vm or install it from ISO.
* New vm is needed to bind a assigned NAT IP address.

## Clone a new vm from Proxmox Ubuntu-2204-base vm

Right click 100 (ubuntu-2204-base) vm on master node and clone it

![241107-001](https://github.com/user-attachments/assets/df5cf191-bf14-455f-af22-6404e793c3e4)

Give a vm name

![241107-002](https://github.com/user-attachments/assets/8bb5df22-cc86-4314-a368-47fb98bc6bdf)

Wait new vm creation

![241107-003](https://github.com/user-attachments/assets/b165c7f8-403f-4bbb-8332-ae444db9cfaf)

The new vm 103 (ubuntu-2204-test) was created on master node with default hardware

![241107-004](https://github.com/user-attachments/assets/2d191e5d-8f46-4790-9e31-68868bc6211f)

Default options of vm 103

![241107-005](https://github.com/user-attachments/assets/1f7ceb74-fe46-4080-8c9d-f219c435c627)

Start vm in console

![241107-006](https://github.com/user-attachments/assets/0e9f23da-2996-42e0-a3ad-71d23e2eaa50)

Set your own NAT IP address

![241107-007](https://github.com/user-attachments/assets/e4ab2b18-8f77-4284-bbcf-60e96a113377)

Test network connection through ping command

![241107-008](https://github.com/user-attachments/assets/7ea2385d-864f-4466-8cf9-3231fa788ed1)

## Install a new vm from ISO

Upload your ISO to worker01 node's local which node you want to placed your new vm 

![241107-009](https://github.com/user-attachments/assets/87fcf137-10c4-42b4-ad52-54a7d6cf6fcf)

ubuntu-22.04.5-desktop-amd64.iso is uploaded

![241107-010](https://github.com/user-attachments/assets/3827b60f-bf64-4898-8845-b20e980e22a3)

Click "Create VM" in right-upper corner and fill vm's hardware/info requirement as following

![241107-011](https://github.com/user-attachments/assets/703c1ef1-66e9-4dc3-8cbe-00a6ed9a5a04)

![241107-012](https://github.com/user-attachments/assets/1de0a4e0-244f-4498-b48b-84845b74eb1f)

![241107-013](https://github.com/user-attachments/assets/c83da9a8-e1e4-42c5-b46b-95c6348c8afa)

![241107-014](https://github.com/user-attachments/assets/88da54c3-5e66-4c8d-bd11-90fe19eea6dc)

![241107-015](https://github.com/user-attachments/assets/e65eed31-4977-4ddd-8c13-0c2f3f8f5da3)

![241107-016](https://github.com/user-attachments/assets/67992113-5cf1-457d-988c-f88dc653a6fa)

![241107-017](https://github.com/user-attachments/assets/57f76c51-e1d8-48d4-9d96-3bf7aca9c706)

Confirm vm's hardware/info requirement

![241107-018](https://github.com/user-attachments/assets/02ec221a-fb2f-4a24-89c5-ca9867ede0a8)

The new vm 103 (ubuntu-2204-test) was created on worker01 node

![241107-019](https://github.com/user-attachments/assets/b7818e62-211e-46e0-9be7-bb877a0c875b)

Start vm in console

![241107-020](https://github.com/user-attachments/assets/38c4b494-a02a-4f38-8e46-c2e921404611)

Install Ubuntu 22.04 from ISO and set your NAT IP address after finishing Ubuntu installation

![241107-021](https://github.com/user-attachments/assets/9f0616b2-13c2-4a28-9e01-25511a957850)






