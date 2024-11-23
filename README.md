# Performance-Analysis-of-MANET-Routing-Protocols-using-NS3-Simulator

Comparison of MANET routing Protocols
1. AODV
2. DSDV
3. DSR
4. OLSR

using NS3 (Network Simulator 3)

1. Reactive Vs Proactive routing
2. PErformance comparison of MANET protocols
3. AODV Vs DSDV Vs OLSR Vs DSR Comparison

What Version: ns-3-dev using git clone
OS - Ubuntu 24.04.1

This file which was used for simulation in ns3:
/home/akhil-sai-kandula/workspace/ns-3-allinone/ns-3-dev/scratch/manet-routing-compare.cc

Step 1: Copy the above file in to ~ns-3.3-dev/scratch/ folder
Step 2: Understand this code.
Step 3: Run this code
Open the terminal, Go to ns-3-dev and run the following command 

./ns3 --run scratch/manet-routing-compare

enable the following header file

#include "ns3/flow-monitor-helper.h"

four files got generated
AODV.csv
AODV.mob
AODV.flomon
temp.data

Parameters:
Number of nodes: 300
No of sinks : 10
Mobility Model: 
Propagation Model: ConstantSpeedPropagationDelay
Propagation Loss Model: Friis
Position Allocator: RandomRectangularPositionAllocator
Mac: AdhocWifiMAC
Mac Standard: 802.11B
Bps: 2Kbps
Total Simulation Time: 200 seconds
Node speed: 20m/s
Node pause time: 0
Protocol: AODV, OLSR, DSR, DSDV


