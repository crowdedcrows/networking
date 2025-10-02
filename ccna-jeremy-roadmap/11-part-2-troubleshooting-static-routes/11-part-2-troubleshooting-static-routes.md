# CONTENTS

## [LAB](#lab)
### [Q1](#q1)

### <a name="lab"></a>LAB

<img src="../00-files/PacketTracer_Qu6zzNCEvs.png" alt="Resim" width="800">

### <a name="q1"></a>Q1

#### ÇÖZÜM
- R1'de hatalı static route yapılandırması(192.168.3.0/24 ağı için hatalı NEXT_HOP girildi)
- R2'de hatalı static route yapılandırması(192.168.3.0/24 ağı için hatalı interface girildi)
- R3'de g0/0 arayüzünde hatalı ip address yapılandırması ve 192.168.1.0/24 ağı için static route eklenmemesi

#### RESULT

<img src="../00-files/PacketTracer_uUtGik8kKr.png" alt="Resim" width="800">