# IETF-DMSC-side-meeting
Distributed Micro Services Communication(DMSC) Charter
Name: Distributed Micro Services Communication(DMSC)
Description
The DMSC(Distributed Micro Services Communication) BOF aims to build one service oriented, distributed infrastructure that can accommodate the communications requirements among various micro-services, which are currently relying on the centralized controlled Service Mesh to accomplish the tasks. It will focus on tailoring the various HTTP methods, QUIC/TCP based micro services to the content semantic based framework, to facilitate the development of one distributed, service oriented network that can carry micro services, CDN and various live broadcast services.

Information for IAB/IESG
Micro services are used widely within the current cloud based applications. To facilitate the communication of large amounts of these micro services, Cloud Service Providers build the Service Mesh infrastructure(for example: Istio, https://istio.io/)themselves to accomplish the task of authentication, authorization, load balancing, circuit breaker, service discovery and observability.

Such Service Mesh infrastructure has been widely used for a few years, but it encounters various challenges. The main challenge comes from its centralized control design philosophy and its tight integrated and co-located deployment with the micro services.

Then, in order to solve the challenges of the current Service Mesh infrastructure, the DMSC(Distributed Micro Services Communication) group will discuss how to build one distributed, shared infrastructure that can be utilized by various Cloud Service Providers, and also the Content Service Provider, to assist the communications of the wide deployed micro services.

Apart from this, recent research has shown that network devices undertaking some computing tasks can greatly improve the network and application performance in some scenarios, like for instance aggregating path-computing , key-value(K-V) cache, and in network securities etc. In the context of such heterogeneity of scenarios, it is desirable to have a generic and flexible framework, able to explicitly signaling the computing, service operation to be performed by network devices, which can be regarded as one kind of distributed services that are deployed within the network.

DMSC group will try to accomodate the distributed services around the network and within the network in one coherent architecture to accomplish the service discovery, service routing and service engineering functions to satify the emerged scenarios and requirements.

Any protocols or practices that already exist in this space:
Istio(https://istio.io/) is one open source implementation of such infrastructure, but is in centralized control mode, has amounts of challenges in its current deployment and future development.

Which (if any) modifications to existing protocols or practices are required:
Http/TCP/QUIC may be needed to adapt to the content semantic based layer

Which (if any) entirely new protocols or practices are required:
One new transport protocol may be needed to design if the existing one can't be tailored to meet the micro services communication requirements.

Open source projects (if any) implementing this work:
iStack: A General and Stateful Name-based Protocol Stack for Named Data Networking (https://www.usenix.org/conference/nsdi24/presentation/li-tianlong)

Links to the mailing list, draft charter if any, relevant Internet-Drafts, etc.
Mailing List: https://www.ietf.org/mailman/listinfo/dmsc
