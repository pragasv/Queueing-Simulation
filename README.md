# Simple Matlab simulation to understand queue behavior And traffic congestion

To visualize and test out the scenario the following matlab model was created in Simulink.
![](model.PNG)
The model basically gives the ability to visualize the given task by controlling the following parameters.
- Queue size
-- Both servers having the same queue size
-- Both the servers having a different queue size
- Service time
-- Both servers having the same mean service time exponential distribution
-- Both servers having different mean service time exponential distribution
Additionally it is notable that the packet generated interval or the switching probabilities were not changed as it was kept constant to achieve the optimum performance parameters. The entity generated was also kept at a constant with a new entity generated every second. The mean of the time distribution was kept the same as the entity generated rate.
