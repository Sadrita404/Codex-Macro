| Title | Codex Macro|
| :-- | :---|
|Author |Sadrita Neogi|
|Type | Hardware  |
Total Hrs |  19.2 |

## Started design designing the product and taking info from the previous one that had already existed.
So for this project the main design inspo for me was the all new Codex Micro by Open Ai ( made by the company Work Louderand I like the brand ) So I thought to make a same thing under budget as the Codex Micro is costed at $230which is too much for what it's offer so I named it " Codex Macro "

#### Inspo 
<img width="1500" height="1500" alt="image" src="https://github.com/user-attachments/assets/16ed898a-19f2-4ba6-ad5c-37c4eae76fce" />

#### Mine Design 
<img width="798" height="487" alt="design" src="https://github.com/user-attachments/assets/a960c9aa-61fe-4f04-92af-0d114e3b7697" />

This is just the wire frame of the project and I have made it just for the reference so that I can use it to design the PCb also the CAD model of that


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

**all are correct the U_22 had no connection so it will be blank**

<img width="280" height="419" alt="Screenshot 2026-08-11 at 4 11 21 AM" src="https://github.com/user-attachments/assets/497596af-fb36-4037-9869-f3b962e0ba8e" />

## Final schematic 

<img width="708" height="488" alt="Screenshot 2026-08-11 at 4 10 45 AM" src="https://github.com/user-attachments/assets/f59c14d5-39fd-42cd-8157-36341038fb59" />

_Total Time = 4hrs_

---

## Now the PCB
After completing designing the full schematic for the project. Now I convert the schematic into PCV, where I need to place all the components to their designated spot, and then I need to trace all the places and after that, I need to run the DRC check and then if everything is fine, then I can complete generating the Garber file for the project.

<img width="1193" height="674" alt="Screenshot 2026-08-11 at 4 14 12 AM" src="https://github.com/user-attachments/assets/b47c27c7-1856-494d-b763-e32035120f58" />

<img width="541" height="462" alt="Screenshot 2026-08-11 at 4 15 10 AM" src="https://github.com/user-attachments/assets/3486867e-9dd9-4858-863f-b2ff14ad7f74" />

<img width="851" height="278" alt="Screenshot 2026-08-11 at 4 16 18 AM" src="https://github.com/user-attachments/assets/e96c85ca-eb8d-492c-9575-1ad507b65374" />

<img width="447" height="357" alt="Screenshot 2026-08-11 at 4 17 34 AM" src="https://github.com/user-attachments/assets/8cb5c537-f865-41d1-92a9-57da78b60444" />

<img width="678" height="536" alt="Screenshot 2026-08-11 at 4 19 47 AM" src="https://github.com/user-attachments/assets/b1d37ed6-4e69-4765-ab52-523c71cc259e" />

<img width="851" height="664" alt="Screenshot 2026-08-11 at 4 20 02 AM" src="https://github.com/user-attachments/assets/542d6333-22ce-4a03-896e-d0a31548e5b3" />

<img width="644" height="481" alt="Screenshot 2026-08-11 at 4 21 24 AM" src="https://github.com/user-attachments/assets/ba361290-03c5-4b09-9c12-1c7d2e3993b4" />

### This just the start now I need to work on the Main PCB to add all the 3d models to make the traces more wide also make the footprint to be good .

_Total Time = 1.3hrs_

---

## Final PCB Done
After a lot of doing the PCB and making some changes to the schematic, also, I forgot to add the resistor to the small LED after that, I have also placed the components in such a way as that all the switch along with the key caps are now perfectly fit, and I have also placed the microphone LED Rotary encoder all of this in the correct places along with. I have also make that trace line width to more wide for good connectivity and added some good silk screen .

<img width="658" height="588" alt="Screenshot 2026-08-11 at 4 25 05 AM" src="https://github.com/user-attachments/assets/f604bd80-14f1-4465-bb03-0046172db847" />

<img width="582" height="552" alt="Screenshot 2026-08-11 at 4 25 17 AM" src="https://github.com/user-attachments/assets/b63e95a9-cbcd-4fbc-97e9-9c7a38cc3e8c" />

### Final look 
<img width="602" height="563" alt="Screenshot 2026-08-11 at 4 25 35 AM" src="https://github.com/user-attachments/assets/0b7f1ed8-34b2-4992-8937-41a34a0a364b" />

<img width="544" height="533" alt="Screenshot 2026-08-11 at 4 25 49 AM" src="https://github.com/user-attachments/assets/8b86adb9-6132-4652-a1d4-3eb8c88c3a86" />

_Total Time = 2hrs_

---

## Now the CAD Part for this 
So for the CAD part I will go for fusion360 to make the case of this project and also the final render of it.

For this first I need to take the dimensions of the PCB 
<img width="593" height="516" alt="Screenshot 2026-07-25 at 7 00 01 AM" src="https://github.com/user-attachments/assets/b2286165-bb09-4d98-84a8-af393a365049" />

<img width="1470" height="956" alt="Screenshot 2026-07-25 at 7 02 29 AM" src="https://github.com/user-attachments/assets/0f05965e-bedd-4e69-931f-71301f8bc2c6" />

<img width="1470" height="956" alt="Screenshot 2026-07-25 at 7 49 32 AM" src="https://github.com/user-attachments/assets/ef0dfb96-35c9-4286-9b36-8deacb506770" />

<img width="1470" height="956" alt="Screenshot 2026-07-25 at 7 51 20 AM" src="https://github.com/user-attachments/assets/6b54c302-b230-4f5f-bd2b-40436d96a7b5" />

<img width="1470" height="956" alt="Screenshot 2026-07-25 at 7 52 01 AM" src="https://github.com/user-attachments/assets/04e2393a-dceb-41e5-a1ba-47cd1dd7da16" />

**The Base case is complete**

_Total Time = 0.6hrs_

---

## Now I need to make a slop like structure for the case so that it will looks good 

So I started trying different methods like how I will make this kind of design

<img width="1470" height="956" alt="Screenshot 2026-07-25 at 8 59 54 AM" src="https://github.com/user-attachments/assets/b5e371ea-c8a7-45e9-93dc-0afb829f07cf" />
<img width="1470" height="956" alt="Screenshot 2026-07-25 at 9 00 16 AM" src="https://github.com/user-attachments/assets/08efc4d3-df93-4efc-bc29-a1612a07e788" />
<img width="1470" height="956" alt="Screenshot 2026-07-25 at 9 11 09 AM" src="https://github.com/user-attachments/assets/83160d6e-61e1-4bb7-a059-c83c87962968" />

**After a couple of tries I have finally made the slop like structure for the case now I need to make the base part which I will do later**
This took me a lot of time as there is not dedicated tool in fusion to make this type of design so I had to make it from scratch 

_Total Time = 1.1hrs_

---

## Now adding holes for the type-c and plate for the mounting holes for the threaded inserts

<img width="1470" height="956" alt="Screenshot 2026-07-25 at 9 19 54 AM" src="https://github.com/user-attachments/assets/f19c4b0c-a804-4ace-b414-e177919484a8" />
<img width="1470" height="956" alt="Screenshot 2026-07-25 at 9 31 55 AM" src="https://github.com/user-attachments/assets/40bee02a-9e19-4565-b5f2-461bfbe6f2fb" />

_Total Time = 0.51hrs_

---

## The main base of the case 
For this I want it to be like the inspo " Codex Micro " like the slant height one so I started designing that in the fusion and I have made it properly 

<img width="1470" height="956" alt="Screenshot 2026-07-25 at 10 57 38 AM" src="https://github.com/user-attachments/assets/63240f8c-0676-43f8-a018-b8128f4e02e1" />

<img width="1470" height="956" alt="Screenshot 2026-07-25 at 11 03 40 AM" src="https://github.com/user-attachments/assets/cf96343c-d426-4cbf-9515-60d3397e8418" />

<img width="1470" height="956" alt="Screenshot 2026-07-25 at 11 04 06 AM" src="https://github.com/user-attachments/assets/52e3be24-eae0-4e31-9473-765e70be7227" />

<img width="1470" height="956" alt="Screenshot 2026-07-25 at 11 12 02 AM" src="https://github.com/user-attachments/assets/515a3e4b-99ed-4a66-80f5-997c83728c7d" />

_Total Time = 0.44hrs_

---

## Now the final CAD assembly of the project 

So I started downloading all the 3d models for the switches , keycaps , mic , encoder, etc and added it to the final cad model that I have done in fusion360

I have finally assemble all the components into the final CAD model and export it, and after that, I will publish it to the GitHub. This took me a lot of time to make the alignment correct, but after all of that, the final project turned out to be good. I like it.

<img width="1470" height="956" alt="Screenshot 2026-07-25 at 11 41 38 AM" src="https://github.com/user-attachments/assets/f1678739-0d30-40cd-b3d0-d2b05836a2e1" />

<img width="1470" height="956" alt="Screenshot 2026-07-25 at 3 32 50 PM" src="https://github.com/user-attachments/assets/e53d658b-e282-4d5d-b25d-824f6241a9be" />

<img width="1470" height="956" alt="Screenshot 2026-07-25 at 5 32 52 PM" src="https://github.com/user-attachments/assets/dadc984b-45d0-401d-ad5d-9f52f909ed24" />

I have also added colour to the model so that I can render some good images for it 

_Total Time = 1.3hrs_


---

## Rendering some good images for the gitrepo 

I am rendering the images since this is also helps the other user that how the final project looks like after I built it, so I prefer to render some good images since fusion 360 offers that in his own app, so I render some images so that I can also put it in the GitHub as well as it will work as the showcase of the project
<img width="1470" height="956" alt="Screenshot 2026-07-25 at 5 33 05 PM" src="https://github.com/user-attachments/assets/12bb239f-ae2a-46ac-9bf8-e2426a6b5d94" />
<img width="1470" height="956" alt="Screenshot 2026-07-25 at 5 33 15 PM" src="https://github.com/user-attachments/assets/dc1c379b-5d94-4138-afa3-a6fc8920ab66" />

### Final Render 

<img width="2940" height="1272" alt="Render 1" src="https://github.com/user-attachments/assets/5160831d-fe49-4af2-be5f-935588615a46" />

<img width="2940" height="1272" alt="Render 2" src="https://github.com/user-attachments/assets/f34d11d9-1b39-4dc3-b555-91b59e23aa3d" />

<img width="2940" height="1272" alt="Render 4" src="https://github.com/user-attachments/assets/06f533fd-2596-4876-92da-cefa18baf0c8" />

<img width="2940" height="1272" alt="Render 6" src="https://github.com/user-attachments/assets/279aa14d-8eaf-491c-bd4a-e318ab38b795" />

<img width="2940" height="1272" alt="Render 5" src="https://github.com/user-attachments/assets/e84c9a80-dcda-4830-8bf9-0890445bd842" />

<img width="2940" height="1272" alt="Render 3" src="https://github.com/user-attachments/assets/b025a91e-3e1d-485a-bf47-8ac16cb754df" />


_Total Time = 1.1hrs_


