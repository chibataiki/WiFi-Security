# Wifi Fuzzing Related 
A list of references to fuzzing resources for wifi security testing.

## Contents

- [Papers and Conferences](#papers_and_conferences)
- [Presentations](#presentations)
- [Blogs](#blogs)
- [Tools](#tools)



## papers_and_conferences


- [NDSS 2019] PeriScope: An Effective Probing and Fuzzing Framework for the Hardware-OS Boundary
  - https://www.ndss-symposium.org/ndss-paper/periscope-an-effective-probing-and-fuzzing-framework-for-the-hardware-os-boundary/
  - https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_04A-1_Song_paper.pdf
  - https://www.ndss-symposium.org/wp-content/uploads/ndss2019_04A-1_Song_slides.pdf
  - https://www.youtube.com/watch?v=GDf4IIEhl0Y&list=PLfUWWM-POgQvLhcT_z_rw4_2RvJSXpa7k&index=2&t=2s

- [2020] Fuzzing Wi-Fi in IoT devices


  - https://www.cs.ru.nl/bachelors-theses/2020/Bart_Pleiter___4752740___Fuzzing_Wi-Fi_in_IoT_devices.pdf

- [2020] GREYHOUND: Directed Greybox Wi-Fi Fuzzing

  - https://asset-group.github.io/papers/Greyhound.pdf

- [2021] Black-Box Analysis of Wi-Fi Stacks Security


  -  https://www.fit.vut.cz/study/thesis-file/23755/23755.pdf
  - Master's Thesis 

- [ACM WiSec 2021] DEMO: A Framework to Test and Fuzz Wi-Fi Devices

  - https://www.youtube.com/watch?v=S3HQlNYun-I
  - https://dl.acm.org/doi/10.1145/3448300.3468261

  



## presentations

- [Black Hat Usa 2017] WiFuzz: Detecting and Exploiting Logical Flaws in the Wi-Fi Cryptographic Handshake

  - https://www.blackhat.com/docs/us-17/wednesday/us-17-Vanhoeft-WiFuzz-Detecting-And-Exploiting_Logical-Flaws-In-The-Wi-Fi-Cryptographic-Handshake.pdf
  - https://www.blackhat.com/docs/us-17/wednesday/us-17-Vanhoeft-WiFuzz-Detecting-And-Exploiting_Logical-Flaws-In-The-Wi-Fi-Cryptographic-Handshake-wp.pdf
  - https://www.youtube.com/watch?v=e3utIwUA1Ek

- [Black Hat Usa 2017] BROADPWN: REMOTELY COMPROMISING ANDROID AND IOS VIA A BUG IN BROADCOM'S WI-FI CHIPSETS

  - https://www.blackhat.com/docs/us-17/thursday/us-17-Artenstein-Broadpwn-Remotely-Compromising-Android-And-iOS-Via-A-Bug-In-Broadcoms-Wifi-Chipsets-wp.pdf

  - https://www.blackhat.com/docs/us-17/thursday/us-17-Artenstein-Broadpwn-Remotely-Compromising-Android-And-iOS-Via-A-Bug-In-Broadcoms-Wifi-Chipsets.pdf

  - https://www.youtube.com/watch?v=TDk2RId8LFo

- [POC 2018] 802.11 Smart Fuzzing
  - https://www.powerofcommunity.net/poc2018/lidong.pdf

- [zeronights 2018] Researching Marvell Avastar Wi-Fi: From Zero Knowledge to Over-the-Air Zero-Touch RCE

  - https://2018.zeronights.ru/wp-content/uploads/materials/19-Researching-Marvell-Avastar-Wi-Fi.pdf
  - https://www.youtube.com/watch?v=Him_Lf5ZJ38

- [Black Hat Usa 2019] Exploiting Qualcomm WLAN and Modem Over the Air

  - https://i.blackhat.com/USA-19/Thursday/us-19-Pi-Exploiting-Qualcomm-WLAN-And-Modem-Over-The-Air.pdf
  - https://i.blackhat.com/USA-19/Thursday/us-19-Pi-Exploiting-Qualcomm-WLAN-And-Modem-Over-The-Air-wp.pdf
  - https://www.youtube.com/watch?v=KxdfX9NxfA4

- [Black Hat Asia 2020] WIFI-Important Remote Attack Surface: Threat is Expanding
  - https://www.youtube.com/watch?v=ySUxQ8hktAw
  - http://i.blackhat.com/asia-20/Thursday/asia-20-Xie-WIFI-Important-Remote-Attack-Surface-Threat-Is-Expanding.pdf

- [Black Hat Europe 2021] BadMesher: New Attack Surfaces of Wi-Fi Mesh Network
  - http://i.blackhat.com/EU-21/Thursday/EU-21-LeweiQu-BadMesher_New_Attack_Surfaces_of_Wi-Fi_Mesh_Network.pdf
  - https://www.youtube.com/watch?v=8bhv-BhGDmk

- [HITB CyberWeek2021]  WIFI Security - From 0 To 1
  - https://cyberweek.ae/2021/wp-content/uploads/sites/8/2021/10/COMMSEC-D2-WIFI-Security-From-0-To-1-Sili-Luo.pdf
  - https://www.youtube.com/watch?v=MIbPKLq2AYQ

- [sstic 2022] Ghost in the Wireless, iwlwifi edition

  - https://www.sstic.org/2022/presentation/intel_wifi/

    

## blogs

- [2017] Broadpwn: Remotely Compromising Android and iOS via a Bug in Broadcom’s Wi-Fi Chipsets

    - https://blog.exodusintel.com/2017/07/26/broadpwn/

- [2017] Project Zero Over The Air : Exploiting The Wi-Fi Stack on Apple Devices
  - Part1 https://googleprojectzero.blogspot.com/2017/09/over-air-vol-2-pt-1-exploiting-wi-fi.html
  - Part2 https://googleprojectzero.blogspot.com/2017/10/over-air-vol-2-pt-2-exploiting-wi-fi.html
  - Part3 https://googleprojectzero.blogspot.com/2017/10/over-air-vol-2-pt-3-exploiting-wi-fi.html

- [2017] Project Zero,  Over The Air: Exploiting Broadcom’s Wi-Fi Stack
  - Part1 https://googleprojectzero.blogspot.com/2017/04/over-air-exploiting-broadcoms-wi-fi_4.html
  - Part2 https://googleprojectzero.blogspot.com/2017/04/over-air-exploiting-broadcoms-wi-fi_11.html

- [2019] Reverse-engineering Broadcom wireless chipsets
  - https://blog.quarkslab.com/reverse-engineering-broadcom-wireless-chipsets.html
- [2020] exploiting-wifi-stack-on-tesla-model-s
  - https://keenlab.tencent.com/en/2020/01/02/exploiting-wifi-stack-on-tesla-model-s/
- [2022] CVE-2022-23088: EXPLOITING A HEAP OVERFLOW IN THE FREEBSD WI-FI STACK
  - https://www.zerodayinitiative.com/blog/2022/6/15/cve-2022-23088-exploiting-a-heap-overflow-in-the-freebsd-wi-fi-stack



## tools

-  [wifuzzit](https://github.com/0xd012/wifuzzit)

-  [wifuzz](https://github.com/0x90/wifuzz/)

-  [openwifi](https://github.com/open-sdr/openwifi)

- [Owfuzz](https://github.com/alipay/Owfuzz/)

   



