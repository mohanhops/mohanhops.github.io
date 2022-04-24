# Where is HPC ?

Demand for HPC is growing rapidly as enterprises move further down the path to digital transformation, they are increasing rely on compute and data-intensive applications driven by high performance computing systems. According to MarketsandMarkets, the HPC market will grow to $49.4bn by 2025.

HPC requires High Speed Memory, Powerful Compute  and Fast Network this demands high capital expenditure, as technology is currently in full swing, it is difficult to sticking on to a single hardware stack for complex workloads for many years (average age for cluster is 3 to 5 years).

Traditionally HPC was happening mostly on-premises, building HPC cluster on-premises requires whole cycle of procurement of hardware, setup cluster and maintain it. This approach demands high capex and time consuming. Upgrading the HPC cluster with latest flag ship hardware will be cost in-efficient.

## On-Premise HPC Alternatives?

Cloud can serve almost all the demands required for HPC cluster setup. Cloud provides flexibility to the user to choose the instance types, network, storage, and security policies dynamically.

To give an idea On-premises HPC vs Cloud HPC, tried Biryani (most loved food in India) as example.

To have Biryani, there are mainly 2 ways.

- Option 1:
  * Go to store get all ingredients required
  * Have a kitchen setup and recipe manual (any one recipe)
  * Prepare biryani as per manual
  * Serve the biryani and enjoy it
  * Wash the dishes and keep the kitchen clean 

- Option 2:
  * Go to restaurant
  * Order the biryani (any variety, any number of portions) and enjoy it
  * Pay the bill and leave

Option 1 is feasible for people who eats (Single variety) biryani all the time, because going out every time cost higher then preparing it by own,  Option 2 is feasible for people who eats biryani as and when they feel like having it and dynamically increase the people count.

### Total cost of owning HPC cluster On-Premise vs Cloud?

Rescale have solved some of the required HPC software puzzles by getting ISVs with HPC code to flex their license models. As per Rescale CEO, Joris Poort cost breakdown for on-site HPC clusters versus renting capacity and licenses as follows,

#### Cost of On-Premise Cluster

![On_premises](/img/hpc_beginner/Rescale2.png)

#### Cost of Cloud HPC

![Cloud](/img/hpc_beginner/Rescale4.png)

Poort concludes that ideal use case for HPC customers is to have some combination of on-premises and cloud-based resources to manage the need for peak capacity, but also to balance the costs based on existing hardware investments. He does not expect companies to go full-bore into the cloud for all of their critical HPC workloads, but does see an opportunity to expand access to both the needed diverse hardware and software tools to expand a company’s existing capabilities

## How Far Has This Transition Progressed?

A study by Hyperion Research finds that approximately 20 percent of HPC workloads are now running in the public cloud. There are many good reasons for this trend.

- Drivers for HPC in the cloud
  * Cloud platforms are providing easier access models to clouds, and a larger set of application software is available in the cloud.
  * Many Cloud providers are now support specifically targeted for HPC workloads, including in-house HPC experts and services to help HPC users better understand the process of running their applications in the cloud.
  * Cloud platforms are becoming an important enabler in the emerging and high-growth markets of artificial intelligence and other high performance data analysis applications.

Hyperion notes that HPC is crucial to AI developments. Moreover, the growth of HPC in the cloud, as well as the attention paid to HPC by Cloud providers, has resulted in many AI workflows being created and run-in cloud environments. This trend fueled market growth of HPC in Cloud jumped to $4.3 billion in 2020.

## What is HPC-as-a-Service?

High performance compute-as-a-service (HPC-as-a-service or HPCaaS), a relatively new category of cloud service that provides the hardware, software, and expertise to process HPC workloads. Cloud providers like IBM, AWS, Microsoft Azure, Hewlett Packard Enterprise (HPE), Penguin Computing on Demand, and Google Cloud Platform run and provide access to supercomputing infrastructure in their own datacenters, usually in the form of a collection of interconnected servers that work together in parallel to solve problems.

Due to the low investment costs, HPCaaS is becoming an alternative to on-premises clusters for HPC. HPCaaS offers ease of deployment, scalability, and predictability of costs, using an established service. Creating high performance compute capacity in-house, on the other hand, can be a long process, requiring highly specialized and in-demand workers.

## When to Switch to HPCaaS?

- Cloud switching costs too high for AstraZeneca
  * “On-premise is between five and seven times cheaper than doing a similar type of activity in the cloud,” says Scott Hunter, AstraZeneca’s global infrastructure director.
  * The reason why there is such a high cost associated with cloud-based HPC for AstraZeneca is that it works with a lot of double-precision chemistry workloads, which tend to be operational 24 hours a day, 365 days a year. 
  * “That means that unless we get a cracking deal from one of the major public cloud vendors or Oracle, it makes sense to run on-premise because of the cost,” says Hunter.

## Conclusion

There are Pros and Cons of using HPC in the Cloud. Often it is not attractive to move all HPC workloads to the Cloud to leverage advantages.

A typical feasible approach is “Hybrid HPC”: move part of the HPC workload to the Cloud most suitable for HPC resources in the cloud and keep part of it on-premises in the own data center.

All these aspects need to be considered when deciding the optimal strategy for which workloads to move to the Cloud, and what to keep in your local on-premises HPC Cluster.




---
Credits: Document Center
---
1. [How long until cloud becomes the preferred environment to run HPC workloads?](https://www.computerweekly.com/feature/How-long-until-cloud-becomes-the-preferred-environment-to-run-HPC-workloads)
2. [Why HPC and AI Workloads are Moving to the Cloud](https://insidehpc.com/2020/10/why-hpc-and-ai-workloads-are-moving-to-the-cloud/#:~:text=A%20study%20by%20Hyperion%20Research,running%20in%20the%20public%20cloud.)
3. [THE CLOUD VERSUS HPC CLUSTER COST CONUNDRUM](https://www.nextplatform.com/2015/06/03/the-hpc-cloud-versus-cluster-cost-conundrum/)
4. [What is HPC-as-a-service and why does it matter?](https://venturebeat.com/2022/01/20/what-is-hpc-as-a-service-and-why-does-it-matter/)
