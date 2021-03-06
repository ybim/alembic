---
title: ""
feature_text: ""
feature_image: "https://unsplash.it/1300/400?image=885&gravity=north"
excerpt: ""
aside: true
---
### Research Areas
* TCP latency measurement and solution
* Mobile data offloading
* Next-generation Internet
* Adaptive video streaming
* Data center resource disaggregation

### TCP latency measurement and solution
![tcp_latency](assets/tcp_latency.png)<br />
Emerging applications like VR, AR, and 360-degree video aim to exploit the unprecedentedly low latencies. In order to fulfill them, it is crucial to understand where packet delays happen. In this work, we empirically find that sender-side protocol stack delays can cause high end-to-end latencies. Unfortunately, however, current latency diagnosis tools cannot even distinguish between delays on network links and delays in the end hosts. We present ELEMENT, a latency diagnosis framework that decomposes end-to-end TCP latency into endhost and network delays, without requiring admin privileges. We validate that ELEMENT achieves more than 90% accuracy. To demonstrate ELEMENT’s potential impact on real-world applications, we implement a relatively simple user-level library that uses ELEMENT to minimize delays. For evaluation, we integrate ELEMENT with legacy TCP applications and show that it can reduce latency by up to 10 times while maintaining throughput and fairness. We finally demonstrate that ELEMENT can significantly reduce the latency of a virtual reality application.

### Mobile data offloading
![amuse](assets/amuse.png)<br />
* Wireless Internet service providers (ISPs) are increasingly changing their pricing plans and deploying Wi-Fi hotspots to offload their mobile traffic. However, these ISP-centric approaches for traffic management do not always match the interests of mobile users. Users face a complex, multi-dimensional tradeoff between cost, throughput, and delay in making their offloading decisions. To navigate this tradeoff, we develop Adaptive bandwidth Management through USer-Empowerment (AMUSE), a functional prototype of a practical, cost-aware Wi-Fi offloading system that takes into account a user's throughput-delay tradeoffs and cellular budget constraint. 

### Adaptive video streaming
![flare](assets/flare.png)<br />
* Existing HAS (HTTP adaptive streaming) techniques often suffer from problems like unstable video quality and suboptimal resource utilization. However, our fog computing approach can exploit existing telecommunication APIs, which expose network capabilities to applications, in order to coordinate between clients and the network. Our coordinated HAS solution, FLARE, optimizes the total utility of all clients in a cell while maintaining stable video quality and supporting user- and device-specific needs. We implement FLARE on a commodity LTE femtocell and use the implementation to conduct the first comparison of HAS players on an LTE femtocell.<br />
![experimental_evaluation](assets/comnet.png)<br />
* The HTTP-based Adaptive Streaming (HAS) techniques are widely used in Internet video streaming services including YouTube and Netflix. In this research, we investigate the detailed operations of the different players by code level analysis and through reverse engineering. Specifically, we present the pseudo codes of 3 open source players, and devise a method to obtain the detailed operation information of popular streaming players. We conduct extensive experiments on our testbed, and provide suggestions based on the behaviors of these players.

### Data center resource disaggregation
![fluidmem](assets/fluidmem.png)<br />
Disaggregating resources in data centers is an emerging trend. Recent work has begun to explore memory disaggregation, but suffers limitations including lack of consideration of the complexity of cloud-based deployment, including heterogeneous hardware and APIs for cloud users and operators. In this research, we develop FluidMem, a complete system to realize disaggregated memory in the datacenter. Going beyond simply demonstrating remote memory is possible, we create an entire Memory as a Service. We define the requirements of Memory as a Service and build its implementation in Linux as FluidMem. 
