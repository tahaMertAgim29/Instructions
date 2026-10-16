# Windows Ethernet Adapter Setting

## Introduction

This is an instruction to set the adapter settings for Ethernet in Windows.

## Features

- Setting Ethernet Adapter
- Applying Network Information e.g. mask and Internet Protocol Address

## Prerequisites

- Windows
  
> [!IMPORTANT]
> Windows will be used for this instruction which means you should ensure that
> your operating system is Windows.


## Steps

1 - Press `Windows` button on your keyboard and search for `Control Panel`

![Windows Search](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTg6a2jLo8dno0Ruj6tPzl0NOoPptkLRvMOlTQevju67Q&s=10)

2 - Open `Control Panel` and select `Network and Internet`

![Control Panel Home](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTLnsRnfp92M89T1Q5Y6LDE615K8IYyh93y_1LUvkaDkg&s=10)

3 - Click `Network and Sharing Center`

![Network Sharing](https://geekrewind.com/wp-content/uploads/2021/07/windows-11-network-and-sharing-center.webp)

4 - Select `Change Adapter Settings` on the left menu

![Adapter Settings](https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/1129406632/original/TWlvG40YyYF9BVj9kdrISDHBGMfUdRjmDA.png?1678521058)

5 - Clik `Ethernet` Choice

![Ethernet](https://support.netcraze.ru/asset/images/uuid-b6ae43fb-570e-2d05-2e97-a73c3874706f.png)


6 - Click on `Internet Protocol Version 4` on `Ethernet Properties Interface` and then, toggle `Use the following IP Address`. After you are asked to enter Internet Protocol Address and Subnet Mask. Default Gateway may not be needed depending on your usage or job.


![IPv4 Property](https://support.netcraze.ru/asset/images/uuid-c093850f-1d15-5760-ffaf-8837241b0707.png)

> [!WARNING]
> When you are done setting the addresses and masks, you should click on `OK` button on both `Ethernet Properties Interface` and `Internet Protocol Version Properties Interface` to save as it's on the picture.
> You should ensure that the address and subnet mask must be valid and address must not conflict with the other device which you're connected via Ethernet using Ethernet cable, otherwise you may get failure while you apply `ping` command.


7 - After assigning the IP and subnet, you can open `cmd` to test whether network is provided between the devices using `ping` command.

Ping Command Example:
```
ping <IP Address>
```

Example to explain IP Assignment:
```

Assume that let the device,which you want to connect via Ethernet have IP address as 192.168.1.5 so that means your computer's IP must be different than other device, but also it must have a usable/valid IP address.   

```




## Badges

![Windows](https://img.shields.io/badge/Windows%20-%20%230854C1?style=for-the-badge)