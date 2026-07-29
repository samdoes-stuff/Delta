## 26/07/2026 

All of the journals today. Cause I locked in so hard. I could not focus on anything else. Horizons got me bad. 

Idea 

I made a keyboard in Blueprint. Sadly, that never came to my home. It got lost. 

So, I made a devboard in Fallout with the exact same MCU that I used in my keyboard. And thankfully It work. 

Then, I though just finally make the keyboard. But designing a pcb for the keyboard is so Lame. And also, my devboard is very much suitable for handwire keeb. 

I thought you know what lets get a plate first. Cause the plate is very important. 3D printed Plate doesnot work great with my low profile keycaps and stabilizers.  

And due to its 1.2mm thickness it sags way to much. And the holes does not print great so I have aborted the machine. 

Another fact is my diode is SMD. So, making a fully handwire keeb will be tough as hell. 

Then make a half handwire keeb! How's that possible. First of all FR4 is a great material for keeb plate. It does not sound the best but it works. Also, JLCPCB supports 1.2mm pcb thickness. 

So, make a pcb and order from JLCPCB which is actually a plate. And to properly use it make some Colomn and Row routing so that I don't need to connect all of the swwitches with single core brass wire. 

## 28/07/2026 

So locked in to finish the project. Sorry for not detail journaling. But I already finished the routing but I need to made some changes. 

1. Colomn pads are exposed so I don't separate pads for soldering. 
2. Row pad are too farway from the board and I have to place my own MCU and considering that I pulled in the row pads inside. 

Also, I was struggling with the spacer height cause I don't want it to be thick as well as well as I want it to be fitted with my design.

![alt text](<Design File/Screenshot 2026-07-28 120614.png>)

![alt text](<Design File/Screenshot 2026-07-28 120603.png>)

![alt text](<Design File/Front Layer.png>)

![alt text](<Design File/Back Layer.png>)

So, right now doing the assembly designing.

The assembly is finished. Right now render time 

![alt text](<3D & Plate/Screenshot 2026-07-28 151730.png>)
![alt text](<3D & Plate/Screenshot 2026-07-28 151740.png>)
![alt text](<3D & Plate/Screenshot 2026-07-28 151751.png>)

# 29/07/2026 

Today is the last day of project render is done. But I don't like it as much as I liked my previous renders before. So To DO task is may be generate a better render suitable for the project. It looks more Ugly cause I don't have any longer keycaps than 1U 


Talking about the project, I need to clarify my design thought process in one cause it may seem bit unclear. 

FR4 is a very sturdy material. So, I intentionally have only 4 holes for the plate which is only needed to holde the keyboard. I also used SMD M3 standoffs which can  be soldered to the PCB itself. So that it can work as a spacer between case and keyboard and also a standoff which I can screw from behind. 


In the case itself, I counter sunk the hole. Big enough to use any type of M3 bolts. I things the 3D model bound for the M3 spacer is cooked. Cause it seems so small despite being a 6.6 mm long. But whatever I can work with this cause the switches have their own flat surface to sit one. So as long as I screw, I am good. 

For the PCB design, I used the dxf as a Mechanical layer for reference. Where I cut the Multilayer hole According to the reference. So it is exactly like a plate should be doing. 

I want this plate to be colored but I will order this as a JLCPCB. So, I rather use a colorful image and get the special JLCPCB silksceen pcb. Which are farely priced at 1.2 mm thickeness. I chose cosmic orange as the Iphone color cause it looks stunning to me but printing a case which can appreciate the color is hard. 

Why I advertise this keyboard as Semi- Modular Keyboard? 

Good this about the keyboard is that you can reuse the SMD diodes. There are exposed Colomn and Row pad for working with a micro controller which I made, PHOTON, a nrf52840 based keyboard controller flashed with the necessary firmwares and it is working very good. 

There is soldering pad for the switches around each socket. So, it reduces the pain but I still have coil up my switch contact pad with necessary wires. I need bare wire for that. I may strip cut some wire and re use it from Fallout project. 

There is also some rotated switch sockets in the ROW4. Why? cause I wanted to match the Switches line and mounting holes was blocking me. Specially for the Space key. So, I rotated it 180. Which also made my colomn routing more easier. 

![alt text](<Design File/image.png>)

As you can see it is bit different from the upper row orientation. 


![alt text](<Design File/Screenshot 2026-07-29 095740.png>)


Some of the soldering pads are not identical for many reasons. Such as mounting hole is blocking or the stabilizer is blocking so many have very unorthodox design. 

Problem now is that, how I should approach this project to people? Do I think it is a great idea yeah? Cause you are ditching a seperate PCB for your components only where you are getting a plate PCB? Is it cost affective I'm not sure. Let's calculate together. 

A same separate PCB for keeb is round about 17-18 dollar with shipping safe to assume about 30 dollars. Normally, the plate are 3D printed and shipping for the 3D prints is also about 12 dollars. Overall cost is same. 

This only makes sense if you have a mcu before hand to build this keyboard. Also, 1.2mm 3D printed plate is saggy as hell and breaks easily cause the plate mounted stabilizers are heavy as ... 

Why a backplate? Why no case? My nrf52 devboard has BLTE support. If I make a case, I will have BLTE but the range will not work out. And also it looks very chill Exposing the inner things. 

Now, I think about it. Works greatly cause my MCU would be in the middle. I may have to use a USB extender to the side of the board. I could actually route the usb through my board but solder usb with hands are messy. I did not reached the standard yet. 

So, yeah. That's it. I have to make the project more presentable and make sense cause It is weird as fck project. 

More context, JLCPCB is well priced the keeb with multicolor silkscreen 

![alt text](<Production File/cart.png>)

There are all of the recording below: (My project is hackatime linked that's why I am not taking the piss to attach each lapse with each date) 


- https://lookout.hackclub.com/api/media/4e05dfd7-6041-4e34-b83c-1064116a122c/video.mp4
- https://lookout.hackclub.com/api/media/1dc85741-3fff-4677-a112-51c192c05d4e/video.mp4
- https://lookout.hackclub.com/api/media/0e20855a-b284-464d-8ac7-688112c2406b/video.mp4
- https://lookout.hackclub.com/api/media/2136d317-7a3a-4403-a045-6fbafa5dcc07/video.mp4
- https://lookout.hackclub.com/api/media/ebedb99e-385c-4192-b6f3-6d1dbb1fea1d/video.mp4
- https://lookout.hackclub.com/api/media/5f424804-04c5-425b-a7e6-d0b395b0df84/video.mp4
- https://lookout.hackclub.com/api/media/7cfa19bb-e021-412c-a01a-4581334cabf2/video.mp4
- https://lookout.hackclub.com/api/media/6d00dce2-2f55-4263-8c90-0c44f64115d9/video.mp4
- https://lookout.hackclub.com/api/media/7e3c7925-3d64-4c5d-a133-5fa932962269/video.mp4
- https://lookout.hackclub.com/api/media/2a0de14b-75ca-4dc3-9840-3b0e7193132c/video.mp4
- https://lookout.hackclub.com/api/media/1d4077b3-0860-4030-af31-9b1d1eff7ac8/video.mp4
- https://lookout.hackclub.com/api/media/02adc9c5-d14a-4044-b129-9b42e2bd2b32/video.mp4
- https://lookout.hackclub.com/api/media/c2593c06-2485-46c1-be8c-652129e44806/video.mp4
- https://lookout.hackclub.com/api/media/1f03817f-7202-4d70-a128-753d85da033b/video.mp4
- https://lookout.hackclub.com/api/media/35da5bdc-3d1b-4c87-9576-1a4a8be99c85/video.mp4
- https://lookout.hackclub.com/api/media/bff327be-956b-43dd-bec6-1a58abb70091/video.mp4
- https://lookout.hackclub.com/api/media/f112c032-6ec9-421d-9540-0537e94ae2da/video.mp4
- https://lookout.hackclub.com/api/media/4cd1cc04-864b-4b58-85ce-14655e52a519/video.mp4
- https://lookout.hackclub.com/api/media/8077981b-2dde-45dd-b9f3-6b78c0f506ae/video.mp4
- https://lookout.hackclub.com/api/media/f22e079a-e798-4a40-a452-70f9a00291c8/video.mp4
- https://lookout.hackclub.com/api/media/ec6ec426-f9e7-4000-a042-bd1a28374e71/video.mp4
- https://lookout.hackclub.com/api/media/dff9fcce-78ee-463c-b5a1-d52c81984b88/video.mp4
- https://lookout.hackclub.com/api/media/8a464cfb-4786-4feb-ad4d-de3ac69f420b/video.mp4
- https://lookout.hackclub.com/api/media/9c10cd1d-6c1f-494a-9e35-8bc1dfe80f02/video.mp4
- https://lookout.hackclub.com/api/media/baaf7cc0-775a-4434-aa9e-ed144bda75a2/video.mp4
- https://lookout.hackclub.com/api/media/d0cdc019-1a61-416d-bdc5-c02a9a4f21ac/video.mp4
- https://lookout.hackclub.com/api/media/8fc09045-cc91-4407-8ed5-7eefb6732b84/video.mp4
- https://lookout.hackclub.com/api/media/83e03227-ef92-49d9-80c0-3d5152c342f9/video.mp4
- https://lookout.hackclub.com/api/media/1cc4b188-238c-49da-a516-90676d9cccb5/video.mp4
- https://lookout.hackclub.com/api/media/f5c1bd42-231e-43d6-b16a-2ca92f807f7a/video.mp4
- https://lookout.hackclub.com/api/media/c024995b-aefb-4a4a-bc3d-aac215de3998/video.mp4
- https://lookout.hackclub.com/api/media/902ad01e-57e9-47fe-8fd3-6fbb8dc3bc0b/video.mp4
- https://lookout.hackclub.com/api/media/85b93188-4aab-47e5-a592-0b77e88653ef/video.mp4
- https://lookout.hackclub.com/api/media/f173aa33-6849-4ac2-82b3-09843f01b924/video.mp4
- https://lapse.hackclub.com/timelapse/X9GNSF3x418q
- https://lapse.hackclub.com/timelapse/1dqmjk-5ka2x
- https://lapse.hackclub.com/timelapse/GncaxiOsA7dC