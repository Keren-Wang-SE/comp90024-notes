# COMP90024-CCC

## Week1 - How we got here
- 1. What is cloud computing? 
    - In 2013, Cloud computing is a jargon term without a commonly accepted non-ambiguous scientific or technical definition. (Anything that is not on your computer, e.g.: gmail)
    - Cloud computing is a jargon term without a commonly accepted nonambiguous scientific or technical definition. **In science, cloudcomputing is a synonym for distributed computing over a network and means the ability to run a program on many connected computers at the same time.**
    - In 2016, Proponents claim that cloud computing allows companies to avoid upfront infrastructure costs, and focus on projects that differentiate their businesses instead of on infrastructure. Proponents also claim that cloud computing allows enterprises to get their applications up and running faster, with improved manageability and less maintenance, and enables IT to more rapidly adjust resources to meet fluctuating and unpredictable business demand. Cloud providers typically use a "pay as you go" model. This can lead to unexpectedly high charges if administrators do not adapt to the cloud pricing model. (Everyone has different flavor)
    - 在2013年，云计算是一个行话术语，没有一个被广泛接受的、明确的科学或技术定义。（泛指所有不在你电脑上的东西，例如：Gmail）
    -   云计算是一个行话术语，没有一个被广泛接受的、明确的科学或技术定义。在科学领域，云计算是“分布式计算”的同义词，指的是能够在许多连接的计算机上同时运行一个程序的能力。
    - 到了2016年，支持者声称，云计算可以让公司避免前期的基础设施投入成本，将精力集中在使其业务差异化的项目上，而不是基础设施本身。支持者还声称，云计算能让企业更快地上线应用程序，提升可管理性，减少维护工作，使信息技术部门能更快速地调整资源，以应对不断变化和不可预测的业务需求。云服务提供商通常采用“按需付费”模式。如果管理员没有根据云的定价模型进行调整，这可能会导致意外的高额费用。（每个人对云计算的理解都有所不同）
  


- 2. Cloud Characteristics (Lecture notes and then my paraphrasing)
    - On-demand self-service
        - A consumer can provision computing capabilities as needed without requiring human interaction with each service provider. 
        - Scale computing resources up and down by needs without requiring human interaction with each service provider.
        - For anyone in any time - infinite availability (key)
    - Networked access
        - Capabilities are available over the network and access through standard mechanisms that promote use by heterogeneous client platforms.
        - Resources can be access through network and adapted to heterogeneous client platforms.
    - Resource pooling
        - The provider's computing resources are pooled to serve multiple consumers using a   multi-tenant model potentially with different physical and virtual resources that can be  dynamically assigned and reassigned according to consumer demand. 
        - Provider’s resources are pooled and can be dynamically assigned and reassigned by need.     
        - Enough resource to scale up & down
    - Rapid Elasticity
        - Capabilities can be elastically provisioned and released, in some cases automatically, to scale rapidly upon  demand.
        - Capabilities can scale easily and rapidly upon demand.
    - Measured Service
        - Cloud systems automatically control and optimize resource use by leveraging a metering  capability at some level of abstraction appropriate to the type of service.
        - Resourcing optimization by measuring usage
        - monitor for load balance (e.g.: nigix)
    云计算的特征（讲义内容及个人释义）：
    - **按需自助服务（On-demand self-service）**
        - 用户可以根据需要自行配置计算能力，无需与每个服务提供商人工交互。
        - 可以根据需求随时扩大或缩小计算资源规模，无需人工干预。
        - 任何人在任何时间都可以访问——无限可用性（关键点）。
    - **网络访问（Networked access）**
        - 各种能力可通过网络访问，并通过标准机制，使得不同类型的平台都能使用这些资源。
        - 资源可通过网络访问，并适配不同类型的客户端平台。
    - **资源池化（Resource pooling）**
        - 服务提供者将计算资源集中在一个资源池中，以多租户模型服务于多个用户，这些资源可能是物理的，也可能是虚拟的，并能根据用户需求动态分配与重新分配。
        - 提供者的资源被池化，可根据需求动态分配与重新分配。
        - 资源充足，可随时扩大或缩减规模。
    - **快速弹性（Rapid Elasticity）**
        - 各种能力可弹性地进行配置和释放，在某些情况下甚至可以自动执行，以便在有需求时快速扩展。
        - 各项服务能力可以根据需求快速、轻松地进行扩展。
    - **可计量服务（Measured Service**）**
        - 云系统通过在适当抽象层面上的计量功能，自动控制和优化资源使用。
        - 通过衡量使用量来优化资源分配，例如使用 Nginx 等工具监控负载平衡。



- 3. Flavour
    - Compute clouds
      - Amazon Elastic compute cloud
      - Azure
    - Data Clouds
      - Amazon Simple Storage Service
      - Google docs
      - iCloud
      - Dropbox
    - Application Clouds
      - App store
      - Virtual image factories
    - Public(credit card and pay for using) /Private(Unimelb research cloud)/Hybrid(MRC run out of resource nad buy from Amazon)/Mobile/Health Clouds
    - complexity arise in: decision about what can we move out/what cost ot stay in/who is  allowed this to happen
- 3. 云计算的类型（Flavour）
  - 计算型云（Compute Clouds）
    - Amazon 弹性计算云（Amazon Elastic Compute Cloud）
    - Azure（微软云）
  - 数据型云（Data Clouds）
    - Amazon 简单存储服务（Amazon Simple Storage Service）
    - Google 文档（Google Docs）
    - iCloud（苹果云服务）
    - Dropbox（云文件存储服务）
  - 应用型云（Application Clouds）
    - App Store（应用商店）
    - 虚拟镜像工厂（Virtual Image Factories）
  - 云部署模式
    - 公有云（Public）：刷信用卡按使用量付费的云服务
    - 私有云（Private）：如墨尔本大学的研究云（Unimelb Research Cloud）
    - 混合云（Hybrid）：例如 MRC 资源耗尽时，从 Amazon 购买补充资源
    - 移动云（Mobile Cloud）
    - 健康云（Health Cloud）
  - 复杂性来源于：
    - 决策——我们能将哪些服务迁移到云上？
    - 成本——保留在本地的成本是多少？
    - 权限——谁被允许让这些事情发生？



1. History - tends in computing
    1. Computing and Communication Technologies (r)evolution
        - from **centralised to decentralised**
    2. distributed system history
        - Once upon a time we had standards
        - Then we had more standards
        - mid-90s: focused on computer-computer interaction
        - internet: peer-to-peer
            - challenge: sharing data between different organizations
            - soln: grid computing
            - Grid: only need access to it no matter it is data or super computer the process to move things
                - problem: people have different ways to do it
    - Distributed System
        - <u>**Transparency**</u> and **<u>heterogeneity</u>** in computer-computer interactions
        - Finding resources -> Binding resources -> run time type checking -> invoking resources
        - Dealing with heterogeneous of system
        - Challenges
            - Complexity of implementations
            - Vendor specific solutions
            - Scalability problem
            - Sharing data between different organizations  
    - Grid Computing
        - From computer-computer focus to **organisation-organisation** focus
        - Can be thought of as a **distributed system with non-interactive workloads**.
        - It is in contrast to the traditional notion of a supercomputer, which has many processors connected by a **local high-speed computer bus** instead of **Ethernet**.
        - Grid computing is distinguished from **conventional high-performance computing systems** such as cluster computing in that grid computers have **each node set to perform a different task/application**. Grid computers also tend to be **more heterogeneous and geographically dispersed** (thus not physically coupled) than cluster computers.
        - Although a single grid can be dedicated to a particular application, commonly a grid is used for a variety of purposes. Grids are often constructed with general-purpose grid middleware software libraries. Grid sizes can be quite large.
        - Challenge
            - What resources are available
            - To determine the status of resources
            - Job scheduling
            - Virtual organization support
            - Security
                - Public key infrastructure
- 4. 历史演变 —— 计算趋势（History - Trends in Computing）

- 1. 计算与通信技术的演进（Computing and Communication Technologies (r)evolution）
  - 从集中式计算转向去中心化分布式计算

- 2. 分布式系统的发展历史（Distributed System History）
  - 很久以前，我们有统一的标准  
  - 然后，标准越来越多  
  - 90年代中期：重点是计算机之间的交互  
  - 互联网时代：点对点（peer-to-peer）通信  
    - 挑战：不同组织之间的数据共享  
    - 解决方案：网格计算（Grid Computing）  
    - 网格：无论是访问数据还是超级计算，只需能访问即可，重在处理资源迁移  
      - 问题：不同的人使用不同的方法来实现

- 3. 分布式系统的特征与挑战（Distributed System）
  - **透明性（Transparency）** 和 **异构性（Heterogeneity）** 是计算机之间交互的关键  
  - 资源发现 -> 资源绑定 -> 运行时类型检查 -> 资源调用  
  - 应对系统异构性的挑战包括：  
    - 实现的复杂性  
    - 厂商特有的解决方案  
    - 可扩展性问题  
    - 不同组织间的数据共享  

- 4. 网格计算（Grid Computing）
  - 从“计算机对计算机”的焦点转向“组织对组织”的焦点  
  - 可以视为一种处理非交互式工作负载的分布式系统  
  - 与传统超级计算不同，超级计算机通过高速总线连接多个处理器，而网格计算通过以太网连接各节点  
  - 网格计算与传统高性能计算（如集群计算）的区别在于：  
    - 每个节点通常执行不同的任务或应用  
    - 更加异构且地理位置分散（物理上不耦合）  
  - 单一网格可以专用于某个应用，但通常用于多种用途  
  - 通常使用通用网格中间件构建，网格规模可以非常大  
  - 网格计算的挑战包括：  
    - 资源可用性的确认  
    - 判断资源当前状态  
    - 作业调度  
    - 虚拟组织支持  
    - 安全性保障（如公钥基础设施）



- 5. Comparison between Grid/Cluster/Cloud Computing
    ```
    Clusters "tend" to be tightly coupled, e.g. a bunch of servers in a rack with high speed interconnects - we'll go into some details of this in week 3;  
    Grid is/was more loosely coupled resources that provided single sign-on access to distributed resources that are often hosted by different organisations;  
    Cloud = we'll get to that soon! ;o)
    ```
    - Grid computing
        - Refer to the top
    - Cluster Computing
        - **Clusters tend to be tightly coupled**, e.g. a bunch of servers in a rack with high speed interconnects
        - Example
            - Super computer
    - Cloud Computing
        - Refer to week 5
        - Cloud computing is a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources(networks, servers, storage, applications, services) that can be rapidly provisioned and released with minimal management effort or service provider interaction.
- 5. 网格 / 集群 / 云计算对比（Comparison between Grid/Cluster/Cloud Computing）
  - 集群“往往”是紧密耦合的，例如，机架中的一组服务器通过高速互连连接——我们将在第 3 周详细探讨这一点；
  - 网格是/曾是较为松散耦合的资源，它为分布式资源提供单点登录访问，这些资源通常由不同的组织托管；
  - 云 = 我们很快就会讲到！

- 网格计算（Grid Computing）
  - 详见上方内容

- 集群计算（Cluster Computing）
  - 集群系统通常是紧耦合的，例如：一排机架中放置多台服务器，并通过高速互连进行连接  
  - 示例：超级计算机

- 云计算（Cloud Computing）
  - 详见第5周内容  
  - 云计算是一种模型，用于实现对可配置计算资源（网络、服务器、存储、应用和服务）共享池的无处不在、方便、按需的网络访问。  
  - 这些资源可以迅速配置和释放，且对管理者或服务提供者的交互需求最小化。



### past exam
- > [2013 Q1] A) Explain what is meant by the terms:
    - > Grid Computing [1]
        - focus on organizational collaboration, coordination, activity and technologies to doing it
    - > Cluster Computing [1]
        - multiple servers rach-mounted which are accessible and you can run jobs across the cluster
    - > Cloud Computing [1]
        - is a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources(networks, servers, storage, applications, services) that can be rapidly provisioned and released with minimal management effort or service provider interaction.

- > [2013 Q1, 2017 Q1 B [5]] B) Current Cloud Computing systems do not solve many key challenges of large-scale distributed systems. Discuss. [7]
    - by below

- > [sample Q2 A] Describe some of the current challenges associated with large-scale distributed systems. [4] 
    - distributed systems didn't solve data heterogeneity. And we have big data challenges.
    - distributed systems has scalability and issues of fixed hardware system. We have distributed computers running on different hardware system.
    - fault tolerance not solved
        - Many diverse faults can happen with distributed systems
            - , e.g. server failures or partial failures, network outages, overloading of components etc etc. 
            - There is no simple solution to this that has been widely adopted/accepted.
    - results in software stack
        - Each system tends to develop its own technical solution
            - , e.g. using queuing or having back-ups/failovers of system for failures. 
            - This can result in complex software stacks and recipes that have to be cooked to address  specific needs/demands.
    - (And all these erroneous assumption can't be made at week 2 last)
    - The network is reliable
    - Latency is zero
    - Bandwidth is infinite - I can send any amount of data I wish between any nodes
    - The network is secure
    - Topology doesn't change - Node x is always there
    - There is one administrator
    - Transport cost is zero - I can send as much data as I like for free
    - The network is homogeneous
    - Time is ubiquitous - Clock is same across all computers in network

- > [sample Q2 B] Cloud computing solves some of these issues but not all. Explain. [4]
    - scalability and elastic scaling (purchase cloud when you need its service)
    - software deployment easier as we have snapshots/scripted deployment
    - more tools available, e.g.: load balancers, proven solutions. You might not have this much in distributed system
    - data centers better networked. they are targeted to solve your problems
    - geospatially distributed and easy to migrate application
    - doesn't address many of the above though (但并没有解决上面的很多问题) (**bandwidth from user/organization to data center**)

- > [2015 Q1] A) Describe some of the erroneous assumptions that are often made in designing large-scale distributed systems. [5]
    - above

- > [2014 Q1] A) Discuss the major trends in research and research computing over the last 20 years that have led to the emergence of Cloud computing. [6]
    - Mainframes
        - main frames to move to the distributed system
    - decentralised PCs
    - explosion of the Internet
    - distributed system move back to the centralised system
    - scale of compute/storage
    - clouds and data centres

- > [2013 Q1] A) 解释以下术语的含义：
    - > 网格计算（Grid Computing） [1]  
        - 关注组织间的协作、协调、活动以及实现这些目标的技术  
    - > 集群计算（Cluster Computing） [1]  
        - 多个机架安装的服务器，可以被访问并在整个集群上运行任务  
    - > 云计算（Cloud Computing） [1]  
        - 一种模型，用于实现对可配置计算资源（网络、服务器、存储、应用、服务）共享池的无处不在、方便、按需的网络访问，这些资源可以快速配置和释放，且管理或服务提供者交互需求最小  

- > [2013 Q1, 2017 Q1 B [5]] B) 当前的云计算系统并没有解决大规模分布式系统的许多关键挑战。请讨论。 [7]  
    - 见下方内容  

- > [sample Q2 A] 描述与大规模分布式系统相关的一些当前挑战。 [4]  
    - 分布式系统没有解决数据异构性问题。同时我们面临大数据带来的挑战。  
    - 分布式系统存在可扩展性问题，以及固定硬件系统的限制。分布式计算通常运行在不同硬件环境中。  
    - 故障容错问题尚未解决  
        - 在分布式系统中可能发生多种故障  
            - 例如：服务器故障或部分故障、网络中断、组件过载等  
            - 目前尚无一种被广泛采用或接受的简单解决方案  
    - 导致复杂的软件堆栈  
        - 每个系统往往发展出自己的技术解决方案  
            - 例如：使用队列、备份/故障转移机制来处理故障  
            - 结果可能是必须针对具体需求“烹饪”出复杂的软件栈  
    - （而所有这些错误假设都不应在第二周课程中出现）  
        - 网络是可靠的  
        - 网络延迟为零  
        - 带宽是无限的——我可以在任意节点之间发送任意数量的数据  
        - 网络是安全的  
        - 拓扑结构不会变化——节点 x 总是存在  
        - 系统只有一个管理员  
        - 传输成本为零——我可以免费发送任意多的数据  
        - 网络是同质的  
        - 时间是同步的——网络中所有计算机的时钟一致  

- > [sample Q2 B] 云计算解决了其中的一些问题，但不是全部。请解释。 [4]  
    - 提供可扩展性和弹性扩展（按需购买云服务）  
    - 软件部署更容易，因为我们有快照和脚本化部署工具  
    - 提供更多可用工具，例如负载均衡器和成熟的解决方案，而在传统分布式系统中这些工具可能不多  
    - 数据中心之间网络连接更好，针对特定问题进行优化  
    - 地理分布性强，应用程序迁移更容易  
    - 但仍未解决上文提到的许多问题（例如从用户/组织到数据中心的带宽问题）  

- > [2015 Q1] A) 描述在设计大规模分布式系统时常见的一些错误假设。 [5]  
    - 网络是可靠的  
    - 延迟为零  
    - 带宽是无限的  
    - 网络是安全的  
    - 所有节点都有统一的时间  

- > [2014 Q1] A) 讨论过去 20 年中研究与科研计算的主要趋势，这些趋势导致了云计算的出现。 [6]  
    - 大型主机系统（Mainframes）  
        - 从主机向分布式系统转变  
    - 去中心化的个人电脑  
    - 互联网的爆炸式发展  
    - 分布式系统又回归到集中式模式  
    - 计算与存储的规模增长  
    - 云和数据中心的兴起  


## Week2 - Domain Drivers – tour of some big data projects
1. compute scaling
    - method:
        1. Vertical Computational Scaling
            - adv: Have faster processors. Switch your n GHz CPU for a 2n GHz one = 2x faster, Easy to do but cost more
            - disadv: Limits of fundamental physics/matter (nanoCMOS)  
              Moore's law is no longer working, CPU stop goes faster as we expected
        2. Horizontal Computational Scaling
            - Have more processors
            - adv: 
                - 1) Easy to **add more** (more cores or cluster of nodes)
                    - add more = 
                        - Single machine multiple cores
                            - Typical laptop/PC/server these days
                        - Loosely coupled collection/cluster of machines
                            - Polling/sharing of resources
                            - Dedicated vs available only when not in use by others
                        - Tightly coupled cluster of machines
                            - Typical HPC/HTC set-up (SPARTAN)
                            - Which many servers in same room, often with fast message passing interconnects
                        - Widely distributed clusters of machines
                            - UK NGS, EGEE
                        - Hybrid combination of the above
                            - Leads to many challenges with distributed systems
                            - Shared state
                            - Delayed and lost in message passing
                - 2) cost increase not so much
            - disadv: 
                - 1) **add more** limition (see week3 - Amdahl's law)
                - 2) harder to design, develop, test
- I think at the time when it sort of peaked about 3.6 gigahertz, it was like the maximum clock speed maybe they exceeded it occasionally
2. network scaling
    - volume of data on network grows each year
3. massive amount of data generated among a time requires compute infrasture
    - e.g. mapping the sky with data from tele-scope
- 1. 计算扩展（Compute Scaling）
- 方法：
    1. 垂直计算扩展（Vertical Computational Scaling）  
        - 使用更快的处理器  
        - 缺点：处理器速度存在极限  
          - 摩尔定律已逐渐失效，CPU 不再像预期那样不断加速  
    2. 水平计算扩展（Horizontal Computational Scaling）
        - HTC高吞吐量比HPC更重要  
        - 使用更多的处理器  
        - 优点：  
            - 1）易于**增加更多**（更多核心或节点集群）  
                - 增加更多 =  
                    - 单台机器，多核心  
                        - 当今典型的笔记本/台式机/服务器  
                    - 松散耦合的机器集合/集群  
                        - 资源轮询/共享  
                        - 专用资源 vs 在空闲时才可用的资源  
                    - 紧耦合的机器集群  
                        - 典型的高性能/高通量计算环境（如 SPARTAN）  
                        - 多台服务器在同一机房中，常通过快速消息传递互连  
                    - 分布广泛的机器集群  
                        - 例如 UK NGS、EGEE  
                    - 上述多种形式的混合组合  
                        - 会引发很多分布式系统的挑战  
                        - 共享状态  
                        - 消息传递中的延迟与丢失  
            - 2）成本增长不明显  
        - 缺点：  
            - 1）**增加更多**存在限制（见第3周内容：阿姆达尔定律）  
            - 2）更难设计、开发、测试
- Amdahl's Law:
   最大加速比 = 1 /（1 - 并行部分） = 1 /（1 - 0.95） = 20
   也就是说：
   无论你用多少核心或处理器并行计算，最终的整体加速最多也只能是 20 倍。即便你有上千个处理器，那非并行的那 5% 部分仍然是瓶颈，限制了性能的上限 
   非并行部分的比例决定了系统最终的加速上限
- Gustafson-Barsis’s Law ：
  如果你有更多处理器，你就能处理更大的问题（比如模拟更复杂的大脑、处理更大的图像等），
  那么那 5% 的串行部分虽然绝对时间不变，但相对占比变小了，总执行效率仍然大大提升。
  **S=(1−a)+aN**
  **S是speedup总加速比，T是总时间，a是程序中可并行的部分占总时间的比例（0 ≤ a ≤ 1），N是处理器数量**
  Amdahl's Law 假设问题规模不变（固定任务，增加核数看速度能快多少）
  Gustafson’s Law 假设总时间 T 是固定的，问题规模可以增长（即：更多核 → 可以做更大的问题）
  **Gustafson's Law 告诉我们：并行计算的真正价值不只是“把程序跑得更快”，而是“能在相同时间内处理更大的问题”。**

  

2. 网络扩展（Network Scaling）
- 网络上的数据量每年都在增长  

3. 短时间内产生大量数据需要计算基础设施支撑
- 例如：通过望远镜绘制星空图，需要处理大量数据



4. Cloud Computing in Different Domains
    - **High energy physics**
    - Astrophysics
    - **Macro-micro simulations**
    - Electronics
    - Arts and humanities
    - Life sciences
        - Extensive Research Community
            - Parkville Precinct for example
        - Many people care about them
            - Health, Food, Environment – truly interdisciplinary!
        - Interacts with virtually every discipline
            - Physics, Chemistry, Maths/Stats, Nano-engineering, …
        - Thousands of databases relevant to bioinformatics (and growing!)
            - Heterogeneity, Interdependence, Complexity, Change, …
        - Some of the Big Questions/Challenges
            - How does a cell work?
            - How does a brain work?
            - How does an organism develop?
            - Why do people who eat less tend to live longer?
    - Social sciences
        - Aurin
    - Clinical sciences
    - Data sharing and ethics
    - **e-Health**
        - **Security**
    - environmental
    - social
    - geographical
    - Genome
    - Hierarchical statistical system simulations 
        - Very large device and circuit simulations
            - 3D devices
            - 10^5 circuit components
        - Large statistical samples
            - 1000 - 100000 3D simulations 
            - 4D 1000 - 100000 circuit simulations
        - Complex flow and storage of data
            - Many files per simulation
            - Metadata capture and data provenance
        - Collaboration between 5 partners
            - Multidisciplinary background
            - Complex data exchange 
        - Stringent security requirements
            - Commercial IP
            - Expensive software licenses
4. 云计算在不同领域中的应用（Cloud Computing in Different Domains）

- 高能物理（High energy physics）  
- 天体物理学（Astrophysics）  
- 宏观-微观模拟（Macro-micro simulations）  
- 电子工程（Electronics）  
- 人文与艺术（Arts and humanities）  
- 生命科学（Life sciences）  
    - 拥有庞大的研究群体  
        - 例如 Parkville Precinct（墨尔本大学医学园区）  
    - 众多群体对其高度关注  
        - 涉及健康、食品、环境——是真正的跨学科领域！  
    - 几乎与所有学科都有交集  
        - 物理、化学、数学/统计、纳米工程……  
    - 与生物信息学相关的数据库成千上万，且持续增长  
        - 异构性、相互依赖性、复杂性、变化性……  
    - 一些重大科学问题/挑战：  
        - 细胞是如何工作的？  
        - 大脑是如何运作的？  
        - 生物体是如何发育的？  
        - 为什么吃得少的人更长寿？  
- 社会科学（Social sciences）  
    - 例如：AURIN（澳大利亚城市研究基础设施网络）  
- 临床科学（Clinical sciences）  
- 数据共享与伦理问题（Data sharing and ethics）  
- 电子健康（e-Health）  
    - 安全性（Security）  
- 环境科学（Environmental）  
- 社会领域（Social）  
- 地理信息（Geographical）  
- 基因组研究（Genome）  
- 层级统计系统模拟（Hierarchical statistical system simulations）  
    - 超大规模器件与电路模拟  
        - 3D器件模拟  
        - 包含 10^5 个电路元件  
    - 大量统计样本  
        - 1000 - 100000 次 3D 模拟  
        - 4D 模拟中有 1000 - 100000 个电路样本  
    - 数据流动与存储复杂  
        - 每个模拟生成许多文件  
        - 元数据捕获与数据溯源  
    - 5个合作伙伴间的协作  
        - 跨学科背景  
        - 数据交换复杂  
    - 严格的安全要求  
        - 商业知识产权  
        - 昂贵的软件授权



5. challenges are shaping the technological landscape
    - Challenges happen in multiple perspectives in research domains. - Big data - Big compute - Big distribution - Big collaboration - Big security
    - Tools, technologies and methodologies have been/can/are evolving to tackle these challenges
        - That there is a huge amount of work still to be done 
        - Domain knowledge is also required
5. 挑战正在塑造技术发展格局（Challenges Are Shaping the Technological Landscape）

- 在多个研究领域中面临挑战  
    - 大数据  
    - 大计算  
    - 大规模分布  
    - 大协作  
    - 大安全性  

- 各种工具、技术与方法正在不断发展以应对这些挑战  
    - 仍有大量工作尚未完成  
    - 同时也需要领域知识的支持  

- **补充**
- Flynn’s Taxonomy
    -SISD
        A sequential execution computer, which does not use any parallelism in either the instruction stream or the data stream.
        It consists of a control unit (CU or CPU) that fetches a single instruction stream from memory,
        The control unit then generates the corresponding control signals,
        These control signals drive a single processing unit to operate on a single data stream,
        Thus, only one operation is executed at a time.
        This is the basic model of the von Neumann architecture,
        And it has virtually been phased out by modern computing systems that incorporate parallelism at various levels.
        定义：
        一种顺序执行的计算机架构，在指令流和数据流方面都不使用并行处理。
        结构：
        只有一个控制单元（Control Unit，CU 或 CPU），
        从内存中获取一条指令流，
        控制单元产生控制信号，
        使一个处理单元对一个数据流执行操作，
        一次只执行一个操作。
        特性：
        不具备并行性，
        属于**冯·诺依曼架构（von Neumann）**的基本模型，
        如今这种结构几乎已经被淘汰。

– Single Instruction, Multiple Data streams (SIMD)
    A parallel computing architecture in which multiple processing units (PUs/CPUs) perform different operations on the same data stream.
    Each processor runs its own instruction stream, but all processors operate on the same input data.
    Example:
    Used in fault-tolerant computer systems,
    For instance, multiple processors may run independent error-checking algorithms on the same data to ensure reliability and redundancy.

    Note:
    MISD architectures are rare in practice,
    Mainly used in specialized applications such as mission-critical systems (e.g., avionics, spacecraft).
    MISD（多指令流，单数据流）
    一种并行计算架构，在该架构中，多个处理单元（PU/CPU）对相同的数据流执行不同的操作。
    每个处理器运行自己的指令流，但所有处理器都处理同一组输入数据。
    示例：
    用于容错计算系统，
    例如，多个处理器对同一数据流执行独立的错误检测算法，以实现高可靠性和冗余。

    注意：
    MISD 架构在实际中非常少见，
    通常只用于特种应用场景，例如航空航天、飞行控制等关键任务系统。

– Multiple Instruction, Single Data stream (MISD)
    A parallel computing architecture in which multiple processing elements perform the same operation on multiple data points simultaneously.
    The emphasis is on data-level parallelism:
    There is only one instruction stream (one process),
    But it is applied to many data elements in parallel.
    Widely used in modern computing, especially in:
    Multimedia processing (e.g., image and video processing),
    Scientific simulations,
    GPU architectures (Graphics Processing Units).
    Examples of SIMD instruction sets include Intel SSE, AVX, and ARM NEON.
    SIMD（单指令流，多数据流）
    一种并行计算架构，多个处理单元可以在多个数据点上同时执行相同的操作。
    重点在于数据级并行性（data-level parallelism）：
    整个系统中只有一条指令流（即一个进程），
    这条指令会被同时应用于多个数据元素。
    在现代计算机中广泛应用，特别是在：
    多媒体处理（如图像处理、视频解码等），
    科学模拟，
    **GPU 架构（图形处理器）**中。
    SIMD 指令集的例子包括：Intel 的 SSE、AVX，以及 ARM 的 NEON


– Multiple Instruction, Multiple Data streams (MIMD) 
    A parallel computing architecture involving a number of processors that operate asynchronously and independently.
    At any given time, different processors may be executing different instructions on different data elements.
    MIMD machines can fall into two categories based on how memory is accessed:
    Shared memory systems: all processors access a common memory space (e.g., multi-core CPUs),
    Distributed memory systems: each processor has its own local memory and communicates via messages (e.g., cluster computing, MPI).
    Most modern computing systems follow the MIMD model:
    High Performance Computing (HPC),
    Cloud computing clusters,
    General-purpose multi-core processors.
    一种并行计算架构，其中有多个处理器以异步且独立的方式运行。
    在任意时刻，不同的处理器可以执行不同的指令，并处理不同的数据。
    根据内存访问方式的不同，MIMD 系统可以分为两类：
    共享内存系统：所有处理器访问同一块内存区域（例如多核 CPU）；
    分布式内存系统：每个处理器有自己的本地内存，并通过消息传递进行通信（例如集群计算、使用 MPI 的系统）。

    大多数现代计算系统都采用 MIMD 架构：
    高性能计算（HPC），
    云计算集群，
    通用多核处理器。

- 隐式并行（Implicit Parallelism）
    由并行编程语言或自动并行化编译器支持，
    它们负责自动识别哪些代码可以并行执行，负责计算调度和数据分配。
    程序员用常规的顺序方式编写代码，系统自动寻找并行机会。
    实际很难实现，因为编译器必须推断许多复杂的并行策略，尤其是在数据依赖性不明确的程序中。
    显式并行（Explicit Parallelism）
    需要程序员亲自负责并行化工作，包括：
    将任务拆分成多个子任务（任务分解）；
    把子任务分配到不同的处理器（任务映射）；
    管理进程间通信（例如消息传递、同步）。
    假设程序员最了解如何为特定应用实现最优的并行方式。
    通常很复杂且不容易实现，尤其在大规模高性能计算中。
    举例说明：
    在使用 SPARTAN 高性能计算集群时，提交作业时可以使用 SLURM 脚本：


    #SBATCH --ntasks=2 --cpus-per-task=4
    表示你启动 2 个并行进程（tasks），每个进程内部用 4 个 CPU 核心进行线程并行，总共用 8 个核心。

    #SBATCH --ntasks=1 --cpus-per-task=8
    表示你启动 1 个进程，但该进程可以并行使用 8 个 CPU 核心。

    尽管总核数一样，但这两种方式的并行模型不同，程序需要对线程/进程的结构有明确的控制，这属于显式并行编程的设计选择。

- OpenMP
    - Widely used API for shared-memory parallel programming
      Provides features that make it easier to write parallel
      programs for multicore and multiprocessor systems 

    - Work Sharing Constructs：

        - #pragma omp for ：将循环迭代分配给不同线程执行

        - #pragma omp sections ：将不同代码段分配给不同线程

        - #pragma omp single ：指定某一段代码只能由一个线程执行

        - #pragma omp task ：动态创建任务，由线程调度执行

    - Thread Management：

        - omp_set_num_threads() ：设置线程的数量

        - omp_get_num_threads() ：获取当前的线程总数

        - omp_get_thread_num() ：获取当前线程的 ID

    - Synchronization Constructs：

        - #pragma omp critical ：临界区，一次只能一个线程进入，防止数据冲突

        - #pragma omp atomic ：原子操作，用于同步简单操作，性能优于 critical

        - #pragma omp barrier ：线程屏障，所有线程在此同步等待

        - omp_set_lock() / omp_unset_lock() ：设置/释放锁，用于更细粒度的互斥控制

    - Data Sharing Attributes

        - shared ：所有线程访问的是同一份变量

        - private ：每个线程都有自己的变量副本

        - firstprivate ：每个线程有自己的变量副本，并由主线程进行初始化

        - reduction ：各线程处理局部副本，最后将结果**归约（合并）**为一个值（如求和、最大值等）

    - Loop Scheduling

        - static ：编译时预先确定每个线程负责哪些迭代

        - dynamic ：运行时线程动态获取迭代任务

        - guided ：线程获取的迭代块数量逐渐减小，从大到小

        - auto ：交由编译器或运行时系统决定调度策略

    - 可移植性与可扩展性（Portable and Scalable）

        - OpenMP 被设计为可移植，支持多种硬件平台和操作系统，可用于多种编程语言：C、C++、Fortran、Python（通过扩展）等。

- **MPI消息传递接口**

    - 是在并行计算系统中进行消息传递（进程间通信）的广泛采用的方法。支持多种主流编程语言：Fortran、C、C++、Python、Java。

    - 具备以下特点：

        - 标准化（由 MPI Forum 维护标准）

        - 广泛采用

        - 可移植性强（可运行于不同平台和操作系统）

        - 性能优良

        - 然而，并行化的具体实现仍然是程序员的责任，需要手动处理通信逻辑。

    - 核心函数：

        - MPI_Init ：初始化 MPI 运行环境（程序开始时调用）

        - MPI_Finalize ：结束 MPI 运行环境（程序结束前调用）

        - MPI_COMM_SIZE ：获取通信器中总进程数

        - MPI_COMM_RANK ：获取当前进程的唯一标识符（编号）

        - MPI_SEND ：向其他进程发送消息

        - MPI_RECV ：从其他进程接收消息

- HTCondor 是一个专门用于计算密集型任务的工作负载管理系统，由美国威斯康星大学开发。

    特点：

        - 提供作业队列管理机制、调度策略、优先级系统、资源监控与管理功能。

            用户将任务提交给 Condor，Condor 会选择合适的时间与地点执行任务，监控任务进度，并在任务完成后通知用户。

        - 可用于收集“空闲”计算资源，如：利用处于闲置状态的办公桌面机。当键盘或鼠标被检测到活动时，系统会将当前任务迁移到另一台空闲机器（checkpoint & migrate）

        - 不需要在所有机器之间有共享文件系统：

        - 所需数据可在执行时动态传送到对应机器（数据分发）

        - 可跨组织边界运行：

        - 使用 Condor Flocking（集群联合调度） 实现。

        - 使用 ClassAds（分类广告机制）：

        - 每台机器或任务通过 ClassAds 来发布资源信息或表达资源需求，系统根据策略进行任务匹配和调度。

    - 数据并行化方法（Data Parallelism Approaches）

        - 面临的挑战：
        - 大数据带来的挑战可能是当前并行计算中最重要的问题之一

    - 分布式数据问题：
        - 如何在系统中同时满足一致性（Consistency）、可用性（Availability）、分区容忍性（Partition Tolerance）

        - 这正是著名的 CAP 定理（稍后会详细讲）

    - 分布式数据库解决方案：
        - 如 ElasticSearch（一种基于集群的搜索和数据库系统）

        - 提供在 ACID（传统事务一致性模型）与 BASE（弱一致性模型）之间的灵活性选择

    - 分布式文件系统（Distributed File Systems）：
        - 常见系统包括：

            - Hadoop 分布式文件系统（HDFS）

            - Lustre

            - Ceph
- 一些分布式系统错误假设：
  - The network is reliable  
    - 网络是可靠的  

  - Latency is zero  
    - 网络延迟为零  

  - Bandwidth is infinite  
    - 带宽是无限的  

  - The network is secure  
    - 网络是安全的  

  - Topology doesn't change  
    - 网络拓扑结构是固定不变的  

  - There is one administrator  
    - 系统中只有一个管理员  

  - Transport cost is zero  
    - 数据传输成本为零  

  - The network is homogeneous  
    - 网络环境是同质化的（所有设备、系统都是一致的）  

  - Time is ubiquitous  
    - 所有设备的时间是同步且一致的  
- Network reliability（网络可靠性）

  - 如果我通过网络发送一些数据：
    - 它会到达（It will arrive）
    - 它会按我发送的顺序到达（It will arrive in the order I sent it）
    - 它不会被破坏（It will arrive uncorrupted）

  - 如果网络不可靠，它通常只会以其中一种方式表现出来
    - 并且是**一致地**以这种方式失败（Consistently）

  - 网络协议栈中的底层会对这些问题提供一定的保护  
    - （The lower layers in the networking stack protect me from these issues）

  - **但上述每一条陈述都不总是成立！**
    - None of these statements are always true!

- Latency is zero（延迟为零）

  - 如果我发送一些数据，它会立刻到达（It will arrive “now”）
    - 或者说，快得可以认为是“现在” （So fast to be effectively “now”）

  - 真的是这样吗？（Really…?）

  - 举个例子：从墨尔本访问 Twitter（位于旧金山）
    - 距离约为 12,600 公里（~12,600 km）
  
- Latency Consequences（延迟的后果）

  - 在一条 1Gbps 的链路上：
    - 大约有 9MB 的数据可能处于“飞行中”（尚未收到响应），具体取决于 TCP 的分包大小
    - 在开始收到响应之前，可能已经发送了 18MB 的数据，这些数据都会被缓存在 TCP 协议栈的缓冲区中

  - 实际上的网络延迟可能更高

  - 在一个包含多个节点或跳数（hops）的系统中，每一条链路可能具有不同的延迟：
    - 下一跳（next hop）的行为可能变得复杂和难以预测
    - 这些问题在主动网络技术（Active Networking）和软件定义网络（SDN）中有研究与探索

- Bandwidth is infinite（带宽是无限的）

  - 我可以在任意节点之间传输任意数量的数据  
    - I can send any amount of data I wish between any nodes

  - 真的如此吗？（Really?）

    - 想想大数据（BIG DATA）场景：
      - 从 TB 到 PB 级别的数据（Tb → Pb+）
      - 如：SKA（平方公里阵列射电望远镜）、LHC（大型强子对撞机）、基因组学（Genomics）……

    - 这对其他用户也有影响，例如墨尔本的医院

  - 网络带宽通常如下：
    - 1GB、10GB、100GB……（指的是每秒带宽容量）
    - 对于医院或家庭网络，带宽差异巨大

  - 网络容量是经过**精确规划的**
    - 例如：英国的 JANET 教育科研骨干网络，其带宽规划最多只利用了约 25% 的实际容量

- Security

  - 所以我不需要担心……？

  - 有人向我的服务发送数据？
    - 比如重复密码尝试、SQL 注入攻击等

  - 有人主动攻击我？
    - 分布式拒绝服务攻击（DDoS）

  - 有人窃听我发送的数据？
    - 中间人攻击（Man-in-the-middle）

  - 有人冒充我的节点？
    - 网络欺骗（Spoofing）

  - 有人入侵我的节点？
    - 木马、病毒、暴力破解等

  - 有人直接偷走我的物理设备？

- 节点 x 总是在那儿（Node x is always there）

  - “在那儿”是什么意思？
    - 延迟（Latency）
    - IP 地址（IP）
    - 路由路径（Route）
    - 提供的服务（Services）

  - 实际上，路由路径和延迟通常都无法保证一致

    - 除非使用特定的路由协议，如差异化服务（DiffServ）或带有预约的协议
    - 但这些在常规 TCP/IP 网络中通常是不可用的

  - 又是“下一跳行为”（Next hop behaviour）的问题！

- Only one admin


  - 谁是墨尔本大学的管理员？

    - 防火墙的更改？
    - 服务器的重配置？
    - 服务管理？
    - 访问控制管理？（学生 / 教职工 / 其他）

  - 组织之间的管理员权限如何协调？（Inter-organisational administrators）

- Transport cost is zero

  - 有些地方看起来似乎是免费的，但其实……

    - 比如澳大利亚……？？？？

    - 上传/下载有额度限制（capped）

    - 墨尔本大学的研究人员因为未通过 AARNET 网络访问数据而被收取 $50,000 的账单

    - 在 Amazon EC2/S3 上传/下载数据……价格 $$$$$

  - 结论：传输**永远不是免费的**！

- Time is ubiquitous（时间是统一的）

  - 时钟本身存在差异：
    - 时钟频率、时钟周期
    - 时钟漂移（drift）、时钟偏差（skew）等问题

  - 时间同步协议：
    - NTP（Network Time Protocol，网络时间协议）可将参与设备的时间同步到协调世界时（UTC）误差在几毫秒内

  - 实际应用挑战：
    - 例如配音同步中的延迟和抖动（jitter）处理
    - 为了减少延迟和抖动，有许多技术方法被提出和使用

  - 某些领域对时间同步极为敏感：
    - 例如金融交易系统（延迟和时间误差会造成巨大经济损失）





## Week3 - Overview of Distributed and Parallel Computing Systems
1. Question: If n processors (cores) are thrown at a problem how much faster will it go?
    - Some terminology:
        - <img src="./docs/1.png" width="50%" height="50%" />
        - Proportion of speed up depends on parts of program that cannot be parallelised
    1. Amdahl's law
        - assumes a fixed problem size – sometimes can’t predict length of time required for jobs, 
            - e.g. state space exploration or differential equations that don’t solve
        - <img src="./docs/2.jpg" width="60%" height="50%" />
        - That is, if 95% of the program can be parallelized, the theoretical maximum speedup using parallel computing would be 20 times, no matter how many processors are used.
        - If the non-parallelisable part takes 1H, then no matter how many cores are used, it won’t complete in < 1H
        - Amdahl’s Law greatly simplifies the real world
    2. Gustafson-Barsis's Law
        - speedup is a linear formula dependent on the number of processes and the fraction of time to run sequential parts
        - <img src="./docs/3.jpg" width="60%" height="50%" />
        - Faster (more parallel) equipment available, larger problems can be solved in the same time.
    3. comparison
        - Amdahl’s Law suggests that with limited task, speed up could not be too fast. 
        - Gustafson-Barsis’s Law suggests that with enough processors and remaining tasks, speed up will always meet the requirement.
3. Computer Architecture
    - At the simplest level a computer comprises:
        - CPU for executing programs
        - Memory that stores/executing programs and related data
        - I/O systems
            - keyboards, networks
        - Permanent storage for read/writing data into out of memory
        - HPC needs to keep balance of these
            - Based on the problem needs to be solved
    - There are many different ways to design/architect computers
        - different flavours suitable to different problems (below)
            |               | Simple Instruction | Multiple Instruction |
            | ------------- | ------------------ | -------------------- |
            | Single Data   | SISD               | MISD                 |
            | Multiple Data | SIMD               | MIMD                 |
            - Single Instruction, Single Data Stream (SISD)
              - Sequential computer which exploits no parallelism in either the instruction of data streams
              - Single control unit fetches single instruction stream from memory. The CU/CPU then generates appropriate control signals to direct single processing element to operate on single Data Stream, i.e. one operation at a time.
              - Example
                - von Neumann computer
            - Multiple Instruction, Single Data stream (MISD)
              - <u>**Parallel**</u> computing architecture where many functional units (PU/CPU) perform different operations on the same data
              - Example 
                - fault tolerant computer architectures: multiple error checking on the same date source
            - Single Instruction, Multiple Data Stream (SIMD)
              - Multiple processing elements that perform the same operation on multiple data points simultaneously
              - Focusing on data level parallelism: many parallel computations, but only a single process (instruction) at a given moment (<u>**Concurrency**</u>)
              - Example
                - to improve performance of multimedia use such as for image processing
            - Multiple Instruction, Multiple Data stream (MIMD)
              - Number of processors that function **asynchronously** and independently.
              - at any time, different processors may be executing different instructions on different pieces of data
              - Machines can be shared memory or distributed memory categories.
                - Depends on how MIMD processors access memory
              - Example
                - HPC
3. Approaches for Parallelism (Where and how)
    - Explicit vs Implicit Parallelisation
        - Implicit Parallelism
            - **<u>Compiler</u>** is responsible for identifying parallelism and scheduling of calculations and the placement of data
            - Disadv: Pretty hard to do
        - Explicit Parallelisation
            - **<u>Programmer</u>** is responsible for most of the parallelization effort
    - Hardware
        - Hardware Parallelisation
            - **Cache**: much faster than reading/writing to main memory; instruction cache, data cache (multi-level) and translation lookaside buffer used for virtual-physical address translation (more later on Cloud and hypervisors). 
            - **Add CPU (parallelisation)**: Parallelisation by adding extra CPU to allow more instructions to be processed per cycle. Usually shares arithmetic units. 
                - Disadv: Heavy use of one type of computation can tie up all the available units of the CPU preventing other threads from using them.
            - **Multiple cores**: Multiple cores that can process data and perform computational tasks in parallel.
                - Disadv: Typically share same cache, but issue of cache read/write performance and cache coherence. 
                - Disadv: Possibility of cache stalls (CPU not doing anything whilst waiting for caching)
                    - To address the issue that CPU not doing anything whilst waiting for caching. Many chips have mixture cache L1 for single core, L2 for pair cores and L3 shared with all cores.
                - Disadv: typical to have different cache speeds and cache sizes (higher hit rates but potentially higher latency). 
        - Symmetric Multiprocessing (SMP)
            - Two (or more) identical processors connected to a single, shared main memory, with full access to all I/O devices, controlled by a single OS instance that treats all processors equally. Each processor executes different programs and works on different data but with capability of sharing common resources (memory, I/O device, …). Processors can be connected in a variety of ways: buses, crossbar switches, meshes.  
                - Disadv: More complex to program since need to program both for CPU and inter-processor communication (bus).
        - Non-Uniform Memory Access (NUMA)
            - provides speed-up by allowing a processor to access its own local memory faster than non-local memory.
                - Disadv: Improved performance as long as data are localized to specific processes/processors. 
                - Key is allocating memory/processors in NUMA friendly ways, 
                    - e.g. to avoid scheduling/locking and (expensive) inter-processor communication. Approaches such as ccNUMA with range of cache coherency protocols/products. 
    - Operating System
      - parallel vs interleaved semantics 
        - Most modern multi-core operating systems support different "forms" of parallelisation
        - e.g.: A || B vs A ||| B
      - Compute parallelism
        - Processes
          - Used to realize tasks, structure activities
        - Theads
          - Native threads
            - Fork, Spawn, Join
          - Green threads
            - Scheduled by a VM instead of natively by the OS
      - Data parallelism
        - Caching
    - Software/Applications
      - Programming language supports a range of parallelisation/concurrency features
        - Threads, thread pools, locks, semaphores ...
      - Programming languages developed specifically for parallel/concurrent systems
      - Key issues:
        - Deadlock
          - Processes involved constantly waiting for each other
        - LiveLock
          - Process constantly change with regard to one another, but none are progressing
    - Message Passing Interface (MPI)
        - Widely adopted approach for message passing in parallel systems
        - Supports point-point, broadcast communications
        - Key MPI functions
            - ```
                MPI_Init	:initiate MPI computation
                MPI_Finalize	:terminate computation
                MPI_COMM_SIZE	:determine number of processors
                MPI_COMM_RANK	:determine my process identifier
                MPI_SEND	:send a message
                MPI_RECV	:receive a message
                ```
        - Adv: 
            - Standardised, widely adopted, portable, performant
            - Parallelisation = users problem (user controll how to parallel)
    - (HT) Condor
        - A specialized workload management system for compute-intensive jobs developed at University of Wisconsin
        - Adv:
            - Offers job queueing mechanisms, scheduling policies, priority schemes, resource monitoring/management
            - User submits jobs to Condor and it chooses when and where to run the jobs, monitors their progress, and informs the user upon completion 
            - Allows to harvest “free” (?) CPU power from otherwise idle desktop workstations
                - e.g. use desktop machines when keyboard and mouse are idle 
                    - key press detected checkpoint and migrate a job to a different (idle) machine 
            - No need for shared file system across machines
                - Data can be staged to machines as/when needed
            - Can work across organisational boundaries
                - Condor Flocking
            - ClassAds
                - Advertise resources and accept jobs (according to policy)
    - Data Parallelism Approaches (week 9)
        - Challenges of big data
            - The most important kind of parallelism challenge?
        - Distributed data
            - CAP Theorem: Consistency, Availability, Partition tolerance
            - ACID <-> BASE
        - Distributed File Systems 
            - e.g. Hadoop, Lustre, Ceph…
4. Erroneous Assumptions of Distributed Systems (detail see slides)
    - Challenges with Distribution 
        - "A distributed system is one in which the failure of a computer you didn't even know existed can render your own computer unusable" by Leslie Lamport
    - The network is reliable
    - Latency is zero
    - Bandwidth is infinite - I can send any amount of data I wish between any nodes
    - The network is secure
        - People sending data to my services
            - Repeated password attempts, SQL injections, …!?
        - People actively attacking me
            - Distributed denial of service attacks
        - People reading the data sent over the network
            - Man in the middle attacks
        - People masquerading as one of my nodes
            - Spoofing 
        - People breaking into one of my nodes
            - Trojans, viruses, brute force attacks, …
        - People stealing the physical hardware
    - Topology doesn't change - Node x is always there
    - There is one administrator
        - e.g.: Firewall changes, server reconfigurations, services, access control (students/staff/others…)
    - Transport cost is zero - I can send as much data as I like for free
    - The network is homogeneous
    - Time is ubiquitous - Clock is same across all computers in network
    - [-- Assumption ends --]
    - issues of heterogeneity of compute, data, security from lecture 1
    - Distributed systems are widespread - The Internet
    - Many approaches to design parallel or distributed systems (below)
        - No single algorithm
        - No single technical solution
        - Eco-system of approaches explored over time and many open research questions/challenges
        - Flavour of some of these…
5. Strategies for Development of Parallel/Distributed Systems
    - strategies: (detail see slides)
        - Automatic parallelization
        - Parallel libraries
        - Major recording
    - Challenges:
        - dependence analysis is hard for code that uses pointers, recursion, …; 
        - loops can have unknown number of iterations; 
        - access to global resources, e.g. shared variables
6. Design Stages of Parallel Programs
    - Partitioning
        - Decomposition of computational activities and data into smaller tasks 
        - Numerous Pprallelisation paradigms:
            - Master-Worker/task-farming
                - Master decomposes the problem into small tasks
                - distributes to workers and gathers partial results to produce the result
                - Master-worker/task-farming is like divide and conquer with master doing both split and join operation
                - <img src="./docs/4.jpg" width="20%" height="50%" />
            - Divide and Conquer
                - 1) A problem is divided into two or more sub problems
                - 2) each of these sub problems are solved independently
                - 3) their results are combined
                - 3 operations: split, compute, and join
                - Master-worker/task-farming is like divide and conquer with master doing both split and join operation
                - <img src="./docs/7.jpg" width="20%" height="50%" />
            - Single Program Multiple Data (SPMD)
                - Each process executes the same piece of code, but on different parts of the data
                - Data is typically split among the available processors
                - Data splitting and analysis can be done in many ways
                - Commonly exploited model: MapReduce
                - <img src="./docs/5.jpg" width="20%" height="50%" />
            - Pipelining 
                - Suitable for applications involving multiple stages of execution
                - typically operate on large number of data sets.
                - <img src="./docs/6.jpg" width="30%" height="50%" />
            - Speculation
                - Used when it is quite difficult to achieve parallelism through the previous paradigms
                - use "look ahead" execution
                    - Like look ahead, if the data is predictable, we could use the predicted data to do the following action while waiting for data.
                    - If the prediction is incorrect, we have to take corrective action.
                - procedure: 
                    - Consider a (long running) producer P and a consumer C such that C depends on P for the value of some variable V. If the value of V is *predictable*, we can execute C speculatively using a predicted value in parallel with P.
                        - If the prediction turns out to be correct, we gain performance since C doesn’t wait for P anymore. 
                        - If the prediction is incorrect (which we can find out when P completes), we have to take corrective action, cancel C and restart C with the right value of V again. 
            - Parametric Computation
                - not discussed?
        -  Communication (relates with MPI)
            - Flow of information and coordination among tasks that are created in the partition stage
        -  Agglomeration
            - (performance measuring) Tasks and communication created in above stages are evaluated for performance and implementation cost
            - Tasks may be grouped into larger tasks to improve communication
            - Individual communications can be bundled
        -  Mapping/Scheduling
            - (design to be able to scale up/down) Assign tasks to processors such that job completion time is minimized and resource utilization is maximized

### past exam
- > [sample Q5] A) Explain Amdahl's law and discuss the challenges of its practical implementation. [2]
    - Program always bound by limitations caused by sequential part.
    - no matter how mang cores thrown at problem will be limited to the sequential part of the algorithm. 
        - Also inlcudes overheads required to deal with parallelism (loops, variables, communications)
- > [2014 Q4] A) Define Gustafson-Barsis’ law for scaled speed-up of parallel programs. [2]
    - Gustafson-Barsis’s Law suggests that with enough processors and remaining tasks, speed up will always meet the requirement. Faster (more parallel) equipment available, larger problems can be solved in the same time.
- > [2014 Q4] B) A parallel program takes 128 seconds to run on 32 processors. The total time spent in the sequential part of the program is 12 seconds. What is the scaled speedup? [2]
    - S(N) = N - alpha * (N - 1) where N = n processors, alpha = time on sequential / time on parallel
    - S(N) = 32 - (12/128) * (32-1) = 931/32 = 29.09375
- > [2014 Q4] C) According to Gustafson-Barsis’ law, how much faster could the application _theoretically_ run if it ran across all 32 processors compared to running on a single processor? [3]
    - we know from b/ that it (theoretically) runs 29.09375 times faster using 32 processors compared to running on a single processor. 
    - If it takes 128 seconds with the 32 processor case then it would (theoretically) take 29.09375*128 = 3724 seconds in the single processor case.
- > [2014 Q4] D) Why is theoretically italicized in the above? [3]
    - you are not factoring the overheads dealing with the scalling system. If you have parallel processing, this can carry additional overheads, e.g. loops, communications, variables introduced to deal with parallel aspects. While you don't have this overheads in sequential programs.

- > [2014 Q3] A) What is Flynn’s Taxonomy? [2]
    | -             |      | Simple Instruction | Multiple Instruction |
    | ------------- | ---- | ------------------ |
    | Single Data   | SISD | MISD               |
    | Multiple Data | SIMD | MIMD               |

    - > a. What have been the implications of Flynn’s taxonomy on modern computer architectures?  
    Give examples of its consequences on modern multi-core servers and clusters of servers such as the University of Melbourne Edward HPC facility. [4]
        - The HPC uses MIMD so you can have multiple applications running at the same time, reading/writing/processing multiple different types of data but still on the same cluster
- > [2015 Q4] A) Explain the following terms in the context of high performance computing.
    - > a. Data parallelization [1]
        - problem like you have a large amount of data But you need to process, analysis and aggregrate  in a small amount in a parallel way.
    - > b. Compute parallelization [1]
        - many processes and many threads for process things concurrently
- > [2015 Q4] D) Compute parallelization of an application can be achieved through a variety of paradigms including task farming and single program multiple data. Describe these approaches and explain when they might best be applied. [3]
    - Master-Worker/task-farming
        - Master decomposes the problem into small tasks
        - distributes to workers and gathers partial results to produce the result
        - Master-worker/task-farming is like divide and conquer with master doing both split and join operation
    - Single Program Multiple Data (SPMD)
        - Each process executes the same piece of code, but on different parts of the data
        - Data is typically split among the available processors
        - Data splitting and analysis can be done in many ways
        - Commonly exploited model: MapReduce
    
[sample Q5] A) 解释 Amdahl 定律并讨论其在实际实现中的挑战。 [2]

程序总是受限于其串行部分所带来的限制。

无论投入多少个核心，程序的运行速度都将受限于算法中的串行部分。

并且还包括为实现并行性而引入的开销（如循环控制、变量管理、通信等）。

[2014 Q4] A) 定义用于并行程序**扩展加速比（scaled speed-up）**的 Gustafson-Barsis 定律。 [2]

Gustafson-Barsis 定律表明：当拥有足够数量的处理器和待处理任务时，程序的加速比总能达到需求。随着更多可并行的硬件资源的出现，我们可以在相同时间内解决更大规模的问题。

[2014 Q4] B) 某并行程序在 32 个处理器上运行耗时 128 秒。其中串行部分耗时 12 秒。问该程序的**扩展加速比（scaled speed-up）**是多少？ [2]

使用公式：S(N) = N - α × (N - 1)，其中：

N = 处理器数量

α = 串行时间 / 并行总时间

带入数据计算：

S(N) = 32 - (12/128) × (32 - 1) = 931 / 32 = 29.09375

[2014 Q4] C) 根据 Gustafson-Barsis 定律，如果程序运行在单处理器上，其理论上运行时间将是多少？相比之下，32 个处理器运行速度提升了多少倍？ [3]

根据 b/ 的计算，32 处理器下理论加速比为 29.09375 倍。

如果 32 个处理器运行耗时 128 秒，则单处理器理论上需要时间：

29.09375 × 128 = 3724 秒

[2014 Q4] D) 为什么上面提到的“理论上（theoretically）”要用斜体表示？ [3]

因为这个计算没有考虑并行系统中额外引入的开销。例如：

循环控制

通信同步

并行变量管理

而这些开销在串行程序中是不存在的，所以“理论上”的意思是忽略了现实中并行性带来的复杂性。

[2014 Q3] A) 什么是 Flynn 分类法？ [2]
| | 简单指令（Simple Instruction） | 多重指令（Multiple Instruction） |
| --------------- | ---------------------------- | ------------------------------- |
| 单数据流 | SISD | MISD |
| 多数据流 | SIMD | MIMD |

a. Flynn 分类法对现代计算机架构有何影响？请举例说明其在现代多核服务器和如墨尔本大学 Edward HPC 设施中的应用影响。 [4]

Edward 高性能计算集群使用的是 MIMD 架构，这意味着可以同时运行多个应用程序，每个程序处理不同类型的数据，但仍然在同一个集群内。这样大大提升了计算效率和资源利用率。

[2015 Q4] A) 在高性能计算的背景下，解释以下术语：

a. 数据并行化（Data Parallelization） [1]

面对大规模数据，需要将其分割为小块，利用并行方法同时进行处理、分析和聚合。

b. 计算并行化（Compute Parallelization） [1]

利用多个进程和线程同时执行任务，从而实现并发计算。

[2015 Q4] D) 应用的计算并行化可以通过多种模型实现，包括任务农场（task farming）和 SPMD（单程序多数据）。请描述这些方法并说明其适用场景。 [3]

Master-Worker / Task-Farming（主从任务农场模型）

主进程将问题划分为多个小任务

分发给多个工作进程并收集部分结果，最终合并为最终输出

类似于分而治之，由主进程负责“拆分”和“合并”

单程序多数据（SPMD）

每个进程执行同一段代码，但处理的数据是不同部分

通常将数据划分分配给可用处理器

数据的划分与分析可以通过多种方式完成

一个被广泛采用的模型为：MapReduce



## Week4 - The Spartan HPC System
- Some background on **supercomputing, high performance computing, parallel computing, research computing**(they're not the same thing!).
    - Supercomputer
        - Any single computer system that has exceptional processing power for its time.
    - Clustered computing
        - is when two or more computers serve a single resource 
            - e.g.: A collection of smaller computers strapped together with a high-speed local network
        - Adv: improves performance and provides redundancy;
    - HPC - high performance computing
        - It is any computer system whose architecture allows for above average performance
        - The clustered HPC is the most efficient, economical, and scalable method, and for that reason it **dominates supercomputing**.
    - Parallel and Research Programming
        - **Parallel computing refers to the submission of jobs or processes over multiple processors and by splitting up the data or tasks** between them
            - With a cluster architecture, applications can be more easily parallelised across them.
        - Research computing is the software applications used by a research community to aid research.
            - challenge: This skills gap is a major problem and must be addressed because as the volume, velocity, and variety of datasets increases then researchers will need to be able to process this data.
- 1. 超级计算、高性能计算、并行计算、科研计算的一些背景（它们并不完全相同）
    超级计算（Supercomputer）

    指的是在其所处时代具有卓越计算能力的单一计算机系统。

    集群计算（Clustered Computing）

    指的是两个或多个计算机作为一个统一资源协同工作。

    例如：通过高速局域网连接在一起的一组小型计算机。

    优点：提升性能并提供冗余（容错能力）。

    高性能计算（HPC, High Performance Computing）

    指的是其架构能够实现高于平均水平性能的计算系统。

    基于集群的 HPC 是最有效、最经济、最具可扩展性的方法，因此在超级计算领域占主导地位。

    并行与科研计算（Parallel and Research Programming）

    **并行计算指的是将作业或进程提交到多个处理器，并将数据或任务分割给它们并行执行。**

    使用集群架构时，应用程序更容易进行并行化。

    科研计算指的是研究社区用于辅助科研的软件应用。

    挑战：技能缺口是一个严重问题，随着数据集的规模、速度和多样性增长，研究人员需要具备处理这些数据的能力。

2. Flynn’s Taxonomy and Multicore System
    - Over time computing systems have moved towards multi-processor, multi-core, and often multi-threaded and multi-node systems.
    - As computing technology has moved increasingly to the MIMD taxonomic classification additional categories have been added:
        - Single program, multiple data streams (SPMD)
        - Multiple program, multiple data streams (MPMD)
- 2. Flynn 分类法与多核系统
    随着时间推移，计算系统不断发展为多处理器、多核，常常还有多线程和多节点结构。

    随着计算技术逐步向 MIMD（多指令流多数据流）分类靠拢，新的类别也被引入：

    SPMD（单程序多数据流）

    MPMD（多程序多数据流）
3. Things are more important than performance
    - Correctness of code and signal
    - Clarity of code and architecture
    - Reliability of code and equipment
    - Modularity of code and components
    - Readability of code and hardware documentation
    - Compatibility of code and hardware
- 3. 比性能更重要的事情
    代码和信号的正确性

    代码与架构的清晰性

    代码与设备的可靠性

    代码与组件的模块化

    代码与硬件文档的可读性

    代码与硬件的兼容性
4. x-windows forwarding
    - allows you to start up a remote application (on Spartan) but forward the display to your local machine.
- 4. X-Windows 转发
  
    允许你在远程系统（如 Spartan）上启动一个应用程序，但将图形界面转发显示到你的本地电脑上。


5. Why Module?
    - have the advantages of being shared with many users on a system and easily allowing multiple installations of the same application but with different versions and compilation options. Sometimes users want the latest and greatest of a particular version of an application for the feature-set they offer. In other cases, such as someone who is participating in a research project, a consistent version of an application is desired. In both cases consistency and therefore reproducibility is attained.
  - 5. 为什么要使用 Module？
    它可以使系统上的多个用户**共享相同的软件**，并轻松实现同一个应用程序的**多个版本与编译选项共存**。

    有些用户希望使用最新版本以获得新功能，而另一些（如参与研究项目的用户）则希望使用固定版本以保证结果一致。

    在这两种情况下，都可实现**一致性与可重现性**。


- Why performance and scale matters, and why it should matter to you.
- An introduction to Spartan, University of Melbourne's HPC/cloud hybrid system
- Logging in, help, and environment modules.
- Job submission with Slurm workload manager; simple submissions, multicore, multi-node, job arrays, job dependencies, interactive jobs.
- Parallel programming with shared memory and threads (OpenMP) and distributed memory and message passing (OpenMPI)
- Tantalising hints about more advanced material on message passing routines.
- 其他主题
    为什么性能与可扩展性很重要，以及为什么它对你也重要。

    介绍 Spartan：墨尔本大学的 HPC / 云混合系统。

    如何登录系统、获取帮助以及管理环境模块。

    使用 Slurm 工作负载管理器提交作业：

    简单作业

    多核、多节点

    作业数组

    作业依赖关系

    交互式作业

    使用 OpenMP（共享内存与线程）与 OpenMPI（分布式内存与消息传递）进行并行编程。

    关于更高级消息传递操作的**“吊胃口”式介绍**。
'''
module help
显示所有可用的选项、子命令和参数。

module avail
列出所有当前可加载的模块。 module avail

module whatis <modulefile>
显示指定模块的描述信息。   module whatis <>

module display <modulefile>
显示该模块将对环境变量做出的修改，如添加哪些路径到 PATH、MANPATH 等。module display <>

module load <modulefile>
加载一个或多个模块到当前环境（有些模块可能会自动加载其他模块）。module load

module unload <modulefile>
从当前环境中卸载指定模块。 module unload

module switch <modulefile1> <modulefile2>
卸载模块 modulefile1 并加载模块 modulefile2。 module switch

module purge
清除当前环境中所有已加载的模块。 module purge

module spider（Lmod 系统特有，如 Spartan 使用）
搜索所有可用的模块，包括不在当前模块路径中的，并提供描述信息。 
'''

- **Operation on sparton**
  - Submitting and running jobs is a relatively straight-forward process consisting of:
    - 1) Setup and launch
    - 1) Job Control, Monitor results
    - 1) Retrieve results and analyse.
- Instructions
    - squeue | less 查看作业队列
    - sbatch [jobscript] 提交作业脚本
    - squeue -j [jobid] 查看作业状态（或者scontrol show job [jobid]）
    - scancel [jobid] 取消作业
    - Example:
 '''
 # !/bin/bash 
 # SBATCH --partition=cascade partition指定分区 或者 #SBATCH -p physical
 # SBATCH --nodes=2           nodes命令指定节点数
 # SBATCH --ntasks-per-node=4 ntasks-per-node 每个节点任务数n任务数-每隔-节点 MPI指令
 # SBATCH --cpus-per-node=8   OPENMP指令
 # SBATCH --time=01:00:00     wall time指定时间 
 # SBATCH --mem-per-cpu=2G       每个任务2G
 module load mpi4py/3.1.4-Python-3.1.3    module load加载所需软件模块

 srun my-mpi-app 或 srun python my-app.py my-app.ndjson 运行脚本
 ''' 

 提交到调度器指令

 '''
 sbatch myjob.slurm
 '''

**作业数组（batch arrays）和作业依赖（batch dependencies）**

一个典型的例子是对多个数据集执行相同的任务。下面的示例提交了 10 个批处理作业，myapp 分别处理数据集 dataset1.csv、dataset2.csv，…… 一直到 dataset10.csv

'''
# SPATCH --array = 1-10
myapp ${SLURM_ARRAY_TASK_ID}.csv
spatch --dependency=afterok:myfirstjobid mysecondjobid  `after`, `afterok`, `afternotok`, `before`, `beforeok`, `beforenotok`
一个依赖于从上一个的结果
'''
- 对于实时交互式操作，可以在命令行中直接指定资源请求，从而启动一个交互式作业（interactive job）。这会将用户分配到一个计算节点上。

    这种方式通常用于以下情况：

    - 用户希望运行一个大型脚本（不应在登录节点上运行）；

    - 用户希望测试或调试作业。
'''
sinteractive --nodes=1 --ntasks-per-node=4
'''

- OpenMP（Open Multi-Processing） 是一种多线程编程的实现方式。它是一个应用程序接口（API），提供了一组用于多线程、共享内存并行编程的编译指令。
- 只能运行在单个计算节点（共享内存系统）上，不能用于分布式内存系统；它基于线程，而不是基于消息传递（message passing）

- MPI: 多个处理器通过公共通信网络传递消息，协同解决问题。这种灵活的架构克服了串行瓶颈
- OPENMP是多线程，MPI是多进程；OPENMP是共享内存，MPI是分布式内存。后者通过消息传递，前者通过共享变量和同步

### past exam
- > [2015 Q4] B) Explain the role of a job scheduler on a high performance computing system like the University of Melbourne Edward cluster. What commands can be used to influence the behavior of the job scheduler in supporting parallel jobs running on single or multiple nodes (servers)? [3]
    - you can specify wall time, number of processess, number of threads in slurm scripts 
    - and job scheduler schedule you job depend on theses
    - wall time is a massive influence on this
        - If you give a small wall time, the scheduler might schedule faster for you
- [2015 Q4] B) 说明作业调度器在类似墨尔本大学 Edward 集群这样的高性能计算系统中的作用。可以使用哪些命令来影响调度器对在单节点或多节点（服务器）上运行的并行作业的调度行为？[3]

    你可以在 Slurm 脚本中指定 wall time（预计运行时间）、进程数量、线程数量

    作业调度器会根据这些参数安排你的作业

    wall time 对调度影响很大

    如果你设置了较短的 wall time，调度器可能会更快安排运行

- > [sample Q5] B) The actual performance as experienced by users of shared-access HPC facilities such as the Edward cluster at the University of Melbourne can vary – where here performance can be considered as the throughput of jobs, i.e. from the time of first job submission to the time of last job completion. Explain why this can happen. [2]
    - Stuck in queue
    - Overall usage of facility (some nodes can be super busy)
        - e.g.: I/O or node load
    - not all nodes are identical
    - the nature of the application itself
- [sample Q5] B) 在像墨尔本大学 Edward 集群这样的共享访问 HPC 系统中，用户实际体验到的性能（例如作业的吞吐量，即从提交第一个作业到最后一个作业完成的时间）可能会有所不同。请解释为什么会发生这种情况。[2]

    作业可能会长时间排队

    整体资源使用率高（某些节点可能特别繁忙）

    例如：I/O 压力或节点负载高

    并非所有节点都是完全相同的

    应用程序本身的特性也会影响运行效率



- > [sample Q5] C) Explain how the Edward cluster has been set up to minimize this. [2]
    - Stuck in queue: Multiple queues dedicated to certain jobs
        - e.g.: Cloud, physical, ...
    - Overall usage of facility (some nodes can be super busy): Queueing system to only schedule jobs when resources free
        - (avoid starvation/blocking of system by users with large reservation demands for their jobs)
    - Modules set uo with main libraries installed
- [sample Q5] C) 请解释 Edward 集群是如何设置来尽量减少上述情况的。[2]

    排队等待：有多个队列专门用于特定类型的作业

    例如：Cloud 队列、Physical 队列等

    整体资源使用率：排队系统只在资源空闲时安排作业运行

    避免因某些用户大规模资源申请而导致其他用户作业饿死或被阻塞

    模块系统配置好了主要的库和应用，用户可直接使用




- > [sample Q5] D) Explain what users can do to optimize their throughput (use) of the Edward cluster. [2]
    - wall time choices (minimal necessary)
        - If too large, then the job might be queued in a longer time it actually needs
        - If too small, then the job might be terminated before it finishes
    - avoid demanding large scale resource
    - Load right modules
    - benchmark small data then scale up to appropriate large value
 - [sample Q5] D) 用户如何优化他们在 Edward 集群上的吞吐量（使用效率）？[2]

    合理设置 wall time（尽量只设置实际需要的时间）

        - 时间过长：作业排队等待时间可能比实际运行时间还长

        - 时间过短：作业可能在完成前被系统终止

    避免一次性请求过多资源

    加载正确的模块

    先用小数据集做基准测试，再根据情况扩展到大数据集



- > [sample Q5] E) Describe some of the challenges with application benchmarking on HPC facilities. [2]
    - Stuck in queue for a long time
    - Shared facility is not just for you. Thus, can't guarantee runs the same results for same application
    - benchmarking apps is hard
        - different alogrithm implementation different performance
    - use Linpack which is a fixed set of algorithms that doesn't reflect real world apps
        - e.g.: Twitter analytics

- [sample Q5] E) 在 HPC 系统上进行应用程序基准测试会面临哪些挑战？[2]

    作业可能会在队列中等待很长时间

    这是共享平台，不是你一个人在用，因此无法保证每次运行结果都完全一致

    基准测试本身就很难做

        - 不同算法的实现会导致性能不同

    有些人用 Linpack 测试，但它是一组固定的算法，不能代表真实应用的场景

        - 例如：做 Twitter 数据分析时就不适用

- > [2014 Q3, 2015 Q4 C [1]] B) What features does the Edward HPC facility offer to allow utilization of multiple servers (nodes)? [2]
    - firstly, they exist
    - secondly, you can specify your slurm scripts, you can specify the cloud resources you need (nodes/threads/cores). allows you to express these
- [2014 Q3, 2015 Q4 C [1]] B) Edward HPC 系统提供了哪些功能来支持使用多个服务器（节点）？[2]

    首先，它确实配备了多个节点

    其次，你可以在 Slurm 脚本中指定资源，例如云资源、节点数量、线程数、CPU 核数等，这样调度系统就可以据此分配任务

  
- > [2015 Q4] A) Explain the following terms in the context of high performance computing.
    - > c. Wall-time [1]
        - the time limit when you submit job that you think the job will finish by

## Week5 - Cloud Computing & ~~Getting to Grips with the University of Melbourne Research Cloud~~
Cloud computing is a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources (e.g., networks, servers, storage, applications, and services) <u>that can be rapidly provisioned and released with minimal management effort or service provider interaction</u> 可以通过最少的管理工作或服务提供者交互从而可以快速地配置和发布
- <img src="./docs/8.jpg" width="70%" height="50%" />
1. Deployment Models

    |         | Private                                                                                                                                                                                                                      | Community | Public                                                                                                                                                                                                          | Hybrid                                                                                                                                                                                                                      |
    | ------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | pro     | 1. **Control**<br>2. **Consolidation of resources**<br>3. **Easier to secure** - easy to setup firewall<br>4. **More trust**                                                                                                 |           | 1. Utility computing<br>2. **Can focus on core business** - no need to care infrasture or be a devop<br>3. Cost-effective - use as much as you need<br>4. “Right-sizing”<br>5. Democratisation of computing<br> | 1. **Cloud-bursting** - Use private cloud, but burst into (突然变成) public cloud when needed (What is hybrid cloud)                                                                                                        |
    | con     | 1. Relevance to core business?<br>e.g. Netflix to Amazon<br>2. Staff/management overheads - need devop<br>3. Hardware obsolescence - need to refesh hardware<br>4. Over/under utilisation challenges - recycle resources<br> |           | 1. **Security** - people can see your sensitive data<br>2. Loss of control<br>3. **Possible lock-in** - difficult to switch Azure if using AWS<br>4. Dependency of Cloud provider continued existence<br>       | 1. How do you move data/resources when needed?<br>2. How to decide (in real time?) what data can go to public cloud?<br>3. Is the public cloud compliant with PCI-DSS (Payment Card Industry – Data Security Standard)?<br> |
    | example |                                                                                                                                                                                                                              |           |                                                                                                                                                                                                                 | Eucalyptus, VMWare vCloud Hybrid Service                                                                                                                                                                                    |

- Public cloud:
  - Pros
  – Utility computing
  – Can focus on core business
  – Cost-effective
  – “Right-sizing”
  – Democratisation of computing
  - Cons
  – Security
  – Loss of control
  – Possible lock-in
  – Dependency of Cloud provider continued existence
- Private Cloud:
  - Pros
  – Control
  – Consolidation of resources
  – Easier to secure
  – More trust
  - Cons
  – Relevance to core business?
      - e.g., Netflix ->Amazon
  – Staff/management overheads
  – Hardware obsolescence
  – Over/under utilisation challenges
  – (Effort and cost of establishing a data centre)

- Hybrid Clouds
    - Pros
        – Cloud-bursting
            - Use private cloud, but burst into public cloud when
            needed
    - Cons
    - How do you move data/resources when needed?
    - How to decide (in real time?) what data can go to public
    cloud?
    - Short term need can be much more expensive
    - Is the public cloud compliant with PCI-DSS (Payment
    Card Industry – Data Security Standard)?
    - Examples
    – Eucalyptus, VMWare Cloud Foundation (vSphere)

☁️ 公有云（Public Cloud）

✅ 优点：

按需计费（Utility computing）：根据使用多少资源来计费，灵活高效

聚焦核心业务：不需要自己维护硬件，可以专注于自身的业务发展

成本效益高：无需前期投入大量硬件资源，适合中小企业

资源按需匹配（Right-sizing）：可根据实际需求自动调整资源规模

计算资源大众化：让所有人都能接触到强大计算力，推动创新

❌ 缺点：

安全性问题：数据和服务运行在第三方平台上，存在安全隐忧

控制权缺失：企业无法完全掌控底层硬件和架构

可能存在供应商绑定（lock-in）：系统高度依赖某家云服务商

依赖云提供商的持续运营：一旦云厂商出问题，业务可能受影响

🔒 私有云（Private Cloud）

✅ 优点：

完全掌控：企业自己管理云平台，数据和系统在自己控制下

资源整合：可集中管理企业内部的计算资源

更容易实现安全策略：网络和系统由内部团队设定和监控

更高的信任度：企业员工和管理层通常更信任私有部署

❌ 缺点：

是否与核心业务相关？（如 Netflix 最终选择使用亚马逊公有云）

人力和管理成本：需要配备专业的 IT 团队进行维护

硬件老化问题：需要定期更换服务器和设备

资源配置难题：容易出现资源过剩或不足的情况

建立数据中心的成本和复杂度：基础设施投入大，部署周期长

🌤️ 混合云（Hybrid Cloud）

✅ 优点：

云突发（Cloud-bursting）能力：

平时使用私有云，有高峰需求时自动扩展到公有云

实现资源的灵活调度与成本优化

❌ 缺点：
数据/资源迁移难题：在需要时如何快速、可靠地迁移到公有云？

实时决策困难：如何实时决定哪些数据可以进入公有云？

短期使用代价高：突发性资源可能比长期租用更贵

合规问题：公有云是否符合如 PCI-DSS（支付卡行业数据安全标准）等法规？

💡 混合云平台示例：
Eucalyptus

VMWare Cloud Foundation（vSphere）





2. Delivery Models
- responsibilities:
    - <img src="./docs/9.jpg" width="70%" height="50%" />
-
    |         | Iaas                                                 | Paas  | Saas  |
    | ------- | ---------------------------------------------------- | ----- | ----- |
    | example | Amazon Web Services<br>Oracle Public Cloud<br>NeCTAR | Azure | Gmail |

### past exam
- > [2015 Q6] C) Describe some of the challenges in delivering hybrid Clouds? [2]
    - How do you move data/resources when needed?<br>
    - How to decide (in real time?) what data can go to public cloud?<br>
    - Is the public cloud compliant with PCI-DSS (Payment Card Industry – Data Security Standard)?<br>
- > [2015 Q6] B) What are the advantages/disadvantages of public, private and hybrid clouds? [5]
    - below
- > [2014 Q2] A) According to Wikipedia “Cloud Computing is a colloquial expression used to describe a variety of different types of computing concepts that involve a large number of computers that are connected through a real-time communication network (typically the Internet). Cloud computing is a jargon term without a commonly accepted non-ambiguous scientific or technical definition”.
    - > a. Is this justified? Your answer should cover:
        - > i. public, private and hybrid Cloud computing models and their advantages and disadvantages; [4]
                
            |     | Private                                                                                                                                                                                                                      | Public                                                                                                                                                                                                          | Hybrid                                                                                                                                                                                                                      |
            | --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
            | pro | 1. **Control**<br>2. **Consolidation of resources**<br>3. **Easier to secure** - easy to setup firewall<br>4. **More trust**                                                                                                 | 1. Utility computing<br>2. **Can focus on core business** - no need to care infrasture or be a devop<br>3. Cost-effective - use as much as you need<br>4. “Right-sizing”<br>5. Democratisation of computing<br> | 1. **Cloud-bursting** - Use private cloud, but burst into (突然变成) public cloud when needed                                                                                                                               |
            | con | 1. Relevance to core business?<br>e.g. Netflix to Amazon<br>2. Staff/management overheads - need devop<br>3. Hardware obsolescence - need to refesh hardware<br>4. Over/under utilisation challenges - recycle resources<br> | 1. **Security** - people can see your sensitive data<br>2. Loss of control<br>3. **Possible lock-in** - difficult to switch Azure if using AWS<br>4. Dependency of Cloud provider continued existence<br>       | 1. How do you move data/resources when needed?<br>2. How to decide (in real time?) what data can go to public cloud?<br>3. Is the public cloud compliant with PCI-DSS (Payment Card Industry – Data Security Standard)?<br> |
        - > ii. the different flavours of “X as a Service (XaaS)” models including their associated advantages and disadvantages. [4]
            - IaaS
                - adv
                    - give access to service where we can now deploy our services on top of that using Ansible/Heater
                disadv
                    - you need to spend time to build such services
            - PaaS
                - adv
                    - almost everything is organized by professionals, at the same time you have some freedom of action
                - disadv
                    - great dependency on the vendor
            - SaaS
                - adv
                    - everything is organized for you by professionals
                - disadv
                    - no freedom, you fully depend on the vendor
- > [2015 Q6] A) Describe the terms Cloud-based IaaS, PaaS and SaaS and give examples for each. [3]
    - IaaS
        - is a computing infrastructure giving access to service where we can now deploy our services on top of that using Ansible/Heater
        - Amazon Web Services
    - PaaS
        - is a computing infrastructure almost everything is organized by professionals, at the same time you have some freedom of action
        - Azure
    - SaaS
        - is a computing infrastructure everything is organized for you by professionals
        - Gmail
- > [sample Q2 C] What are availability zones in NeCTAR and what restrictions do they impose on NeCTAR Cloud-based application developers? [2]
    - availability zone: locations of data centers used to provide logical view of cloud
    - restriction: can't mount volumes to VMs in remote locations. If you have computer in Melbourne, you can't have your storage somewhere else in a different availability zone and you can't mount that volume.
- > [2017 Q6] b. What are the implications of availability zones with regards to virtual machine instance creation and data volumes offered by NeCTAR? [2]
    - The implications of availability zones with data volumes is that Can’t mount volumes to VMs in remote locations.
    - Instances (on Nectar) can be created in and availability zone.


## workshop week 4: MRC Services
- Keystone
– Provides an authentication and authorization service for OpenStack services
    - Tracks users/permissions
– Provides a catalog of endpoints for all OpenStack services
    - Each service registered during install
– Know where they are and who can do what with them
    - Project membership; firewall rules; image mgt; 
– *Generic authorization system for openStack
    - more in security lecture

- Keystone
    – 为 OpenStack 服务提供认证和授权服务

    - 跟踪用户和权限
        – 提供所有 OpenStack 服务的端点目录

    - 每个服务在安装时都会注册
        – 知道每个服务的位置以及谁可以对其进行哪些操作
        - 项目成员关系；防火墙规则；镜像管理；

    -  OpenStack 的通用授权系统



- Horizon
    – Provides a web-based self-service portal to interact with underlying OpenStack services, such as launching an instance, assigning addresses and configuring access controls.
    – Based on Python/Django web application
    – Mod_wsgi
    - Apache plug realising web service gateway interface
    – Requires Nova, Keystone, Glance, Neutron
    – Other services optional…

- Horizon(Dashboard )
    – 提供一个基于 Web 的自助服务门户，用于与底层 OpenStack 服务交互，例如启动实例、分配地址和配置访问控制。
    – 基于 Python/Django 的 Web 应用程序
    – 使用 Mod_wsgi Apache 插件，用于实现 Web 服务网关接口（WSGI）
    – 依赖 Nova、Keystone、Glance、Neutron 服务
    – 其他服务为可选项…



- Nova
    – Manages the lifecycle of compute instances in an OpenStack environment
    – Responsibilities include spawning, scheduling anddecommissioning of virtual machines on demand
    – Virtualisation agnostic
        - Libvirt
    – Open-source API, daemon and tools for managing platform virtualisation including support for Kernel based virtual machine (KVM), Quick Emulator (QEMU), Xen, Lightweight,Linux Container System (LXC)
    - XenAPI, Hyper-V, VMWare ESX,…
    - Docker
    – API
        - Nova-api - accepts/responds to end user API calls; supports openStack Compute & EC2 & admin APIs
    – Compute Core
        - Nova-compute - Daemon that creates/terminates VMs through hypervisor APIs
        - Nova-scheduler - schedules VM instance requests from queue and determines which server host to run
        - Nova-conductor - Mediates interactions between compute services and other components, e.g. image database
    – Networking
      - Nova-network - Accepts network tasks from queue and manipulates network, e.g. changing IPtable rules
    – Image Mgt, Client Tools, …

- Nova
    – 管理 OpenStack 环境中计算实例的生命周期
    – 职责包括按需启动、调度和注销虚拟机
    – 与虚拟化平台无关
    - 支持 Libvirt
    – 提供开源的 API、守护进程和工具，用于管理平台虚拟化，支持如内核虚拟机（KVM）、Quick Emulator（QEMU）、Xen、轻量级 Linux 容器系统（LXC）

    - 支持 XenAPI、Hyper-V、VMWare ESX 等

    - 也支持 Docker
    - 
    – API
    nova-api：接受并响应用户的 API 请求，支持 OpenStack Compute API、EC2 API 及管理员 API

    – 计算核心
      - nova-compute：守护进程，通过 hypervisor API 创建和终止虚拟机
      - nova-scheduler：从任务队列中调度虚拟机请求，并决定在哪个服务器主机上运行
      - nova-conductor：协调计算服务与其他组件之间的交互，例如镜像数据库
    – 网络

    nova-network：接受网络任务队列的请求并执行相关网络操作，例如修改 IP 表规则
    – 镜像管理、客户端工具等

- Swift(Object Storage)
    – Stores and retrieves arbitrary unstructured data objects via RESTful API, e.g. VM images and data

    • Not POSIX (atomic operations); eventual consistency

    – Fault tolerant with data replication and scale-out architecture.

    • Available from anywhere; persists until deleted

    • Allows to write objects and files to multiple drives, ensuring the data is replicated across a server cluster

    – Can be used with/without Nova/compute

    – Client; admin support

    • e.g. Swift client – allows users to

    submit commands to ReST API through command line clients to configure/ connect object storage to VMs

- Swift
    – 通过 RESTful API 存储和检索任意非结构化数据对象，例如虚拟机镜像和数据

    • 不支持 POSIX（原子操作）；采用最终一致性模型

    – 具有容错能力，采用数据复制和横向扩展架构

    • 可从任何地点访问；数据会一直保存，直到被删除

    • 允许将对象和文件写入多个磁盘，确保数据在服务器集群中被复制

    – 可以配合或不配合 Nova/计算服务使用

    – 支持客户端与管理员操作

    • 例如 Swift 客户端：允许用户通过命令行客户端向 REST API 提交命令，以配置/连接对象存储至虚拟机

Cinder
    – Provides persistent block storage to virtual
    machines (instances) and supports creation and
    management of block storage devices
    – Cinder access associated with a VM
    • Cinder-api – routes requests to cinder-volume
    • Cinder-volume – interacts with block storage service and
    scheduler to read/write requests; can interact with
    multiple flavours of storage (flexible driver architecture)
    • Cinder-scheduler – selects optimal storage provider node
    to create volumes (ala nova-scheduler)
    • Cinder-backup – provides backup to any types of volume
    to backup storage provider
    – Can interact with variety of storage solutions

- Cinder(block storage)
– 为虚拟机（实例）提供持久性块存储，支持块存储设备的创建和管理

– Cinder 存储与特定虚拟机关联

组件包括：

Cinder-api

接收并将请求路由给 cinder-volume

Cinder-volume

与块存储服务和调度器交互，处理读/写请求；

可与多种类型的存储交互（具有灵活的驱动架构）

Cinder-scheduler

选择最优的存储提供节点来创建卷（类似于 nova-scheduler）

Cinder-backup

支持将任意类型的卷备份到备份存储提供方

– 可与多种存储解决方案集成


Glance(Image Service)
– 负责接收有关磁盘或服务器镜像及其相关元数据的请求（通常来自 Swift），并通过 Nova 实现镜像的获取与安装

组件包括：

Glance-api

处理镜像的发现、获取与存储请求

Glance-registry

存储、处理并检索镜像的元数据（例如大小和类型）

示例镜像类型：

Fedora-CoreOS-38？

NeCTAR Windows Server 2022？

NeCTAR R-Studio？

NeCTAR JupyterLab？

我上一次成功的快照…？



Neutron
用于支持 OpenStack 服务中的网络连接

提供一个 API，使用户可以定义网络及其连接方式（如交换机、路由器等）

拥有可插拔架构，支持多个网络厂商和技术

组件：

Neutron-server：接收并路由 API 请求至相应插件进行处理

管理端口，例如默认 SSH、VM 专属规则等

更广泛地配置可用区域的网络，如子网、DHCP 等

Heat
是一个模板驱动的服务，用于管理部署在 OpenStack 上的应用的生命周期

Stack（堆栈）：表示用于创建基础设施和所需资源的模板及执行流程

可与自动化工具集成，例如：

Chef

Puppet

Ansible










## Workshop week5: Auto-Deployment -- Ansible
- Reason for auto-deployment (**comparison**)
  - We are easy to forget what software we installed, and what steps we took to configure the system
  - Manual process is error-prone, can be non-repeatable
  - Snapshots are monolithic
    - provide no record of what has changed
  - Manual deployment provides no record of what has changed
- Automation is the mechanism used to make servers reach a desirable state.
  - Automation provides (**advantages**)
    - A record of what you did
    - Knowledge about the system in code
    - Making the process repeatable
    - Making the process programmable
    - Infrastructure as Code
- Configuration management (CM) tools
    - Configuration management refers to the process of systematically handling changes to a system in a way that it maintains integrity over time.
- Ansible is an automation tool for configuring and managing computers.
  - Features about ansible (Pros)
    - Easy to learn
      - Playbooks in YAML, templates in Jinja2
      - Sequential execution
    - Minimal requirements
      - No need for centralized management servers/daemons
      - Single command to install
      - Using SSH to connect to target machine
    - Idempotent
      - Executing N times no different to executing once
      - Prevents side-effects from re-running scripts
    - Extensible
      - Write you own modules
    - Rolling updates
      - Useful for continuous deployment/zero downtime deployment
    - Inventory management
      - Dynamic inventory from external data sources
      - Execute tasks against host patterns
    - Ansible Vault for encryption

### past exam
- > [Sample Q1, 2017 Q7 B each [2], 2015 Q7 A [4, 3]] Applications can be deployed across Clouds either through creation and deployment of virtual images (snapshots) or through scripting the installation and configuration of software applications.
    - > What are the benefits and drawbacks of these approaches? [3]
        - Snapshots
            - benefits
                - Snapshots are easy, can be created just by clicking buttons on dashboard
            - drawbacks
                - No history of how the instance built -> no control
        - Scripting
            - benefits
                - Scripting allows to do much more 
                    - start application
                    - configure application
                    - deploy application
                    - upgrade system
                    - thus, have more controll over the system
                - Scripting has complete record of how to build and deploy
            - drawbacks
                - harder compared to clicking buttons in Snapshots
    - > Discuss the mechanisms used to support these approaches. You may refer to specific tools used to support these processes on the NeCTAR Research Cloud. [3]
        - openstack API (Nova/Glance/Swift/etc)
        - openstack Service (Heat/etc)
            - templates the flavor of deployment
                - e.g.: specify the version of Ubuntu used
        - Ansible scripting allows to automate software deployment including tasks/role
- > Describe the approach that would be taken using Ansible for scripted deployment of SaaS solutions onto the Cloud. [2]
    - Create a playbook that contains YAML files. Typical contents include variables, inventories and roles/tasks/templates. Inventories will include the servers/database used for the software etc etc. 
    - Then say how you would run the script using openrc.sh etc. Note 2 points so massive amounts of detail not needed.

## Week 6 – Web Services, ReST Services ~~and Twitter demo~~

### SOA

1. What's in an Architecture?
    - A (system) architecture is just the way different components are distributed on computers, 
    - and the way in which they interact with each other.
2. Why Service-oriented Architectures - SOA?
    - When an architecture is completely contained within the same machine, components can communicate directly
        - e.g. through function calls or object instantiations.
    - However, when components are distributed such a direct approach typically cannot be used  (e.g. Assignment 2!)
    - Therefore, components (more properly, systems) have to interact in more loosely-coupled ways. 
    - **Services** are often used for this. Typically combinations and commonality of services can be used to form a **Service-oriented Architecture (SoA)**.
3. SOA goal

    |                                                          |                                                                                                                                                                                                 |
    | -------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | A set of externally facing services                      | that a business wants to provide to external collaborators                                                                                                                                      |
    | An architectural pattern                                 | based on service providers, one or more brokers, and service requestors based on agreed service descriptions                                                                                    |
    | A set of architectural principles, patterns and criteria | that support modularity, encapsulation, loose coupling, separation of concerns, reuse and composability                                                                                         |
    | A programming model                                      | complete with standards, tools and technologies that supports development and support of services (note that there can be many flavours of services)                                            |
    | A middleware solution                                    | optimized for service assembly, orchestration, monitoring, and management (Can include tools and approaches that combine services together.)<br/>e.g. as workflows. - later on security lecture |

4. SOA design principle

    |                               |                                                                                                                                          | exmaple                                                                                                                                 |
    | ----------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
    | Standardized service contract | Services adhere to a communications agreement, as defined collectively by one or more service-description documents.                     | Use defined twitter API                                                                                                                 |
    | Service loose coupling        | Services maintain a relationship that minimizes dependencies and only requires that they maintain an awareness of each other.            |
    | Service abstraction           | Beyond descriptions in the service contract, services hide logic from the outside world.                                                 | Twitter decide the API for you to use i.e. the rule how you can see inside through the Twitter, hide things which you have no access to |
    | Service reusability           | Logic is divided into services with the intention of promoting reuse.                                                                    |
    | Service autonomy              | Services have control over the logic they encapsulate.                                                                                   | you can have tweets older than 2 weeks than you really can't                                                                            |
    | Service statelessness         | Services minimize resource consumption by deferring the management of state information when necessary.                                  |
    | Service discoverability       | Services are supplemented with communicative meta data by which they can be effectively discovered and interpreted.                      |
    | Service composability         | Services are effective composition participants, regardless of the size and complexity of the composition.                               |
    | Service granularity           | a design consideration to provide optimal scope at the right granular level of the business functionality in a service operation.        |
    | Service normalization         | services are decomposed and/or consolidated to a level that minimizes redundancy, for performance optimization, access, and aggregation. |
    | Service optimization          | high-quality services that serve specific functions are generally preferable to general purpose low-quality ones.                        |
    | Service relevance             | functionality is presented at a level of granularity recognized by the user as a meaningful service.                                     |
    | Service encapsulation         | many services are consolidated for use under a SOA and their inner workings hidden.                                                      |
    | Service location transparency | the ability of a service consumer to invoke a service regardless of its actual location in the network.                                  | client only use url to use the service on the web regardless of location of service                                                     |

### Web Services
1. Web Services & SOA
    - Web Services = SOA for the Web
    - Both use HTTP, hence can run over the web (although SOAP/WS often run over other protocols as well)
    - Web services used to implement SOA
2. Web Services flavor
    - (main focus of the lecture) SOAP-based Web Services
    - (main focus of the lecture) ReST-based Web Services
        - Both flavours to call services over HTTP
    - Geospatial services (WFS, WMS, WPS…)
    - Health services (HL7)
    - SDMX (Statistical Data Markup eXchange)
        - approach the statistical data around the world
3. SOAP/WS v.s. ReST  
    SOAP (Simple Object Access Protocol)

    | ReST                                                                                              | SOAP/WS                                                                                                                                                                  |
    | ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
    | is centered around resources, and the way they can be manipulated (added, deleted, etc.) remotely | built upon the <u>Remote Procedure Call paradigm (a language independent function call that spans another system)</u>                                                    |
    | Actually ReST is more of a style to use HTTP than a separate protocol                             | while SOAP/WS is a stack of protocols that covers every aspect of using a remote service, from service discovery, to service description, to the actual request/response |
4. How to describes the functionality offered by a web service?
    - WSDL: is an XML-based interface description language that describes the functionality offered by a web service.
    - WSDL provides a machine-readable description of how the service can be called, what parameters it expects, and what results/data structures it returns:
        - Definition – what it does 
        - Target Namespace – context for naming things
        - Data Types – simple/complex data structures inputs/outputs
        - Messages – messages and structures exchanged between client and server
        - Port Type - encapsulate input/output messages into one logical operation
        - Bindings - bind the operation to the particular port type
        - Service - name given to the web service itself

### ReST-based Web Services
1. What is ReST?  
Representational State Transfer (ReST) is intended to evoke an image of how a well-designed Web application behaves: a network of web pages (a virtual state-machine), where the user progresses through an application by selecting links (state transitions), resulting in the next page (representing the next state of the application) being transferred to the user and rendered for their use.
2. How it works?
    - <img src="./docs/10.png" width="50%" height="50%" />
    - Client wants to access a service (Amazon) a product and things come back
        ```
        1. Clients requests Resource through Identifier (URL)
        2. Server/proxy sends representation of Resource 
        3. This puts the client in a certain state. 
        4. Representation contains URLs allowing navigation.
        5. Client follows URL to fetch another resource.
        6. This transitions client into yet another state.
        7. Representational State Transfer!
        ```
3. ReST Best Practices (principle)
    - Keep your URIs short – and create URIs that don’t change.
    - URIs should be opaque identifiers that are meant to be discovered by following hyperlinks, not constructed by the client.
    - Use nouns, not verbs in URLs
    - Make all HTTP GETs side-effect free.  Doing so makes the request "safe".
    - Use links in your responses to requests!  Doing so connects your response with other data.  It enables client applications to be "self-propelled".  That is, the response itself contains info about "what's the next step to take".  Contrast this to responses that do not contain links.  Thus, the decision of "what's the next step to take" must be made out-of-band.
    - Minimize the use of query strings.  
        - For example:
            - Prefer: http://www.amazon.com/products/AXFC
            - Over: http://www.amazon.com/products?product-id=AXFC
    - Use HTTP status codes to convey errors/success
    - In general, keep the REST principles in mind. 
        - In particular:
            - Addressability (discussed above about address design)
            - Uniform Interface (below)
            - Resources and Representations instead of RPC (below Resource section)
            - HATEOAS (below)
4. ReST – Uniform Interface
    - Uniform Interface has four more constrains:
        - Identification of Resources
            - All important resources are identified by one (uniform) resource identifier mechanism (e.g. HTTP URL)
        - Manipulation of Resources through representations
            - Each resource can have one or more representations. Such as application/xml, application/json, text/html, etc. Clients and servers negotiate to select representation.
        - Self-descriptive messages
            - Requests and responses contain not only data but additional headers describing how the content should be handled.
            - (HTTP GET, HEAD, OPTIONS, PUT, POST, DELETE, CONNECTION, TRACE, PATCH): eneryone knows what these means, no need to google the document (one advantage over SOAP)
        - HATEOAS: Hyper Media as the Engine of Application State
            - Resource representations contain links to identified resources
            - Resources and state can be used by navigating links
                - links make interconnected resources navigable
                - without navigation, identifying new resources is service-specific
            - RESTful applications **<u>navigate</u>** instead of **<u>calling</u>**
                - Representations contain information about possible traversals
                - application navigates to the next resource depending on link semantics
                - navigation can be delegated since all links use identifiers
            - Making Resources Navigable
                - RPC-oriented systems need to expose the available functions
                    - functions are essential for interacting with a service
                    - introspection or interface descriptions make functions discoverable
                - ReSTful systems use a Uniform Interface
                    - no need to learn about functions
                    - To find resources
                        - find them by following links from other resources
                        - learn about them by using URI Templates
                        - understand them by recognizing representations

4. Resource  
    - is anything that’s important enough to be referenced as a thing in itself.
    - e.g.: 
        ```
        If your users might
        - want to create a hypertext link to it
        - make or refute assertions about it
        - retrieve or cache a representation of it
        - include all or part of it by reference into another representation
        - annotate it
        - or perform other operations on it
                    ...then you should make it a resource.
        ```
3. Resource-Oriented Architecture (ROA)
    - what is it?
        - is a way of turning a problem into a RESTful web service:   
    an arrangement of URIs, HTTP, and XML that works like the rest of the Web
        - ROA has a style of supporting Restful services that allows folk to interact/navigate their functionality (HATEOS etc). The services still do PUT, POST, GET etc.
            - can be used to support the definition and creation of services or service endpoints. 
    - ROA \& Rest
        - ROA has a style of supporting Restful services that allows folk to interact/navigate their functionality (HATEOS etc). The services still do PUT, POST, GET etc.
    - ROA v.s. SOA
        - similar
            - Much of the philosophy behind SOA applies to ROA, 
                - e.g. services should support abstraction, contract, autonomy etc, 
        - difference
            - ROA is compared to SOA as a different (better) approach that can be used to support the definition and creation of services or service endpoints. 
        - ROA has advantages
            - there is no need to understand what methods mean or deal with complex WSDL etc. You can mix/match service models
                - e.g. consider the AURIN architecture with ReST, SOAP and many other service flavours.
    - ROA procedure
        - ```
            1. Figure out the data set 
            2. Split the data set into resources and for each kind of resource 
            3. Name the resources with URIs 
            4. Expose a subset of the uniform interface 
            5. Design the representation(s) accepted from the client 
            6. Design the representation(s) served to the client 
            7. Integrate this resource into existing resources, using hypermedia links and forms 
            8. Consider the typical course of events: what’s supposed to happen? - How would a user interact with it?
            9. Consider error conditions: what might go wrong?
            ```
    -  ROA actions
        |         -         |                  Action                  | HTTP METHOD |
        | :---------------: | :--------------------------------------: |
        |  Create Resource  | PUT to a new URI POST to an existing URI |
        | Retrieve Resource |                   GET                    |
        |  Update Resource  |         POST to an existing URI          |
        |  Delete Resource  |                  DELETE                  |
        - Don't mapping PUT to Update and POST to create
            - **PUT** should be used when target resource URL is known by the client.
            - **POST** should be used when target resource URL is server generated
7. HTTP Methods can be 
    - **Safe**
        - Do not change, repeating a call is equivalent to not making a call at all 
        - GET , OPTION, HEAD
    -  **Idempotent**
        - Effect of repeating a call is equivalent to making a single call; if not can has side-effects
        - *PUT*, *DELETE*
    - **Neither**
        - POST

### past exam
- > [2015 Q2] A) Explain the general principles that should underlie the design of Service-Oriented Architectures (SOA). [7]
    | -                             |                                                                                                                                          |                                                                                                                                         | exmaple |
    | ----------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
    | Standardized service contract | Services adhere to a communications agreement, as defined collectively by one or more service-description documents.                     | Use defined twitter API                                                                                                                 |
    | Service loose coupling        | Services maintain a relationship that minimizes dependencies and only requires that they maintain an awareness of each other.            |
    | Service abstraction           | Beyond descriptions in the service contract, services hide logic from the outside world.                                                 | Twitter decide the API for you to use i.e. the rule how you can see inside through the Twitter, hide things which you have no access to |
    | Service reusability           | Logic is divided into services with the intention of promoting reuse.                                                                    |
    | Service autonomy              | Services have control over the logic they encapsulate.                                                                                   | you can have tweets older than 2 weeks than you really can't                                                                            |
    | Service statelessness         | Services minimize resource consumption by deferring the management of state information when necessary.                                  |
    | Service discoverability       | Services are supplemented with communicative meta data by which they can be effectively discovered and interpreted.                      |
    | Service composability         | Services are effective composition participants, regardless of the size and complexity of the composition.                               |
    | Service granularity           | a design consideration to provide optimal scope at the right granular level of the business functionality in a service operation.        |
    | Service normalization         | services are decomposed and/or consolidated to a level that minimizes redundancy, for performance optimization, access, and aggregation. |
    | Service optimization          | high-quality services that serve specific functions are generally preferable to general purpose low-quality ones.                        |
    | Service relevance             | functionality is presented at a level of granularity recognized by the user as a meaningful service.                                     |
    | Service encapsulation         | many services are consolidated for use under a SOA and their inner workings hidden.                                                      |
    | Service location transparency | the ability of a service consumer to invoke a service regardless of its actual location in the network.                                  | client only use url to use the service on the web regardless of location of service                                                     |
- > [2015 Q2] B) Explain why and how Cloud infrastructures have benefited from SOA. [3]
    - standardized interfaces available tn enable you not worry how the cloud internal do tasks for external interactions
    - When an architecture is completely contained within the same machine, components can communicate directly
        - e.g. through function calls or object instantiations.
    - However, when components are distributed such a direct approach typically cannot be used  (e.g. Assignment 2!)
    - Therefore, components (more properly, systems) have to interact in more loosely-coupled ways. 
    - **Services** are often used for this. Typically combinations and commonality of services can be used to form a **Service-oriented Architecture (SoA)**.
- > [2014 Q1] B) How has the evolution of service-oriented architectures supported Cloud computing? [2]
    - SOA has Uniform interface, abstraction, standard contract etc etc avoid all Clouds building their own bespoke solutions (from the forum, below from recording)
    - you have standardized interface for the service-oriented architectures
        - it offers the autonomy 
        - you are providing interface that people/software can interact with
    - Where it is helping cloud computing is every single cloud provider at the builder of the interface using different technlogies i.e. you have to learn the programming language to do that and this can be a major bottleneck. Adpoting SOA like ReST can help to solve this problem. We have apis provided by openstack where you can interact with the cloud with the help of set of libraries for doing that. 
- > [2013 Q4] A) Compare and contrast Representational State Transfer (ReST) based web services and Simple Object Access Protocol (SOAP)-based web services for implementing service-oriented architectures. [8]
    - They are different flavors of web services
    - complexity of SOAP
        - have namespace and standardization around us to do with the operation names of parameters
        - using XML which is bloated (臃肿的) and not easy to use
            - SOAP uses  a stack of protocols that covers every aspect of using a remote service, from service discovery, to service description, to the actual request/response. While ReST uses HTTP than a separate protocol
            - SOAP uses WSDL which is an XML-based interface description language that describes the functionality offered by a web service. WSDL provides a machine-readable description of how the service can be called, what parameters it expects, and what results/data structures are.
            - While ReST doesn't deal with complex WSDL. You can mix/match service models
            - While ReST has no need to understand what methods mean. There is a very small subset of methods that are available in operation where you can do PUT, POST, GET, etc. This very limited vocabulary provide many advantages:
                - simplify understanding from developers who are implementing system to make client to interact with
        - too much standards compared to ReST
    - SOAP is built upon the <u>Remote Procedure Call paradigm (a language independent function call that spans another system)</u> while ReST is centered around resources, and the way they can be manipulated (added, deleted, etc.) remotely
- > [2015 Q3] A) _SOAP is dead; ReST is the future!_ Explain this statement with regards to Representational State Transfer (ReST) based web services compared to Simple Object Access Protocol (SOAP)-based web services for implementing service-oriented architectures. [5]
    - above
- > [2016 Q4] A) Representational State Transfer (ReST) based web services are often used for creating Resourceoriented Architectures (ROA) whilst Simple Object Access Protocol (SOAP)-based web services are often used to implement Service-oriented Architectures (SOA). Discuss the similarities and differences between a ROA and a SOA. [3]
    - similar
        - Much of the philosophy behind SOA applies to ROA, 
            - Standardized service contract
                - Services adhere to a communications agreement, as defined collectively by one or more service-description documents.|Use defined twitter API|
            - Service abstraction
                - Beyond descriptions in the service contract, services hide logic from the outside world.|Twitter decide the API for you to use i.e. the rule how you can see inside through the Twitter, hide things which you have no access to
            - Service autonomy
                - Services have control over the logic they encapsulate.|you can have tweets older than 2 weeks than you really can't
        - both uses HTTP for the communication between client and the resource
    - difference
        - ROA is compared to SOA as a different (better) approach that can be used to support the definition and creation of services or service endpoints. 
        - ROA has no need to understand what methods mean or deal with complex WSDL.
- > [2013 Q4] B) Explain the differences between ReST-based PUT and POST methods and explain when one should be used over another. [2]
    - PUT is used to create resource
    - POST is used to update resource
    - **PUT** should be used when target resource URL is known by the client.
    - **POST** should be used when target resource URL is server generated
- > [2014 Q1] C) A HTTP method can be _idempotent_
    - > What is meant by this italicized term? [1]
        - Effect of repeating a call is equivalent to making a single call; if not can has side-effects
    - > Give an example of an idempotent ReST method. [1]
        - PUT
- > [2015 Q3] B) HTTP methods can be safe or idempotent.
    - > a. What is meant by a safe HTTP method? [1]
        - Do not change, repeating a call is equivalent to not making a call at all 
    - > b. Give an example of a safe HTTP method. [1]
        - GET
    - > c. What is meant by an idempotent HTTP method? [1]
        - Effect of repeating a call is equivalent to making a single call; if not can has side-effects
    - > d. Give an example of an idempotent HTTP method. [1]
        - PUT
    - > e. Give an example of a HTTP method that is neither safe nor idempotent? [1]
        - POST

## Week 7 – Big Data and CouchDB
### "Big data" challenges and architectures
#### challenge
1. four "Vs"

    | Big data challenges |                                                                                                                                                                                     |
    | ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | Volume              | No one really knows how much new data is being generated, but the amount of information being collected is huge.                                                                    |
    | Velocity            | **the frequency (that data arrive)** at which new data is being brought into the system and analytics performed                                                                     |
    | Variety             | **the variability and complexity** of data schema. The more complex the data schema(s) you have, the higher the probability of them changing along the way, adding more complexity. |
    | Veracity            | **the level of trust** in the data accuracy (provenance); the more diverse sources you have, the more unstructured they are, the less veracity you have.                            |

2. Big Data Calls for Ad hoc Solutions
    - While Relational DBMSs are extremely good at ensuring consistency, they rely on normalized data models that, in a world of big data (think about Veracity and Variety) can no longer be taken for granted.
    - Therefore, it makes sense to use DBMSs that are built upon data models that are not relational (relational model: tables and relationships amongst tables).
    - While there is nothing preventing SQL to be used in distributed environments, alternative query languages have been used for distributed databases, hence they are sometimes called NoSQL DBMSs

3. DBMSs for Distributed Environments
    | -                            |                                                                                                                                                                                                 |                                              | e.g. |
    | ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- |
    | key-value store              | is a DBMS that allows the retrieval of a chunk of data given a key: **fast, but crude**                                                                                                         | (e.g. Redis, PostgreSQL Hstore, Berkeley DB) |
    | BigTable DBMS store          | data in columns grouped into column families, with rows potentially containing different columns of the same family for **quick retrive**                                                       | (e.g. Apache Cassandra, Apache Accumulo)     |
    | Document-oriented DBMS store | - data as structured documents, usually expressed as XML or JSON<br/>- Document-oriented databases are one of the main categories of NoSQL databases                                            | (e.g. Apache CouchDB, MongoDB)               |
    | NoSQL DBMSs                  | While there is nothing preventing SQL to be used in distributed environments, alternative query languages have been used for distributed databases, hence they are sometimes called NoSQL DBMSs |
    - Why Document-oriented DBMS for Big data?
        - While Relational DBMSs are extremely good for ensuring consistency and availability, the normalization that lies at the heart of a relational database model implies fine-grained data, which are less conducive to partition-tolerance than coarse-grained data.
            - Example:
                -  A typical contact database in a relational data model may include: a person table, a telephone table, an email table and an address table, all relate to each other.
                -  The same database in a document-oriented database would entail one document type only, with telephones numbers, email addresses, etc., nested as arrays in the same document.
        - While Relational DBMSs are extremely good at ensuring consistency, they rely on normalized data models that, in a world of big data (think about Veracity and Variety) can no longer be taken for granted.
            - Therefore, it makes sense to use DBMSs that are built upon data models that are not relational (relational model: tables and relationships amongst tables).
        - While there is nothing preventing SQL to be used in distributed environments, alternative query languages have been used for distributed databases, hence they are sometimes called NoSQL DBMSs
        - Relational database finds it challenging to handle such huge data volumes. To address this, RDBMS added more central processing units (or CPUs) or more memory to the database management system to scale up vertically
        - The majority of the data comes in a semi-structured or unstructured format from social media, audio, video, texts, and emails.
        - Big data is generated at a very high velocity. RDBMS lacks in high velocity because it’s designed for steady data retention rather than rapid growth

4. Brewer’s CAP Theorem
    - Consistency, Availability, Partition-Tolerance

        |                     |                                                                                                                                         |
        | ------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
        | Consistency         | every client receiving an answer receives **the same answer** from all nodes in the cluster (it doesn't depend on which node is quired) |
        | Availability        | every client receives **an answer** from any node in the cluster (which might differ from node to node)                                 |
        | Partition-Tolerance | the cluster **keeps on operating** when one or more nodes cannot communicate with the rest of the cluster                               |
    - Brewer’s CAP Theorem: you can only pick any two of Consistency, Availability and Partition-Tolerance.
        - <img src="./docs/13.jpg" width="30%" height="50%" />
        - The CAP theorem forces us to consider trade-offs among different options
        - (not quite) While the theorem shows all three qualities are symmetrical, Consistency and Availability are at odds when a Partition happens (虽然定理表明这三个性质都是对称的，但是当一个分区发生时，一致性和可用性是不一致的)
            - “Hard” network partitions may be rare, but “soft” ones are not (a slow node may be considered dead even if it is not); ultimately, every partition is detected by a timeout
                - Can have consequences that impact the cluster as a whole
                    - e.g. a distributed join is only complete when all sub-queries return
                - Traditional DBMS architectures were not concerned with network partitions, since all data were supposed to be in a small, co-located cluster of servers
            - Consequence:
                - The emphasis on numerous commodity servers, can result in an increased number of hardware failures

5. CAP Theorem and the Classification of Distributed Processing Algorithms
    - <img src="./docs/14.jpg" width="30%" height="50%" />

    1. Two phase commit: Consistency and Availability
        - This is the usual algorithm used in relational DBMS's (and MongoDB)

            |                      | what does it entail?                                                        | by                                                                                                                                                                                                                                                                                       |
            | -------------------- | --------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
            | enforces consistency | every database is in a consistent state, and all are left in the same state | 1. locking data that are within the transaction scope <br/>2. performing transactions on write-ahead logs <br/>3. completing transactions (commit) only when all nodes in the cluster have performed the transaction <br/>4. aborts transactions (rollback) when a partition is detected |
            | reduced availability | data lock, stop in case of partition                                        |
        - Conclusion
            - Therefore, two-phase commit is a good solution when the cluster is co-located, less good when it is distributed
    2. Paxos: Consistency and Partition-Tolerance
        - This family of algorithms is driven by consensus, and is both partition-tolerant and consistent
        - In Paxos, every node is either a proposer or an accepter:
            - a proposer proposes a value (with a timestamp)
            - an accepter can accept or refuse it (e.g. if the accepter receives a more recent value)
            - When a proposer has received a sufficient number of acceptances (a quorum is reached), and a confirmation message is sent to the accepters with the agreed value
        - Conclusion
            - Paxos clusters can recover from partitions and maintain consistency, but the smaller part of a partition (the part that is not in the quorum) will not send responses, hence the availability is compromised
    3. Multi-Version Concurrency Control (MVCC): Availability and Partition-tolerance
        - MVCC is 
            - **a method to ensure availability** (every node in a cluster always accepts requests) and
            - **some sort of recovery from a partition** by reconciling the single databases with revisions (data are not replaced, they are just given a new revision number)
        - In MVCC, **concurrent updates are possible without distributed locks** (in optimistic locking only the local copy of the object is locked), since the updates will have different revision numbers; 
            - the transaction that completes last will get a higher revision number, hence will be considered as the current value.
        - In case of cluster partition and concurrent requests with the same revision number going to two partitioned nodes, both are accepted, but once the partition is solved, there would be a conflict. 
            - Conflict that would have to be solved somehow (CouchDB returns a list of all current conflicts, which are then left to be solved by the application).
        - To achieve consistency, Bitcoin uses a form of MVCC based on proof-of-work (which is a proxy for the computing power used in a transaction) and on repeated confirmations by a majority of nodes of a history of transactions.

#### Architecture
1. Sharding
    - What is it?  
        - Sharding is the partitioning of a database “horizontally”, i.e. the database rows (or documents) are partitioned into subsets that are stored on different
    servers. 
        - shard: Every subset of rows
    - Number of shards
        - Larger than the number of replica
        - the number of shards = the max number of nodes (lest a node contains the same shard file twice)
    - Number of nodes
        - larger than the number of replicas (usually set to 3)
        - The max number of nodes = the number of shards (lest a node contains the same shard file twice)    
    - The main advantage of a sharded database lies in the
        - improve performance through the distribution of computing load across nodes. 
            - i.e.: better distribution of data
        - makes it easier to move data files around, 
            - e.g. when adding new nodes to the cluster
    - sharding strategies:
        |                |                                                                                      |
        | -------------- | ------------------------------------------------------------------------------------ |
        | Hash sharding  | to distribute rows evenly across the cluster                                         |
        | Range sharding | similar rows (say, tweets coming for the same area) that are stored on the same node |
6. Replication and Sharding
    - What is replication?   
        - Replication is the action of storing the same row (or document) on different nodes to make the database fault-tolerant.
    - (adv) Replication and sharding can be combined with the objective of maximizing availability while maintaining a minimum level of data safety.
    - A bit of nomenclature:
        - n is the number of replicas (how many times the same data item is repeated across the cluster)
        - q is the number of shards (how many files a database is split)
        - n * q is the total number of shard files distributed in the different nodes of the cluster
        - <img src="./docs/31.png" width="60%" height="50%" />
            
            - There are 16 shards since the three node clustered database has n=2 replicas and q=8 shards. 
7. Partitions
    - What is it?  
        - A partition is a grouping of logically related rows in the same shard 
            - e.g.: all the tweets of the same user
    - Advantage:  
        - Partitioning improves performance by restricting queries to a single shard
            - To be effective, partitions have to be relatively small (certainly smaller than a shard)
    - A database has to be declared “partitioned” during its creation
    - Partitions are a new feature of CouchDB 3.x
8. MapReduce Algorithms
    - What is it?  
        - This family of algorithms is particularly suited to parallel computing of the Single-Instruction, Multiple-Data type (SIMD) (see Flynn's taxonomy in a previous lecture)
    - Advantage:  
        - parallelism
        - greatly reducing network traffic by moving the process to where data are
    - Procedure:  
        1. Map: distributes data across machines, while 
        2. Reduce: hierarchically summarizes them until the result is obtained.

                function map(name, document):
                    for each word w in document:
                        emit (w, 1)
                function reduce(word, partialCounts):
                    sum = 0
                    for each pc in partialCounts:
                        sum += pc
                    emit (word, sum)
1. Clustered database architecture
    - Distributed databases are run over “clusters”, that is, sets of connected computers
    - Clusters are needed to: 
        - Distribute the computing load over multiple computers, e.g. to improve availability
        - Storing multiple copies of data, e.g. to achieve redundancy 
    - Consider two document-oriented DBMSs (CouchDB and MongoDB) and their typical cluster architectures
2. CouchDB Cluster Architecture
    - <img src="./docs/11.jpg" width="30%" height="50%" />
    - In this example there are 3 nodes, 4 shards and a replica number of 2
        - replica: copy of data
    - All nodes answer requests (read or write) at the same time
        - no master
    - Sharding (splitting of data across nodes) is done on every node
        - if a read request to shard A to node 1, then node 1 answer it
        - if a read request to shard A to node 2, then redirect it to node 1 or node 3 answer it
        - How Shards Look in CouchDB see lecture 7 slide 23 
            - and section "Replication and Sharding" below
            ```
            This is the content of the data/shards directory on a node of a three-node cluster
            The test database has q=8, n=2, hence 16 shards files
            The *.couch files are the actual files where data are stored
            The sub-directories are named after the document _ids ranges
            ```
    - When a node does not contain a document (say, a document of Shard A is requested to Node 2), the node requests it from another node (say, Node 1) and returns it to the client
    - Scalability: Nodes can be added/removed easily, and their shards are re-balanced automatically upon addition/deletion of nodes
    - Quorums
        - Write
            - Can only complete successfully if the document is committed to a quorum of replicas, usually a simple majority
        - Read
            - Can only complete successfully only if a quorum of replicas return matching documents
3. MongoDB Cluster Architecture
    - <img src="./docs/12.jpg" width="30%" height="50%" />
    - Sharding (splitting of data) is done at the replica set level
        - i.e.: it involves more than one cluster (a shard is on top of a replica set)
    - write requests can be answered only by the primary node in a replica set
    - read requests can be answered by every node (including secondary nodes) in the set 
        - depend on the specifics of the configuration 
    - Updates flow only from the primary to the secondary
        - If a primary node fails, or discovers it is connected to a minority of nodes, a secondary of the same replica set is elected as the primary
    - Data are balanced across replica sets 
    - Arbiters (MongoDB instances without data) can assist in breaking a tie in elections.
    - Since a quorum has to be reached, it is better to have an odd number of voting members (the arbiter in this diagram is only illustrative)
4. MongoDB vs CouchDB Clusters

    |                | MongoDB                                                                                                                                                                                                                               | CouchDB                                                                                                                                      |
    | -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
    | complexity     | Higher                                                                                                                                                                                                                                | Lower                                                                                                                                        |
    | Availability   | Lower                                                                                                                                                                                                                                 | Higher                                                                                                                                       |
    | Accessibility  | MongoDB software routers must be embedded in application servers                                                                                                                                                                      | Can connected by any HTTP client                                                                                                             |
    | Data Integrity | Lossing two nodes in the MongoDB in this example implies losing write access to half the data, and possibly read access too, depending on the cluster configuration parameters and the nature of the lost node (primary or secondary) | Losing two nodes out of three in the CouchDB example implies losing access to between 1/4 and 1/2 the data, depending on the nodes that fail | in the MongoDB example implies **losing write access |
    | Functionality  | Some features, such as unique indexes, are not supported in MongoDB sharded environments                                                                                                                                              | Can support this                                                                                                                             |
    | CAP            | <u>**Two-phase commit**</u> for replicating data from primary to secondary. <br/>**<u>Paxos-like</u>** to elect a primary node in a replica-set.                                                                                      | MVCC                                                                                                                                         |

    |                                                     | CouchDB                                                                                                                                   | MongoDB                                                                                                                                                                                                                                                                         |
    | --------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | clusters are (difference in API)                    | less complex                                                                                                                              | more complex                                                                                                                                                                                                                                                                    |
    | clusters are                                        | more available                                                                                                                            | less available, as - by default - only primary nodes can talk to clients for read operations, (and exclusively so for write operations)                                                                                                                                         |
    | software routers                                    | while any HTTP client can connect to CouchDB                                                                                              | (MongoS) must be embedded in application servers                                                                                                                                                                                                                                |
    | Losing two nodes                                    | out of three in the CouchDB architecture shown, means **losing access to between 1/4 and 1/2 the data, depending on the nodes that fail** | in the MongoDB example implies **losing write access** to half the data (although there are ten nodes in the cluster instead of three), and possibly read access too, depending on the cluster configuration parameters and the nature (primary or secondary) of the lost nodes |
    | Some features (such as unique indexes)              |                                                                                                                                           | not supported in MongoDB sharded environmen                                                                                                                                                                                                                                     |
    | Classification of Distributed Processing Algorithms | uses MVCC                                                                                                                                 | - uses a mix of two-phase commit (for replicating data from primary to secondary nodes) <br/> - Paxos-like (to elect a primary node in a replica-set)                                                                                                                           |
    | emphasis on and all have partition-tolerance        | Availability                                                                                                                              | consistency                                                                                                                                                                                                                                                                     |
    - These differences are rooted in different approaches to an unsolvable problem, a problem defined by Brewer’s CAP Theorem
        - first 5
    - The different choices of strategies explains the different cluster architectures of these two DBMSs
        - last 2


### Introduction to CouchDB
- Part 2: Introduction to CouchDB, recording 07:: 01:15:16

### past exam
- > [2016 Q3] A) Big data is often associated with data having a range of properties including high volume, high velocity and high variety (heterogeneity).  
Discuss the advantages, disadvantages and suitability more generally of the following data solutions with regards to these big data properties:  
Your answer should include the way in which these solutions implement MapReduce.
    - > a. CouchDB [3]
        - document-oriented approach (less fine grained schema which is typically needed for many big data scenarios)
            - is a document oriented database which helps to solve the data variaty challenge
        - supports MVCC for availability and partition tolerance
        - support for MapReduce for data analytics
            - the use of mapreduce in CouchDB parallelize data processing from huge amout in a small amount way which can helps to solve the high volume challenge
        - may not be suitable for all  big data scenarios (where consistency needed)
        - MapReduce not as rich analytics as others
            - e.g. running machine learning algorithms hence we have Spark
        - supports unique index which helps to improve storage space when there is data duplication for high volume challenge
    - > b. Apache Hadoop Distributed File System (HDFS) [3]
        - Apache Hadoop started as a way to distribute files over a cluster and execute MapReduce tasks
        - HDFS distributed file system so suited for high velocity data (not single server bottleneck)
        - MapReduce for big data processing and increased block size so suited to larger data
        - variety needs programming to tackle
    - > c. Apache Spark [3]
        - Spark was designed to reduce the latency inherent in the Hadoop approach for the execution of MapReduce job
        - Spark supports large in memory analysis
        - richer data processing capabilities (plug-ins)
        - typically used with HDFS to benefit from above two
        - maybe also mention RDDs etc
    - > What other data properties can be associated with big data challenges? [1]
        - Veracity: the level of trust in the data accuracy (provenance); the more diverse sources you have, the more unstructured they are, the less veracity you have.
- > [2013 Q7] A) Many research domains are facing "big data" challenges. Big data is not just related to the size of the data sets. Explain. [5]
    | -        | Big data challenges                                                                                                                                                                 |  |
    | -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | Volume   | No one really knows how much new data is being generated, but the amount of information being collected is huge.                                                                    |
    | Velocity | **the frequency (that data arrive)** at which new data is being brought into the system and analytics performed                                                                     |
    | Variety  | **the variability and complexity** of data schema. The more complex the data schema(s) you have, the higher the probability of them changing along the way, adding more complexity. |
    | Veracity | **the level of trust** in the data accuracy (provenance); the more diverse sources you have, the more unstructured they are, the less veracity you have.                            |
    - For life science, there can be all kinds of flavours of datasets and it's not as simple as integrating them all as there can be huge heterogeneous across data sets.
- > [2013 Q7] B) What capabilities are currently offered or will be required for Cloud Computing infrastructures such as the NeCTAR Research Cloud to tackle these "big data" challenges. [5]  
You may refer to specific research disciplines, e.g. life sciences, astrophysics, urban research (or others!) in your answer to part A) and B) of this question.
    -  You can have access to CouchDB service on the cloud but this does not help to the high velocity problems or sensitive data problems or it doesn't solve other challenges in the big data space. These problems should be solved by engineers and shouldn't be expected to be solved by the NeCTAR.
    - For life science, there is no cancer database. You have to build your own by using the infrastructure provided by the NeCTAR.
    - No fine-grained security service, you have to build it on the cloud.
    - For life science, there can be all kinds of flavours of datasets and you need to provide a service to integrate them and make the result accessible.
    - For life science, there are thousands of databases relevant to bioinformatics and growing! i.e. we know there can be lots of data but we don't know exact how much. So we should make the NeCTAR be scalable to the volumes of the data to be stored.

- > [2013 Q3] A) Explain the consequences of Brewer's CAP theorem on distributed databases. [4]
    - Brewer’s CAP Theorem: you can only pick any two of Consistency, Availability and Partition-Tolerance.
    - Two phase commit can achieve Consistency and Availability
    - Paxos can achieve Consistency and Partition-Tolerance
    - Multi-Version Concurrency Control (MVCC) can achieve Availability and Partition-tolerance
- > [2013 Q3] B) Describe which aspects of the CAP theorem are supported by the following database technologies:
    - > non-SQL (unstructured) databases such as CouchDB. [2]
        - CouchDB uses MVCC to support Availability and Partition-tolerance
    - > relational databases such as PostGreSQL. [2]
        - Relational DBMSs are extremely good for ensuring consistency and availability
    - > Describe the advantages of MapReduce compared to other more traditional data processing approaches. [2]
        - You can map to multiple different servers and you can reductions on all data and it can scale.
        - parallelism
        - greatly reducing network traffic by moving the process to where data are
- > [sample Q4] A) In the context of distributed databases, explain the concepts of: 
    - > Consistency [1]
        - every client receiving an answer receives **the same answer** from all nodes in the cluster (it doesn't depend on which node is quired)
    - > Availability [1]       
        - every client receives **an answer** from any node in the cluster (which might differ from node to node)
- > [sample Q4] B) Give an example of a database technology that supports Availability in the presence of a (network) partition.  [1]
    - Multi-Version Concurrency Control (MVCC)
- > [sample Q4] C) In the context of CouchDB clusters what is the meaning of:
    - > Replica number [1]
        - Number of copies of the same shard kept in the cluster
    - > Number of shards [1]
        - Number of horizontal partitions of the cluster
    - > Read quorum [1]
        - Minumum number of nodes that have to give the same result to a read operation for it to be declared valid and sent back to the client
    - > Write quorum [1]
        - Minumum number of nodes that have to occur for a write operation for it to be accepted
- > [2014 Q5] A) Discuss the advantages and disadvantages of unstructured (noSQL) databases such as CouchDB for dealing with “big data” compared to more traditional databases, e.g. relational databases such as MySQL.  
Your answer should cover challenges with data distribution, traditional database ACID properties, heterogeneity of data and large-scale data processing. [6]
    - In traditional database, we have things like schema, keys tables. While we don't have these in noSQL database which is more flexible.
    - In traditional database, we have to write queries. While we don't to do these in noSQL database
    - Because we have heterogenous data, we would like to save them as document in the noSQL database which is not supported by traditional database
            - The majority of the data comes in a semi-structured or unstructured format from social media, audio, video, texts, and emails.
    - Because noSQL database support mapreduce, we can run mapreduce across many many services which full-scale the processing opportunities for large scale analytics on multiple servers and processing them
    - For ACID, in mySQL transaction needs to be complete while this not a problem with distributed database which shard across multiple servers and everyone of returns with the same answer which can causes overhead on the limitation to do that. CouchDB's nodes can fail but you can still get results.
    - While Relational DBMSs are extremely good for ensuring consistency and availability, the normalization that lies at the heart of a relational database model implies fine-grained data, which are less conducive to partition-tolerance than coarse-grained data.
        - Example:
            -  A typical contact database in a relational data model may include: a person table, a telephone table, an email table and an address table, all relate to each other.
            -  The same database in a document-oriented database would entail one document type only, with telephones numbers, email addresses, etc., nested as arrays in the same document.
        - While Relational DBMSs are extremely good at ensuring consistency, they rely on normalized data models that, in a world of big data (Veracity and Variety) can no longer be taken for granted.
            - Therefore, it makes sense to use DBMSs that are built upon data models that are not relational (relational model: tables and relationships amongst tables).
        - Relational database finds it challenging to handle such huge data volumes. To address this, RDBMS added more central processing units (or CPUs) or more memory to the database management system to scale up vertically
        - Big data is generated at a very high velocity. RDBMS lacks in high velocity because it’s designed for steady data retention rather than rapid growth






## Workshop week6: Containerization and docker
### Virtualization vs Containerization
- Virtualization
  - Pros
    - Application containment
    - Horizontal scalability
  - Cons
    - The guest OS and binaries can give rise to duplications between VMs wasting server processors, memory and disk space and limiting the number of VMs each server can support -> virtualization overhead

优点（Pros）

应用隔离

横向可扩展性

缺点（Cons）

每个虚拟机（VM）都包含一个完整的操作系统和相关二进制文件，可能导致不同虚拟机之间存在大量重复，从而浪费服务器的 CPU、内存和磁盘空间，限制每台服务器可支持的 VM 数量 → 称为虚拟化开销（virtualization overhead）
- Containerization
  - Pros
    - It allows virtual instances to share a single host OS (and associated drivers, binaries, libraries) to reduce these wasted resources since each container only holds the application and related binaries. The rest are shared among the containers.

容器化允许虚拟实例共享同一个主机操作系统（包括驱动程序、二进制文件、库），从而减少资源浪费，因为每个容器只包含应用和相关二进制文件，其他资源在容器之间共享。

- In real world they can co-exist
  - When deploying applications on the cloud, the base computation unit is a Virtual Machine. Usually Docker containers are deployed on top of VMs.
- Containers not always better
  - It depends on: 
    - The size of the task on hand
    - The life span of the application
    - Security concerns
    - Host operation system


实际场景中，两者可以共存

在云环境中部署应用时，基础的计算单元通常是虚拟机。

通常会在虚拟机上部署 Docker 容器。

容器并非总是更优选择

是否选择容器取决于：

当前任务的规模

应用的生命周期长短

安全性需求

主机操作系统的类型和兼容性



🖥️ 虚拟机（Virtual Machines）

Guest OS：运行在虚拟硬件上，每个虚拟机有自己独立的操作系统内核

通信方式：通过虚拟的以太网设备（Ethernet devices）

安全性：安全性依赖于虚拟机管理程序（Hypervisor）

性能：运行指令需在 Guest OS 与 Host OS 间转换，存在一定性能开销

隔离性：与主机的文件系统和库完全隔离

启动时间：慢，通常需要几分钟

存储占用：大，每个 VM 需要完整操作系统镜像

📦 容器（Containers）

Guest OS：共享同一个操作系统内核，不需要单独的内核

通信方式：通过 进程间通信机制（IPC），如管道、Socket

安全性：需要更加仔细的安全审查，因容器共享宿主内核

性能：几乎接近原生（Near-native）性能，因无虚拟化开销

隔离性：文件系统可以共享，库也可以共享（如通过挂载）

启动时间：非常快，通常只需几秒

存储占用：较小，且大多数组件（如基础镜像）可复用

方面	虚拟化（Virtualization）	容器化（Containerization）
启动单元	虚拟机（VM）	容器（Container）
依赖内核	每个 VM 有自己独立的操作系统内核	所有容器共享主机的操作系统内核
启动速度	较慢（通常为几十秒到几分钟）	较快（通常几秒内启动）
资源开销	较大，占用更多内存、磁盘空间	较小，更轻量
隔离性	强（由于独立操作系统）	较弱（共享内核，需额外手段增强安全）
典型用途	完整系统模拟，适用于运行多种不同操作系统的场景	快速部署、微服务架构，适用于轻量级应用
示例技术	VMware、KVM、Hyper-V	Docker、LXC、Podman


### What is Container?
- Similar concept of resources isolation and allocation as a virtual machine
- Without bundling the entire hardware environment and full OS
- What container runtimes are in use?
  - Docker
    - The leading software container platform
  - Containerd
  - cri-o
- 什么是容器（Container）？

    容器与虚拟机类似，具备资源隔离与分配的概念

    但不需要打包整个硬件环境和完整操作系统

- 容器编排技术（Container orchestration technologies）

容器编排技术提供了一个在大规模环境下整合与管理容器的框架。

- 容器编排技术的主要特性（features）

    Networking：容器之间的网络通信管理

    Scaling：根据负载自动扩展或缩减容器数量

    Service discovery and load balancing：服务发现与负载均衡

    Health check and self-healing：健康检查与自我修复机制

    Security：安全性控制与隔离

    Rolling updates：滚动更新，实现无中断部署

- 目标（Goals）
    简化容器管理流程

    帮助管理容器的可用性与扩展性

### Docker
  - What is it?
    - the most successful containerization technology.
  - Docker Nomenclature
    - Container: a process that behaves like an independent machine, it is a runtime instance of a docker image.
    - Image: a blueprint for a container.
    - Dockerfile: the recipe to create an image.
    - Registry: a hosted service containing repositories of images. E.g., the Docker Hub (https://hub.docker.com)
    - Repository: is a sets of Docker images.
    - Tag: a label applied to a Docker image in a repository.
    - Docker Compose: Compose is a tool for defining and running multi-containers Docker applications. 
    - Docker SWARM: a standalone native clustering / orchestration tool for Docker.
  - Manage Data in Docker
    - By default, data inside a Docker container won’t be persisted when a container is no longer exist.
    - You can copy data in and out of a container.
    - Docker has two options for containers to store files on the host machine, so that the files are persisted even after the container stops.
      - Docker volumes (Managed by Docker, /var/lib/docker/volume/)
      - Bind mounts (Managed by user, any where on the file system)
  - different networking options
    - host: every container uses the host network stack; which means all containers share the same IP  address, hence ports cannot be shared across containers
    - bridge: containers can re-use the same port, as  they have different IP addresses, and expose a port of their own  that belongs to the hosts, allowing the containers to be somewhat visible from the outside.


**Docker**

是什么？（What is it?）

最成功的容器化（containerization）技术。

Docker 术语（Docker Nomenclature）

Container：一个行为像独立机器的进程，是 Docker 镜像的运行时实例。

Image：用于创建容器的蓝图。

Dockerfile：用于构建镜像的配方（脚本文件）。

Registry：托管镜像仓库的服务，例如 Docker Hub。

Repository：Docker 镜像的集合。

Tag：应用于镜像的标签，用于标识镜像的版本。

Docker Compose：一个定义并运行多容器 Docker 应用的工具。

Docker SWARM：一个独立的、原生的 Docker 集群编排工具。

- 在 Docker 中管理数据（Manage Data in Docker）

    - 默认情况下，容器内部的数据在容器消失后将不会被持久化。

    - 可以手动将数据复制进出容器。

- Docker 提供两种方式将容器文件存储到主机上，即使容器停止后数据仍然保留：

    - Docker volumes（由 Docker 管理，路径为 /var/lib/docker/volume/）

    - Bind mounts（由用户管理，可以在文件系统的任意位置）

-   不同的网络选项（Different networking options）

    - host：每个容器使用主机的网络栈，因此所有容器共享主机的 IP 地址，因此不能在容器之间重复使用端口。

    - bridge：容器具有不同的 IP 地址，可以复用端口，同时暴露主机端口，使容器可以被外部访问。

    - “none”: no network, completely isolated. i.e. No access from outside, no access to the outside.

    - “overlay”: used in Docker SWARM for multi-host communications.

    - “macvlan”: containers gets its own IP on the physical network (like a real machine).

    "none"：无网络，完全隔离。即：无法从外部访问，也无法访问外部。

    "overlay"：用于 Docker SWARM 中进行多主机通信。

    "macvlan"：容器在物理网络上获得自己的 IP 地址（就像一台真实的机器一样）。


Docker 加固（安全性）

使用官方或可信的镜像 Use official or trusted images

    - 优先使用官方仓库，避免使用未知镜像。

以非 Root 用户运行容器 Run the containers as a Non-Root user

    - 使用非 root 用户来运行你的应用程序。

最小化容器镜像体积 Minimize the container size

- 镜像越小，攻击面越小。

扫描镜像中的安全漏洞 Scan images for vulnerabilities

修复已知的 CVE（通用漏洞和暴露）和漏洞。

使用如 docker scan 等工具。

限制网络和卷（volume）访问权限 Limit network and volume access

不要暴露不必要的端口。

只挂载所需的卷，并设置严格的权限。

如果可能，使用只读文件系统。Keep Docker engine up-to-date

保持 Docker 引擎更新

修复已知的 CVE（通用漏洞和暴露）和错误。`

**CI-CD**
持续集成（CI）
开发人员频繁地推送代码更改，
系统通过自动构建代码和运行自动化测试来进行验证，
目的是快速发现并修复错误。

好处包括：

自动化的构建和测试流程

早期错误检测

提高透明度

更快的发布周期

持续交付（CD）
在通过持续集成后，代码更改会被自动部署，
可以在无需人工干预的情况下发布新功能或修复漏洞。

好处包括：

自动化的部署流程

更频繁且更小规模的发布

提高效率与生产力

CI/CD 流水线
是将持续集成和持续交付的实践、工具以及软件从开发到部署所经历的各个阶段整合起来的一套流程。

### Dockerfile
  - ```
    FROM nginx:latest

    ENV WELCOME_STRING "nginx in Docker"

    WORKDIR /usr/share/nginx/html

    COPY ["./entrypoint.sh", "/"]

    RUN cp index.html index_backup.html; \
            chmod +x /entrypoint.sh; \
            apt-get update && apt-get install -qy vim
    # above run at build time
    # below run at start up

    ENTRYPOINT ["/entrypoint.sh"]
    CMD ["nginx", "-g", "daemon off;"]
    ```
  - ENTRYPOINT
    - ENTRYPOINT gets executed when the container starts. CMD specifies arguments that will be fed to the ENTRYPOINT.
    - Unless it is overridden, ENTRYPOINT will always be executed.



### What are Orchestration Tools?
- Container orchestration technologies provides a framework for integrating and managing containers **<u>at scale</u>**
- Goals/benefits
  - Simplify container management process
  - Help to manage availability and scaling of containers
- Features
  - Networking
  - Scaling
  - Service discovery and load balancing
  - Health check and self-healing
  - Security
  - Rolling update
- Tools
  - Kubernetes and Hosted Kubernetes
  - Docker SWARM / Docker Compose
  - OpenShift

- You can think of container orchestration tool as: operating systems for the cloud
- Container Orchestration tools tend to follow two principles: Declarative Application Management, and Infrastructure as Code

### 什么是编排工具（Orchestration Tools）？

- 容器编排技术提供了一个框架，用于在**<u>大规模</u>**环境下集成和管理容器。

- 目标 / 好处：
  - 简化容器管理流程
  - 帮助管理容器的可用性和扩展性

- 功能：
  - 网络（Networking）
  - 扩展（Scaling）
  - 服务发现与负载均衡（Service discovery and load balancing）
  - 健康检查与自我修复（Health check and self-healing）
  - 安全性（Security）
  - 滚动更新（Rolling update）

- 常见工具：
  - Kubernetes 及托管型 Kubernetes（Hosted Kubernetes）
  - Docker SWARM / Docker Compose
  - OpenShift

- 你可以将容器编排工具理解为：**云环境中的操作系统**
- 容器编排工具通常遵循两个原则：
  - **声明式应用管理（Declarative Application Management）**
  - **基础设施即代码（Infrastructure as Code）**

### 声明式应用管理（Declarative Application Management）

- 声明式应用管理是一种通过声明期望的系统状态来管理软件的方式，而不是通过一系列命令或图形界面操作（这被称为命令式应用管理）。
- 专注于“期望状态”让容器编排工具具备**自我修复能力**，即当系统偏离预期状态时（例如节点故障、容器崩溃等），能够自动恢复到预期状态。
- 另一个重要特性是**幂等性idempotence：多次应用相同的配置configuration不会改变系统状态，从而减少错误的可能性**。例如：
  - 如果你连续执行两次“创建容器”命令，会创建两个容器，即使你只需要一个。
  - 如果你声明两次“始终运行一个容器”的期望状态，系统只会创建一个容器，正如你预期的那样。
- 这种“期望状态”通常使用 YAML 或 JSON 格式的配置文件来表达。

### 基础设施即代码（Infrastructure as Code, IaC）

- 基础设施即代码（IaC）是一种通过**编写代码（主要是配置文件）**来管理基础设施的方法，而不是使用命令行界面（CLI）命令或图形界面工具手动配置。
- IaC 的主要优势包括：
  - **追踪基础设施的变更**（可结合 Git 等软件版本控制工具使用）
  - **更好地文档化系统架构**（相比之下，命令行操作或图形界面操作通常不会被记录）


### Compose vs Swarm vs Kubernetes

- **Docker Compose** 允许你定义并管理一组在**同一个计算节点**上运行的容器，这些容器协同工作来提供某种功能（在 Kubernetes 中这种结构被称为一个 “Pod”）。
  - 一个典型的 Docker Compose 应用栈示例：一个 Nginx 容器、一个 WordPress 容器和一个 MySQL 容器，通过链接它们来实现完整的 WordPress 部署（参考实际工作坊）。

- **Docker Swarm** 将这种能力扩展到**多个计算节点**的集群中。

- **Kubernetes** 和 **Docker Swarm** 拥有相同的核心功能（即在一组计算节点上管理容器），但：
  - Docker Swarm 的功能相对基础，主要只做容器编排。
  - Kubernetes 在此基础上增加了**更强大的抽象机制和工具**，可以用来构建**更复杂的系统**。

### Kubernetes (k8s)

- Kubernetes 最初由 Google 开发，用于管理其分布式应用程序，并在 2014 年成为开源项目。
- Kubernetes 是容器编排的行业标准。
- 围绕基础的 Kubernetes 形成了一个庞大的工具和项目生态系统，大多数由 **云原生计算基金会（Cloud Native Computing Foundation）** 管理。
- Kubernetes 通常简称为 **k8s**。
- 在 k8s 中，开发者通常编写 **YAML 文件（称为 manifests）** 来定义系统配置，而不是向每个节点发出命令（manifests 也可以用 JSON 编写，YAML 是 JSON 的超集，可以在 YAML 中混合 JSON 片段）。
- Kubernetes 拥抱 **基础设施即代码（Infrastructure as Code）** 和 **声明式应用管理（Declarative Application Management）** 的理念。
- Kubernetes 集群具有 **自我修复（self-healing）** 能力。
- Kubernetes 技能不仅适用于学术环境（如 MRC/OpenStack），在 **任何云平台** 都非常有用。
- Kubernetes **不依赖于任何特定的商业云服务商**。

### Kubernetes Architecture结构

- Kubernetes (k8s) 包含许多组件，这些组件运行在 k8s 集群的节点上（一个 k8s 集群是由多个节点组成，由一个或多个 master 节点统一管理）。
- Kubernetes 的组件分为两类：

  #### 控制平面（Control Plane）：
  - 负责保持集群的**期望状态**（desired state）：
    - 调度 pods
    - 存储配置
    - 管理服务
    - 发布 k8s API 等

  #### 数据平面（Data Plane）：
  - 实际运行用户指定的工作负载（workloads）

- 在 Kubernetes 中，节点分为两类：
  - **Master 节点**：运行控制平面组件（可以是单个或多个节点）control plan components, manage pods, configurations,srvices and public k8s apis
  - **Worker 节点**：运行实际的应用容器，即数据平面工作负载 working plan componentsrun actual workloads

- Kubernetes 的 API（通常运行在 6443 端口）允许用户与控制平面交互，但你将主要通过 **命令行工具（CLI）** 来间接操作 API。

### What K8s Does for Software Applications

- 使用 Kubernetes 集群的主要目的是运行真正对用户有用的软件应用程序。

#### Kubernetes 在**应用部署**方面的优势：

- **自动保持容器中的应用程序运行**（如果容器崩溃会自动重启；如果节点宕机，容器会转移到其他健康节点） automatically running
- 自动分配 **DNS 名称给服务**（如数据库可通过 `pg.dev.svc.cluster.local` 访问，而不依赖可能变化的 IP 地址） distribute dns to services
- 可以自动将特定容器调度到满足条件的节点（如 GPU 节点或内存 ≥16GB 的节点） automatically containers to specific nodes
- 将容器负载分布在整个集群中 
- 可使用 **namespace** 在同一集群中同时运行同一应用的多个版本（如 dev 和 prod）run many versions of an app at same time
- 提供配置分发机制，可向容器传递参数或设置环境变量

### Kubernetes Concepts

| 概念        | 描述 |
| ----------- | ---- |
| **Node**    | 计算节点（通常是虚拟机），Kubernetes 在其上运行 |
| **Volume**  | 可挂载到节点的持久化存储 |
| **Pod**     | 一个或多个协作容器的集合，是 k8s 中最小的可部署单元 |
| **Deployment** | 同一时间运行的多个相同 Pod，可用于保持应用的多个副本（如运行 3 个 Nginx 的 Pod） |
| **Service** | Pod 提供的功能（如端口上的 HTTP 服务），在 k8s 集群内部使用 |
| **Ingress** | 允许外部客户端访问集群中服务的入口，支持基于 hostname、路径的路由等功能 |
| **ConfigMap** | 用于在 k8s 集群中传递参数 |
| **Namespace** | **除节点外，所有对象都可分组到不同的命名空间中以便管理**。每个 k8s 集群都默认包含一个名为 `default` 的命名空间 |


### Pods

- 虽然一个 Pod 通常只包含一个容器，但 Pod 是一种非常有用的抽象概念，因为在许多场景中，在同一节点上**并行运行多个容器**是最佳的架构选择：

  - 示例：一个 CouchDB 容器旁边运行一个 Lucene 文本搜索引擎容器，以实现全文搜索功能。
  - 示例：一个应用容器旁边运行一个身份验证容器，用于验证传入请求的合法性。

- 一个 Pod 的 manifest（清单）**必须**包含以下内容：**pod names, container names, container images**
  - **Pod 的名称**
  - **容器名称**
  - **容器镜像**
  - 可选项：环境变量值、容器暴露的端口、挂载的卷等

- Pod 内的容器：**run on same node and share memories and network**
  - 运行在同一个节点上
  - 共享存储与网络

- Pod 的调度可以通过以下方式进行更细粒度控制：
  - **Affinity/Anti-affinity 规则**：定义 Pod 应该（不应该）运行在哪些类型的节点上。
  - 其他调度控制机制：
    - `nodeSelector`
    - `taints` 和 `tolerations`

- 容器镜像会被 Kubernetes 自动下载并运行
  - 如果是私有镜像仓库，需要在集群中配置其位置和认证信息

---

### Why Pods?

- Pods 支持基于**微服务**的松耦合架构（将应用拆分为多个独立服务）

#### 举例说明：

- **日志采集: collect logs: one container->local logs/ another one monitor file changes on elasticsearch**
  - 传统做法：应用程序自行记录日志（如写入文件）
  - 问题：若需要更换日志目标（如从本地文件切换到 Elasticsearch），则需要改动应用代码
  - 更好的方案：
    - 应用容器输出日志到本地文件
    - 辅助容器监听文件变更，并将日志发送到目标（ElasticSearch、云日志服务等）

- **初始化任务: add init containers in pods**
  - 使用 init 容器为主容器预处理数据后终止
  - 示例：数据库容器在启动前先由 init 容器预创建数据库、表和用户

- **输出增强: 著容器关注业务逻辑，sidecar负责extend functionality**
  - 辅助容器可对应用容器的输出进行修改
    - 如添加或移除 HTTP headers（提高安全性）

- 与主应用容器并行运行、**扩展其功能**的容器称为：`sidecar 容器`

```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: harvester-flickr
spec:
  replicas: 1
  template:
    metadata:
      labels:
        app: harvester-flickr
    spec:
      containers:
        - name: harvester-flickr
          image: ado/ado-harvester-flickr:0.1.0
          env:
            - name: DYNACONF_COUCHDB_DATABASE
              value: "flicker"
      affinity:
        nodeAffinity:
          requiredDuringSchedulingIgnoredDuringExecution:
            nodeSelectorTerms:
              - matchExpressions:
                  - key: "magnum.openstack.org/nodegroup"
                    operator: In
                    values:
                      - "default-worker"
```

### Kubernetes 中的 Service 示例说明

- **Service** 是通过指定一个或多个端口来暴露 Pod 的服务。
- 使用 **Pod 的标签（labels）** 来选择目标 Pod。
- 下面是一个将 CouchDB 应用暴露为 NodePort 的 Service 配置示例：

```yaml
apiVersion: v1               # API 版本
kind: Service                # 资源类型是 Service
metadata:
  name: "couchdb-ingress-service"  # Service 的名称
spec:
  type: NodePort             # Service 类型为 NodePort（可从外部访问）
  ports:
    - name: http             # 端口名称
      protocol: TCP          # 使用的协议
      port: 80               # Service 对外暴露的端口
      targetPort: 5984       # Pod 内部容器监听的端口（CouchDB 默认端口）
  selector:
    app: couchdb             # 匹配标签为 app=couchdb 的 Pod
```

### Ingress 路由示例（Ingress Routing）

- Ingress 用于将来自外部的 HTTP 请求路由到集群内部的 Service。
- 在此示例中，所有的 HTTP 流量会被路由到名为 `couchdb-ingress-service` 的 Service 的 80 端口。

```yaml
apiVersion: networking.k8s.io/v1beta1  # API 版本（注意此版本为较旧版本）
kind: Ingress                          # 资源类型是 Ingress
metadata:
  name: "couchdb-ingress"              # Ingress 名称
spec:
  rules:
    - http:
        paths:
          - path: /                    # 匹配路径（可用正则表达式）
            backend:
              serviceName: "couchdb-ingress-service"  # 路由目标服务名
              servicePort: 80                          # 路由到服务的端口

    虽然可以直接在 Pod 或 Deployment 中设置环境变量，但更推荐使用 ConfigMap。

    ConfigMap 是一种 以键值对形式存储配置参数 的 Kubernetes 对象，可以被多个 Pod 引用。

    适合集中管理配置，而不将配置硬编码在 Pod 定义中。
```


### 访问 MRC 的 Kubernetes 集群

- MRC 为了安全，对基础设施施加了一些限制，**访问集群的过程比一般云服务更复杂**（将在实践课中演示）。
- 要通过命令行客户端访问 Kubernetes 服务或 Pod，**必须使用端口转发（port forwarding）**。
- 端口转发是基于 **Kubernetes API 的 6443 端口** 实现的。
  - 只有拥有正确 **SSL 证书** 的客户端（包含在 `kubeconfig` 文件中）才能访问。
- 上述过程可通过 **UML 部署图（Deployment Diagram）** 表示。
  - UML 是国际标准（ISO/IEC 19501），可用于 Assignment 2 报告中描述系统结构。
### kubeconfig 文件放在哪？

- `kubeconfig` 文件 提供身份验证信息，由创建集群的团队成员生成。
- `kubeconfig` 文件中包含：
  - **主节点的浮动 IP 地址**
  - **SSL客户端证书**（该集群唯一）用于身份验证
  - **Kubernetes API 的端口号**（通常为 6443，所有通信都走 HTTPS）
  - 其他配置参数
- 创建完成后，**需要分发给所有团队成员**，他们需要将其放在各自的电脑上本地使用。


### Kubernetes Tools

- **Magnum**:  **与配置kubernates集群所需资源**
  - 是 OpenStack 的一部分，用于从云基础设施中预配资源  
  - 提供客户端工具，可以向 OpenStack 云基础设施发送命令

- **Kubectl**:  
  - 命令行工具，用于向 Kubernetes 集群 API 发送命令

- **Helm**:  
  - 命令行工具，用于在 k8s 集群上安装软件应用程序（可类比为包管理器）

- **Minikube**:  
  - 在单个节点（例如本地笔记本电脑）上构建一个迷你 Kubernetes 集群  
  - 适合用于学习和本地开发

---

### Magnum

- **Magnum 使用集群模板（cluster template） 来预配创建 Kubernetes 集群所需的资源**
- 集群模板是一个 **manifest 文件**，声明了所需的资源，例如：
  - worker/master 节点数量
  - 节点使用的镜像
  - 网络配置等

- Magnum 使用命令：`openstack coe`（COE = Container Orchestration Engine）

#### 常用 Magnum 命令：

```bash
openstack coe cluster create     # 创建集群
openstack coe cluster list       # 查看已有集群列表
openstack coe cluster show       # 显示集群详情
openstack coe cluster config     # 生成 kubeconfig 配置文件
openstack coe cluster resize     # 调整集群规模
openstack coe cluster delete     # 删除集群
```


### Kubectl 简介

- **kubectl** 是使用最广泛的命令行工具，用于与 Kubernetes 集群交互。
- 在 **Magnum** 创建完 Kubernetes 集群后，可以使用命令：

```
openstack coe cluster config <cluster-name>
kubectl get nodes 查看集群节点
kubectl get pods -n couchdb 查看某个命名空间下的pods
kubectl describe pods couchdb-couchdb-0 -n couchdb 查看某个pod详细信息
kubectl describe node <node-id> 查看某个pod资源使用情况
kubectl top pods -n <namespace> 查看pods 的资源使用
kubectl port-forward deployment/<deployment-name> <local-port>:<container-port> 本地端口转发

```

### Helm

- **Helm** 是一种非常方便的工具，用于在 Kubernetes 集群上部署应用程序。
- Helm 的作用类似于 `pip` 或 `npm`，但它用于部署容器化应用程序。



### Helm Chart

- **Helm chart** 是一组 Kubernetes manifests 的集合，用于定义部署在集群上的资源。
- 可以从 **Helm 仓库（Helm repositories）** 下载 chart。



### 自定义配置

- 通常 Helm charts 允许通过 **命令行参数（CLI parameters）** 来进行一些自定义。
- 例如，可以使用以下方式安装 chart 并覆盖默认配置：
helm install <release-name> <chart-name> --set <parameter>=<value>


### Service-oriented Architectures（服务导向架构，SoA）

- 当系统架构完全包含在同一台机器中时，组件之间可以通过函数调用等方式直接通信。
- 然而，当组件是分布式的（例如 Assignment 2！），就无法使用直接调用方式。
- 因此，系统之间必须以更松散耦合的方式进行交互。
- 服务（Services）常用于此目的，多个服务的组合与通用性构成了服务导向架构（SoA）。

---

### SoA 与 Web Services（Web 服务）

- Web 服务通常用于实现服务导向架构（SoA）。
- Web 服务有很多不同的实现方式，例如：
  - **SOAP（Simple Object Access Protocol）** - 基于 XML 的协议
  - **ReST（Representational State Transfer）** - 基于资源的风格
- 两者都使用 HTTP，因此可以通过互联网运行
  - 不过 SOAP/WS 也可以运行在其他协议之上
- 还有其他专业领域的 Web 服务标准：
  - 地理空间服务：WFS、WMS、WPS
  - 医疗健康服务：HL7
  - 统计数据交换：SDMX

---

### SOAP vs ReST

| 特性              | SOAP                                            | ReST                                        |
|-------------------|-------------------------------------------------|---------------------------------------------|
| 核心思想          | 远程过程调用（Remote Procedure Call）          | 操作资源（Resources）                       |
| 接口描述          | 使用 WSDL 描述服务功能                          | 不使用统一描述语言（可选 OpenAPI）         |
| 协议栈            | 协议栈庞大（描述、发现、请求等）                | 是一种使用 HTTP 协议的风格                 |
| 格式              | 通常为 XML                                       | 通常为 JSON 或 XML                         |
| 规范性            | 非常标准化                                       | 更加轻量灵活                               |
| 开销              | 大（复杂度高）                                   | 小（效率高）                               |
| 语言独立性        | 是                                               | 是                                         |
| 服务调用方式      | 明确操作，如调用 addUser()                      | 通过 HTTP 方法如 POST /users               |

---

### WSDL（Web Services Description Language）

- **WSDL** 是一种 XML 格式的接口描述语言，用于描述 Web 服务提供的功能。
- 它为客户端提供了机器可读的服务说明：如何调用服务、需要什么参数、返回什么数据结构。

#### WSDL 的结构组成：

- **Definition**：服务的基本定义
- **Target Namespace**：定义命名上下文
- **Data Types**：输入/输出的数据结构（简单/复杂）
- **Messages**：客户端与服务端之间交换的信息结构
- **Port Type**：将输入/输出消息封装为逻辑操作
- **Bindings**：将操作绑定到特定的通信协议
- **Service**：Web 服务的名称及其描述

---

### 语言独立性与位置透明性

- **SOAP/WS** 构建在远程过程调用（RPC）之上：
  - 支持不同语言之间的函数调用
  - 客户端不需要知道服务的具体位置和语言实现
- **ReST** 以资源为中心：
  - 更像是一种**如何使用 HTTP 的设计风格**，而非协议本身
  - 更适合构建现代 Web 应用程序与微服务架构

| 角色       | 描述                                |
| -------- | --------------------------------- |
| **WSDL** | 描述 **Web 服务的结构和功能**，告诉你“有什么、怎么调用” |
| **SOAP** | 是实际传输数据的协议，用来按照 WSDL 描述进行通信       |






### What is ReST?

- **ReST（Representational State Transfer，表征状态转移）** 的设计初衷是模拟一个设计良好的 Web 应用程序的行为：
  - 用户通过选择链接（状态转移）在一组网页（虚拟状态机）中导航，
  - 每次选择都导致“下一页”（即应用的下一个状态）被传输并呈现给用户。

---

### What's in a Name? （名字的含义）

1. 客户端通过标识符（URL）请求资源
2. 服务器/代理发送资源的表征（representation）
3. 这会将客户端置于某个状态
4. 表征中包含链接（URL）供进一步导航
5. 客户端跟随链接请求下一个资源
6. 这将客户端转移到另一个状态
7. 整个过程即为 **Representational State Transfer（状态的表征式转移）**

→ RESTful 应用强调**导航（navigate）**而不是函数调用  
→ 表征中包含了可导航的链接  
→ 应用根据链接的语义跳转至下一个资源  
→ 所有链接都使用标识符，因此**导航可以被委托**

---

### ReST Best Practices #1（最佳实践）

1. 保持 URI 简短，并确保其**不可变**
2. URI 应为**不透明标识符 opaque identifiers**，应通过链接发现而不是客户端构造
3. URL 使用**名词**而非动词
4. 所有 HTTP GET 请求应无副作用（safe） **side-effect free， make requests safe**
5. 在响应中包含链接！这样可以引导客户端进行下一步操作，实现“自驱动”
6. **最小化查询字符串 Minimize use of query strings**的使用：
   - 推荐：  
     `http://www.amazon.com/products/AXFC`  
   - 不推荐：  
     `http://www.amazon.com/products?product-id=AXFC`
7. 使用 **HTTP 状态码** 表示错误或成功状态

---

### RESTful 服务应有统一接口（Uniform Interface）**四个约束**

- **资源标识（Identification of Resources）**：所有资源都有标识
  - 所有重要资源通过统一的标识机制（如 HTTP URL）识别 
- **通过表征（representation）操作资源**：客户端和服务端之间交换的是资源的“表征”，即资源在某一时刻的“表达形式”，而不是直接访问数据库或对象本身。
  - 每个资源可有多种表征格式，如 `application/json`、`text/html` 等
  - 客户端与服务器协商选择合适的表征方式
- **自描述信息（Self-descriptive messages）**：每个请求和响应都是自包含的，通过头信息（headers）和主体（body）表达清楚意图和数据
  - 请求与响应中除了数据，还包含附加的头信息（例如是否应缓存、是否需要认证等）
- **统一访问语义（Universal Semantics）**：所有资源都遵循 HTTP 标准方法的语义，操作方式通用、一致
  - 所有资源的访问方法语义一致，例如 GET 总是用于读取资源

---

### HTTP Methods（方法语义）

| 方法       | 安全（Safe） | 幂等（Idempotent） | 说明                                            |
|------------|--------------|---------------------|-------------------------------------------------|
| GET        | ✅           | ✅                  | 获取资源，无副作用                              |
| OPTIONS    | ✅           | ✅                  | 获取服务器支持的通信选项                        |
| HEAD       | ✅           | ✅                  | 类似于 GET，但只返回头信息                      |
| PUT        | ❌           | ✅                  | 更新资源，多次调用效果一样                     |
| DELETE     | ❌           | ✅                  | 删除资源，多次调用结果相同                     |
| POST       | ❌           | ❌                  | 创建资源，每次调用可能产生不同结果             |

- **Safe**：调用不会改变状态（不会产生副作用）get,option,head不变所以安全
- **Idempotent**：多次调用等价于一次调用 除了post





### Docker SWARM
- What is Docker SWARM (the correct name: Docker in SWARM mode)? 
  - It is a Docker orchestration tool.
- Why Docker SWARM?
  - Hundreds of  containers to manage?
  - Scalability
  - Self-healing
  - Rolling updates
- Features
  - Raft consensus group
    - consists of internal distributed state store and all manager nodes. 
  - Internal Distributed State Store
    - built-in key-value store of Docker Swarm mode.
  - Manager Node 
    - It conducts orchestration and management tasks. Docker Swarm mode allows multiple manager nodes in a cluster. However, only one of the manager nodes can be selected as a leader. 
  - Worker Node 
    - receives and executes tasks directly from the manager node
  - Node Availability
    - In Docker Swarm mode, all nodes with ACTIVE availability can be assigned new tasks, even the manager node can assign itself new tasks (unless it is in DRAIN mode)
  - Service 
    - consists of one or more replica tasks which are specified by users when first creating the service.
  - Task
    - A task in Docker Swarm mode refers to the combination of a single docker container and commands of how it will be run. 

### past exam
- > [Sample Q1] Applications can be deployed across Clouds either through creation and deployment of virtual images (snapshots) or through scripting the installation and configuration of software applications.
    - > Container based solutions such as Docker have advantages and disadvantages compared to traditional Cloud-based virtualization solutions based upon hypervisors. Discuss. [4]
        - Guest OS
            - Running on virtual Hardware will have their own OS kernels, thus introduce virtualization overhead. While container allows virtual instances to share a single host OS to reduce these wasted resources
        - Communication
            - Virulization communicate through Ethernet devices. Container communicate through IPC mechanisms
        - Security
            - Virulization depends on the Hypervisor. Container requires close scrutiny.
        - Performance
            - Virulization has small overhead incurs when instructions are translated from guest to host OS. Container have near native performance.
        - Isolation
            - Virulization has file systems and libraries are not shared between guest and host OS. Container has file systems and libraries can be shared.
        - Startup time 
            - Virulization's startup time is slow. Container's startup time is fast.
        - Storage
            - Virulization's requires storage space is large. Container's requires storage space is small and most are reusable.
        - (Virtualization vs Containerization table above)
- > [sample Q6] A)  What are container orchestration technologies? What are the main benefits of using container orchestration tools? Name two of the most popular Docker orchestration tools?                [3]
    - Container orchestration technologies provides a framework for integrating and managing containers **<u>at scale</u>**
    - benefits
        - Simplify container management process
        - Help to manage availability and scaling of containers
    - Docker orchestration tools
        - Kubernetes
        - Docker SWARM
- > [2017 Q4] d ii What is the relationship between a Docker Image and a Docker
Container? [1]
    - Container is a process that behaves like an independent machine, it is a runtime instance of a docker image.
    - Image is a blueprint for a container.

- > [sample Q6] B)  A researcher wants to attach to an already running Postgresql container and list all of the databases it contains. The command to list all of the database is psql -U postgres -c “\l”. The name of the container is postgres and it exposes the port 5432 to the host. Is the following command correct? If not, please correct it:                     docker exec -p 5432 --name postgres sh -c psql -U postgres -c “\l”             [3]    
    - docker exec -t postgres sh -c "psql -U postgres -c \"\I\""
    - docker exec -t postgres psql -U postgres -c "\I"

- > [sample Q6] C) The following Docker compose file starts two Docker containers that are used to run a WordPress website. What are the equivalent Docker commands that could be used to start these two containers individually?   [4]
    ```
    version: '3.6'

    services:

    wordpress:

        image: wordpress

        restart: always

        ports:

        - 8080:80

        environment:

        WORDPRESS_DB_HOST: database

        WORDPRESS_DB_USER: wordpress

        WORDPRESS_DB_PASSWORD: wordpress

        WORDPRESS_DB_NAME: wordpress

    database:

        image: mysql:5.7

        restart: always

        environment:

        MYSQL_DATABASE: wordpress

        MYSQL_USER: wordpress

        MYSQL_PASSWORD: wordpress

        MYSQL_ROOT_PASSWORD: P@ssw0rd

        volumes:

        - /data/mysql:/var/lib/mysql
    ```
    - ```
        docker run -e WORDPRESS_DB_HOST=database \
        -e WORDPRESS_DB_USER=wordpress \
        -e WORDPRESS_DB_PASSWORD=wordpress \
        -e WORDPRESS_DB_NAME=wordpress \
        -p 8080:80 --restart always wordpress
        ```
    - ```
        docker run -e MYSQL_DATABASE=wordpress \
        -e MYSQL_USER=wordpress \
        -e MYSQL_PASSWORD=wordpress \
        -e MYSQL_ROOT_PASSWORD=P@ssw0rd \
        -v /data/mysql:/var/lib/mysql \
        -d --restart always mysql:5.7
        ```

## Week 8.1 – Virtualisation
Terminology
- <img src="./docs/15.png" width="30%" height="30%" />
- 
    |                                    |                                                                                                                                                              |
    | ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
    | Virtual Machine Monitor/Hypervisor | The virtualisation layer between the underlying hardware the virtual machines and guest operating systems it supports. Give a perception of a whole machine. |
    | Virtual Machine                    | A representation of a real machine using hardware/software that can host a guest operating system                                                            |
    | Guest Operating System             | An operating system that runs in a virtual machine environment that would otherwise run directly on a separate physical system.                              |
1. What happens in a VM?
    - <img src="./docs/16.jpg" width="70%" height="30%" />
    - Inside the virtual machine, there are Virtual Network Device, VHD(Virtual Hard disk), VMDK(Virtual Machinie Disk), qcow2(QEMU Copy on Write)
    - Guest OS apps “think” they write to hard disk but translated to virtualised host hard drive by VMM
        - Which one is determined by image that is launched

2. Motivation (why we want VM/virtualization/advantages) ~~& History~~
    | motivation                                         |                                                                                         |
    | -------------------------------------------------- | --------------------------------------------------------------------------------------- |
    | Server Consolidation                               | 1. Increased utilisation<br/>2. Reduced energy consumption                              |
    | Personal virtual machines can be created on demand | 1. No hardware purchase needed<br/>2. Public cloud computing - won't lockin Amazon      |
    | Security/Isolation                                 | Share a single machine with multiple users - won't want everyone see what you are doing |
    | Hardware independence                              | Relocate to different hardware                                                          |
    - originally, virtual machine = an efficient, isolated duplicate of the real machine
        - Properties of interest (can also be thought as motivation):
            - Fidelity
                - Software on the VMM executes behaviour identical to that demonstrated when running on the machine directly, barring timing effects
            - Performance
                - An overwhelming majority of guest instructions executed by hardware without VMM intervention
            - Safety
                - The VMM manages all hardware resources
    - history see lecture 8.1 slide 7
3. Classification of Instructions
    |                         |                                                                                        |                                                                                                                          |
    | ----------------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
    | Privileged Instructions | instructions that trap if the processor is in user mode and do not trap in kernel mode |
    | Sensitive Instructions  | instructions whose behaviour depends on the mode or configuration of the hardware      | Different behaviours depending on whether in user or kernel mode<br/>- e.g. POPF interrupt (for interrupt flag handling) |
    | Innocuous Instructions  | instructions that are neither privileged nor sensitive                                 | Read data, add numbers etc                                                                                               |
    - Popek and Goldberg Theorem  
        - For any conventional third generation computer, a virtual machine monitor may be constructed if the set of **sensitive instructions** for that computer is a subset of the set of **privileged instructions** i.e. have to be trappable
    - x86 architecture was historically not virtualisable, due to **<u>sensitive instructions</u> that could not be trapped** 
    - Intel and AMD introduced extensions to make x86 virtualisable
3. What are the requirements for virtualisation?
    - <img src="./docs/17.jpg" width="40%" height="30%" />
    | Typical Virtualisation Strategy   |                                                                                                                                                                                                                         | Achieved by                                                                                                                                                                                 | problem                                                                                                          |
    | --------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
    | De-privileging (trap-and-emulate) | trap-and-emulate: VMM emulates the effect on system/hardware resources of privileged instructions whose execution traps into the VMM                                                                                    | running GuestOS at a lower hardware priority level than the VMM                                                                                                                             | Problematic on some architectures where privileged instructions do not trap when executed at de-privileged level |
    | Primary/shadow structures         | 1. VMM maintains “shadow” copies of critical structures whose “primary” versions are manipulated by the GuestOS, e.g. memory page tables<br/>2. Primary copies needed to insure correct versions are visible to GuestOS |
    | Memory traces                     | Controlling access to memory so that the shadow and primary structure remain coherent                                                                                                                                   | write-protect primary copies so that update operations cause page faults which can be caught, interpreted, and addressed <br/>- Someones app/code doesn’t crash the server you are using!!! |
    - Do sensitive instructions and privileged instructions both need to be trap-and-emulate?
        - All sensitive/privileged instructions have to be dealt with. Some will need to be emulated/translated
        - others can just happen depending on the mode and/or whether para-virtualisation is supported.
        - (Popek and Goldberg Theorem above and sth below)
4. Virtualisation approaches (compare with each other pair wise 1 v.s. 2, ...)
    | Aspects of VMMs                       | What is it?                                                                                                                                                                                                                                                                                                                                                           | e.g.               | Advantages                                                                                                                                                 | Disadvantages                                                                                                                                                                |
    | ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
    | Full virtualisation                   | allow an unmodified guest OS to run in isolation by simulating full hardware <br/>- Guest OS has no idea it is not on physical machine                                                                                                                                                                                                                                | VMWare             | 1. Guest is unaware it is executing within a VM<br/>2. Guest OS need not be modified<br/>3. No hardware or OS assistance required<br/>4. Can run legacy OS | 1. can be less efficient                                                                                                                                                     |
    | Para-virtualisation                   | - VMM/Hypervisor exposes special interface to guest OS for better performance. Requires a modified/hypervisor-aware Guest OS <br/> - Can optimise systems to use this interface since not all instructions need to be trapped/dealt with because "VMM emulates the effect on system/hardware resources of privileged instructions whose execution traps into the VMM" | Xen                | 1. Lower virtualisation overheads, so better performance                                                                                                   | 1. Need to modify guest OS - Can’t run arbitrary OS!<br/>2. Less portable<br/>3. Less compatibility<br/>                                                                     |
    | Hardware-assisted virtualisation      | Hardware provides architectural support for running a Hypervisor<br/>- New processors typically have this<br/>- Requires that all sensitive instructions trappable                                                                                                                                                                                                    | KVM                | 1. Good performance<br/>2. Easier to implement<br/>3. Advanced implementation supports hardware assisted DMA, memory virtualisation                        | 1. Needs hardware support                                                                                                                                                    |
    | software virtualization               | Any virtualisation that does not involve hardware support.                                                                                                                                                                                                                                                                                                            |
    | Binary Translation                    | Trap and execute occurs by scanning guest instruction stream and replacing sensitive instructions with emulated code <br/> - Don’t need hardware support, but can be much harder to achieve                                                                                                                                                                           | VMWare             | 1. Guest OS need not be modified<br/>2. No hardware or OS assistance required<br/>3. Can run legacy OS                                                     | 1. Overheads<br/> 2. Complicated<br/> 3. Need to replace instructions “on-the-fly”<br/> 4. Library support to help this, e.g. vCUDA                                          |
    | Bare Metal Hypervisor                 | VMM runs directly on actual hardware<br/>- Boots up and runs on actual physical machine<br/>- VMM has to support device drivers, all HW mgt                                                                                                                                                                                                                           | VMWare ESX Server  |
    | Hosted Virtualisation                 | VMM runs on top of another operating system                                                                                                                                                                                                                                                                                                                           | VMWare Workstation |
    | Operating System Level Virtualisation | 1. Lightweight VMs<br/>2. Instead of whole-system virtualisation, the OS creates mini-containers                                                                                                                                                                                                                                                                      | Docker             | 1. Lightweight<br/>2. Many more VMs on same hardware<br/>3. Can be used to package applications and all OS dependencies into container                     | 1. Can only run apps designed for the same OS<br/>2. Cannot host a different guest OS<br/>3. Can only use native file systems<br/>4. Uses same resources as other containers |
    | Memory Virtualisation                 | VMM maintains shadow page tables in lock-step with the page tables.<br/> detail see below section                                                                                                                                                                                                                                                                     |                    |                                                                                                                                                            | 1. Adds additional management overhead                                                                                                                                       |
    - <img src="./docs/18.jpg" width="60%" height="30%" />  for Full virtualisation, Binary Translation
        - but in each case there can be some differences in rangs for each service see lecture 8.1 slides 15, 19
    - <img src="./docs/19.jpg" width="40%" height="30%" /> for Para-virtualisation, Hardware-assisted virtualisation
        differ in ring 0 service, see lecture 8.1 slides 16, 18
        - New Ring -1 for VMM supported Page tables, virtual memory mgt, direct memory access for high speed reads etc
        
5. Memory Virtualisation
    - <img src="./docs/20.jpg" width="40%" height="30%" />
        
        - In conventional case, page tables store the logical page number and physical page number mappings
    - <img src="./docs/21.jpg" width="40%" height="30%" />
        
        - In VMM case, VMM maintains shadow page tables in lock-step with the page tables. Additional management overhead is added.
    - Shadow Page Tables
        - VMM maintains shadow page tables in lock-step with the page tables
        - <img src="./docs/22.jpg" width="40%" height="30%" />
        - In this case, one OS represent in blue, the other in green
        - Disadv: Adds additional management overhead
            - Hardware performs guest -> physical and physical -> machine translation
6. Live migration
    - having continuity of service during data moving
    - Live Migration from Virtualisation Perspective/Live migration of virtual machines
        - <img src="./docs/30.jpg" width="40%" height="30%" />

### past exam
- > [2014 Q7] A) Define the following terms and their relevance to Cloud Computing:
    - > a. Hypervisor [1]
        - above
    - > b. Virtual machine [1]
        - A representation of a real machine using hardware/software that can host a guest operating system
    - > c. Machine image [1]
        - is a Compute Engine resource that stores all the configuration, metadata, permissions, and data from one or more disks required to create a virtual machine (VM) instance.
    - > d. Object Store [1]
        - is a strategy that manages and manipulates data storage as distinct units
    - > e. Volume Store [1]
        - Store = Storage
        - Volume storage is the virtual equivalent of a USB drive. A USB drive retains your data, whether it is plugged in or not. Manipulating the data on a USB drive requires that it is plugged into a computer and that it is mounted by the operating system. Your USB drive can be unplugged and plugged into another (newer, bigger, better) computer, but your USB drive can only ever be plugged in to one computer at a time. 
        - Equivalently a volume in your Nectar project can retain your data, whether it is attached to an instance or not. Manipulating the data on the volume requires that is attached to an instance, and that the file systems is mounted by the operating system. Your volume can be detached and attached to another (newer, bigger, better) instance, but your volume can only ever be attached to one instance at a time. 
    - > f. Key-pair [1]
        - A key pair consists of a private key and a public key.
- > [2013 Q5] A) Explain what is meant by the following terms:
    - > Virtual Machine Monitor/Hypervisor [1]
        - is a technology to provide virtualization by providing a virtualisation layer between the underlying hardware the virtual machines and guest operating systems it supports.
    - > Full virtualization [1]
        - allow an unmodified guest OS to run in isolation by simulating full hardware 
            - Guest OS has no idea it is not on physical machine
    - > Para-virtualization [1]
        - VMM/Hypervisor exposes special interface to guest OS for better performance. Requires a modified/hypervisor-aware Guest OS 
        - Can optimise systems to use this interface since not all instructions need to be trapped/dealt with
    - > Shadow page tables [1]
        - VMM (virtual machine monitar) keeps a mapping between what a vitual machine on the server rack you think that if you are dealing with address spaces and memory update. And it keeps a logical mapping so that all the instances think their own page tables which they don't. All of that is managed indirectly by the shadow page table.
    - > Explain how hardware virtualization and software virtualization can differ in their treatment of shadow page tables. [2]
        <!-- - hardware virtualization has less performance overheads
        - hardware virtualization has the ability to trap various sensitive calls and different software solutions to do that -->
        - Main issue is that the hardware does a lot of the management of shadow page tables and hence is faster but needs all calls to be trappable by hardware. Doing it via software virtualisation requires sensitive calls to be trapped and handled by the VMM which is slower. 
        - The VMM needs to keep shadow page tables synchronised with guest page tables. You might add para-virtualisation to hardware virtualization (the one has shadow page table) can improve things from a performance perspective.
    - > Explain the advantages and disadvantages of virtual machines. [2]
        - adv
            - reuse hardware and have multiple different OS running on the same physical system
        - disadv
            - performance overhead
            - privacy and security issue
            - virtual machine has slow startup time
    - > [2017 Q7 C [3]] Describe the typical steps that are required to support live migration of virtual machine instances using a Cloud facility such as the NeCTAR Research Cloud. [2]
        - picture above
- > [2016 Q5] A) Popek and Goldberg laid down the foundations for computer virtualization in their 1974 paper, Formal Requirements for Third Generation Architectures.
    - > a. Identify and explain the different types of classification of instruction sets for virtualization to occur according to the theorem of Popek and Goldberg. You should include the relationships between the instruction sets. [3]
        | -                       |                                                                                        |  |
        | ----------------------- | -------------------------------------------------------------------------------------- |
        | Privileged Instructions | instructions that trap if the processor is in user mode and do not trap in kernel mode |
        | Sensitive Instructions  | instructions whose behaviour depends on the mode or configuration of the hardware      |
        | Innocuous Instructions  | instructions that are neither privileged nor sensitive                                 |
        - relation = subset
            - For any conventional third generation computer, a virtual machine monitor may be constructed if the set of **sensitive instructions** for that computer is a subset of the set of **privileged instructions** i.e. have to be trappable
        - innocuous instructions do not need to be trapped and dealt with and hence can be considered separately.
    - > b. Describe how these principles are realized by modern virtual machine monitors/hypervisors. [2]
        | -                                 | Typical Virtualisation Strategy                                                                                                                                                                                         |  |
        | --------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
        | De-privileging (trap-and-emulate) | trap-and-emulate: VMM emulates the effect on system/hardware resources of privileged instructions whose execution traps into the VMM                                                                                    |
        | Primary/shadow structures         | 1. VMM maintains “shadow” copies of critical structures whose “primary” versions are manipulated by the GuestOS, e.g. memory page tables<br/>2. Primary copies needed to insure correct versions are visible to GuestOS |
        | Memory traces                     | Controlling access to memory so that the shadow and primary structure remain coherent                                                                                                                                   |
        - sensitive/privileged instructions (calls) have to be trapped and dealt with
    - > c. Explain the differences between full virtualization and para-virtualisation. Give an example of a hypervisor that uses full virtualization and an example of a hypervisor that uses paravirtualisation. [2]
        - full virtualization
            - allow an unmodified guest OS to run in isolation by simulating full hardware 
            - VMWare
        - para-virtualisation
            - VMM/Hypervisor exposes special interface to a modified/hypervisor-aware Guest OS for better performance.
            - Xen
    - >  d. Describe the role of a virtual machine manager/hypervisor with regards to memory management and shadow page tables. [3]
        - VMM maintains shadow page tables in lock-step with the page tables. Additional management overhead is added.
        - VMM emulates the effect on system/hardware resources of privileged instructions whose execution traps into the VMM
        - VMM maintains “shadow” copies of critical structures whose “primary” versions are manipulated by the GuestOS
        - Control access to memory so that the shadow and primary structure remain coherent


## Week 8.2 – OpenStack & Comparing and Contrasting AWS with NeCTAR Cloud
- Offers free and open-source software platform for cloud computing for <u>**IaaS**</u>
- Consists of interrelated components (services) that control / support compute, storage, and networking resources
- Often used through web-based dashboards, through command-line tools, or programmatically through ReSTful APIs

### Openstack architecture
- <img src="./docs/33.jpg" width="60%" height="30%" />

    - As a user, login in through Horizon to have access to cloud and get identity
        - identity is passed among the components
        - operation is restricted based on your identity and resource available
            - reformat other's disk
    - launch server/instance
        - identity is passed among the components
        - operation is restricted based on your identity and resource available
        - use pre-existing instance, use Ubuntu via Glance's image service
        - attach some storage 
            - object storage via Swift or
            - block storage via Cinder
        - setup firewall, ssh port via Neutron's Networking Services
    - **Identity works as a glue among components**

### Typically asynchronous queuing systems used (AMQP)
- <img src="./docs/29.jpg" width="60%" height="30%" />

    - AMQP: queueing service for load balance when large request comes
        - queue an instance creation request and starts when one is released

### Key Services
#### Keystone -- Identity Service
- Provides an authentication and authorization service fro OpenStack services
  - Tracks users/permissions
- Provides a catalog of endpoints for all OpenStack services
  - Each service registered during install
    - Know where they are and who can do what with them
  - Project membership
  - firewall rules
- Generic authorization system
  - More refer to week10 ==TODO==
#### Nova -- Compute Service
- Manages the lifecycle of compute instances in an OpenStack environment
- Responsibilities for virtual machines on demand, include 
  - spawning
  - scheduling
  - Decommissioning
- Virtualisation agnostic
  - Key point of success as it allows openStack works with **<u>any kind</u>** of virtualisation solution, including
    - XenAPI, Hyper-V, VMWare ESX
    - Docker
  - You are not binding with any specific solution
- ==(The following not covered in detail in the lecture)==
- API
  - Nova-api
    - Accepts/responds to end user API calls
    - Supports openStack Compute & EC2 & admin APIs
  - Compute Core
    - Nova-computer
      - Daemon that creates/terminates VMs through hypervisor APIs
    - Nova-scheduler
      - schedules VM instance requests from queue and determines which server host to run
    - Nova-conductor
      - Mediates interactions between compute services and other components, e.g. image database
  - Networking
    - Nova-network
      - Accepts network tasks from queue and manipulates network, e.g. changing IP table rules
  - <img src="./docs/34.jpg" width="60%" height="30%" />
    
    - I need a VM with: 64Gb memory, 8vCPUs, in Melbourne, running Ubuntu 12.04
        - The call comes in through load balancer and buffered
        - nova-api Accepts/responds to end user API calls
        - Nova-scheduler schedules VM instance requests from queue and determines which server host to run
        -  Nova-conductor mediates interactions between compute services and other components, e.g. image database
#### Swift - Object Storage
- Stores and retrieves arbitrary unstructured data objects via ReSTful API
  - e.g.: VM images and data
  - This service can be used to access arbitrary unstructured data
- Fault tolerant with data replication and scale-out architecture
  - Available from anywhere; persists until deleted
  - Allows to write objects and files to multiple drives, ensuring the data is replicated across a server cluster
- Can be used with/without **<u>Nova</u>**
- Client/admin support
  - Swift client allows users to submit commands to ReST API through command line clients to configure/connect object storage to VMs
#### Cinder -- Block Storage
- Provides persistent block storage to virtual machines (instances) and supports creation and management of block storage devices
- Cinder access associated with a VM
  - Cinder-api
    - routes requests to cinder-volume
  - Cinder-volume
    - interacts with block storage service and scheduler to read/write requests; can interact with multiple flavours of storage (flexible driver architecture)
  - Cinder-scheduler
    - selects optimal storage provider node to create volumes (ala nova-scheduler)
  - Cinder-backup
    - provides backup to any types of volume to backup storage provider
#### Glance -- Image Service
- Accepts requests for disk or server images and their associated metadata (from **<u>Swift</u>**) and retrieves / installs (through **<u>Nova</u>**)
  - Find the image at **<u>Swift</u>**, but getting the image at **<u>Glance</u>**
- API
  - Glance-api
    - Image discovery, retrieval and storage requests
  - Glance-registry
    - Stores, processes and retrieves metadata about images, e.g. size and type
      - Ubuntu 14.04
      - My last good snapshot
        - I (the owner) can control who can access the snapshot using **<u>Keystone</u>**
#### Neutron -- Networking Services
- Supports networking of OpenStack services
  - subnet
  - Network in and out
  - Network security group
- Offers an API for users to define networks and the attachments into them,
    - e.g.: 
        - switches
        - routers
- Pluggable architecture that supports multiple networking vendors and technologies
- Neutron-server
  - accepts and routes API requests to appropriate plug-ins for action
  - Port management, e.g. default SSH, VM-specific rules, ...
  - More broadly configuration of availability zone networking, e.g. subnets, DHCP, ...
#### Horizon -- Dashboard Service
- Provides a web-based self-service portal to interact with underlying OpenStack services, such as 
  1. launching an instance
  2. assigning IP addresses
  3. configuring access controls
- Based on Python/Django web application
- Requires Nova, Keystone, Glance, Neutron
- Other services optional...
#### Trove -- Database Service
- Provides scalable and reliable Cloud database (DBaaS) functionality for both <u>relational</u> and <u>non-relational</u> database engines
- Benefits
  - Resource isolation
  - high performance
  - automates deployment
  - config
  - patching
  - backups
  - restores
  - monitoring
  - ...
- Use image service for each DB type and trove-manage to offer them to tenants/user communities
#### Sahara -- Data Processing Service
- Provides capabilities to provision and scale Hadoop clusters in OpenStack by specifying parameters such as Hadoop version, cluster topology and node hardware details
- User fills in details and Sahara supports the automated deployment of infrastructure with support for addition/removal of worker nodes on demand
#### Heat -- Orchestration Service
- Template-driven service to manage lifecycle of applications deployed on Openstack
- Stack
  - Another name for the template and procedure behind creating infrastructure and the required resources from the template file
- Can be integrated with automation tools such as Chef
  - Puppet
  - Ansible
- Heat details
    - heat_template_version: allows to specify which version of Heat, the template was written for (optional)
    - Description: describes the intent of the template to a human audience (optional)
    - Parameters: the arguments that the user might be required to provide (optional)
    - Resources: the specifications of resources that are to be created (mandatory)
    - Outputs: any expected values that are to be returned once the template has been processed (optional)

### Creating Stacks in MRC/NeCTAR
1. Create the template file according to your requirements
2. Provide environment details (name of key file, image id, etc)
3. Select a name for your stack and confirm the parameters
4. Make sure rollback checkbox is marked, so if anything goes wrong, all partially created resources get dumped too
5. Wait for the magic to happen! 

### past exam
- > [sample Q3 A] The NeCTAR Research Cloud is based on the OpenStack technology. Describe the role and features of the following OpenStack components:
    - Nova    [1] (one of below)
        - Manages the lifecycle of compute instances in an OpenStack environment
        - Responsibilities for virtual machines on demand, include spawning, scheduling and decommissioning
    - Horizon [1]
        - Provides a web-based self-service portal to interact with underlying OpenStack services, such as launching an instance, assigning IP addresses and configuring access controls.
    - Heat    [1]
        - Template-driven service to manage lifecycle of applications deployed on Openstack
    - Glance [1]
        - Accepts requests for disk or server images and their associated metadata (from **<u>Swift</u>**) and retrieves / installs (through **<u>Nova</u>**)
    - Swift    [1]
        - Stores and retrieves arbitrary unstructured data objects via ReSTful API, e.g.: VM images and data
    - Keystone [1]
        - Provides an authentication and authorization service fro OpenStack services
        - Tracks users/permissions
        - Provides a catalog of endpoints for all OpenStack services
    - Neutron [1]
        - Supports networking of OpenStack services
        - Offers an API for users to define networks and the attachments into them, e.g.:  switches, routers
        - Port management, e.g. default SSH, VM-specific rules, ...
- > [sample Q3 B]  Describe the interplay between these components that allows a researcher to create an instance of a virtual machine through a pre-existing snapshot from a non-public NeCTAR Cloud image, e.g. a snapshot created by a user. [3]
    - Authenticate via Keystone. provide unimelb id and password for MRC. And Keystone identity enable us to use other components in the system so that the system knows that's us using them.
    - Daemon that creates/terminates VMs through hypervisor APIs via Nova-computer
    - schedules VM instance requests from queue and determines which server host to run via Nova-scheduler
    - Mediates interactions between compute services and other components, e.g. image database via Nova-conductor
    - looking up resoueces required via Swift/Glance
    - preparing the VM on machine required
- > Describe the approach that would be taken using the openStack Heat service for deployment of SaaS solutions onto the Cloud. [2]
    1. Create the template file according to your requirements
    2. Provide environment details (name of key file, image id, etc)
    3. Select a name for your stack and confirm the parameters
    4. Make sure rollback checkbox is marked, so if anything goes wrong, all partially created resources get dumped too
    5. Wait for the magic to happen! 

### 往年考试题目翻译

> [样题 Q3 A] NeCTAR 研究云基于 OpenStack 技术。请描述以下 OpenStack 组件的作用与特性：

- **Nova [1]**  
  - 管理 OpenStack 环境中计算实例的生命周期  
  - 负责按需处理虚拟机，包括创建、调度和销毁等操作  

- **Horizon [1]**  
  - 提供基于 Web 的自助门户，用户可与底层 OpenStack 服务交互，例如启动实例、分配 IP 地址以及配置访问控制等  

- **Heat [1]**  
  - 通过模板驱动的服务，用于管理部署在 OpenStack 上的应用程序生命周期  

- **Glance [1]**  
  - 接收磁盘或服务器镜像及其相关元数据的请求（来自 **Swift**）  
  - 通过 **Nova** 检索并安装镜像  

- **Swift [1]**  
  - 通过 ReSTful API 存储和检索任意非结构化数据对象，例如：虚拟机镜像和数据文件  

- **Keystone [1]**  
  - 为 OpenStack 服务提供身份认证和授权服务  
  - 跟踪用户及其权限  
  - 提供所有 OpenStack 服务的端点目录  

- **Neutron [1]**  
  - 为 OpenStack 服务提供网络支持  
  - 提供 API，让用户能够定义网络及其连接，例如交换机、路由器等  
  - 管理端口，例如默认 SSH、虚拟机专属规则等  

---

> [样题 Q3 B] 描述上述组件如何协作，使研究人员能够通过非公开 NeCTAR 云镜像（例如用户创建的快照）创建虚拟机实例。[3分]

1. 通过 Keystone 进行身份认证，使用 unimelb 账号和密码登录 MRC；Keystone 身份认证使我们能够访问系统中的其他组件，让系统知道是我们在使用它们。  
2. Nova-compute 守护进程通过 hypervisor API 创建/销毁虚拟机  
3. Nova-scheduler 从请求队列中调度虚拟机实例请求，并决定在哪台服务器主机上运行实例  
4. Nova-conductor 协调计算服务与其他组件之间的交互，例如连接镜像数据库  
5. 通过 Swift/Glance 查找所需资源  
6. 在目标机器上准备好虚拟机实例  

---

> 描述使用 OpenStack Heat 服务将 SaaS 解决方案部署到云上的方法。[2分]

1. 根据部署需求创建模板文件  
2. 提供环境详情（如密钥文件名称、镜像 ID 等）  
3. 为你的栈（stack）选择一个名称，并确认各项参数  
4. 勾选“回滚”选项，这样如果部署失败，系统会自动删除所有已部分创建的资源  
5. 然后静待“魔法”发生（即 Heat 自动完成部署）


## Week 8.3 - Serverless (Function as a Service (FaaS))
1. Why Functions?
    - A function in computer science is typically a piece of code that takes in parameters and returns a value
    - Functions are the founding concept of functional programming - one of the oldest programming paradigms
    - Why they are used in Faas?
    - Functions in server less comuting are:
        - free of side-effects, 
            - What is it?
                - A function that does not modify the state of the system
                    - e.g.: a function that takes an image and returns a thumbnail of that image
                - A function that changes the system somehow is not side-effect free
                    - e.g.: a function that writes to the file system the thumbnail of an image
            - How Side-effect free benefits parallel execition?
                - Side-effect free functions can be run in parallel, and are guaranteed to return the same output given the same input
            - How it benefits FaaS?
                - Side-effects are almost inevitable (不可避免的) in a relatively complex system. 
                Therefore consideration must be given on how to make functions with side effects run in parallel, as typically required in FaaS environments.
        - ephemeral (短暂的;瞬息的),
            - Synchronous/Asynchronous Functions
            - Relationship to FaaS
                - By default functions in FaaS are synchronous, hence they return their result immediately
                - However, there may be functions that take longer to return a result, hence they incur timeouts and lock connections with clients in the process, hence it is better to transform them into asynchronous functions
                    - a publish/subscribe pattern involving a queuing system can be used to deal with asynchronous functions
            - How them work?
                | Function               | How                                                                                                                          |
                | ---------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
                | Synchronous functions  | return their result immediately                                                                                              |
                | Asynchronous functions | return a code that informs the client that the execution has started, and then trigger an event when the execution completes |
        - stateless, 
            - What is it?
                - A subset of functions with side-effects is composed of stateful functions 
                    |                    |                                                                                                                               | e.g.                                                                                                                                               |
                    | ------------------ | ----------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
                    | stateful function  | is one whose output changes in relation to internally stored information (hence its input cannot entirely predict its output) | a function that adds items to a "shopping cart" and retains that information internally                                                            |
                    | stateless function | is one that does not store information internally                                                                             | adding an item to a "shopping cart" stored in a DBMS service and not internally would make the function above stateless, but not side-effect free. |
            - Why it is important for FaaS?
                - Because there are multiple instances of the same function, and there is no guarantee the same user would call the same function instance twice.
        - which make them ideal for 
            - parallel execution and 
            - rapid scaling-up and -down
            - Functions are free of side-effects, ephemeral, and stateless, which make them ideal for parallel execution and rapid scaling-up and -down, hence their use in FaaS
2. Function & FaaS
    - Side effects
    - stateful & stateless
    - Synchronous/Asynchronous Functions
3. What is Function as a Service (FaaS)?
    - FaaS is also know as Serverless computing
    - FaaS is an extreme form of microservice architecture
    - The idea behind Serverless/FaaS is to develop software applications without bothering with the infrastructure (especially scaling-up and down as load increases or decreases). Therefore, it is more Server-unseen than Server-less
    - What does it do?
        - A FaaS service allows functions to be added, removed, updated, executed, and auto-scaled
4. Why we need Faas?
    | Reason                         | How                                                         |
    | ------------------------------ | ----------------------------------------------------------- |
    | Simpler deployment             | the service provider takes care of the infrastructure       |
    | Reduced computing costs        | only the time during which functions are executed is billed |
    | Reduced application complexity | due to loosely-coupled architecture                         |
5. FaaS application
    - Functions are triggered by events
    - Functions can call each other
    - Functions and events can be combined to build software applications
    - Combining event-driven scenarios and functions resembles how User Interface software is built: user actions trigger the execution of pieces of code
    - E.g.: FaaS Services and Frameworks
        - Amazon’s AWS Lambda
        - Google Cloud Functions
        - Azure Functions by Microsoft
    - proprietary FaaS services v.s. open-source FaaS frameworks
        - open-source FaaS frameworks can be deployed on your cluster, peered into, disassembled, and improved by you.

### 1. 为什么使用函数（Functions）？
- 在计算机科学中，函数通常是指一个接受参数并返回结果的代码片段
- 函数是函数式编程的基础概念——这是最古老的编程范式之一
- 那么，为什么在 FaaS 中使用函数呢？

在无服务器计算中，函数具备以下特性：
#### - side-effect free function 无副作用函数
- **什么是副作用？**  
  - 不改变系统状态的函数就是无副作用的函数  
    - 例：一个函数接收一张图片并返回缩略图  
  - 改变系统状态的函数则是有副作用的  
    - 例：一个函数将缩略图写入文件系统

- **无副作用如何有利于并行执行？**  
  - 无副作用的函数可以并行运行，并且在相同输入下能保证返回相同的输出

- **无副作用对 FaaS 的意义？**  
  - 在较复杂的系统中，副作用几乎不可避免  
  - 因此需要考虑如何让具有副作用的函数在并行执行时仍然安全可靠，而这是 FaaS 环境中的常见需求

#### - stateful/stateless function 有状态和无状态函数
- **什么是无状态？**
    - 有副作用的函数中有一类是有状态的
    - **有状态函数**：输出依赖于内部存储的信息，输入无法完全预测输出，**不适合FaaS**  
      - 例：一个函数将商品添加到购物车，并内部保存该信息。例如保存苹果进去，内部变成苹果；再输入香蕉，变成苹果和香蕉
    - **无状态函数**：不在内部保存信息  
      - 例：一个函数将商品添加到保存在数据库中的购物车，而不是保存在内部变量中 —— 这使函数变得无状态，但仍然有副作用
    - **无副作用 不等于 无状态，无副作用函数不仅仅不保存状态，还不影响外部世界**

- **无状态性对 FaaS 的重要性？**  
  - 因为相同函数会以多个实例运行，不能保证用户总是连接到同一个函数实例


#### - 同步/异步函数
- **与 FaaS 的关系：**
  - **默认情况下，FaaS 中的函数是同步执行的**，即立即返回结果  
  - 某些函数运行时间较长，可能导致超时和客户端连接阻塞，故应转换为异步函数  
    - 可通过发布/订阅（pub/sub）模式和队列系统实现异步处理

- **它们是如何工作的？**
  - 同步函数：立即返回结果
  - 异步函数：返回一个状态码表示函数已开始执行，并在完成时触发事件通知客户端

#### - 短暂函数 Ephemeral Functions
- 执行时间很短的函数

#### - 这些特性使函数特别适合：
  - 并行执行  
  - 快速的扩展与收缩  
  - 无副作用、短暂、无状态的函数最适合用于 FaaS

---

### 2. 函数与 FaaS 的关系
- 副作用
- 有状态 / 无状态
- 同步 / 异步函数

---

### 3. 什么是函数即服务（FaaS）？
- FaaS 也被称为无服务器计算（Serverless）
- FaaS 是微服务架构的一种极端形式
- 无服务器计算的理念是：**开发者专注于业务逻辑，无需关心基础设施（尤其是扩容/缩容）**
  - 所以，“Serverless”更像是“看不见服务器”而非“没有服务器”

- **FaaS 提供的能力：**
  - 添加、删除、更新、执行函数  
  - 函数可以自动伸缩

---

### 4. 为什么我们需要 FaaS？
- 简化部署  
  - 服务提供商负责管理底层基础设施
- 降低计算成本  
  - 只为函数执行期间计费
- 降低应用复杂性  
  - 通过松耦合架构实现

---

### 5. FaaS 应用场景
- 函数由事件触发
- 函数之间可以互相调用
- 函数与事件结合可以构建完整软件应用
- 将事件驱动与函数结合类似于构建用户界面应用：用户操作触发特定代码的执行

- 例如：常见的 FaaS 服务与框架
  - 亚马逊 AWS Lambda
  - Google Cloud Functions
  - 微软 Azure Functions

- **专有 FaaS 服务 vs 开源 FaaS 框架**
  - 开源框架可以部署在自己的集群中，供你研究、拆解和改进


#### - 单体应用（Monolithic Application）

- 一个标准的 Web 应用可以如下满足需求：

    一个定时器调用 API 的采集端点，用于从 BoM（气象局）和空气质量监测站采集数据

    采集到的数据被转换成统一格式

    转换后的数据被插入到 ElasticSearch 中

    另一个端点允许客户端应用请求平均温度（通过 ElasticSearch 查询计算）

- 单体应用的特点：

    - 应用只能垂直扩展（使用更强大的虚拟机），无法水平扩展到集群的其他节点 **vertically scale**

    - 所有组件在运行时都同时加载到内存中，占用比实际需要更多的资源 **all parts load in the same time**

    - 如果应用的某个部分发生严重故障（如 Java 内存溢出），会导致整个应用崩溃 **one part malfunction, bring down whole app**

    - 所有组件高度耦合（大多用相同语言开发），因此对某部分代码的更改可能引发一连串连锁反应（例如升级某个库）**components tightly coupled**

- 无服务器（Serverless）版本的应用

    每项功能都由一个独立的函数提供 one functionality <- one function

    大多数函数之间通过异步消息队列通信，而不是直接通信  communicate via message queue

    函数仅在需要时才加载 load only  when need

    **某个函数出现故障时，不会影响整个应用** one malfunction, no effect to others

    可以在多个节点上部署相同函数的副本，实现水平扩展 horizontally scale

    函数可以使用不同编程语言实现，仍可正常协作 different language

    函数可以运行在不同的运行环境中（例如 Python 3.9 和 3.10），互不影响 run in different environment

    应用整体更加易于修改、健壮、资源利用率更高 more robust , easy to change


#### - Fission
- Fission 的核心概念
    - 函数（Function）：一个可以独立被触发器调用并返回结果的软件模块（在 Docker 容器中运行）
    - 环境（Environment）：函数运行的 Docker 镜像。环境是与语言相关的，包含 HTTP 服务器和一些基础库，但可以通过包（Packages）进行自定义
    - 包（Package）：用于自定义环境的一组文件（通常是源代码或已编译的二进制文件）
    - 触发器（Trigger）：触发函数执行的事件，例如：
        - HTTP 请求
        - 定时器
        - 队列中的消息发布
        - Kubernetes 任务完成
    - 路由器（Router）：负责将 HTTP 请求路由到对应函数的组件
    - 规范文件（Specifications / Specs）：定义 Fission 应用各组件的一组 YAML 文件。与 CLI 命令相比，使用规范文件可以更轻松地部署和维护应用

- 环境、包与函数（Environments, Packages, and Functions）
    - 一个函数在 Pod 上运行，但实际上是在 Pod 的 Docker 容器 中执行的，而该容器是基于某个 Docker 镜像 构建的。

    - 这个 Docker 镜像就是 Fission 中所谓的 环境（Environment）。

    - 对环境的定制通过 包（Package） 来完成。

    - 例如：

        - Python 是一种环境（通常在 Fission 中，每种编程语言对应一个环境）

        - 如果要在基础 Python 环境中添加一些库（比如 ElasticSearch 客户端），就需要 创建一个包 并将其添加到函数中，从而在创建函数时扩展该环境的功能。


# Fission 中的函数执行器（Function Executors）

Fission 以两种不同的方式执行函数：

## ● PoolManager 模式 低延迟，易过载

- Fission 为**每个环境管理一个 Pod 池**。 
- 当一个函数被调用时，函数包会被加载到 Pod 中并被执行。
- 每次只运行一个函数实例。
- 优点：
  - 最小化函数执行的延迟（**热启动**）。**minimum latency**
- 缺点：
  - 无法很好地应对高负载。**cannot hold heavy load, may be obverloaded**
  - 虽然函数是多线程的，能够同时处理多个请求，但仍可能出现过载。

## ● NewDeploy 模式

- 随着负载的增加，会创建新的 Pod。
- 优点：
  - 允许同一个函数的多个实例同时运行，更适应高负载情况。 **better for heavy load**
  - 额外的函数实例会根据某些指标（如 CPU 使用率）自动创建。
- 缺点：
  - 延迟较高（默认是**冷启动**）。
- 为了减少延迟，可以设置 NewDeploy 执行器始终保持一个 Pod 常驻运行。

> 🛠️ **默认执行器：** Fission 默认使用的是 **PoolManager** 模式。

# Fission 的命令行工具（CLI）
## ● 常见命令示例

- 列出环境：`fission environment list`
- 列出包：`fission packages list`
- 查看日志 fission function log --name <函数名> --namespace <命名空间>
- 调用函数 fission function test --name <函数名> --namespace <命名空间>
- 创建函数 fission function create --name hello --env python --code hello.py


Fission Websockets 支持
    ● 用于长时间任务的异步通信
    HTTP 请求是同步的，不适合长时间任务。WebSocket 提供了一个双向非阻塞通道。

    示例场景：浏览器客户端发起 ML 任务

    - 客户端通过 HTTP POST 请求发起任务。
    - Fission 将任务请求写入队列，返回 HTTP 202（接受请求）。
    - 客户端建立 WebSocket 通道。
    - 后端 Fission 函数从队列读取并执行任务。
    - 任务完成后，通过 WebSocket 通道返回结果。

- Fission 规范（Specifications）
    ● 为什么使用 Specs？

    使用 CLI 命令逐一管理组件效率低，违背了两个云原生核心原则：

    基础设施即代码（Infrastructure as Code）

    声明式应用管理（Declarative Application Management）



### past exam
- > [sample Q7] A) In the context of Cloud, what is meant by serverless computing? [1]
    - A way of developing applications as **collections of functions** that are deployed on a computing infrastructure without the need to manage it.
- > [sample Q7] B) List three reasons why it may be beneficial to choose a serverless solution. [3]
    | -                              | Reason                                                      | How |
    | ------------------------------ | ----------------------------------------------------------- |
    | Simpler deployment             | the service provider takes care of the infrastructure       |
    | Reduced computing costs        | only the time during which functions are executed is billed |
    | Reduced application complexity | due to loosely-coupled architecture                         |
        - "Why we need Faas?" above
- > [sample Q7] C) Discuss the role of functions in serverless computing. Your answer should include key properties of functions that make them suitable for serverless environments.  [3]
    - Serverless applications are composed of functions
    - key properties of functions that make them suitable for serverless environments:
        - Functions in server less comuting are:
            - free of side-effects
            - ephemeral
            - stateless
            - which make them ideal for 
                - parallel execution and 
                - rapid scale up and scale down
        - Functions are triggered by events
        - Functions can call each other
### 历年考题（Past Exam）

> [示例题 Q7] A) 在云计算的背景下，什么是无服务器计算（serverless computing）？[1]

- 一种将应用程序开发为**函数集合**的方式，这些函数部署在计算基础设施上，而**无需自行管理该基础设施**。

---

> [示例题 Q7] B) 请列出选择无服务器解决方案的三个好处。[3]

- **更简单的部署**：服务提供商负责基础设施的管理  
- **更低的计算成本**：仅为函数执行期间的时间付费  
- **更低的应用复杂度**：由于其松耦合架构，简化了系统设计  

---

> [示例题 Q7] C) 论述函数在无服务器计算中的作用。你的回答应包括使函数适合于无服务器环境的关键属性。[3]

- 无服务器应用由多个函数组成
- 函数具有以下关键特性，使其非常适合无服务器环境：
  - **无副作用**（free of side-effects）
  - **短暂存在**（ephemeral）
  - **无状态**（stateless）
  - 这些特性使函数适用于：
    - **并行执行**
    - **快速扩展和收缩**
  - 函数通过事件触发执行
  - 函数之间可以相互调用





## Workshop week8: OpenFaaS
### Properties
- Functions are passed a request as an object in the language of choice and return a response as an object
- OpenFaaS \& container
    - Open-source framework that uses Docker containers to deliver FaaS functionality
    - role of container technologies and their relationship with functions:
        - Every function in OpenFaaS is a Docker container, ensuring loose coupling between functions
            - Function can be written in different languages and mixed freely
    - OpenFaaS can use either Docker Swarm or Kubernetes to manage cluster of nodes on which functions run
    - By using Docker containers as functions, OpenFaaS allow to freely mix different languages and environments at the cost of **<u>decreased performance</u>** as containers are inherently heavier than threads
        - However, it is possible to reduce the size to only a few MBs
### Auto-scalability and OpenFaaS
- OpenFaaS can add more Docker containers when a function is called more often, and remove containers when the function is called less often 
- The scaling-up (and down) of functions can be tied to memory or CPU utilization as well (currently only on Kubernetes-managed clusters though)

### past exam
- > [sample Q7] D) OpenFaaS is an open source framework that can be used to deliver serverless computing solutions. Discuss the role of container technologies such as Docker in OpenFaaS and their relationship with functions and how they might be used to support auto-scaling.  [3]
    - Every function in OpenFaaS is a Docker container, ensuring loose coupling between functions
    - When the load increases, OpenFaaS add more container executing the same function.
    - When the load decreases, OpenFaaS remove containers for the function is called less often.





## Week 9 - Big Data Analytics
1. Why we need it?
    - There would not be much point in amassing vast amount of data without being able to analyse it, hence the blossoming of large-scale business intelligence and more complex machine learning algorithms. 
    - Overlapping among business intelligence, machine learning, statistics and data mining.
        - Just use big data analytics
2. What is it?
    - There is a good deal of overlap and confusion among terms such as business intelligence, machine learning, statistics, and data mining. For the sake of clarity, we just use the more general term (big) data analytics
3. Examples of Analytics
    |                     |
    | ------------------- |
    | Full-text searching |
    | Aggregation of data |
    | Clustering          |
    | Sentiment analysis  |
    | Recommendations     |
4. Challenges of Big Data Analytics
    - A framework for analysing big data has to distribute both data and processing over many nodes, which implies:
        | imply                                                 |                                                                           |
        | ----------------------------------------------------- | ------------------------------------------------------------------------- |
        | Reading and writing distributed datasets              |
        | Preserving data in the presence of failing data nodes |
        | Supporting the execution of MapReduce tasks           |
        | Being fault-tolerant                                  | a few failing compute nodes may slow down the processing, but not stop it |
        | Coordinating the execution of tasks across a cluster  |
5. Tools for Analytics:
    - Apache Hadoop
    - Apache Spark
### Apache Hadoop
1. How it works?
    - Apache Hadoop started as a way to distribute files over a cluster and execute MapReduce tasks, but many tools have now been built on that foundation to add further functionality
2. Components
    - Hadoop Distributed File System (HDFS)
    - Hadoop Resource Manager (YARN)
2. Hadoop Distributed File System (HDFS)
    - What is it?
        - The core of Hadoop is a fault tolerant file system that has been explicitly designed to span many nodes
    - HDFS blocks v.s. blocks
        - HDFS blocks are much larger than blocks used by an ordinary file system (say, 4 KB versus 128MB)
        - Why?
            |                                                                         | How achieve it?                                                                |
            | ----------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
            | Reduced need for memory to store information about where the blocks are | metadata                                                                       |
            | More efficient use of the network                                       | with a large block, a reduced number network connections needs to be kept open |
            | Reduced need for seek operations on big files                           |
            | Efficient when most data of a block have to be processed                |
    - HDFS Architecture
        - A HDFS file is a collection of blocks stored in datanodes, with metadata (such as the position of those blocks) that is stored in namenodes
        - <img src="./docs/23.png" width="60%" height="50%" />
    - The HDFS Shell
        - Why we need it?
            - Managing the files on a HDFS cluster cannot be done on the operating system shell
                - hence a custom HDFS shell must be used.
        - The HDFS file system shell replicates many of the usual commands (ls, rm, etc.), with some other commands dedicated to loading files from the operating system to the cluster (and back)
3. The Hadoop Resource Manager (YARN)
    - What is it/What does it do?
        - YARN deals with Executing MapReduce jobs on a cluster
            - It is composed of a central ***Resource Manager*** and
            - Many ***Node Managers*** that reside on slave machines
    - Every time a MapReduce job is scheduled for execution on a Hadoop cluster, YARN starts an **<u>Application Master</u>** that negotiates resources with the **<u>Resource Manager</u>** and starts Containers on the slave nodes
        - Containers are the processes where the actual processing is done
5. Programming on Hadoop
### Apache Spark
1. Why Spark not Hadoop?/Spark v.s. Hadoop
    - While Hadoop MapReduce works well, it is geared towards performing relatively simple jobs on large datasets.
        - While the execution order of Hadoop MapReduce is fixed, the lazy evaluation of Spark allows the developer to stop worrying about it, and have the Spark optimizer take care of it. 
        - In addition, the driver program can be divided into steps that are easier to understand without sacrificing performance (as long as those steps are composed of transformations).
    - However, when complex jobs are performed, we would like
        - Caching data in memory
        - Having finer-grained control on the execution of the jobs
    - Spark was designed to 
        - reduce the latency inherent in the Hadoop approach for the execution of MapReduce job
        - How?
            - The transformations in the program use lazy evaluation, hence Spark has the possibility of optimizing the process
    - Spark can operate within the Hadoop architecture, using YARN and Zookeeper to 
        - Manage computing resources
        - Storing data on HDFS
    - Spark has a tightly-coupled nature of its main components
    - Spark has a cluster manager of its own, but it can work with other cluster managers, such as YARN or MESOS.
2. Spark Architecture
    - One of the strong points of Spark is the tightly-coupled nature of its main components
        - <img src="./docs/24.jpg" width="60%" height="50%" />
    - Spark ships with a cluster manager of its own, but it can work with other cluster managers, such as YARN or MESOS.
3. The Spark Shell
    - allows to send commands to the cluster interactively in either Scala or Python.
    - While the shell can be extremely useful, it prevents Spark from deploying all of its optimizations, leading to poor performance.
4. Programming on Spark
    - Lecture 09:: 00:34:24
5. Spark Runtime Architecture
    - Applications in Spark are composed of different components including
      - Job
        - The data processing that has to be performed on a dataset
        - the overall processing that Spark is directed to perform by a driver program
      - Task
        - A single operation on a dataset
        - a single transformation operating on a single partition of data on a single node
      - Stage
        - Set of task operating on a single partition
      - Stage \& performance
        - The fewer the number of stages, the faster the computation (shuffling data across the cluster is slow)
      - Stage \& Job
        - A job is composed of more than one stage when data are to be transferred across node
      - Executors
        - The processes in which tasks are executed
      - Cluster Manager
        - The process assigning tasks to executors
      - Driver program
        - The main logic of the application
      - Spark application
        - Driver program + Executor
      - Spark Context
        - The general configuration of the job
            - The **deployment is set in the Stpark Context**, which is also used to set the configuration of a Spark application, including the cluster it connects to in cluster mode.
                -  For instance, this hard-coded Spark Context directs the execution to run locally, using 2 threads (usually, it is set to the number of cores): 
                    - sc = new SparkContext(new SparkConf().setMaster("local[2]"));
                - This other hard-coded line directs the execution to a remote cluster:
                    - sc = new SparkContext(new SparkConf().setMaster("spark://192.168.1.12:6066"));
            - Spark Contexts can also be used to **tune the execution** by setting the memory, or the number of executors to use.  
    - These different components can be arranged in **<u>three</u>** different deployment modes (below) across the cluster
    - Spark Runtime Mode
        - Local Mode
            - In local mode, every Spark component runs within the same JVM. However, the Spark application can still run in parallel, as there may be more than on executor active
            - When used?
                - Good for developing and debugging
        - Cluster Mode
            - In cluster mode, every component, including the driver program, is executed on the cluster. Upon launching, the job can run autonomously. 
            - When used?
                - This is the common way of running non-interactive Spark jobs.
        - Client Mode
            - The driver program talks directly to the executors on the worker nodes. Therefore, the machine hosting the driver program has to be connected to the cluster until job completion.
            - When used? 
                - Client mode must be used when the applications are interactive, as happens in the Python or Scala Spark shells.
5. Caching Intermediate Results
    - rdd.persist(storageLevel) can be used to save an RDD either in memory and/or disk. 
        - The storageLevel can be tuned to a different mix of use of RAM or disk to store the RDD
        - since RDDs are immutable, 
            - the result of the final transformation is cached, not the input RDD. 
            - In other words, when this statement is executed
                - rddB = rddA.persist(DISK_ONLY)
                - only rddB has been written to disk.
6. Resilient Distributed Dataset (RDDs) (Central to Spark)
    - What is it?
        - the way data are stored in Spark during computation, and understanding them is crucial to writing programs in Spark:
            |             | What?                                                                              |
            | ----------- | ---------------------------------------------------------------------------------- |
            | Resilient   | data are stored redundantly, hence a failing node would not affect their integrity |
            | Distributed | data are split into chunks, and these chunks are sent to different nodes           |
            | Dataset     | a dataset is just a collection of objects, hence very generic                      |
    - Properties of RDDs
        - RDDs are
            | Property         |                                                                                                                                                                                                                                                                                                                       | benefit                                                                                                   |
            | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
            | immutable        | once defined, they cannot be changed                                                                                                                                                                                                                                                                                  | simplifies parallel computations on them, and <br/>is consistent with the functional programming paradigm |
            | transient        | they are meant to be used only once, then discarded (but they can be cached, if it improves performance)                                                                                                                                                                                                              |
            | lazily-evaluated | the evaluation process happens only <br/> - when data cannot be kept in an RDD, as when the number of objects in an RDD has to be computed, <br/> - or an RDD has to be written to a file (these are called actions), but <br/> - not when an RDD are transformed into another RDD (these are called transformations) | optimizing the process                                                                                    |
            - The transformations in the program use lazy evaluation, hence Spark has the possibility of optimizing the process
    - How to Build an RDD?
        - created out of data stored elsewhere (HDFS, a local text file, a DBMS)
        - created out of collections too, using the parallelize function
    - RDD variable
        - are just placeholders until the action is encountered. Remember that the Spark application is not just the driver program, but all the RDD processing that takes place on the cluster
    - RDD Transformations
        - rdd.filter(lambda) selects elements from an RDD
        - rdd.distinct() returns an RDD without duplicated elements
        - rdd.union(otherRdd) merges two RDDs
        - rdd.intersection(otherRdd) returns elements common to both
        - rdd.subtract(otherRdd) removes elements of otherRdd
        - rdd.cartesian(otherRdd) returns the Cartesian product of both RDDs
    - RDD Action
        - rdd.collect() returns all elements in an RDD
        - rdd.count() returns the number of elements in an RDD
        - rdd.reduce(lambda) applies the function to all elements repeatedly, resulting in one result (say, the sum of all elements. Not to be confused with the reduceByKey transformation)
        - rdd.foreach(lambda) applies lambda to all elements of an RDD

### past exam
- > [2014 Q5] B) Apache Hadoop is a software framework that enables processing of large data sets.
    - > a. Explain the role of Hadoop Distributed File System (HDFS) in supporting the Apache Hadoop framework. [2]
        - HDFS has blocks existing on nodes and there is a name node which contains the meta data about which block is running.
        - HDFS is a fault tolerant file system that has been explicitly designed to span many nodes
    - > b. Describe the process by which Apache Hadoop supports fault tolerant data processing. [2]
        - HDFS has blocks existing on nodes and there is a name node which contains the meta data about which block is running and if one of the nodes fails then the data is still available somewhere else in the system load balanced. And it will try to rebalnce itself.
- > [sample Q4] D) Describe the three different Apache SPARK runtime modes:    
    - > Local [1]
        - The driver program and the executors are all hosted on the same computer (no need for a cluster manager).
        - The Spark appplication is hosted on the same computer.
    - > Cluster [1]
        - The cluster manager, driver program and the executors are all hosted on the cluster.
        - The cluster manager and Spark appplication is hosted on the cluster.
    - > Client [1]
        - The driver program is hosted on the same computer that is not part of the cluster, while the cluster manager and executors are hosted on the cluster.
- > [2017 Q2] B What is the Apache Hadoop Resilient Distributed Dataset (RDD) operation type that triggers RDD evaluations? Which operation type does not trigger RDD evaluations? [2]
    - Spark's RDDs provide two kinds of operations: transformations and actions, where only actions such as reduce or collect trigger the evaluation. So transformation does not trigger RDD evaluations.






## Week 10.1 – Security and Clouds
1. Why is security so important?
    - If systems (Grids/Clouds/outsourced infrastructure!) are not secure 
        - Large communities will not engage
            - medical community, industry, financial community, etc they will only use their own internal resources, e.g.: private clouds!
    - Expensive to repeat some experiments
        - Huge machines running large simulations for several years
    - Legal and ethical issues possible to be violated with all sorts of consequences
        - e.g. data protection act violations and fines incurred
            - Amazon Web Services, Sydney
    - Trust is easily lost and hard to re-establish
- What do we mean by security anyway?
    - Secure from whom?
        - From sys-admin?
        - From rogue employee?
- Secure against what?
    - Security is never black and white but is a grey landscape where the context determines the accuracy of how secure a system is
        - e.g. secure as given by a set of security requirements
- security technology ≠ secure system
    - Ultra secure system using 2048+ bit encryption technology, packet filtering firewalls, …
        - on laptop in unlocked room
        - on PC with password on “post-it” on screen/desk
        - the challenge of peta/exa-scale computers and possibility for brute force cracking
2. The Challenge of Security
    - Grids and Clouds (IaaS) allow users to compile codes that do stuff on physical/virtual machines
        - In the Grid world a rich blend of facilities co-existed (were accessible/integrated!) which had "issues" - prevent people do bad staff
            - Highly secure supercomputing facilities compromised by single user PCs/laptops
            - Need security technologies that scales to meet wide variety of applications 
        - Using services for processing of patient data through to “needle in haystack” searching of physics experiments
    - Should try to develop generic security solutions
        - Avoid all application areas re-inventing their own (incompatible/inoperable) solutions
    - Clouds allow scenarios that stretch inter-organisational security
        - Policies that restrict access to and usage of resources based on pre-identified users, resources
            - Groups/tenancy…
        - But what if new resources added, new users added, old users go…?
            - Over-subscription issues
            - User management (per user, per team, per organisation, per country…)
        - What if organisations decide to change policies governing access to and usage of resources, or bring their data back inside of their firewall?
            - Really not replicated somewhere else?
        - What if you share a tenancy with a noisy neighbour!
            - I/O demanding applications
                - You hopefully never experienced this, but early NeCTAR RC had performance issues!
        - The multi-faceted challenges of ”life beyond the organisational firewall”?
3. Technical Challenges of Security
    - All are important but some applications/domains have more emphasis on concepts than others
        - Key is to make all of this simple/transparent to users!
    - <img src="./docs/25.jpg" width="60%" height="50%" />
    - Single sign-on
        - What is it?
            - Login once, but can access many more resources that potentially provided by other providers
            - When you login The university of Melbourne Cloud, you could also access the amazon cloud
        - **The Grid model (and Shib model!) needed**
        - **Currently not solved for Cloud-based IaaS**
            - has to build by deveoplers
        - Onus (责任) is on non-Cloud developers to define/support this
    - Auditing 
        - What is it?
            - logging, intrusion detection, auditing of security in external computer facilities. Logging the actions by each user
                - When bad thing happen, we have the record
        - **well established in theory and practice and for local systems**
            - Less mature in Cloud environments (beyond the firewall!)
        - Tools to support generation of diagnostic trails 
            - Across federations of Clouds?
            - Log/keep all information?
            - For how long?
        - Problem/challenge 
            - The record are distributed most of time
        - Solution
            - Use block-chain ledger to provide confidentiality of the log
    - Deletion (and encryption!!!)
        - **Data deletion with no direct hard disk** (might cost a lot of money to delete it)
            - Many tools and utilities don’t work!
        - Scale of data
            - Securely deleting a few Mb easy enough
    - Liability
        - Using contract to state the risk when put data here
    - Licensing
        - Challenges with the Cloud delivery model (Where can jobs realistically run)
        - Many license models
            - Per user
            - Per server
            - Per organisation
            - Floating licenses
            - Fixed to machines
    - Workflows
        - Many workflow tools for combing SoA services/data flows
            - Taverna, Pegasus, Galaxy, Kepler, Nimrod, OMS, …
        - **Many workflows models**
            - Orchestration (**centralised** definition/enactment),
            - Choreography (**decentralised**)
        - Serious challenges of 
            - defining, 
            - enforcing, 
            - sharing, 
            - enacting 
        - security-oriented workflows
    - The Ever Changing Technical/Legal Landscape 
        - requirements and guarantee on cloud using

- Authentication
    What does it do?
        - prove who you are
    - What is it?
        - Authentication is <u>**the establishment and propagation of a user’s identity in the system**</u>
        - e.g. so site X can check that user Y is attempting to gain access to it’s resources
            - Note <u>**does not check what user is allowed to do, only that we know (and can check!) who they are**</u>
                - <u>**Masquerading always a danger**</u> (and realistic possibility)
                - Security guidance/balances
                    - Password selection
                        - 16 characters, upper/lower case and must include nonalphanumeric characters and be changed quarterly…!?!?!?!
                    - Treatment of certificates
        - challenge: 
            - Local username/password?
                - 100,000+ users that come and go (scalability)
            - Centralised vs decentralised systems?
                - More scalable solution needed
                - Decentralised Authentication (Proof of Identity) thru Shibboleth
                    - <img src="./docs/28.jpg" width="80%" height="50%" />
                    
                        - Supports Single-Sign On (in case you were unaware)
                        - service provider
                            - web site/Journal in the picture
                        - identity provider
                            - the federation, listed in this case
                    - <img src="./docs/32.png" width="60%" height="50%" />
                        
                        - How does the role of AURIN project go into the unimelb system
                        - How does the unimelb system a user is involved in the AURIN project
                        - How does the unimelb system know to send the information to the service provider related to which when it is required
                            - Only send one attribute related to the project not the whole database
                        - How does the site know what to do with these information when gets it
                            - certificated have to be trusted
                        - If the site is a gateway to remote service, how does these privilages which have been defined in the unimelb to allow me to access the site. 
                            - How can this be used to unlock the remote services which are outside of unimelb
                        - Only several attributes used to federation authentication access control
    - Public Key Infrastructures (PKI) underpins MANY systems
        - What is it?
            - an arrangement that binds public key with respective identities of entities(like people and organization). 
            - The binding is established through a process of registration and issurance of certificates at and by a certificate authority 
            - The PKI role that assures valid and correct registration is called a registration authority(RA). RA is responsible for accepting requests for digital certificates and authenticating the entity making the reques
        - Based on public key cryptography
        - Public Key Cryptography
            - Also called Asymmetric Cryptography
                - Two distinct keys
                    - One that must be kept private
                        - Private Key
                    - One that can be made public
                        - Public Key
                - Two keys complementary, but essential that cannot find out value of private key from public key
                    - With private keys can digitally sign messages, documents and validate them with associated public keys
                        - Check whether changed, useful for non-repudiation
            - Public Key Cryptography simplifies key management
                - Don’t need to have many keys for long time
                    - The longer keys are left in storage, more likelihood of their being compromised
                        - Instead use Public Keys for short time and then discard
                        - Public Keys can be freely distributed
                    - Only Private Key needs to be kept long term and kept securely
        - PKI and Cloud
            - So what has this got to do with Cloud…?
                - IaaS – key pair!
            - Cloud interoperability begins with security!
                - There is no single, ubiquitous CA, there are many
            - There are many ways to prove your identity
                - OpenId, FacebookId, Visa credit card for Amazon, …
                    - Degrees of trust 
                - But remember need for single sign-on
                - Prove identity once and access distributed, autonomous resources!
        - Public Key Certificates
            - (PKC & PKI) Mechanism connecting public key to user with corresponding private key is Public Key Certificate 
                - Public key certificate contains public key and identifies the user with the corresponding private key
                    - Distinguished Name (DN): CN=Richard Sinnott; OU=Dept CIS; O=UniMelb; C=AU
                - Not a new idea
                    - Business card
                        - My name, my association, contact details, …
                            - Can be distributed to people I want to exchange info with
                        - If include public key on it, then have basic certificate, but
                            - has to be delivered in person (or no trust!), who says I work at Melbourne?, could be a forgery, I might be an impostor, what if I move to Monash or my phone number changes, who would have 1024-bit key on business card, …
            - Public Key Certificates & Certification Authority
                - Public Key Certificates issued by trusted "Certification Authority"
        - Certification Authority
            - What it it?
                - <u>**Central component of PKI is Certification Authority (CA)**</u>
            - CA has numerous responsibilities 
                - <u>**Policy and procedures**</u>
                    - How to’s, do’s and don’ts of using certificates 
                    - Processes that should be followed by users, organisations, service providers …(and consequence for violating them!)
            - challenge: 
                - Issuing certificates
                    - Often need to delegate to local Registration Authority
                    - Prove who you are, e.g. with passport, student card
                - Revoking certificates
                    - Certificate Revocation List (CRL) for expired/compromised certificates
                - Storing, archiving 
                    - Keeping track of existing certificates, various other information, …
            - models
                - <img src="./docs/26.jpg" width="60%" height="50%" />
            - Typical Simple CA
                - Based on statically defined centralised CA with direct single hierarchy to users
                - Typical scenario for getting a certificate
                - steps:
                - <img src="./docs/27.jpg" width="60%" height="50%" />
- Authorisation
    - What is it?
        - Authorisation is concerned with controlling access to resources based on policy 
            - Can this user invoke this service, make use of this data?
            - Complementary to authenticationL Know it is this user, now can we restrict/enforce what they can/cannot do
    - Many different approaches for authorisation
        | approach                       | e.g.             |
        | ------------------------------ | ---------------- |
        | Group Based Access Control     | your project VMs |
        | Role Based Access Control      | RBAC             |
        | Identity Based Access Control  | IBAC             |
        | Attribute Based Access Control | ABAC             |
    - Many Technologies
        - XACML, PERMIS, CAS, VOMS, AKENTI, VOMS, SAML, WS-*
    - typical model: RBAC
        - Basic idea is to define:
            - **roles** applicable to specific collaboration
                - roles often hierarchical
                    - Role X ≥ Role Y ≥ Role Z
                    - X can do everything and more than Y who can do everything and more than Z
            - **actions** allowed/not allowed for VO members
            - **resources** comprising VO infrastructure (computers, data etc)
            - A policy then consists of sets of these rules
                - { Role x Action x Target }
                    - Can user with VO role X invoke service Y on resource Z?
                - Policy itself can be represented in many ways, 
                    - e.g. XML document, SAML, XACML, …
            - Standards on when/where these used (PEP) and enforced (PDP)
            - Policy engines consume this information to make access decisions
    - Authorisation and Clouds
        - Authorisation typically applies to services/data deployed on Clouds, i.e. when they are running 
        - But not only… 
            - Who can install this patch, when can they do it, how many VMs will be affected if this happens…?
            - Is this virtual image free of trojans, malware etc?
            - Lots of tools to support this: Pakiti, Cfengine, Puppet, …
            - Real challenge of software dependency management for complex systems
                - Amazingly (?) most users/organisations do not patch!!! 
                - Side-effects, complexities, stopping jobs, restarting jobs etc
    - What does it do?
        - Defining what they can do and define and enforce rules
            - Each site will have different rules/regulations
    - How it is achieved?
        - Often realised through Virtual Organisations (VO)
            - Collection of distributed resources shared by collection of users from one or more organizations typically to work on common research goal
                - Provides conceptual framework for rules and regulations for resources to be offered/shared between VO institutions/members 
                - Different domains place greater/lesser emphasis on expression and enforcement of rules and regulations (policies)
    - Should all be transparent to end users!
    - Reflect needs and understanding of organisations involved!
    - Identity Provider
        - The place you got authenticated
























## 为什么我们需要大数据分析（Why we need it?）

- 如果无法分析数据，那么积累大量数据就毫无意义，因此推动了大规模商业智能（BI）和更复杂的机器学习算法的发展。
- 商业智能、机器学习、统计学和数据挖掘之间存在重叠。
  - 为了统一，我们使用“大数据分析”（Big Data Analytics）这一通用术语。

---

## 什么是大数据分析（What is it?）

- 商业智能、机器学习、统计学、数据挖掘等术语之间存在大量交叉和混淆。
  - 为了简洁明了，统一使用术语 **大数据分析（Big Data Analytics）**。

---

## 大数据分析的例子（Examples of Analytics）

- 全文搜索（Full-text searching）
- 数据聚合（Aggregation of data）
- 聚类分析（Clustering）
- 情感分析（Sentiment analysis）
- 推荐系统（Recommendations）

---

## 大数据分析的挑战（Challenges of Big Data Analytics）

一个分析大数据的框架必须在多个节点上分布数据和处理，这意味着：

- 读取和写入分布式数据集
- 在数据节点失败时保持数据不丢失
- 支持 MapReduce 任务的执行
- 容错能力强：少量节点故障不会导致整个处理中断
- 在集群中协调任务的执行


### 大数据的四个“V”特征：

- **Volume（体量）**  
  - 没错，数据的体量（以 GB、TB、PB 等衡量）是一个标准，但不是唯一标准。 volume

- **Velocity（速度）**  
  - 指新数据被引入系统的频率，也就是数据产生和处理的速度。 frequency new data bring into 

- **Variety（多样性）**  
  - 指数据结构的多样性和复杂性。数据结构越复杂，变化的可能性越高。 variety of the data(XML,JSON,...)

- **Veracity（真实性）**   the level of trust of the data.more resource,less trust
  - 指数据准确性的可信程度（即数据来源的可靠性）。  
    - 数据来源越多样、越非结构化，其真实性越低。  
    - 尤其是当数据来自不同时间、不同更新频率的数据源时。

> ✅ 所以，“大数据”不仅是“量大”，还包括处理速度、类型复杂和数据可信度等多维挑战。

- 为什么需要数据库集群

    - 分担计算负载，提升系统可用性和吞吐量。

    - 存储冗余副本，实现容错和数据可靠性。

## CouchDB 集群架构（CouchDB Cluster Architecture）

- **所有节点同时响应请求（读写均可）**
- **数据分片（Shards）分布在所有节点上**
- 例如：
  - 1 个数据库
  - 3 个节点
  - 4 个分片
  - 每个分片有 2 份副本
- 当某节点没有某个文档（例如，节点2请求分片A的文档），该节点会向其他节点（如节点1）请求该文档，并返回给客户端
- **若某节点故障，其他两个节点继续工作，因为副本仍然存在**
- 节点可自动增删，分片会根据节点变动自动重新平衡（但已有数据库的重新分片需手动移动分片文件或拆分/合并分片）

---

## PostgreSQL 联邦数据库架构（PostgreSQL Federated Database Architecture）

- 这是 PostgreSQL 多种分布式数据库组织方式中的一种（例如 Citus、Postgres-XL、PL/Proxy）
- **联邦数据库由多个分离数据库组成，对客户端表现为单一数据库**
- **有一个入口节点（节点1）供客户端访问，其他节点上的数据只能通过节点1访问**
- 不同数据库存储不同表，例如客户表在数据库B，发票表在数据库C
- 当查询涉及数据库B或C的表时，PostgreSQL 的外部数据包装器（foreign data wrapper）机制允许节点1像访问本地表一样访问这些表
- 写请求转发至相应数据库节点，事务必须在所有相关节点成功提交
- **若某节点故障，整个集群可能停止工作（取决于故障节点及所请求数据）**
- 注意：PostgreSQL 文档中“集群”指同一节点上的多个数据库，不同于一般意义上的多个进程合作的集群

---

## ElasticSearch 集群架构（ElasticSearch Cluster Architecture）

- ES 主要有两种节点角色：**Master 节点和 Data 节点**（还有其他专用节点角色，本文不涉及）
- 一个节点可以同时承担多个角色
- 例子：4 节点 ES 集群  
  - 1 个 Master 节点  
  - 2 个既是 Master 候选也是 Data 节点  
  - 1 个纯 Data 节点
- 多个节点可拥有 Master 角色，但集群中任一时刻只有一个节点是实际 Master，其他 Master 角色节点为 Master 候选，当前 Master 故障时可接替
- 所有节点均可作为协调节点（协调查询执行），但只有 Master 节点可创建/删除索引及调度分片迁移
- 索引（数据库）可进行分片和复制  shards and replicate
- 集群中的索引示例：
  - Index1：2 个主分片 + 2 个副本分片
  - Index2：无分片，1 个副本
  - Index3：无分片，无副本
- 同一节点上不能存在同一个分片（无论是主分片还是副本）的多个副本
- Master 节点故障时，Master 候选节点接替其角色
- 只有主分片（或无分片索引的整个索引）可被更新，更新内容会同步到副本分片
- ES 采用两阶段提交（two-phase commit）机制同步副本数据
- 副本分片可处理查询（只读请求），以提高查询并发性能

- Master 节点	负责管理集群的元数据，比如创建/删除索引、分片分配等。
- Data 节点	存储实际的数据分片，负责 CRUD 操作和搜索查询等。

- ✅ 节点可以兼任多个角色，比如同时是 master-eligible 和 data node。


## CouchDB vs PostgreSQL vs ElasticSearch 比较

- ElasticSearch 限制对索引的写请求只能由一个节点处理（即主分片所在节点），而 CouchDB 中的每个节点都可以接受写请求。
- ElasticSearch 通过选举机制确定新的 Master 节点以应对 Master 节点故障，且可能因达不到最小 Master 候选节点数（法定人数，quorum）而停止接受写请求。相比之下，CouchDB 没有选举机制，即使一个或多个节点故障也继续运行。
- PostgreSQL 中某个节点故障会阻碍整个集群的正常工作，导致部分数据无法访问。
- 这些差异源于它们对一个无法完全解决的问题的不同处理方式——这个问题由 Brewer 的 CAP 定理定义。

---

## CAP定理：一致性（Consistency）、可用性（Availability）、分区容忍性（Partition-Tolerance）

- **一致性（Consistency）**  consistency:每个client从每个node获取到相同的答案
  - 每个客户端从集群的所有节点收到的响应都是相同的答案。

- **可用性（Availability）**   availability：每个客户端能从每个节点获得相应
  - 每个客户端能从集群的每个节点收到响应（答案不一定相同）。

- **分区容忍性（Partition-Tolerance）**  partition-tolerance 一个或多个节点不工作时依然能够正常运行
  - 当一个或多个节点无法与集群其余部分通信时，集群仍能继续运行。

## 关于 Brewer 的 CAP 定理的更多内容

- 虽然该定理表明一致性（Consistency）、可用性（Availability）和分区容忍性（Partition-Tolerance）三者是对称的，但只有在发生网络分区（Partition）时，一致性和可用性才会发生冲突。
- “硬”网络分区（如节点崩溃）可能较少见，但“软”网络分区（如节点响应变慢）却并不少见。  
  - 例如，ElasticSearch 将主节点延迟超过 500 毫秒视为该节点崩溃，需要进行选举。
- 网络分区可能会对整个集群产生影响，比如分布式连接操作只有当所有子查询都返回结果时才算完成。
- 传统数据库管理系统（DBMS）架构对网络分区关注较少，因为所有数据通常集中在少数高质量的同地服务器集群中。
- 随着大量廉价服务器在商业云环境中共享多租户使用，硬件故障率和延迟时间显著增加。
- CAP 定理促使我们在系统设计时必须权衡不同选项之间的取舍。


## 一致性与可用性的协议：两阶段提交（Two-phase Commit）协议 consistance and availability

这是关系型数据库管理系统（以及一定程度上的 ElasticSearch）常用的算法，通过以下方式保证一致性：

- 锁定事务范围内的数据  **lock data in the transcation scope事务**
- 在写前日志（write-ahead logs）上执行事务  **performing transcations on write-ahead logs**
- 只有当集群中所有节点都完成事务时才提交（commit）  **commit when all nodes perform the transcations**
- 当检测到网络分区时回滚事务（rollback）  **rollback when partition is detected**

这种方式带来的结果是：

- 性能下降（因数据锁定）  reduce performance
- 网络分区时不可用（无可用性）  no available when partition
- 一致性得以强制保证（所有数据库保持一致状态）  strong consistance

因此，**两阶段提交适合节点同地集群，分布式集群则不太适用**。

---

## 一致性与分区容忍性：Paxos 算法 consistance and partition-tolerance

- 这一类算法基于共识机制，既保证分区容忍性，也保证一致性。
- 在 Paxos 中，每个节点充当提议者（proposer）或接受者（accepter）：  
  - 提议者提出一个带时间戳的值  propose with a timestamp
  - 接受者可以接受或拒绝（例如，若收到更近期的值则拒绝旧值）  accepter accept or refuse
- 当提议者收到足够多的接受（达到法定人数 quorum）后，会向接受者发送确认信息，确认达成共识的值。  
- Paxos 集群能够从网络分区中恢复并保持一致性，但分区中较小的部分（不在法定人数内）不会响应客户端，导致可用性降低。  
- Raft 是一个类似但更简单的算法，解决同样问题。

---

## 可用性与分区容忍性：多版本并发控制（MVCC）availability and portion-Tolerance

- MVCC 确保集群中每个节点总能接受请求（可用性），并通过版本修订机制支持分区后数据恢复（数据不会被替换，只是赋予新的版本号）。  
- 在 MVCC 中，允许并发更新且无分布式锁（乐观锁仅锁定本地对象副本），因为更新有不同的版本号，最后完成的事务拥有更高版本号，被视为最新值。  
- 若网络分区导致两个节点收到相同版本号的并发请求，两个请求都会被接受，分区恢复后会出现冲突，需人工或程序解决（CouchDB 会返回所有冲突列表，留给应用处理）。这类似于 Git 这样的版本控制系统。
- No global locks
- every wirte operation will construct a new revision
- will be data conflict when there are more than one version

---

## CouchDB vs PostgreSQL vs ElasticSearch - 复盘

- **CouchDB 使用 MVCC**，因而具备高可用性，即使发生网络分区也能保持可用，但可能牺牲一致性。  
- **ElasticSearch 使用两阶段提交（复制主分片到副本分片）和类似 Paxos 的选举机制**，保证一致性，但发生网络分区时不可用。  
  - 为保证文档更新顺序，事务请求必须包含序列号和主分片编号（primary term）。  
- **PostgreSQL 联邦数据库采用两阶段提交**，因此不容忍网络分区。

---

## 为什么大数据使用面向文档的数据库管理系统？document-oriented

虽然关系型数据库管理系统在确保**一致性和可用性**方面表现优异，但其核心的规范化设计导致数据细粒度较高，这使得它们在分区容忍性方面不如粗粒度数据灵活。
**fine-grained细粒度**
示例：

- 关系型数据库中的典型联系人数据库可能包含多个表：人员表、电话表、邮箱表和地址表，这些表相互关联。  
- 而面向文档的数据库则通常只需一个文档类型，电话号、邮箱地址等作为数组嵌套在同一文档内。

## 分片（Sharding）

- 分片是对数据库进行“水平”分区的过程，即将数据库的行（或文档）划分成多个子集，每个子集称为一个 **分片（shard）**，并存储在不同的服务器上。
- 分片数据库的主要优势在于：
  - 通过将计算负载分散到多个节点上提升性能  
  - 更容易在添加新节点时移动数据文件
- 分片机制允许数据库的总体容量超出任何单个节点的持久存储能力。
- 常见的分片策略包括：
  - **哈希分片（Hash sharding）**：将数据行均匀分布在集群中
  - **范围分片（Range sharding）**：将相似数据（如来自同一地区的社交媒体帖子）存储在同一分片上

---

## 复制（Replication）与分片（Sharding）

- **复制** 是将同一数据行（或文档）存储在多个节点上的过程，目的是使数据库具备容错能力。
- **分片** 是将数据分割成不同的“块”（shard），分布存储。
- 复制与分片可以结合使用：
  - 同时最大化可用性（Availability）
  - 并维持一定程度的数据安全性（如故障恢复）

## ElasticSearch 擅长的场景

- **全文搜索**  full-text search
- **按时间检索数据**，例如计算机日志  search by time-based data
- **存储非结构化数据**  store unstructer data
- **存储变动不频繁的数据**，甚至是静态数据  store data are not  change frequently
- **存储关联数据**（如发票和客户）——不过此时关系型数据库会是更好的选择，因为：
  - ElasticSearch 实际上不支持真正的文档间连接（join），只能通过父子关系实现
  - 即使可以通过多个字段或多层嵌套字段进行文档间连接，效率也很低

---

## ElasticSearch 不太适合的场景
    - store data link to another(doesnt not really suppport joins)
- **需要支持事务的场景**：例如需要“要么全部更新，要么全部回滚”的多文档事务
  - ElasticSearch 仅支持单个文档级别的事务安全 Only supports transation of one doc
- **面向多维分析的数据仓库**：此类任务更适合专门的 OLAP 引擎 data analyse in multify angles/demintions
- **数据频繁变更的场景**：data change frequently
  - ElasticSearch 中的文档不会直接删除或更新
  - 每次更新都会将旧版本标记为已删除，并添加一个新版本文档
  - 这会导致索引文件体积迅速膨胀

## ElasticSearch 核心概念

- **Index（索引）**：相当于关系型数据库中的一个“数据库”  
- **Document（文档）**：ElasticSearch 索引中的数据项，相当于关系型数据库中的“行”，以 JSON 格式表示  
- **Data stream（数据流）**：一组遵循相同命名模式的索引，通常用于日志轮换或其他时间序列数据  
  - 例如命名模式为 `nginx-*`，星号部分包含收集日志的日期  
- **Shard（分片）**：索引的水平分区  
- **Replica（副本）**：某个分片的副本数量  
  - 两个副本表示总共有三份文档副本：1 个主分片（primary shard）+ 2 个副本分片（replica shards）  
- **Node（节点）**：ElasticSearch 的一个运行实例  
- **Cluster（集群）**：多个节点协同管理相同的索引  
- **Mapping（映射）**：将 JSON 文档中的字段映射为特定的数据类型和索引方法的模式（类似数据库 schema）

---

## ElasticSearch 组件

- **ElasticSearch**：核心组件，负责存储和搜索文档  
- **FileBeat**：监听文件（通常是日志文件）的更新，并将更新加载到索引中  
- **MetricBeat**：监控系统状态，将指标数据存储到索引中  
- **LogStash**：将 FileBeat 和 MetricBeat 等数据源采集的数据进行转换，然后存入 ElasticSearch 索引  
- **Kibana**：基于网页的用户界面，支持查询与管理 ElasticSearch 集群  

---

## 其他 Elastic 组件

- **FunctionBeat**：监控无服务器环境（如 AWS Lambda）活动并将结果存储到索引中  
- **HeartBeat**：检测服务的运行状态并将结果存储到索引中  
- **Observability（可观测性）**：监控系统指标、分析并生成洞察信息  
- **Security（安全性）**：类似于 Observability，但针对的是系统安全性  
- **其他更多组件**：Elastic Stack 提供丰富的扩展组件以支持不同数据源与场景

## 节点角色（Node roles）

- 集群中的每个节点都会被分配一个或多个角色  
- 角色种类很多（如：master、data、transform、ingest、ml 等），但**唯一必须的角色**是：`master` 和 `data`  
- **Master 节点**负责协调整个集群的操作，例如：
  - 决定分片的分配位置
  - 跟踪节点健康状况
  - 创建索引等
- 集群中可以有多个 master 节点，但**任意时刻只能有一个活跃的 master 节点**，其余为“候选 master 节点”（master-eligible）
- **Data 节点**：如果不是 master-eligible，它只负责管理数据，**不能参与 master 选举**
- 当 master 节点故障时，其它 master 节点会举行选举以选出新的 master  
- 被删除或崩溃节点上的主分片（primary shard）会被其余节点上的副本分片（replica shard）接替，升级为主分片

---

## ElasticSearch 集群扩展（Scaling）

- 扩展方式有两种：
  - **纵向扩展（Vertical）**：使用更强大的机器节点，并迁移数据过去
  - **横向扩展（Horizontal）**：新增节点到集群
- 当新数据节点加入集群后，部分分片会迁移到新节点，以重新平衡负载
- 当移除数据节点时，该节点上的主分片必须被替换，副本分片将被提升为新的主分片

---

## ElasticSearch 集群状态（Cluster Status）

- **绿色（Green）**：有足够的节点容纳所有主分片和副本分片，状态良好
- **黄色（Yellow）**：分片无法合理分配（例如主分片和副本不能在同一节点），系统仍可正常工作，但无法保证冗余
- **红色（Red）**：主分片数量超过了当前运行节点数，某些数据可能无法访问

---

## ElasticSearch 索引状态与分片（Index & Shard）

- ElasticSearch 默认使用 **基于文档 ID 的哈希分片**，以实现各分片中文档数量大致相同
- 每个索引可以设置不同数量的主分片与副本分片
- 可在创建文档时指定“路由值（routing value）”来将文档写入特定分片，实现**范围分片**
- 查询时，每个分片使用一个线程进行处理（但一个分片上也可同时进行多个查询）
- 分片越大，查询越慢；但每个分片会消耗资源，因此需合理权衡
- **经验法则**：一个分片推荐存放约 `2 亿个文档`，或 `10GB~50GB` 的数据量
- 一般来说，**多分片优于少分片**，因为主分片数限制了一个索引可以使用的最大节点数
- 数据库容量通常比预期增长得更快，因此建议分片留有余量

---

## ElasticSearch 分片生命周期（Shard Lifecycle）

- 有些数据是时间敏感且快速增长的，因此可以在数据过老或过大时将其删除
- ElasticSearch 中索引可以配置“生命周期策略（ILM）”，主要阶段包括：
  - **Hot**：活跃阶段，用于读写
  - **Warm**：只读但仍被频繁访问
  - **Cold**：几乎不访问，只保留
  - **Frozen**：极低访问频率，延迟高
  - **Delete**：被删除
- 可以将不同阶段的索引分配到不同角色的节点（如：data_hot, data_cold）
- 简单设置中，可以让数据流（data stream）在达到特定大小或过了一定天数后“滚动（rollover）”，并最终删除

  例如：
  - 数据流 `nginx-*` 的生命周期策略为：
    - 10 天后进入 warm 状态
    - 30 天后被删除
  - 所以：
    - 第 10 天：可能存在两个索引，如 `nginx-2024-01-01`, `nginx-2024-01-11`
    - 第 20 天：存在三个索引
    - 第 30 天：最旧的索引被删除，仍保持三个索引






### past exam
- > [2013 Q6] A) Explain what is meant by the following security terms:
    - > single sign-on [1]
        - is where you authenticate once then the identity provider will enable you to access set of multiple different services which can be hosted in different places 
    - > public key infrastructures [1]
        - the cloud computing is based on this
        - you have public private key pairs where public key is hold by anyone but only you hold by yourself. And the certificates which issuing the connection between your pulic key and your private key. And the certificate is issued by the certification authority. If you want to get certificates, you have to prove your identity. 
    - > certification authority [1]
        - The certification authority is the authority who is responsible for issuing the certificate.
    - > registration authority [1]
        - The physical individual in the organization who is responsible for checking someone's identity
    - > identity provider (IdP) [l]
        - is the authentication system
        - The place you got authenticated to prove your identity
         - e.g.: When you want to login the AURIN, you are redirected to unimelb authentication where you need to provide your identity
- > [2013 Q6] B) Discuss the challenges in supporting fine-grained security in Cloud environments. You may refer to the importance and/or role of (some of) the terms in part A) of this question. [5]
    - how cloud do authentication
        - e.g.: fine-grained access control which is authorization, auditing. There is still problem which is confidentiality. The fact that you put your data on the given server and you have no idea where the server is
    
    - fine-grained security is not done pretty well in the cloud. We kind of knowing how to do authentication to a certain degree. But building access control system without fine-grain is something that cloud doesn't generally provide for you so that you have to build by yourself.

    - authentication
    - authorization
    - accounting/auditing
    - confidentiality
    - trust
- > [2015 Q5] A) There are many open challenges in delivering secure Clouds. Describe some of the technical and non-technical issues that currently exist for development and delivery of security-oriented Clouds. [4]
    - techincal issues:
        - authorisation
        - trust, 
            - trust the cloud provider that data is secured to be stored on that
        - api, 
        - single sign-on, 
            - Login once, but can access many more resources that potentially provided by other providers
            - **The Grid model (and Shib model!) needed**
            - **Currently not solved for Cloud-based IaaS**
            - Onus (责任) is on non-Cloud developers to define/support this, so cloud developer can't do anything to help with
        - certificate authority
            - challenge: 
                - there isn't centralized certificate authority for the cloud
                - Issuing certificates
                    - Often need to delegate to local Registration Authority
                    - Prove who you are, e.g. with passport, student card
                - Revoking certificates
                    - Certificate Revocation List (CRL) for expired/compromised certificates
                - Storing, archiving 
                    - Keeping track of existing certificates, various other information
    - non-techincal issues:
        - business issue: government won't allow medical data stored on cloud like AWS because it might be backup in somewhere else
        - sensitive issue
        - policy issue
        - Liability
            - Using contract to state the risk when put data here
        - Licensing
            - Challenges with the Cloud delivery model (Where can jobs realistically run)
            - Many license models
                - Per user
                - Per server
                - Per organisation
                - Floating licenses
                - Fixed to machines
- > [2014 Q2] A) b. Outline some of the practical challenges in supporting Cloud interoperability? [2]
    - Security
        - You don't have single sign-on: login once to access a variety of clouds for various reasons
    - API themselves
        - Cloud providers, especially public ones want to lock you in. 
        - They have different business models, different costs
- > [2014 Q6] A) The Internet2 Shibboleth technology as currently supported by the Australia Access Federation provides _federated authentication_ and _single sign-on_.
    - > a. Explain what is meant by the italicized terms [2].
        - federated authentication
            - is basically where you are trying to access a resource while you are proving your identity somewhere else
        - single sign-on 
            - is where you authenticate once then the identity provider will enable you to access set of multiple different services which can be hosted in different places 
    - > b. Explain the role of trust and public key infrastructures in supporting the Internet2 Shibboleth model. [2]
        - trust
            - is a key part of any kind of security system in Shibboleth based on trust. So we all trust the organisation to authenticate their uses
        - public key infrastructures
            - all messages about where you are from and do you authenticate here are digitally signed. We don't trust anyone who is not identity proven. It's only those in the federation and they have keys which are used to do the authentication.
                - e.g. I am from unimelb and I am assigning this message with my key which you can then use this key to verify that this is the key you trust effectively.
    - > c. What are the advantages and disadvantages of the Shibboleth approach for security? [4]
        - adv
            - flexible when you doing single sign-on
            - simple to use, access different service just by proving identity once
        - disadv
            - all of the protocols are static
                - this information which is used to setup professor snott has authenticated at unimelb. So there is a collection about attributes e.g.: he is a staff. This information is pre-agreed in advance. If join the new project, this information wouldn't be available with unimelb system. limited because it is static
            - not flexible, not dynamic 
    - > d. Why isn’t Shibboleth used to access Cloud-based systems more generally? [2]
        - related to trust. differnt cloud provider requires different facts in the Shibboleth
            - e.g.: Amazon requires you credit card info while unimelb only requires student info.
        - Static federation
        - no single CA
- > [2015 Q5] B) The Internet2 Shibboleth technology as currently supported by the Australia Access Federation provides federated authentication.
    - > a. Explain what is meant by this italicized term and discuss the advantages and disadvantages of the Shibboleth approach for security. [3]
        - above
    - > b. Why isn’t Shibboleth used to access Cloud-based systems more generally? [3]
        - above


✅ [2013 Q6] A) 解释以下安全术语的含义：
Single sign-on（单点登录） [1]
指的是你只需认证一次，身份提供者（Identity Provider, IdP）就可以让你访问一组多个不同的服务，这些服务可能托管在不同的地方。

Public key infrastructures（公钥基础设施） [1]
云计算正是基于这种机制。你拥有一对公钥和私钥，公钥可以被任何人持有，而私钥只有你自己持有。证书用来建立公钥和私钥之间的绑定关系，证书由**证书认证机构（CA）**签发。如果你想获取证书，就必须证明你的身份。

Certification authority（证书认证机构） [1]
负责签发证书的权威机构。

Registration authority（注册认证机构） [1]
是机构中的具体人员，负责验证某人的身份。

Identity provider（IdP，身份提供者） [1]
是负责认证的系统，也就是你证明身份的地方。
举例：当你尝试登录 AURIN 时，会被重定向到墨尔本大学的认证系统，在那里你需要提供你的身份信息。

✅ [2013 Q6] B) 讨论在云环境中支持细粒度安全所面临的挑战。你可以参考上面 A 部分中的术语。[5 分]
云中如何实现身份认证：
比如：细粒度访问控制（授权）和审计。
仍然存在的一个问题是保密性——你将数据放在服务器上，但你并不知道服务器在哪里。

云中的细粒度安全做得并不好：
我们对认证有一定的掌握，但构建一个细粒度的访问控制系统并不是云服务提供商会为你自动构建的，因此你通常需要自己实现。

关键安全元素包括：

认证（Authentication）

授权（Authorization）

记账/审计（Accounting/Auditing）

保密性（Confidentiality）

信任（Trust）

✅ [2015 Q5] A) 云安全交付中存在许多挑战。请描述当前在开发与部署安全导向的云服务中面临的一些技术和非技术问题。[4 分]
技术问题：

授权机制尚不完善

信任：你需要相信云提供商能安全地存储你的数据

API：可能存在安全漏洞

单点登录（SSO）：

登录一次即可访问许多资源，可能由不同提供商提供

类似于 Grid 或 Shibboleth 模型

目前在基于云的 IaaS 上还未很好解决

责任落在非云开发者身上，云开发者无法协助

证书认证（CA）相关问题：

没有统一的 CA 管理整个云

颁发证书需本地注册机构验证身份（如护照、学生证）

吊销机制依赖证书吊销列表（CRL）

需要长期存储和归档证书数据

非技术问题：

政府监管问题：如政府不允许将医疗数据存储在 AWS 上，因为备份可能在海外

敏感性问题：特定行业数据敏感性高

政策限制

责任归属问题（Liability）：使用合同声明风险

许可问题（Licensing）：

云交付模型带来的挑战（任务在哪运行）

许可方式复杂：按用户、按服务器、按组织、浮动许可、绑定机器等

✅ [2014 Q2] A) b. 说明支持云互操作性时面临的一些实际挑战？[2 分]
安全性问题：
你没有单点登录功能——也就是说，无法只登录一次就访问多个云服务。

API 问题：
云提供商（尤其是公共云）往往希望将你锁定在他们的平台上。因为他们的商业模式和费用结构都不一样。

✅ [2014 Q6] A) Internet2 Shibboleth 技术在 Australia Access Federation 中支持联合身份认证和单点登录。
a. 解释斜体词语的含义 [2 分]：
联合身份认证（Federated Authentication）：
指你在访问一个资源时，是在另一个地方验证身份。

单点登录（SSO）：
是指你只需认证一次，IdP 就可以让你访问多个不同服务。

b. 解释信任（Trust）和公钥基础设施（PKI）在支持 Shibboleth 模型中的作用 [2 分]：
信任（Trust）：
是安全系统的核心。Shibboleth 的基础是各组织之间的相互信任，彼此信任对方能正确认证用户身份。

公钥基础设施（PKI）：
所有有关你身份的信息都被数字签名。你不会信任未验证身份的来源，只有在联邦内的组织才具有签名权限，使用其私钥签名信息，其他组织可用其公钥验证身份。

举例：我来自 unimelb，我用自己的密钥签名此消息，你能用我的公钥验证我确实来自 unimelb。

c. 试分析 Shibboleth 安全模型的优点与缺点 [4 分]：
优点：

使用灵活，支持单点登录

用户体验简单，验证一次即可访问多个服务

缺点：

协议是静态的：

所有身份信息是预先协商的（如：他是工作人员）。若后来加入新项目，旧信息无法支持

不够灵活，不具备动态扩展能力

d. 为什么 Shibboleth 没被广泛用于访问基于云的系统？[2 分]
原因包括：

涉及信任问题：不同云提供商需要不同的身份验证信息

例如：Amazon 需要你的信用卡信息，而 unimelb 只需要学生信息

静态联邦机制：不灵活

没有统一的证书认证机构（CA）

✅ [2015 Q5] B) Internet2 Shibboleth 技术支持联合身份认证
a. 解释该术语并分析 Shibboleth 安全模型的优缺点 [3 分]
同上所述（联合身份认证与优缺点）

b. 为什么 Shibboleth 没有被广泛用于访问基于云的系统？[3 分]
同上所述（信任机制、静态机制、无统一 CA）





## 虚拟化的动机 Virtualisation

- **服务器整合（Server Consolidation）**
  - 提高资源利用率
  - 降低能源消耗

- **可以按需创建个人虚拟机**
  - 无需购买硬件
  - 支持公有云计算（Public Cloud Computing）

- **安全性 / 隔离性（Security / Isolation）**
  - 在单一机器上与多个用户共享资源

- **硬件无关性（Hardware Independence）**
  - 可以迁移到不同的硬件平台


## 特权指令（Privileged Instructions）

- 如果处理器处于用户模式（user mode），执行这些指令会产生陷阱（trap）
- 如果处于内核模式（kernel mode），则不会产生陷阱

## 敏感指令（Sensitive Instructions）

- 其行为依赖于硬件的模式或配置
- 在用户模式和内核模式下，表现不同
- 例如：POPF 指令（用于中断标志的处理）

## 无害指令（Innocuous Instructions）

- 既不是特权指令，也不是敏感指令
- 执行诸如读取数据、数字相加等操作



## 虚拟机监控器（VMM）需要支持的功能：

- **去特权化（De-privileging）**
  - VMM 模拟特权指令对系统/硬件资源的影响，这些指令的执行会陷入（trap）到 VMM
  - 又称为“陷阱并模拟”（trap-and-emulate）
  - 通常通过将 Guest OS 运行在比 VMM 低的硬件优先级上实现

- **主结构和影子结构（Primary/Shadow Structures）**
  - VMM 维护关键结构的“影子”副本，这些结构的“主”版本由 Guest OS 操作，例如内存页表
  - 需要主副本确保 Guest OS 能看到正确的版本（后续会详细说明）

- **内存访问跟踪（Memory Traces）**
  - 控制对内存的访问，保证影子结构和主结构保持一致
  - 常用策略是对主副本设置写保护，使得可能引起页面错误（page fault）的更新操作能够被捕获、解释并处理
  - 这样可以防止某个应用或代码崩溃你正在使用的服务器！


## 全虚拟化（Full Virtualisation）

- 允许未修改的来宾操作系统（Guest OS）在隔离环境中运行，通过模拟完整硬件实现（例如 VMWare）
- 来宾操作系统完全不知道自己并非运行在真实物理机上

### 与之对比

## 半虚拟化（Para-virtualisation）

- VMM/Hypervisor 向来宾操作系统暴露特殊接口以提高性能
- 需要修改或使来宾操作系统具备虚拟化感知能力（例如 Xen）
- 可以优化系统使用该接口，因为不是所有指令都需要被捕获和处理

---

## 全虚拟化的优缺点

### 优点

- 来宾操作系统不知道自己在虚拟机内执行
- 来宾操作系统无需修改
- 不需要硬件或操作系统的协助
- 可以运行旧版操作系统（legacy OS）

### 缺点

- 性能可能不如半虚拟化高效 low performance

---

## 半虚拟化的优缺点

### 优点

- 虚拟化开销较低，性能更好，例如 Xen

### 缺点

- 需要修改来宾操作系统
- 不能运行任意操作系统
- 移植性较差
- 兼容性较低

---

## 虚拟机监控器的实现方式（续）

### 硬件辅助虚拟化（Hardware-assisted Virtualisation）

- 硬件提供架构支持来运行 Hypervisor（例如 KVM）
- 许多新处理器通常具备此功能
- 要求所有敏感指令都能被捕获（trappable）

### 与之对比

### 二进制翻译（Binary Translation）

- 通过扫描来宾指令流，替换敏感指令为模拟代码来实现陷阱和执行（例如 VMWare）
- 不需要硬件支持，但实现难度较大
- 指令集间通常不存在 1:1 的映射关系

---

## 硬件辅助虚拟化

### 优点

- 性能较好
- 实现更简单
- 高级实现支持硬件辅助的 DMA、内存虚拟化等功能

### 缺点

- 需要硬件支持

---

## 二进制翻译

### 优点

- 来宾操作系统无需修改
- 不需要硬件或操作系统协助
- 可以运行旧版操作系统

### 缺点

- 开销较大 overheads
- 实现复杂
- 需要“即时”替换指令
- 需要库支持辅助实现，例如 vCUDA

| 名称    | 关键点                 |
| ----- | ------------------- |
| 全虚拟化  | 不改 OS，完全模拟，性能一般     |
| 半虚拟化  | 改 OS，不模拟，性能高 ，hard to move on different os       |
| 硬件辅助  | 不改 OS，靠 CPU 帮忙，性能最好 |
| 二进制翻译 | 不改 OS，翻译指令，最慢 ,费用高,complicated     |

### Hypervisor（虚拟机管理器,又叫VMM）

### 裸机型虚拟机监控器（Bare Metal Hypervisor）run on hardware

- VMM 直接运行在物理硬件上（例如：VMWare ESX Server）
- 启动时直接运行在真实物理机器上
- VMM 需要支持设备驱动和硬件管理

### 托管型虚拟化（Hosted Virtualisation）run on another os

- VMM 运行在另一个操作系统之上（例如：VMWare Workstation）

## 操作系统级虚拟化（Operating System Level Virtualisation）

- 实现轻量级虚拟机（容器，Containers）lightweight VM
- 与传统系统级虚拟化不同，操作系统创建“迷你容器” docker
  - 对于许多使用场景来说，**共享一个通用的操作系统就足够了**
  - 无法在 Linux 上运行 Windows，但很多场合并不需要这么做
- 示例：LXC、Docker、OpenVZ、FreeBSD Jails
- 可与云端 Hypervisor 结合使用

### 优点

- 更加轻量 lightweight
- 更快的启动和运行速度 faster
- 在同一台硬件上可运行更多虚拟机 more than one VM on one
- 可以将应用程序及其所有依赖打包成容器
  - 更贴近应用开发流程

### 缺点

- 只能运行为同一操作系统设计的应用程序 only run apps designed for one os
- 不能托管不同的来宾操作系统
- 只能使用本地文件系统 use local file system
- 与其他容器共享相同的系统资源 share resources with other VM
  
## 内存虚拟化（Memory Virtualisation）

- 传统上，页表（Page Tables）存储逻辑页号（Logical Page Number）到物理页号（Physical Page Number）的映射
  - 看起来比实际拥有的内存更多

## 影子页表（Shadow Page Tables）

- VMM 维护与来宾页表同步的“影子页表”
- 带来额外的管理开销
- 硬件负责从来宾地址到物理地址、再到机器地址的双重地址转换

- **多个虚拟机在同一系统上工作，靠的是特权指令拦截** **priviledge instruction interception** and virtual memory makes each VMthought hey has their own memory.有些计算机也支持hardware virtualization, easier to handle instructions and memory virtualization


## OpenStack 与 AWS 比较

### OpenStack

- 由社区驱动、基于模块组件的架构
- MRC（墨尔本研究云）仅提供 OpenStack 部分服务：
  - **不支持 Designate**（DNS 即服务）
  - **不支持 HEAT 的自动扩缩功能**
  - ……（还有其他服务缺失）
- 某些服务虽在 MRC 中可用，但你所在的项目无法使用：
  - **Trove**（关系数据库即服务）
  - **LBaaS**（负载均衡即服务）


## AWS 服务概览

### EC2 – 弹性云计算（Elastic Cloud Computing）

- 实例（Instance）
- 安全组（Security Group）
- 弹性 IP（Elastic IP 或 Floating IP）
- 弹性负载均衡器（Elastic Load Balancer）
- 安全连接 EC2 实例的方式：
  - 使用 Web 界面的 Session Manager
  - 使用命令行（CLI）通过 SSH 调用 Session Manager

---

### 数据库服务（Database Services）

- **Amazon RDS**
  - 托管的关系型数据库服务
  - 支持：MySQL、PostgreSQL、MariaDB、Oracle、MS SQL

- **Amazon DocumentDB**
  - 可扩展、高可用、完全托管的 MongoDB 数据库服务
  - 兼容 MongoDB 开源 API（版本 3.6、4.0 和 5.0）
  - 是否选择 MongoDB Atlas（另一个托管 MongoDB 服务）？

- **Amazon OpenSearch Services**（原 Amazon Elasticsearch Services）
  - 全托管、自动部署、补丁、故障恢复、备份和监控
  - 支持扩展性并可与 AWS 其他服务集成（如 Lambda、S3）

---

### S3 – 简单存储服务（Simple Storage Service）

- 面向对象的存储服务，提供业界领先的可扩展性、数据可用性、安全性与性能
- 用于存储任意类型的数据，适用于任何用途
- 可通过 Web 界面、CLI、API 及第三方工具上传和下载数据
- 可使用 S3 桶托管静态网站
- 支持数据版本管理与生命周期策略配置

---

## AWS 系统管理服务（System Manager）

### Fleet Manager

- 远程管理节点
- 查看节点的运行状况与性能状态，收集系统数据

### Session Manager

- 提供无需打开入站端口的安全可审计的节点管理方式
- 可通过浏览器交互式 shell 或 AWS CLI 使用

### Run Command

- 自动化执行常见的管理任务
- 实现大规模的一次性配置更改

### Patch Manager

- 自动修补托管节点的操作系统与应用程序补丁

---

## AWS 安全服务

### WAF – Web 应用防火墙（Web Application Firewall）

- 监控发送到 API 网关、CloudFront 分发网络或应用负载均衡器的 Web 请求
- 根据指定条件（如来源 IP 地址）保护资源免受恶意访问

---

## AWS 容器编排服务（Container Orchestration）

### ECS – 弹性容器服务

- 可运行在 EC2 上
- 可运行在 Fargate 上（无服务器化，Serverless！）

### EKS – 弹性 Kubernetes 服务

- 可运行在 EC2 上
- 可运行在 Fargate 上（无服务器化，Serverless！）