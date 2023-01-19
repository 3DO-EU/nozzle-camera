# 3DO NOZZLE CAMERA

After seeing a lot of cool nozzle camera videos with hacked-up endoscopes...
We decided to make a real "Nozzle Camera" for 3D printers.
We ended up making this.
-	MIPI Camera with external USB webcam encoder (to make the camera as small as possible)
-	Fixed focus lens (AF lenses start to shake a loose focus when moving fast)
-	Custom FEP+Silicone USB cable, as we couldn’t find any high temp flexible USB cables on the market.
-	Custom SK6812 WWCW LED, we wanted as much light as possible while keeping the SK6812 protocol, therefore we ended up making our LEDs similar to RGBW just with only white diodes inside.
-	Two versions having different price points (IMX258 and OV5648)
IMX258 can do 60FPS@1080P and are therefore optimal for fast printing, whereas OC5648 can do 30FPS@1080p.

(Camera Picture)

|                         | 4K (Sony IMX258)     | FHD (OV5648)  |
|-------------------------|----------------------|---------------|
| Sensor Size             | 1/3.06               | 01/4       |
| Mega-Pixel              | 13MP                 | 5MP           |
| Frame Rate              | 30FPS@4K 60FPS@1080P | 30FPS@1080P   |
| Lens type*              | Fixed Focus          | Fixed Focus   |
| FoV                     | 80Deg                | 82.7Deg       |
| FPC length              | 25cm                 | 25cm          |
| Operating temperature** | -20°C TO 60°C        | -20°C TO 60°C |
| Storage temperature     | -40°C TO 80°C        | -40°C TO 80°C |

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
-	Dennis Jespersen (From RatRig Comunnity)

Software Development & Testing
-	Meteyou (Mainsail founder)
-	KwadFan (Crowsnest founder)
-	Rogerlz(Crowsnest Tester)
	
Beta Testers
-	Mitsuma (From RatRig Comunnity)
-	Joao Barros (From RatRig Comunnity)

## Where to buy
EU [3DO](https://3do.eu/)
USA [Fabreeko](https://www.fabreeko.com/)