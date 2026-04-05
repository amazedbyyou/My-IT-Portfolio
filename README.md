# My-IT-Portfolio







4.  Drew up a quick chart of my NAS storage structure to show the current tiering setup I'm using. While UNRAID's FUSE file system is reliable, I still prefer creating direct network shares at every storage level: RAM, SSDs, and HDDs. One of the biggest selling points of UNRAID for me is its drive-saving mechanism. Keeping the mechanical drives spun down for extended periods not only extends their lifespan, but also saves a few bucks on the power bill. By tiering the storage more thoroughly, I can also significantly reduce the wear on my SSD cache.
<img width="3207" height="4096" alt="UNRAID Storage structureV2" src="https://github.com/user-attachments/assets/61d4786a-77ae-40ce-9a78-3cbbce623ab4" />

3. Built my own 6-bay NAS with standard PC hardware. The processor is from Intel's low-power lineup, the Celeron N150, paired with 16 Gigs of SO-DIMM RAM. For the motherboard, I chose not to go with a DC-powered board but an ATX 24-pin ITX mobo for better upgradability in the future. For the power supply, I went with a Delta 250W Flex-ATX bronze option. All of these parts were assembled into a compact chassis named UE-S6.Here's a size comparison picture between my self-built NAS and Synology's DS720+. Not that space-consuming considering mine has 4 extra drive bays. Testing Unraid on this system now, and you can see how power-efficient the N150 can be. At 5 Watts during a medium workload, I can finally say goodbye to Synology's J4125 lineup.
![Hardware (1)](https://github.com/user-attachments/assets/a6c1e4b3-d0f9-4b2b-949c-56f628ac33b6)
![Hardware (2)](https://github.com/user-attachments/assets/9bed13ff-86a7-43c2-a5e7-b19ad12701ea)
![Hardware (3)](https://github.com/user-attachments/assets/8888d04c-985b-4e7d-a970-7ec0ebc12da3)
![Hardware (8)](https://github.com/user-attachments/assets/896c6542-7b50-44f1-9aba-201cb5861108)
![Hardware (10)](https://github.com/user-attachments/assets/bed5b4a8-1294-4c49-afeb-78467df9d953)
![Hardware (11)](https://github.com/user-attachments/assets/504b4370-9329-4391-a924-07d3e9f3c312)
![Hardware (13)](https://github.com/user-attachments/assets/095e9983-89c0-421e-a269-6f1fbe4cee31)
![Hardware (14)](https://github.com/user-attachments/assets/bfb02011-b648-4c78-a641-69cc0feb7734)
<img width="677" height="308" alt="螢幕擷取畫面 2025-12-01 133002" src="https://github.com/user-attachments/assets/51c6b521-8e54-48aa-bcda-dd07c77f078a" />

2. Turned a scratched, low-end laptop into a backup NAS. I discarded the original peripherals, using only the motherboard, and asked a local shop to design the acrylic case for a fair price. Considering its spec, a dual-core mobile i5 with 6GB of RAM, I'm using fnOS. This is a lightweight NAS OS that runs smoothly on machines with only 4GB of RAM, as long as you aren't using ZFS heavily. For storage, I'm using a 128GB SSD for the OS and a 2TB 2.5”HDD for data. Limiting the ZFS ARC usage to 1GB makes the entire machine operate at about 3GB total usage, so I'm actually planning to lower it to 4GB RAM in the future. However, fnOS has its risks; it tends to run everything with root privileges. So, for now, no public services will be run on this machine, I'm only accessing it via VPN.
![Before](https://github.com/user-attachments/assets/51f228e9-0d40-4492-8f3c-d8523649ddb1)
![After](https://github.com/user-attachments/assets/8c63a48e-4029-45b1-892d-49e3d6181d9f)
<img width="2467" height="1255" alt="FNOS" src="https://github.com/user-attachments/assets/f125ab1e-df6b-4f46-91f6-fd964f0a64f2" />

1. Bought a 4 port 2.5GbE switch with metal finishes from Netcore for only about 16 USD. Although my router, formerly also being a switch, can only handle GbE traffic, it should be fine until my ISP provides decent pricing for multi-GbE internet. 
Drew a simple topology to compare the state of before and after. Quite satisfying to see my read speed finally reaching over 200MB/s not only on my PC but also on mobile devices. Since my AP is also 2.5GbE ready with 2400Mbps transfer available.
![IMG_20250920_214822](https://github.com/user-attachments/assets/b4d02d7c-2597-4be2-bd37-3bde28dca313)
<img width="753" height="638" alt="202503_GbE" src="https://github.com/user-attachments/assets/24276ffe-8ba2-4e30-bba7-08bcaa4dcc11" />
<img width="482" height="427" alt="202602_2 5GbE" src="https://github.com/user-attachments/assets/535b9fe9-fac5-4e12-b1e8-63a14ed4eabb" />
