Download link :https://programming.engineering/product/problem-set-1-solution-networking-fundamentals-performance-analysis/

# Problem-Set-1-Solution-Networking-Fundamentals-Performance-Analysis
Problem Set 1 Solution: Networking Fundamentals &amp; Performance Analysis
Assume that 1 Kbps = 103 bits/sec, 1 Mbps = 106 bits/sec, 1 Gbps = 109 bits/sec, and 1MB = 106 x 8 bits. The capital ‘B’ typically means ‘byte’ while the lowercase ‘b’ indicates ‘bit’.


(3pts) What advantage does a circuit-switched network have over a packet-switched network?
 

(3pts) What advantage does TDM have over FDM in a circuit switched network?
 

(21pts) Consider two hosts, A and B, which are connected by a link (R bps). Suppose that the two hosts are separated by m meters, and the speed along with link is s meters/sec. Host A is to send a packet of size L bits to Host B.
 

Express the propagation delay, dprop, in terms of m and s.
Determine the transmission time of the packet, dtrans, in terms of L and R.
Ignoring processing and queuing delays, obtain an expression for the end-to-end delay (one-way delay from Host A to Host B).
Suppose Host A begins to transmit the packet at time t = 0, At time t = dtrans, where is the last bit of the packet?
Suppose dprop is greater than dtrans . At time t = dtrans, where is the first bit of the packet?
Suppose dprop is less than dtrans . At time t = dtrans, where is the first bit of the packet?
Suppose s = 2.5 * 108, L = 120bits, and R = 56Kbps. Find the distance m so that dprop equals dtrans.
 

(8pts) We consider sending real-time voice from Host A to Host B over a packet-switched network. Host A converts analog voice to a digital 65kbps bit stream and send these bits into 56-byte packets. There is one link between Hosts A and B and the transmission rate is 1 Mbps and its propagation delay is 20 msec. As soon as Host A gathers a packet, it sends it to Host B. As soon as Host B receives an entire packet, it converts the packet’s bits into an analog signal. How much time elapses from the time a bit is created (from the original analog signal at Host A) until the bit is decoded (as part of the analog signal at Host B)?
 

(12pts) Consider a Go-Back-N sliding window algorithm (1 packet is 250 bytes long) running over a 100km point-to-point fiber link with bandwidth of 100 Mbps.
 

Compute the one-way propagation delay for this link, assuming that the speed of light is 2 x 108 m/s in the fiber.
Suggest a suitable timeout value for the algorithm to use. List factors you need to consider.
Suggest N to achieve 100% utilization in this link.
 

(12pts) Suppose a 1-Gbps point-to-point link is being set up between the Earth and a new lunar colony. The distance from the moon to the Earth is approximately 385,000 km, and data travels over the link at the speed of light—3×108 m/s.
Calculate the minimum RTT for the link.
 

Using the RTT as the delay, calculate the delay × bandwidth product for the link.
 

What is the significance of the delay × bandwidth product computed in (b) ?

(12pts) Host A wants to send a 1,000 KB file to Host B. The Round Trip Time (RTT) of the Duplex Link between Host A and B is 160ms. Packet size is 1KB. A handshake between A and B is needed before data packets can start transferring which takes 2xRTT. Calculate the total required time of file transfer in the following cases. The transfer is considered complete when the acknowledgement for the final packet reaches A.
The bandwidth of the link is 4Mbps. Data packets can be continuously transferred on the link.
 

The bandwidth of the link is 4Mbps. After sending each packet, A need to wait one RTT before the next packet can be transferred.
 

Assume we have “unlimited” bandwidth on the link, meaning that we assume transmit time to be zero. After sending 50 packets, A need to wait one RTT before sending next group of 50 packets.
 

The bandwidth of the link is 4Mbps. During the first transmission A can send one (21-1) packets, during the 2nd transmission A can send 22-1 packets, during the 3rd transmission A can send 23-1 packets, and so on. Assume A still need to wait for 1 RTT between each transmission.
 

(5pts) Determine the width of a bit on a 10 Gbps link. Assume a copper wire, where the speed of propagation is 2.3 ∗ 108 m/s.
 

(12 pts) Suppose two hosts, A and B, are separated by 20,000 kilometers and they are connected by a direct link of R=1Gbps. Suppose the propagation speed over the link is 2.5 x 108 meters/sec.
 

Calculate the bandwidth delay product (BDP) of the link.
Consider sending a file of 800,000 bits from Host A to Host B as one large message. What is the maximum number of bits that will be in the link at any given time?
What is the width (in meters) of a bit in the link?
Suppose now the file is broken up into 20 packets with each packet containing 40,000 bits. Suppose that each packet is acknowledged by the receiver and the transmission time of an acknowledgement packet is negligible. Finally, assume that the sender cannot send a packet until the preceding one is acknowledged. How long does it take to send the file?
 

(12 pts) Suppose there is a 10 Mbps microwave link between a geostationary satellite and its base station on Earth. Every minute the satellite takes a digital photo and sends it to the base station. Assume a propagation speed of 2.4 x 108 meters/sec. Geostationary satellite is 36,000 kilometers away from earth surface
What is the propagation delay of the link?
What is the bandwidth-delay product, R x (propagation delay)?
Let x denote the size of the photo. What is the minimum value of x for the microwave link to be continuously transmitting?
 
