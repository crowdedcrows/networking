# CONTENTS

## [LAB](#lab)
### [Q1-2-3-4-5](#q1-2-3-4-5)
### [RESULT](#result)

### <a name="lab"></a>LAB

<img src="../00-files/PacketTracer_I96ERT3UkZ.png" alt="Resim" width="800">

### <a name="q1-2-3-4-5"></a>Q1-2-3-4-5

```
Router(config)#hostname R1
R1(config-if)#description ## TO SW1
R1(config-if)#ip address 172.16.255.254 255.255.0.0
R1(config-if)#speed 1000
R1(config-if)#duplex full
R1(config-if)#no shutdown 

.
.
.
SW1...

.
.
.
SW2(config-if)#inter ran f0/3-24,g0/2
SW2(config-if-range)#desc
SW2(config-if-range)#description ## DISABLED
SW2(config-if-range)#shu
SW2(config-if-range)#shutdown 
```
### <a name="result"></a>RESULT

<img src="../00-files/PacketTracer_fRuNDHMXlM.png" alt="Resim" width="1000">

#### Running config R1:

<img src="../00-files/PacketTracer_LfXFu9aww8.png" alt="Resim" width="500">

#### Switch interfaces status

```
### Switch specific command
SW1#show interface status
SW2#show interface status
```
<img src="../00-files/PacketTracer_L8L58gvX2J.png" alt="Resim" width="1000">
<img src="../00-files/PacketTracer_wRbrp0tlmC.png" alt="Resim" width="1000">

---

<img src="../00-files/PacketTracer_1xdm85m9hq.png" alt="Resim" width="1000">


[Go to the top](#contents)