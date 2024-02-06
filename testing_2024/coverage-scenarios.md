# Coverage scenarios


## Branch Coverage

Imagine you are a safety inspector for a building compagny. Your goal is to ensure that all safety protocols are followed during the construction of a building. You should inspect _each decision point_ where security measures vary based on certain conditions. For instance, you should ensure safety for employees working under fluctuating weather conditions, working at different heights on the building, and operating with varying equipment.
> Q: what type of test coverage would suit this real-life situation the best?

> A: Each decision/variation represents a branch. Ensuring **branch coverage** in this case would mean validating safety procedures for all possible scenarios.


## Path Coverage

Imagine you are a detective inspecting a series of events that led to a car crash. You will need to reconstruct and analyze _all possible sequences of actions and events_ that might have led to the collision. This includes considering elements such as weather, road condition, driver alcohol level, speeding, vehicule condition, possible mechanical failures, and any other important variable.
> Q: what type of test coverage would suit this real-life situation the best?

> A: By studying every possible **path** that could have caused/contributed to the accident, you aim to gain a comprehensive understanding of the factors involved (or identify the ones that might have been overlooked)


# Loop Coverage

Imagine you are a QA analyst for a ride-sharing app Ubber. You should ensure that the fare (price of the ride) calculation works flawlessly for all possible scenarios. In the Ubber app, the fare calculation aglorithm includes a loop iterating over various variables such as trip time, distance between origin and destination, time spent stuck in traffic, and any additional Ubber fees.
> Q: what type of test coverage would suit this real-life situation the best?

> A: In this situation **Loop coverage** would involve testing algorithm with different combinations of the factors mentioned above to ensure the loop computes the correct price for each ride accurately. Note that this includes testing cases where the loop iterates multiple times, as well as where it does not iterate at all (e.g. very short trips).


## Statement Coverage
Imagine you are a medical device tester tasked to ensure the accuracy and reliability of a blood glucose monitoring system. This system consists of hardware components like the glucose meter and software components for display. Your goal is to ensure that each function and feature operates as intended, and that every line of code related to glucose level measurement, data storage, and UI interaction is executed at least once. This includes checking that the device correctly eads glucose levels, performs calculation accurately, displays them correctly, and handles inputs/errors appropriately.
> Q: what type of test coverage would suit this real-life situation the best?

// TODO not quite sure how to answer it best yet
> A: When achieving **statement coverage**, you ensure that the glucos monitoring system functions reliably 
By achieving statement coverage, you ensure that the blood glucose monitoring system functions reliably and meets regulatory requirements for accuracy and safety in medical devices.


