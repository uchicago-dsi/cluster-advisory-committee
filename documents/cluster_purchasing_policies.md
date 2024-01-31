# Cluster Purchase Guide

This document contains an overview of the policies around (a) purchasing additional equipment for the DSI cluster and (b) the priorities that we can grant on that provisioned hardware.

Our framework:
1. We want to encourage group investment in the DSI cluster by granting priorities to specific purchased hardware to the people/project who made that purchase.
2. We want to make sure that all purchased hardware conforms to the requirements of the cluster.
3. We want to make sure that there is a defined lifecycle policy associated with each purchase in terms of both physical life and priority access.

This document contains a description of the implementation details of this framework.

## Minimum Investment for Priority Hardware Solution:

Depending on the current configuration of the cluster there are limitations to what types of hardware can be added. 

The minimum investment required to gain priority access to hardware is approximately $100,000. However, the specific hardware specifications fluctuate due to current technological trends and market availability.

As of winter 2024, this investment looks like the follow, with a total cost of roughly \$115,000:

* 4x Nvidia H100 80GB GPUs
* 2x Intel LGA4677 CPUs
* 1TB RAM 
* Misc. server components and cables
    
For up-to-date information on the minimum required specifications, please contact DSI Techstaff.

## Lifecycle Polices

There are a number of different factors that effect the lifecycle of any purchase as well as the associated priority policies.

* Usage Duration: We will continue to operate GPUs in our cluster as long as they do not experience a fatal malfunction. This commitment is in line with our goal to maximize the utility of our resources while ensuring effective support for research needs.

* End of Life Policy: The retirement of any GPU model from our cluster will align with NVIDIA's end-of-life policies for that particular model. We will proactively monitor these guidelines to ensure our hardware remains current and supported.

### Duration of Access for Grants with a Defined Timeline:

* Access Duration: Investors who meet the investment requirements will receive priority access to the hardware they fund for the duration of the grant. 

* Maximum Priority Duration: The general rule is a maximum of five years of priority access to be provided as this roughly aligns with hardware generations. If there are specific concerns about this timeline then additional terms can be discussed, but it may require specific hardware to be purchased.


### Handling Grants without a Defined Timeline

* Default Allocation: Grants without a specified timeline will have a default allocation period of three years. Extensions require discussion and agreement.

* Provisional Allocations: Initial allocation period with options for extension based on progress and resource availability.

* Project Milestones: Regular milestone reporting is encouraged or required for ongoing validation of resource allocation.

## 

## Other Considerations

* Resource Re-allocation Post-Grant: Develop policies for transitioning resources back to the general pool after the grant period, including a phased reduction in priority and a grace period for data migration.

* Over-Subscription Policies: Implement policies for over-subscription to optimize resource utilization. Clear guidelines will manage and prioritize over-subscription.

* Emergency Resource Allocation: Implement a policy for time-sensitive research or critical data processing, offering temporary priority override.

* Transparency in Resource Allocation: Maintain a transparent record or dashboard to display resource allocation and usage, enhancing trust and understanding among users.

* Semi-Priority Queue Access: For investors unable to meet the minimum investment requirements, there may be an opportunity to discuss access to semi-priority queues, contingent upon space availability.

## Troubleshooting and Support

* Software issues (such as those related to the OS, server configuration and SLURM) and hardware issues are the responsibility of the system administrators. Debugging code and project level assistance is the responsibility of the person writing and executing the code.

* If there are any critial failures in the cluster, the system administrators will do their best to diagnose and correct any problems. Hardware isn't unbreakable and if something is no longer usable by the cluster it will be removed, or replaced if possible.

## Additional Questions

For any questions or concerns regarding these guidelines, or to discuss potential investments and allocations, please reach out to the DSI Techstaff. They are available to provide support and clarification, ensuring a smooth and transparent collaboration.
