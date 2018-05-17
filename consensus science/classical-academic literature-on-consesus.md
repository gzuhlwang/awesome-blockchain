
# 共识科学经典论文


## SIGOPS名人堂奖

ACM SIGOPS(Special Interest Group on OPerating Systems)名人堂奖（Hall of Fame Award, HoF）是SIGOPS组织于2005年设立的奖项，用于评选一批发表**10年**以上对操作系统领域产生巨大影响力的文章，是系统领域至高无上的荣誉。该奖项每年评选一次，在每年系统领域顶级会议SOSP和OSDI上颁发

    1、Leslie Lamport “Time, Clocks, and the Ordering of Events in a Distributed System”
    
    获奖理由：Perhaps the first true "distributed systems" paper, it introduced the concept of "causal ordering", which turned out to be useful in many settings. The paper proposed the mechanism it called "logical clocks", but everyone now calls these "Lamport clocks."
    此外，这篇论文获2000年Dijkstra Award。

    2007年入选名人堂。

    2、Leslie Lamport. The Part Time Parliament ACM TOCS 16(2), May 1998, 133--169.
      
    获奖理由：The work (originally published in 1989) was independent and roughly concurrent with the Viewstamped Replication work also recognized this year. It describes the protocol in a more general setting, add
    
    3、Brian M. Oki, Barbara H. Liskov. Viewstamped Replication: A New Primary Copy Method to Support Highly-Available Distributed Systems Proceedings of the Seventh Annual ACM Symposium on Principles of Distributed Computing (PODC 1988), Toronto, ON, Canada, Aug 1988, pp 8--17.
      
    获奖理由：The paper introduces a replication protocol very imilar to what is now known as Paxos. That protocol has become the standard for consistent, fault-tolerant state-machine replication, and is widely used in data centers to keep the state consistent despite failures and reconfiguration. 
    
    2012年入选名人堂。

名人堂奖：http://www.sigops.org/award-hof.html

## Dijkstra论文奖

    1、K. Mani Chandy,Leslie Lamport. Distributed Snapshots: Determining Global States of a Distributed System.1985.
    
    Lamport认为，这篇文章是对文献[1]中思想的直接应用。
    这篇文章获2014年Dijkstra Award。
    
    2、Fischer, M. J.; Lynch, N. A.; Paterson, M. S. (1985). "Impossibility of distributed consensus with one faulty process" (PDF). Journal of the ACM. 32 (2): 374–382.
    这篇论文获2001年Dijkstra Award。
    著名的FLP不可能原理出自这篇论文。
    
    3、Pease, M.; Shostak, R.; Lamport, L. (April 1980). "Reaching Agreement in the Presence of Faults". Journal of the ACM. 27 (2): 228–234.
    这篇论文获2005年Dijkstra Award。
    
    4、Dwork, C.; Lynch, N.; Stockmeyer, L. (1988). "Consensus in the presence of partial synchrony". Journal of the ACM. 35 (2): 288–323. 
    这篇论文获2007年Dijkstra Award。这篇文章是Tendermint的设计思想来源。

Dijkstra Award：https://en.wikipedia.org/wiki/Dijkstra_Prize
    
## 其他

    1、Castro M, Liskov B. Practical Byzantine fault tolerance[C]// Symposium on Operating Systems Design & Implementation. ACM, 1999:173-186.
    第一个实用的弱同步拜占庭解决方案。
    
    2、Sneider F. Implementing Fault Tolerant Service using the State Machine Approach: a Tutorial[J]. 1990.
    此论文和文献lamport的时间，时钟论文是研究复制状态机必读论文。
    
    3、Miller A, Xia Y, Croman K, et al. The Honey Badger of BFT Protocols[C]// ACM Sigsac Conference on Computer and Communications Security. ACM, 2016:31-42.
    这篇论文提出了首个完全异步共识算法。polkadot的共识算法会参考这篇论文。
    这篇论文的实验设计也值得借鉴。
    
    4、Liu S, Viotti P, Cachin C, et al. XFT: Practical Fault Tolerance Beyond Crashes[J]. Computer Science, 2016.
    
## 非拜占庭解决方案

paxos，raft及其变种。
    
## 分布式领域牛人
 Leslie Lamport,Butler Lampson,Barbara Liskov and Nancy Lynch等。
 
## 书籍

    1、《Distributed Algorithms》by Nancy Lynch
    2、《The science of blockchain》 by  Roger Wattenhofer 
    
## 学位论文

    1、《Tendermint: Byzantine Fault Tolerance in the Age of Blockchains,master》by Buchman Ethan,2016-06-23
    2、《Practical Byzantine Fault Tolerance，PhD》by Miguel Castro,January 31, 2001
    3、《Consensus: Bridging Theory and Practice，PhD》 by Diego Ongaro,2014