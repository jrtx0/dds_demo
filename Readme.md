# INTRODUCTION
this project is a eProsima Fast DDS HelloWorld demo.eProsima Fast DDS is a C++ implementation of the DDS(Data Distribution Service) Specification, a protocol defined by the Object Management Group(OMG).The eProsima Fast DDS Library provides both an Application Programming Interface(API) and a communication protocol that deploy a Data-Centric Publisher-Subscriber(DCPS) model, with the purpose of establishing efficient and reliable information distribution among Real-Time Systems.

eProsima Fast DDS is predictable, scalable, flexible, and efficient in resource handling.For meeting these requirements, it makes use of typed interfaces and hinges on a many-to-many distributed network paradigm that neatly allows separation of the publisher and subscriber sides of the communication.eProsima Fast DDS comprises:
1. The DDS API implementation.
2. Fast DDS-Gen, a generation tool for bridging typed interface with the middleware implementation.
3. The underlying RTPS wire protocol implementation.

# eProsima FAST DDNS INSTALLATION
you can install Fast DDS from binaries, sources or docker.you can refer to [offical installation manual](https://fast-dds.docs.eprosima.com/en/latest/index.html)

# SIMPLE USAGE
1. enter **src/gen** folder and run command **fastddsgen HelloWorld.idl**
2. switch to **build** folder and run command **camke .. && make**, you will get subscribe and publisher application
3. run **DDSHelloWorldPublisher** and **DDSHelloWorldSubscriber** in two split termial, where you can see interaction log.