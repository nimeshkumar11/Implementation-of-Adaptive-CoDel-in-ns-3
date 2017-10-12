#  Implementation of Adaptive CoDel in ns-3
## Course Code: CS704
## Overview
Controlled Delay (CoDel)[1] has been proposed as an active queue management (AQM) algorithm to address this problem by setting a limit (i.e., a target delay) on the queueing delay. However, such a target delay is fixed [2], and CoDel is thus unable to adapt to changes in the network environment. In this paper, we propose a framework to adaptively control the target delay [3] with changing network conditions, so as to overcome bufferbloat.This repository provides an implementation of ERED algorithm in ns-3 [4].

## Refrences
[1] J. Gettys and K. Nichols, “Bufferbloat: Dark buffers in the Internet,” Communications of the ACM, Vol. 55, No. 1, pp. 57-65, January 2012. 

[2] S. Floyd and V. Jacobson, “Random early detection gateways for congestion avoidance,” IEEE/ACM Trans. Networking, Vol. 1,  pp. 397-413, August 1993.

[3] http://ieeexplore.ieee.org/document/7833560/

[4] http://www.nsnam.org/
