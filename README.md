# Improvement-in-OSPF-using-EIGRP-Routing-Protocol
Our purpose is to perform the implementation of OSPF, 
and try to design a hybrid protocol between these OSPF and EIGRP, 
using the concepts and methodologies of these two protocols. 
This new routing protocol technology will help in increasing and improving
communication around the world. This will also give us a new routing protocol
which will have features of EIGRP and will work on large network which
is not possible with EIGRP.

ISSUE PROBLEM- problem which will be solved in OSPF are

•	OSPF sends hello packet every 10 seconds and dead=40 sec.
•	OSPF is a link state routing protocol which has fast convergence
but it does not use distance vector routing protocol which determine
the best route for data packet based on distance.
•it selects path on the bases of shortest distance which may sometime 
increase the cost.

METHOD

•	By reducing the time of sending hello package like reducing the time 
to 5 sec we can increase its efficiency.
•	By applying distance-vector routing protocol 
we can make OSPF a hybrid algorithm.
•it uses both distance and cost to find out best path
