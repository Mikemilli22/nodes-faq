
__FAQ ON NODE RUNNING__
-

#### What is VPS?

A VPS or Virtual Private Server is like renting a small part of a powerful computer that you can use just like your own personal computer, but it's accessible over the internet.

#### Can we run node on our own Computer/Laptop/Android phone without buying VPS?

The answer is complex, let's break it down :

The answer is depend on the uptime of the node, for example in some node we generally need the uptime of 15-20 mins (example : Nubit Node, Alligned Testnet Node)

On the other hand, in other nodes like Shardeum node, Taiko Node, we need to keep running node until snapshot so the minimum uptime is 5 months and more.

So, You can run nodes with less uptime (15 mins to 2 hrs) on your Computer/Laptop/Android phone without buying any VPS !!

#### For running Farcaster node, it is required to have 16 GB RAM . I bought s VPS server which have 16 GB RAM but my Computer RAM is only 4 GB, Can I run this Node?

When you are using VPS for running Node, all you need to have required RAM on your VPS not on your PC. So, the answer is yes you can run farcaster node with any device (Laptop/PC/Phone) of any RAM using VPS (Your VPS need to have required RAM, that's it)

#### How to run nodes ( which need less uptime like 15 mins to 2 hrs) using phone/PC/Laptop without buying any VPS?

Well here you can use either your local system or Virtual IDE

Local System  | Virtual IDE
------------- | -------------
On PC/Laptop Users can run  | On PC/Laptop/Phone Users can run

__To run less uptime based node on your computer/laptop, follow these steps :__

Run Command Pormpt as an Administrator
Then use these commands one by one
 ```bash
  wsl --install
```
```bash
  wsl --install -d Ubuntu
```
Another terminal will pop up, open it, if there is any issue duirng installing Ubuntu, Comeback again on cmd and use this commmand

```bash
  wsl --set-default-version 1
```
It will fix the problem, now open Ubuntu, it will  ask to set up an username and password. Set the username and password and then execute node commands on Ubuntu terminal not on Command prompt/Powershell

__To run less uptime based node on virual IDE, follow these steps :__

You can use any of the following IDE and run nodes commands -

- [Gitpod](https://gitpod.io/)
- [Repl It](https://replit.com/)
- [CoCaltc](https://cocalc.com/)
- [Glitch](https://glitch.com/)
- [Codespace](https://github.com/codespaces)
