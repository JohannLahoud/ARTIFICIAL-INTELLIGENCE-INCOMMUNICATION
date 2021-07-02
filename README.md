# ARTIFICIAL INTELLIGENCE IN COMMUNICATION

## Contents
* 1\. [ARTIFICIAL INTELLIGENCE](#ARTIFICIAL-INTELLIGENCE)
    * 1.1\. [Introduction](#Introduction)
    * 1.2\. [Advantages of AI](#Advantages-of-AI)
    * 1.3\. [Ability to learn](#Ability-to-learn)
    * 1.4\. [Ability of collaboration](#Ability-of-collaboration)
       
* 2\.  [SDN/NFV](#SDN/NFV)
    * 2.1\. [SDN](#SDN) 
    * 2.2\. [SDN Architecture](#SDN-Architecture) 
    * 2.3\. [NFV](#NFV) 
    * 2.4\. [NFV Architecture](#NFV-Architecture) 
    * 2.5\. [NFV relationship to SDN](#NFV-relationship-to-SDN) 
* 3\. [ POSSIBILITY TO USE AI IN NETWORKING AND COMMUNICATION](#POSSIBILITY-TO-USE-AI-IN-NETWORKING-AND-COMMUNICATION)
    * 3.1\. [AI in SDN](#AI-in-SDN) 
      * 3.1.1\. [Neural Networks in SDN](#Neural-Networks-in-SDN) 
      * 3.1.2\. [CIPA](#CIPA) 
      * 3.1.3\. [Neural Network for Load Balancing](#Neural-Network-for-Load-Balancing) 
    * 3.2\. [AI in NFV](#AI-in-NFV) 
      * 3.2.1\. [IP traffic classification in NFV](#IP-traffic-classification-in-NFV) 
* 4\. [Conclusion](#Conclusion) 

## Abstract

Artificial intelligence (A.I.) is a wide-ranging branch of computer science whose goal is to automate activities that presently require human intelligence. Recent successes involve improvements in automatic text generation, facial and speech recognition, detecting motion gestures, drug discovery and quantum supremacy. 
AI-powered solutions are used by dozens of companies and implemented in different fields, changing a lot of industries and reshaping the landscape of health, learning, daily living. IT is a  revolutionary technology which the communication industry is exploring, in order to introduce it to the communication field, and to improve the user experience and networks efficiency by providing new services. The FINE framework is a contender in the steps to find a better solution for the network systems, which can be illustrated by the example of an SDN/NFV.

# 1.ARTIFICIAL INTELLIGENCE
Artificial intelligence (AI), the ability of a digital computer or Computer-controlled robot to perform tasks commonly associated with intelligent beings. Most AI projects that you hear about today from chess-playing computers to self-driving cars rely heavily on deep learning and natural language processing. Using AI technologies, computers can be trained to accomplish specific tasks by processing large amounts of data and recognizing patterns in the data.

## 1.1 Introduction

Artificial intelligence (AI) is becoming rapidly present in all aspects of everyday life. It affects everyone, and its capabilities are volving extremely fast. Artificial intelligence exists since 1956, but AI has become more popular today thanks to the big ideas coming in waves. In 2016, the win of the Go match by AlphaGo against Lee Sedol has attracted a lot of attention to AI. Communication is a sector playing a key role in any business or organization, and it deals with a variety of consumer demands specially in multimedia services. Due to AI, software-defined networks (SDN) and network functions virtualization (NFV) exist and the intellectualization of communication networks and services are becoming possible.

## 1.2 Advantages of AI

Artificial intelligence continues to make a huge difference in the communication industry. Similar to all the companies, Communication companies hope to take advantage of AI. We can see the appearance of the chatbots powered by AI that is used to automate communication. They are used in many ways to engage with customers, such as answering questions or providing shopping assistance and communicating with clients. Let us look at some of the advantages in the next few subsections.

## 1.3 Ability to learn

AI is already used in multiple disciplines and industries. These devices are capable of reading, writing, speaking and understanding. Unlike humans, AI has computational power that allows it to process copious amounts of data. As AI’s tasks continue to become more advanced, there’s also an increase in computational power necessary—which can become expensive. In order to avoid this need, AI was made to be a specific purpose learner. Operators need intelligent decisions to manage the dynamic traffic, deep learning can be used to solve this problem. As a conclusion AI can learn how to operate, manage and maintain networks.

## 1.4 Ability of collaboration

Due to the increasing number of users and to the expansion of the network in size, 
the structure complexity to build and maintain a network has increased too. To collaborate and manage the nodes, we find a new technology, a multi-agent collaboration, of distributed AI into the network management.

# 2 SDN/NFV

Software-defined networking (SDN) seeks to separate network control functions from network forwarding functions, while network functions virtualization (NFV) seeks to abstract network forwarding and other networking functions from the hardware on which it runs.

## 2.1 SDN

Software-defined networking (SDN) uses a logically centralized management to adopt the concept of programmable networks . It provides network operators with a logical centralized control and application programming interfaces to communicate with underlying hardware infrastructure.The SDN paradigm separates the control plane from the data plane, which results in achieving a faster approach in compared with a conventional network architecture. As seen, SDN is used to make a network more flexible and easier to manage.

## 2.2 SDN Architecture

The SDN architecture is designed based on the idea of the separation between control and dataplanes. An SDN framework is composed of three layers: infrastructure layer, control layer, and application layer. The infrastructure includes network elements. The control layer contains the SDN controller which is the core component of the SDN. It controls the network traffic. The application layer contains the D-CPI which is responsible for exchanging data between the SDN controller and the network elements. The A-CPI is responsible for providing the upper-level application with the channel exchange to send the data to the low-level network.

## 2.3 NFV

Network functions virtualization (NFV) uses virtualized networks to support an infrastructure.
With NFV, functions like load routing, balancing and firewalls are packaged as virtual machines on commodity hardware.
NFV replaces traditional, custom-designed network equipment (black boxes) that continues to dominate the installed base of networks.

## 2.4 NFV Architecture

The network function virtualization consists of three components. First, Management, automation and network orchestration (MANO) that provides the methods and frameworks to manage NFV infrastructures. Second, the Virtualised network functions (VNFS), software that provide the network functions. Third, the network functions virtualisation infrastructure(NFVi), an infrastructure component that compute the storage.

## 2.5 NFV relationship to SDN

NFV and SDN have similarities but they are not dependent on each other. It is possible to build a virtualized network function (VNF) as a standalone entity using existing networking. However, there are inherent benefits in leveraging SDN concepts to implement and manage an NFV infrastructure, particularly when looking at the management and orchestration of VNFs. An NFV infrastructure needs management system, automation and network orchestration  them into storage and network configuration needed to bring VFN to operate. these functionalities center that takes requests associated with VNF and transformare done by the SDN concepts.

# 3 POSSIBILITY TO USE AI IN NETWORKING AND COMMUNICATION

Enad Kojic suggested a neural network to optimize routing in communication networks. And a lot of engineers and researchers worked on this domain and presented multiple solutions for multiple problems using AI. But their work was focused on the theoretical analysis and this cannot be used in real communication networks. However, NFV/SDN, have been able to build a system which can be executed by network equipment, and it is possible to realize real-time monitoring of networks.

## 3.1 AI in SDN

AI and ML approaches have been widely used for solving various problems such as  traffic classification, routing, flow  clustering intrusion  detection, load  balancing, fault detection, quality of service and quality of experience optimization. However, concerning SDN the role of AI was enormously increased due to the big efforts made by the research community and the industry. The biggest advantage of SDN is that it provides an interface that introduces the AI to the network device, how? SDN uses an interface to send data as programming instructions to the network device. With AI, network managers can schedule an automated intelligent business orchestrator, also program the AI optimized network strategy and automatically compile them into the task script. Network managers can also collect data and network statistics to help for the optimization in the future.

### 3.1.1 Neural Networks in SDN

Instruction detection and prevention are the methods used by the neural networks to solve the load balancing, the routing, to optimize virtual machine (VM), as well as solving controller placement problem.

### 3.1.2 CIPA

Chen and Yu, suggested CIPA, a collaborative intrusion prevention architecture, consists of an intrusion prevention system based on NN. The results of the experiences showed that CIPA detects DDOS flooding attacks. CIPA performs wel in both simulated networks and real world SDN. Coordinated intrusion, like DDoS, Worm outbreak and Botnet, is a major threat to network security nowadays and will continue to be a threat in the future. In addition, CIPA does not require high communication and computation overhead.


### 3.1.3 Neural Network for Load Balancing
On the other hand, Chen-Xiao and Ya-Bin suggested another neural network approach for load  balancing.  the experiments showed that this approach can achieve a better performance. Hence, resulting in a 19.3 percent of decrease of the network latency.

## 3.2 AI in NFV
Network functions virtualization (NFV) is a way to virtualize network services, such as routers, firewalls, and load balancers, that have traditionally been run on proprietary hardware. These services are packaged as virtual machines on commodity hardware, which allows service providers to run their network on standard servers instead of proprietary ones. AI can play its role in critical network management.


### 3.2.1 IP traffic classification in NFV
 The  work  in "IP traffic classification in NFV: A bench marking of supervised Machine  Learning  algorithms,”,
 suggested a machine learning  algorithms  to  manage the  hidden  traffic  in  NFV-based  networks.  Hidden  traffic  invirtualized  networks  is  the  invisible  traffic  that  does  not  hit the physical layer. The authors benchmark the performance of different  supervised  learning  algorithms  for  the  classification of  IP  traffic  in  NFV-based  networks.  Based  on  the  results in the research,  the  authors  find  Naive  Bayes  (NB)  algorithms the best IP traffic classifier in NFV-based networks, with a maximum value of 99.9 percent accuracy.

 What is the Naive Bayes algorithm?

 Naive Bayes is a machine learning model that is used for large volumes of data. 

 What is the Naive Bayes Classifier?

 It is a classification technique based on Bayes’ theorem with an assumption of independence between predictors. 
 The algorithm first creates a frequency table (similar to prior probability) of all classes and then creates a likelihood table. Then, finally, it calculates the posterior probability.

# 4. Conclusion
In  this article,  we  provided  a  state of the art  overview  of  research  efforts  made  for  applying  artificial  intelligence  techniques in SDN paradigm, as well as an  adoption  of  various  artificial intelligence  techniques to solve a wide range of networking problems and address new challenges introduced by the SDN paradigm. Artificial intelligence plays an important role in the network industry, we have seen how artificial intelligence can be included in NFV and SDN for a better future of communication. However, more efforts towards studying the AI approaches under adversarial settings need to be take into consideration for a better communication.
