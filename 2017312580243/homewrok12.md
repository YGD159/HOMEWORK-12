P10、

a)A的平均吞吐量由Pa(1-PB)*P**a*(1−*P**B*)给出.总效率为Pa(1-PB)PB(1-Pa)*P**a*(1−*P**B*)*P**B*(1−*P**a*).

b)A的吞吐量为Pa(1-PB)=2PB(1-PB)=2PB-2(PB)2*P**a*(1−*P**B*)=2*P**B*(1−*P**B*)=2*P**B*−2(*P**B*)2，B的吞吐量为PB(1-Pa)=PB(1-2PB)=PB-2(PB)2*P**B*(1−*P**a*)=*P**B*(1−2*P**B*)=*P**B*−2(*P**B*)2，很明显，A的吞吐量不是B的两倍，为了使PA(1-PB)=2PB(1-Pa)*P**A*(1−*P**B*)=2*P**B*(1−*P**a*)，我们需要PA=2-(Pa/PB)*P**A*=2−(*P**a*/*P**B*)。

P17、

等待51200比特时间。对于10 Mbps，这个等待是

\frac{51.2\times 10^3 bits}{10\times 10^6 bps}=5.12ms10×106*b**p**s*51.2×103*b**i**t**s*=5.12*m**s*

对于100Mbps，等待时间是512\mu s*μ**s*

P18、

在t=0时A发射。在t=576时，A将完成传输。在最坏的情况下，B在时间t=324开始发送，即A的第一个帧到达B之前的时间。在时间t=324+325=649时 B的第一个比特到达A时，A在检测到B已经发送之前就完成了传输，所以A错误地认为它的帧在没有碰撞的情况下被成功地传输了。