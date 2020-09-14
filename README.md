This repository has been created for experimenting the EE-Hello scheme proposed in 
"Adaptive Hello Interval in FANET Routing Protocols for Green UAVs".
Article link: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8715766

The EE-Hello scheme has been implemented on the AODV and OLSR routing protocols.
You can find the algorithm in the following files:
/src/aodv/model/aodv-routing-protocol.cc
/src/aodv/model/aodv-routing-protocol.h
/src/olsr/model/olsr-routing-protocol.cc
/src/olsr/model/olsr-routing-protocol.h

Step 1: Clone this repo:
git clone https://github.com/imtiaztee/EE-Hello-Adaptive-Hello-Interval-for-FANETs

Step 2: Configure and build the cloned repo:
./waf configure
./waf

Step 3: Put your scenario in the scratch and run, 
        You can test the EE-Hello scheme by implementing AODV or OLSR routing protocols into your scenario.

********************************************************

Thanks and regards. <br />
Dr. Imtiaz Mahmud.

********************************************************
For any inquiry, please contact at imtiaz.tee@gmail.com.
