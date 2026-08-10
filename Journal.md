
## Started design designing the product and taking info from the previous one that had already existed.
So for this project the main design inspo for me was the all new Codex Micro by Open Ai ( made by the company Work Louderand I like the brand ) So I thought to make a same thing under budget as the Codex Micro is costed at $230which is too much for what it's offer so I named it " Codex Macro "

#### Inspo 
<img width="1500" height="1500" alt="image" src="https://github.com/user-attachments/assets/16ed898a-19f2-4ba6-ad5c-37c4eae76fce" />

#### Mine Design 
<img width="798" height="487" alt="design" src="https://github.com/user-attachments/assets/a960c9aa-61fe-4f04-92af-0d114e3b7697" />

This is just the wire frame of the project and I have made it just for the reference so that I can use it to design the PCb also the CAD model of that

[Lapse](https://lapse.hackclub.com/timelapse/uevxfjE7NHrr)

_Total Time = 15 min_

---

## Now I started research about the components that I can use for this project that can be cost-effective as well as easy to use, and I can get all the data sheet of that so that I can make the PCB

For the main Control Board I choose the **Waveshare RP2040-Zero** as this is not too much expensive and I can use it to control most of the components and this will done the job done.
Now I need to see the data sheet of this Waveshare RP2040-Zero to make sure that it will work with all the components.

#### And I am using this datasheet for this which is uploaded in the roubbu.in website - [Link DOC](https://robu-prod-media.s3.ap-south-1.amazonaws.com/products/attachments/8VoZujeD3ppn3I6F0tEKGp6TgBw9RXaVQka7HNXm.pdf)


<img width="1415" height="709" alt="Screenshot 2026-08-11 at 3 00 20 AM" src="https://github.com/user-attachments/assets/6e035953-2ca6-4484-9604-b1da507e3669" />
<img width="835" height="624" alt="Screenshot 2026-08-11 at 3 00 34 AM" src="https://github.com/user-attachments/assets/7b99a2e9-02cd-4579-95a1-5c4e863543c1" />
### The AHB-Lite Crossbar are perfect for the work that I will do with it 
<img width="1036" height="590" alt="Screenshot 2026-08-11 at 3 00 53 AM" src="https://github.com/user-attachments/assets/70595801-e938-4d81-8be7-08bd6d6241d8" />

The Power can be a problem but I will use type-c connected to it and will work good with wired connection 

<img width="537" height="646" alt="Screenshot 2026-08-11 at 3 01 57 AM" src="https://github.com/user-attachments/assets/73157e38-cc88-4060-aaaa-4eb761a03929" />

### the Pin out 
<img width="960" height="1029" alt="image" src="https://github.com/user-attachments/assets/8d194b23-1dc7-4cc2-8780-aa4c4eeed5cc" />

_Total Time = 1.1hrs_

---

## Now for the switches I want it to be a low profile as I saw in the "Codex Micro"

So after a going to websites I have found many low profile switches but I could not find the datasheet of that and without the datasheet I can't design the PCB . So for that reason I am going with the Kailh Choc v2 Low Profile Switches as they have detailed datasheet for the PCB footprint .

<img width="1437" height="806" alt="Screenshot 2026-08-11 at 3 23 00 AM" src="https://github.com/user-attachments/assets/fdf60feb-3ec3-4932-8876-825a70de5e1a" />


### Kailh Choc v2 Low Profile Switches - [Datasheet DOC](https://cdn.shopify.com/s/files/1/0657/6075/5954/files/SPEC-CPG135301D03_Kailh_Choc_V2_Low_Profile_Blue_Switch.pdf?v=1666690510)


<img width="1009" height="565" alt="Screenshot 2026-08-11 at 3 13 55 AM" src="https://github.com/user-attachments/assets/99a66da3-a2a0-4112-87a8-6afca64c1faa" />

<img width="1433" height="795" alt="Screenshot 2026-08-11 at 3 14 07 AM" src="https://github.com/user-attachments/assets/4e74bffe-9c8a-43f1-acaf-2aeb7cd23b8c" />

<img width="1439" height="792" alt="Screenshot 2026-08-11 at 3 14 28 AM" src="https://github.com/user-attachments/assets/113c633a-5af5-49e8-b50e-20c18fad1ff1" />

<img width="972" height="660" alt="Screenshot 2026-08-11 at 3 14 43 AM" src="https://github.com/user-attachments/assets/979c8cfa-4185-4e48-90e1-8b9df4a42e0a" />


<img width="529" height="553" alt="Screenshot 2026-08-11 at 3 15 27 AM" src="https://github.com/user-attachments/assets/441001c0-9c67-4e2a-9472-bbf796f2cd86" />

So from the datasheet I write all the important details about the switches that I need to make the pcb like the clearence , distance ,etc

### Footprint in EasyEDA for  Kailh Choc v2 Low Profile Switches

<img width="1127" height="602" alt="Screenshot 2026-08-11 at 3 41 57 AM" src="https://github.com/user-attachments/assets/d45a3820-d8ec-4931-868a-6fc6318ffff8" />


_Total Time = 1.3hrs_

---

## Now the rotary encoder switch and the joystick switch 5 way
For this I found some of the options but most of them are not available in India so I need to search for more components and then I found out all the options in the robu also I got the right footprint for all the components and I match the foot prints in the EasyEDA website and they were all correct and good to go with the PCb and the Waveshare RP2040-Zero the main board 

<img width="1314" height="700" alt="Screenshot 2026-08-11 at 3 37 31 AM" src="https://github.com/user-attachments/assets/73080a81-a3b3-445c-9047-95c2ba1c3096" />

### Datasheet - [Link Doc](https://robu-prod-media.s3.ap-south-1.amazonaws.com/products/attachments/euNhwNi9MOSVJ2z0tQazayT965JqkDky92OkwhHG.pdf)

<img width="450" height="628" alt="Screenshot 2026-08-11 at 3 38 15 AM" src="https://github.com/user-attachments/assets/d874327d-70d9-4dbc-98e2-9e1f10bfead2" />



<img width="1117" height="592" alt="Screenshot 2026-08-11 at 3 36 27 AM" src="https://github.com/user-attachments/assets/6b8a70fc-1224-43d7-950d-c5ac8f62ad96" />


Now the Multi-Directional Switches for this I have choose this

<img width="1259" height="674" alt="Screenshot 2026-08-11 at 3 39 21 AM" src="https://github.com/user-attachments/assets/ccf6f635-cbea-46f5-b403-306da29b4b99" />

### Datasheet - [Link Doc](https://robu-prod-media.s3.ap-south-1.amazonaws.com/uploads/2025/08/C2858290.pdf)

<img width="1430" height="801" alt="Screenshot 2026-08-11 at 3 39 54 AM" src="https://github.com/user-attachments/assets/d84d6493-5571-4391-9609-f9ccb3c18836" />

<img width="1074" height="523" alt="Screenshot 2026-08-11 at 3 40 35 AM" src="https://github.com/user-attachments/assets/34759bc3-8a58-44ad-a87b-03771d3254b6" />
<img width="1139" height="603" alt="Screenshot 2026-08-11 at 3 40 51 AM" src="https://github.com/user-attachments/assets/f6d32613-e9ab-4de3-9100-1262cb82406d" />

_Total Time = 2.2hrs_

## Now the Microphone and the small leds

For this I will use the XL-1608UBC leds and for the microphone I will go for the INMP441 MEMS High Precision Omnidirectional Microphone Module I2S as this is budget friendly also meets the requirements that I needed to make this project so that I can use it for the voice commands through the micro pad, and it will directly showcase in the desktop

<img width="1323" height="720" alt="Screenshot 2026-08-11 at 3 55 51 AM" src="https://github.com/user-attachments/assets/cd1334b8-9be3-494d-839b-5178d1124cd7" />

### Datasheet - [Link Doc](https://robu-prod-media.s3.ap-south-1.amazonaws.com/products/attachments/9MGXhjupqmHXpZtpmVg7DCaznTPNYbZJjBvXqi6P.pdf)

<img width="1429" height="799" alt="Screenshot 2026-08-11 at 3 56 03 AM" src="https://github.com/user-attachments/assets/9d49aa57-e487-4769-a570-fb7c5e633457" />


<img width="1085" height="550" alt="Screenshot 2026-08-11 at 3 56 47 AM" src="https://github.com/user-attachments/assets/fac45fdb-3825-4b2e-87fb-692ce621fbe4" />

### PCB DESIGN AND LAND PATTERN LAYOUT

<img width="517" height="609" alt="Screenshot 2026-08-11 at 3 57 11 AM" src="https://github.com/user-attachments/assets/d9614d34-0f6f-46fb-885a-c9fb61b52567" />


### Digital Low-Pass Filter Magnitude Response - will work for this project 

<img width="769" height="556" alt="Screenshot 2026-08-11 at 3 58 02 AM" src="https://github.com/user-attachments/assets/0ae3bc76-ac65-4b0c-9bc9-a27b0c0d38e1" />

### Footprint on EasyEDA

<img width="1134" height="605" alt="Screenshot 2026-08-11 at 3 58 42 AM" src="https://github.com/user-attachments/assets/f51936f3-3880-4c1a-b1cf-62f9fc1ff4b5" />

<img width="1131" height="603" alt="Screenshot 2026-08-11 at 3 59 42 AM" src="https://github.com/user-attachments/assets/e87f5fe6-6799-436a-8160-f529371db291" />

This took me a lot of time to cross verify the project again and again so that it will works fine so that I can make the PCB perfectly with all of this components 

_Total Time = 2hrs_

---

## Now the schematic of the PCB
This look a lot of time for me to correctly choose the components and then the footprint that will match with the datasheet of the components.
So for this I first add all the components to the schematic page and they connecting all the components one by one 

### The Waveshare RP2040-Zero

<img width="1240" height="650" alt="Screenshot 2026-08-11 at 4 05 33 AM" src="https://github.com/user-attachments/assets/1596f069-3f93-4d57-a5ad-0d424c52f6d1" />


### The Smd leds

<img width="1001" height="706" alt="Screenshot 2026-08-11 at 4 06 17 AM" src="https://github.com/user-attachments/assets/7ca2c6dc-cd38-4699-b606-532f03d8aebe" />

### The Micro phone 

<img width="958" height="452" alt="Screenshot 2026-08-11 at 4 06 58 AM" src="https://github.com/user-attachments/assets/a2aa7e50-b3ee-4343-a5d7-7b0f282e45a7" />

### The rotary encoder switch

<img width="392" height="184" alt="Screenshot 2026-08-11 at 4 07 10 AM" src="https://github.com/user-attachments/assets/b3760b38-d627-434f-be3d-518f37ee7399" />


### The joystick switch

<img width="383" height="192" alt="Screenshot 2026-08-11 at 4 07 37 AM" src="https://github.com/user-attachments/assets/3b90c9b0-ef10-4f87-a7a3-fc3c7aee677f" />

### all 12 switches with 12 1N4148 1W Zener Diode 

<img width="789" height="361" alt="Screenshot 2026-08-11 at 4 08 17 AM" src="https://github.com/user-attachments/assets/85ffdc86-3419-455a-b951-522fa1f3cff4" />


<img width="603" height="425" alt="Screenshot 2026-08-11 at 4 09 41 AM" src="https://github.com/user-attachments/assets/1cbd441d-3111-4251-b824-732ecdad96ee" />

**Now I need to make some changes to the schematic and after that it will be good to go**

**all are correct the U_21 had no connection so it will be blank**

<img width="280" height="419" alt="Screenshot 2026-08-11 at 4 11 21 AM" src="https://github.com/user-attachments/assets/497596af-fb36-4037-9869-f3b962e0ba8e" />

## Final schematic 

<img width="708" height="488" alt="Screenshot 2026-08-11 at 4 10 45 AM" src="https://github.com/user-attachments/assets/f59c14d5-39fd-42cd-8157-36341038fb59" />

_Total Time = 4hrs_






