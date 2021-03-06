


![image](https://user-images.githubusercontent.com/19898602/125561367-8227639a-4998-40e0-86e8-33341bd31287.png)


Hi guys in this video I have made a automatic wire cutter and stripper machine,
I have used a nextion 2.8" HMI for user interface from it you can enter the desire length of cuts for wire.

This machine feed the wire of desire length and strip the end of desire length 

I have used a stepper motor feeding system to feed wire upto cutter and other stepper motor

is connected with cutter which cut and strip the wire.

I have placed a servo motor which direct the wire for full cut and half cut.

# VIDEO 

https://www.youtube.com/watch?v=Jl6ZATZypAQ

This the link of complete video you can watch the video from here where I have demonstrated complete steps in 
order to build this cool arduino based wire cutting and striping machine.

# COMPONENTS 

> Arduino nano


> A4988 Stepper driver


> Nextion HMI


> Micro servo motor


> wire cutter


> Custom PCB


> Some 3D printed parts


# CIRCUIT DIAGRAM

![Untitled-4](https://user-images.githubusercontent.com/19898602/125567746-86a8bb3f-6d84-4c88-bd82-8a644690dbb4.jpg)



# CONSTRUCTION

![MVI_0001_2 00_00_43_24 Still001](https://user-images.githubusercontent.com/19898602/125562898-dddd6813-8214-4017-b9c6-6dda569d8615.jpg)

First I cut the wooden shet of size 150 x 150 mm 

I have used 12mm birch plywood for the  based and cut it by using my table saw.

![MVI_0001_2 00_00_55_22 Still002](https://user-images.githubusercontent.com/19898602/125563000-37ebf034-b059-4cff-abeb-177ae8a65653.jpg)

I have design some of my parts in fusion 360 and 3D printed them

I have used PLA filament with almost 50% infill PLA is very best material

for such purpose its easy to work with PLA filament 

I will leave the link to download the 3D files


# 3D FILES

Below is the Link to download 3D files

https://pinshape.com/items/103601-3d-printed-arduino-wire-cutting-machine

![image](https://user-images.githubusercontent.com/19898602/125563332-bc9515ac-77fd-4678-af30-deb6a63565f0.png)



![MVI_0001_2 00_01_10_10 Still003](https://user-images.githubusercontent.com/19898602/125563654-5234eaa8-7bd3-4e59-9b7d-099cb2e0bc9c.jpg)

Then I placed all the 3D printed parts on woden base

and mark the location for hole, then I drill it out using my stand drill

all holes are of 4mm so we can easily fit 3mm Screw through it and leave some tolerance for further adjustment.

![MVI_0001_2 00_03_14_06 Still004](https://user-images.githubusercontent.com/19898602/125563840-56d2d1ed-f39f-4ce7-aae8-4e57bf12cc37.jpg)

This is wire feeding mechanism which made using 3D printed parts.

This system push wire to teethed pully as stepper motor rotates wire will feed to the cutter.


![MVI_0001_2 00_04_05_09 Still005](https://user-images.githubusercontent.com/19898602/125563946-38273048-83fe-45ad-a2ba-52cba3f27469.jpg)

This is the wire cutter, I have removed its grip from the handle

so it can easily fit in the 3D printed parts and secure it tightly to the wooden base

I have made a small grove on the upper handle, I this grove is used to connect 

the wire which is connected to the cutter stepper  motor so that when the 

cutter stepper motor rotates it pull the cutter handle done and we can cut the wire during this process.



![MVI_0001_2 00_05_38_21 Still006](https://user-images.githubusercontent.com/19898602/125564274-aa913191-3e76-478c-9d64-e2c2550cc9c7.jpg)


I have used a 2.8" nextion HMI for the user interface. user can enter how much quantity and length for wire to cut.

Using HMI is very best idea because this Nextion HMI have on board uController on it. Means all the HMI coding 

Is stored in HMI itself no extra load on Arduino. this will make coding simple and fast, HMI itself have some GPIO???s on board


# CUSTOM PCB

![image](https://user-images.githubusercontent.com/19898602/125565116-4c680a77-972b-40bd-89bf-004449d13060.png)


![image](https://user-images.githubusercontent.com/19898602/125565128-45735f1e-9117-4a26-b689-73deb638d1d7.png)


![image](https://user-images.githubusercontent.com/19898602/125565136-36bd92db-1dbf-47f3-b9f9-5dc034d2a6d1.png)




I have designe a PCB which is multipurpose and order it from [JLCPCB](https://jlcpcb.com/IAT ) 

I always prefer [JLCPCB.com](https://jlcpcb.com/IAT) for my PCB needs, [JLCPCB.com](https://jlcpcb.com/IAT) have best deals for their customers
$2 for 1-4 Layer PCBs, free SMT assembly monthly.


and this is not it if you are new customer for [JLCPCB.com](https://jlcpcb.com/IAT) you will get 18$ coupon on your
first registration to their site its limited period offer so what are waiting for go  and get your benefit. 


[Click here to visit JLCPCB.com](https://jlcpcb.com/IAT)


followings are the some features of PCB

1. Wide range of power input 9V to 24V DC
2. Cross polarity protection
3. DC motor voltage selection 9V or 12 V DC
4. Servo motor voltage selection 5V or 9V DC
5. Manual microstepping setting for stepper motor
6. Power indication LED
7. L298N IC for heavier DC motor
8. ON board 5V and 9V regulator no need to arrange different power sources
9. Header pins and screw terminals for easy connections

List of the Components you can connect to the PCB

1. 2 DC motor ( 9V to 24V DC)
2. 2 Potentiometer
3. 2 Servo motors ( 5V to 9V DC)
4. 1 Serial device (BT module, HMI, Communication module, RX, TX)
5. 1 Encoder (2 interrupt pin & 1 PB pin)
6. 1 I2C device (SCL/SDA Device, display, MPU6050 etc)
7. 2 Stepper motors

 

![MVI_0001_2 00_09_37_13 Still007](https://user-images.githubusercontent.com/19898602/125568053-09d45d93-a4db-4103-9674-0dff868a9753.jpg)


I have place the wire roll at one end of the based this wire is feed to the cutter

![MVI_0001_2 00_10_31_11 Still008](https://user-images.githubusercontent.com/19898602/125568165-9d9696a1-5669-44b7-8be9-5489a5fe8343.jpg)


At last we have HMI here we enter the specification for cutting like length of wire cut and strip length.



![MVI_0001_2_3](https://user-images.githubusercontent.com/19898602/125568358-e4eb3470-e845-47b5-8d1d-7b6f564a7edd.gif)



