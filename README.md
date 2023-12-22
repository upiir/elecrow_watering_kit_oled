# Custom Graphics for Elecrow Smart Watering Kit with OLED Display
Learn how to update the graphics on the OLED display for the Watering Kit from Elecrow. 

**YouTube video: https://youtu.be/yhJNsQIChqI**

**WOKWI project: https://wokwi.com/projects/384807026722470913**


Links from the video:
- Smart watering kit: https://www.elecrow.com/arduino-automatic-smart-plant-watering-kit.html?idd=5
- 128x64 SSD1306 OLED Display 1.54": https://s.click.aliexpress.com/e/_DCYdWXb
- 128x64 SSD1306 OLED Display 0.96": https://s.click.aliexpress.com/e/_DCKdvnh
- 128x64 SSD1306 OLED Display 2.42": https://s.click.aliexpress.com/e/_DFdMoTh
- Photopea (online graphics editor like Photoshop): https://www.photopea.com/
- Image2cpp (convert image to c-style array): https://javl.github.io/image2cpp/
- U8g fonts: https://nodemcu-build.com/u8g-fonts.php
- U8g documentation: https://code.google.com/archive/p/u8glib/wikis/userreference.wiki
- Transparent OLED display: https://s.click.aliexpress.com/e/_ABpnu7


Related videos with Arduino UNO and 128x64 OLED screen:
- Arduino OLED menu: https://youtu.be/HVHVkKt-ldc
- U8g vs U8g2: https://youtu.be/K5e0lFRvZ2E
- Arduino Parking Sensor - https://youtu.be/sEWw087KOj0
- Turbo pressure gauge with Arduino and OLED display - https://youtu.be/JXmw1xOlBdk
- Arduino Car Cluster with OLED Display - https://youtu.be/El5SJelwV_0
- Knob over OLED Display - https://youtu.be/SmbcNx7tbX8
- Arduino + OLED = 3D ? - https://youtu.be/kBAcaA7NAlA
- Arduino OLED Gauge - https://youtu.be/xI6dXTA02UQ
- Smaller & Faster Arduino - https://youtu.be/4GfPQoIRqW8
- Save Image from OLED Display to PC - https://youtu.be/Ft2pRMVm44E



![THUMB_watering_kit](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/e1edeb0c-6124-4860-971f-f771ffda937c)


Small animation:

![wokwi_gif_animation](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/0b65792f-d1e8-421d-bdf1-7711f2ba7c87)

![elecrow_smart_watering_kit](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/5db93601-be35-4afd-8d8f-5fb19ed5d00a)



Screenshots from the video:

![CAMTASIA_elecrow_watering_kit (Time 0_00_08;01)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/946eb21f-b4c2-4f3b-beed-77a944220d52)
![CAMTASIA_elecrow_watering_kit (Time 0_00_30;25)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/1b676e49-bb67-4e7d-a8d7-852b8ce44ae2)
![CAMTASIA_elecrow_watering_kit (Time 0_01_17;22)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/90650c76-0156-485e-a621-9af303e78cf7)
![CAMTASIA_elecrow_watering_kit (Time 0_01_25;25)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/0d26b743-45ee-4d84-9e6b-8f5035cdde54)
![CAMTASIA_elecrow_watering_kit (Time 0_02_00;14)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/3134748e-d1be-4bc0-9d14-d53bcdd52f54)
![CAMTASIA_elecrow_watering_kit (Time 0_02_21;25)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/5a55a608-1855-4a6a-9495-9ba1a4366e31)
![CAMTASIA_elecrow_watering_kit (Time 0_03_06;11)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/08d8e948-eb9a-466e-8564-e29cf00c6e55)
![CAMTASIA_elecrow_watering_kit (Time 0_05_02;02)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/3d85830e-0679-433b-b42f-5eb53d98a3e2)
![CAMTASIA_elecrow_watering_kit (Time 0_07_37;01)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/ab2f5510-95bd-4f40-814b-5b64af116916)
![CAMTASIA_elecrow_watering_kit (Time 0_13_23;03)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/b828a2da-3d3b-4120-b515-9f7fca13e53f)
![CAMTASIA_elecrow_watering_kit (Time 0_14_20;26)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/aa8403b2-93a1-4bd9-b5fa-2477d2d7dee3)
![CAMTASIA_elecrow_watering_kit (Time 0_15_06;25)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/68755f45-af77-4ed6-98be-06faf5941594)
![CAMTASIA_elecrow_watering_kit (Time 0_15_35;03)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/5ca7f028-de3d-4fc5-af49-843a230eea25)
![CAMTASIA_elecrow_watering_kit (Time 0_17_49;07)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/708ec94c-f497-4fa7-8719-e78faf1f8b6a)
![CAMTASIA_elecrow_watering_kit (Time 0_20_42;09)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/e7453e0c-c9ca-4ff1-b8d2-d43dc7aaeb7c)
![CAMTASIA_elecrow_watering_kit (Time 0_21_08;23)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/714f33d8-e1ec-463c-98af-afff0b485962)
![CAMTASIA_elecrow_watering_kit (Time 0_21_50;14)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/93aaede1-c24b-4ac7-abf8-42ae6c5261e9)
![CAMTASIA_elecrow_watering_kit (Time 0_22_27;19)](https://github.com/upiir/elecrow_watering_kit_oled/assets/117754156/35658925-dc1a-4f17-9162-741892133bdb)
