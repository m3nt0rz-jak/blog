+++
title = 'Symfonos CTF Walkthrough'
date = 2024-08-12T02:27:24+01:00
draft = false
description = "Symfonos CTF Walkthrough"
image = "/images/symfonos2s.webp"
imageBig = "/images/symfonos2b.webp"
categories = ["tech", "ctf"]
authors = ["m3nt0rz"]
avatar = "/images/m3nt0rz avatar.webp"
+++

CTF Symfonos Content

{{< youtube "Y_vXOqY9S84" "test and CTF walkthrough of Vulnhub Symfonos" >}}


<iframe width="560" height="315" src="https://www.youtube.com/embed/Y_vXOqY9S84?si=-Xv8CfodVaPRbBBZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>





{{< youtube "PTa_WyejOt8" "Symfonos Ctf Walkthrough (Part 2)" >}}

<iframe width="560" height="315" src="https://www.youtube.com/embed/PTa_WyejOt8?si=C8aNaGRH_MkesizM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


**Step 1) ifconfig**

ip address of our local machine (Kali Linux)

`root@kali:~#` **ifconfig**

        eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet 192.168.148.131 netmask 255.255.255.0  broadcast 192.168.148.255
        inet6 fe80::2d94:3836:a948:16a6  prefixlen 64  scopeid 0x20<link>
        ether 00:0c:29:27:f4:5c  txqueuelen 1000  (Ethernet)
        RX packets 389  bytes 53422 (52.1 KiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 27  bytes 2168 (2.1 KiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
        device interrupt 19  base 0x2000

My Kali Linux Local ip address: **192.168.148.131**   
**Note your local ip will be different and unique to your DHCP.**

 **Resource**
 `DHCP: The Networking Protocol That the Gives You an IP Address` 
  https://whatismyipaddress.com/dhcp

