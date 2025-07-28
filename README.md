# IETF-DMSC-side-meeting
Relevant Internet-Drafts: <br>  
Use Cases: <br> 
https://datatracker.ietf.org/doc/draft-song-dmsc-promblem-and-requirements/  <br> 
https://datatracker.ietf.org/doc/draft-lou-rtgwg-sinc/  <br> 
https://datatracker.ietf.org/doc/html/draft-yang-dmsc-distributed-model/  <br> 
https://datatracker.ietf.org/doc/html/draft-si-service-mesh-dta/  <br> 
Solutions: <br>
https://datatracker.ietf.org/doc/draft-li-dmsc-architecture/  <br> 
https://datatracker.ietf.org/doc/draft-song-dmsc-scalable-name-forwarding/  <br> 
https://datatracker.ietf.org/doc/draft-lin-dmsc-content-based-service-router/  <br> 
https://datatracker.ietf.org/doc/draft-yuan-dmsc-technical-considerations  <br> 

Charter:<br>  
Name: Distributed Micro Services Communication(DMSC) <br> 
Description: <br>  
The DMSC(Distributed Micro Services Communication) BOF aims to build one service oriented, distributed infrastructure that can accommodate the communications requirements among various micro-services, which are currently relying on the centralized controlled Service Mesh to accomplish the tasks. It will focus on tailoring the various HTTP methods, QUIC/TCP based micro services to the content semantic based framework, to facilitate the development of one distributed, service oriented network that can carry micro services, CDN and various live broadcast services. <br> 

Information for IAB/IESG: <br>  
Micro services are used widely within the current cloud based applications. To facilitate the communication of large amounts of these micro services, Cloud Service Providers build the Service Mesh infrastructure(for example: Istio, https://istio.io/)themselves to accomplish the task of authentication, authorization, load balancing, circuit breaker, service discovery and observability. Such Service Mesh infrastructure has been widely used for a few years, but it encounters various challenges. The main challenge comes from its centralized control design philosophy and its tight integrated and co-located deployment with the micro services. <br> 

Then, in order to solve the challenges of the current Service Mesh infrastructure, the DMSC(Distributed Micro Services Communication) group will discuss how to build one distributed, shared infrastructure that can be utilized by various Cloud Service Providers, and also the Content Service Provider, to assist the communications of the wide deployed micro services. <br> 

Apart from this, recent research has shown that network devices undertaking some computing tasks can greatly improve the network and application performance in some scenarios, like for instance aggregating path-computing , key-value(K-V) cache, and in network securities etc. In the context of such heterogeneity of scenarios, it is desirable to have a generic and flexible framework, able to explicitly signaling the computing, service operation to be performed by network devices, which can be regarded as one kind of distributed services that are deployed within the network. <br> 

DMSC group will try to accomodate the distributed services around the network and within the network in one coherent architecture to accomplish the service discovery, service routing and service engineering functions to satify the emerged scenarios and requirements. <br> 

Links to the mailing list, draft charter if any, relevant Internet-Drafts, etc. <br> 
Mailing List: https://www.ietf.org/mailman/listinfo/dmsc <br> 
