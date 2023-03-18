# 3DO NOZZLE CAMERA

After seeing a lot of cool nozzle camera videos with hacked-up endoscopes...
We decided to make a real "Nozzle Camera" for 3D printers.
We ended up making this.
-	MIPI Camera with external USB webcam encoder (to make the camera as small as possible)
-	Fixed focus lens (AF lenses start to shake a loose focus when moving fast)
-	Custom FEP+Silicone USB cable, as we couldn’t find any high temp flexible USB cables on the market.
-	Custom SK6812 WWCW LED, we wanted as much light as possible while keeping the SK6812 protocol, therefore we ended up making our LEDs similar to RGBW just with only white diodes inside.


<img src="./images/KIT.jpg "  width="50%">

|                         | 4K (Sony IMX258)     |
|-------------------------|----------------------|
| Sensor Size             | 1/3.06               |
| Mega-Pixel              | 13MP                 |
| Frame Rate              | 30FPS@4K 60FPS@1080P |
| Lens type*              | Fixed Focus          |
| FoV                     | 80Deg                |
| FPC length              | 25cm                 |
| Operating temperature** | -20°C TO 60°C        |
| Storage temperature     | -40°C TO 80°C        |

## Video
[![3DO Nozzle Camera teaser](https://img.youtube.com/vi/BjG8rhLlGIU/0.jpg)](https://www.youtube.com/watch?v=BjG8rhLlGIU)

## Folders
- printers  printers (mounts for different printers)
- hardware (CAD files to help design printer mounts)

## Software
The camera works as a standard UVC web camera and is therefore compatible with Linux, Windows, and Mac.
For streaming, we recommend using [mainsail](https://github.com/mainsail-crew/mainsail) + [crowsnest](https://github.com/mainsail-crew/crowsnest). 

## FAQ
- Does it work in an enclosed printer?

Yes, tho our camera is rated at 60C we have been running it for 48hrs in a 70C industrial heat chamber without any issues.
- Why is FPC so long?

We decided on having 25cm between the camera and PCB for more flexibility on future mount designs.
-  Can I bend/fold the FPC to make it shorter?

Yes, FPC is flexible and can be bent, if you want to fold it (180deg) we recommend doing this max one time in the same spot, or else you risk braking the lanes inside FPC.

Example of folding FPC

<img src="./images/FPC_BEND.jpg "  width="20%">

## Contributors that made this project possible
CAD Design & Testing
-	Olof Ogland (Known from Bondtech)
-	Kenneth Munkholt (VZ Community)
-	Dennis Jespersen (From RatRig Community)

Software Development & Testing
-	Meteyou (Mainsail founder)
-	KwadFan (Crowsnest founder)
-	Rogerlz(Crowsnest Tester)
	
Beta Testers
-	Mitsuma (From RatRig Community)
-	Joao Barros (From RatRig Community)

## Recipient / Nonparticipant
In that start we had one main CAD devolper (RayKn#2312 Raymond Knetemann) 
He said he would be more dedicated to the project if he got some kind of payment, as we wanted to fast-track the project we agreed..
We made a deal on a LDO Voron v0.1 for him making us this mounts 
-	Voron SB
-	RatRig Eva 3.x
-	Voron AB
-	Voron V0.1
-	Prusa MK3S
-	Ender 3

Sadly after Raymond recived a voron from us hes dedication to the project went the oppesit way, and untill now we havent recived anything from him.
We asked him to send the printer back or pay for it, he refused both and we are now working on debt collection.

This is the story in short, Raymond dealyed this project alot. But a huge thanks to Olof Ogland from bondtech that steped in and made a Voron mount in no time, for our release.

## Where to buy
EU

<a alt="3DO" href="https://3do.eu/"><img src="https://3do.eu/img/logo-1645171273.jpg" width="200" ></a>

USA 

<a alt="Fabreeko" href="https://www.fabreeko.com/"><img src="https://cdn.shopify.com/s/files/1/0266/5001/7990/files/Fabreeko_Logo_ecf1536e-3074-4a0e-9306-87ca89f1abbd_320x.png" width="200" ></a>

<a alt="KB3D" href="https://kb-3d.com/"><img src="https://kb-3d.com/store/img/kb-3d-logo-1673465361.jpg" width="200" ></a>