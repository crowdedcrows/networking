# CONTENTS

## [LAB](#lab)
### [Q1](#q1), [Q2](#q2), [Q3](#q3), [Commands](#commands), [Notes](#notes)

### <a name="lab"></a>LAB

<img src="../00-files/PacketTracer_rI6hnz3VAi.png" alt="Resim" width="800">

### <a name="q1"></a>Q1

<img src="../00-files/PacketTracer_YSjQdWTNGM.png" alt="Resim" width="800">

- All interfaces of the root bridge are designated ***generally***. But exception is f0/2 and f0/3 are in the same collision domain because of hub so f0/3 is ***backup port role*** with ***discarding status*** on the root bridge.

### <a name="q2"></a>Q2

- SW1:
    - F0/1:
        - Role: Designated
        - State: Forwarding
    - F0/24: 
        - Role: Designated
        - State: Forwarding
    - F0/2: 
        - Role: Designated
        - State: Forwarding    
    - F0/3: 
        - Role: Backup
        - State: Discarding    

- SW3:
    - F0/2: 
        - Role: Root
        - State: Forwarding
    - F0/1:
        - Role: Designated
        - State: Forwarding
    - G0/1:
        - Role: Designated
        - State: Forwarding    
    - F0/24:
        - Role: Designated
        - State: Forwarding     

- SW4:
    - F0/1:
        - Role: Root
        - State: Forwarding
    - F0/2:
        - Role: Alternate
        - State: Discarding
    - F0/24:
        - Role: Designated
        - State: Forwarding    

- SW2: 
    - F0/1:
        - Role: Root
        - State: Forwarding
    - F0/2:
        - Role: Designated
        - State: Forwarding    
    - G0/1:
        - Role: Alternate
        - State: Discarding   
    - F0/23:
        - Role: Designated
        - State: Forwarding  
    - F0/24:
        - Role: Designated
        - State: Forwarding        

### <a name="q3"></a>Q3

- For instance: 
<img src="../00-files/chrome_Gfz4utbPK1.png" alt="Resim">
<img src="../00-files/chrome_Tk1wmjfuKo.png" alt="Resim">
...
...
...

.
.
.


### <a name="commands"></a>Commands

### <a name="notes"></a>Notes


