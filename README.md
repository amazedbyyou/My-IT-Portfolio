# My-IT-Portfolio









2. Turned a scratched, low-end laptop into a backup NAS. I discarded the original peripherals, using only the motherboard, and asked a local shop to design the acrylic case for a fair price. Considering its spec, a dual-core mobile i5 with 6GB of RAM, I'm using fnOS. This is a lightweight NAS OS that runs smoothly on machines with only 4GB of RAM, as long as you aren't using ZFS heavily. For storage, I'm using a 128GB SSD for the OS and a 2TB 2.5”HDD for data. Limiting the ZFS ARC usage to 1GB makes the entire machine operate at about 3GB total usage, so I'm actually planning to lower it to 4GB RAM in the future. However, fnOS has its risks; it tends to run everything with root privileges. So, for now, no public services will be run on this machine, I'm only accessing it via VPN.
![Before](https://github.com/user-attachments/assets/51f228e9-0d40-4492-8f3c-d8523649ddb1)
![After](https://github.com/user-attachments/assets/8c63a48e-4029-45b1-892d-49e3d6181d9f)
<img width="2467" height="1255" alt="FNOS" src="https://github.com/user-attachments/assets/f125ab1e-df6b-4f46-91f6-fd964f0a64f2" />

    
			




1. Bought a 4 port 2.5GbE switch with metal finishes from Netcore for only about 16 USD. Although my router, formerly also being a switch, can only handle GbE traffic, it should be fine until my ISP provides decent pricing for multi-GbE internet. 
Drew a simple topology to compare the state of before and after. Quite satisfying to see my read speed finally reaching over 200MB/s not only on my PC but also on mobile devices. Since my AP is also 2.5GbE ready with 2400Mbps transfer available.
![IMG_20250920_214822](https://github.com/user-attachments/assets/b4d02d7c-2597-4be2-bd37-3bde28dca313)
<img width="753" height="638" alt="202503_GbE" src="https://github.com/user-attachments/assets/24276ffe-8ba2-4e30-bba7-08bcaa4dcc11" />
<img width="482" height="427" alt="202602_2 5GbE" src="https://github.com/user-attachments/assets/535b9fe9-fac5-4e12-b1e8-63a14ed4eabb" />
