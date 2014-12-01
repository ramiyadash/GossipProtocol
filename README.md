GossipProtocol
==============
1.WHAT IS WORKING :::
  The Various topologies implemented are as follows:
•	Line :  The push-sum algorithm implemented for this topology is found out to be non convergent resulting in endless sequence.
             The Gossip algorithm implemented for this topology results in convergent time and convergence percentage of 95.11% and ultimately kills the master.
•	Full: The push-sum algorithm implemented for this topology is found out to be a convergent series and the graph was drawn for different inputs and the corresponding time consumed.
          The Gossip algorithm executed for the topology is found out to be convergent with 95.11%.
•	2D: The push-sum algorithm utilized for 2D topology results in non-convergent series.
       The Gossip algorithm for this topology results in convergent series with 95.11%.
•	Imperfect2D:The push-sum algorithm for this topology is a convergent series and corresponding graph was done for convergence time as function of size of network.
        The Gossip algorithm for this topology results in convergent series with 95.11%.

  
Sample outputs:
•	Line with push-sum Algorithm:
Actor[akka://Network/user/Node182#1897739797]183.19848110988113
Actor[akka://Network/user/Node183#-1453933073]183.2235927007781
Actor[akka://Network/user/Node182#1897739797]183.21103690532962
Actor[akka://Network/user/Node181#605730630]182.95958412311177
Actor[akka://Network/user/Node182#1897739797]183.08531051422068
Actor[akka://Network/user/Node183#-1453933073]183.1544516074994
Actor[akka://Network/user/Node182#1897739797]183.11988106086005
Actor[akka://Network/user/Node183#-1453933073]183.1371663341797
Actor[akka://Network/user/Node184#156885311]183.48716193888453
……contd. non convergence series
•	Line with Gossip Algorithm:
------line   topology is ready   ------------
….
…
…
Network Coverage : 93.33333333333333
Time taken: 667ms
Network Coverage : 94.44444444444444
Time taken: 667ms
Network Coverage : 94.44444444444444
Time taken: 667ms
Network Coverage : 94.44444444444444
Time taken: 667ms
Network Coverage : 94.44444444444444
Time taken: 668ms
Network Coverage : 94.44444444444444
Time taken: 668ms
Network Coverage : 95.55555555555556
Shutting Down
•	Full with push-sum:

------full topology is ready   ------------

Actor[akka://Network/user/Node10#1996117549]450.65482797165885
Actor[akka://Network/user/Node584#295429019]450.65482796976005
Actor[akka://Network/user/Node264#-1434500109]450.654827969297
Actor[akka://Network/user/Node656#1079447812]450.6548279693043
Actor[akka://Network/user/Node472#-1214756290]450.6548279689032
Actor[akka://Network/user/Node508#-1947048663]450.6548279702789
Actor[akka://Network/user/Node578#1112271750]450.654827968963
Actor[akka://Network/user/Node820#-1857373650]450.6548279689807
d820,450.6548279689807
Time taken: 4854ms
Final Ratio: 450.6548279689807

