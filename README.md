# IIT-KGP-Data-science-RedBus-Data
this repository is for maintaining the on going competition on RedBus data
https://www.youtube.com/watch?v=7isnF5XmDN4

---
The idea to approach this problem is by clustering the batches of every train ---  and identify every Seat type , particular date and time as positional feature as if the bus was going on that moment or was data recorded at that point of time or not.
the way to solve this problem is not a supervised one as it seems we have to look for unsupervised ways of approaching the problem set. for examle - K-Means Clustering and then at last we have to return the following probability of every bus for every bus in a ranked manner. 
for example - 
in row 1 ==>  BUS 1   -> probability (of following BUS 2) = 97% ->  probability (of following BUS 3) = 92%  -> probability (of following BUS 6) = 87% ... and so on ...and  at last we return 97% and BUS 2 for row1 ==> BUS1
