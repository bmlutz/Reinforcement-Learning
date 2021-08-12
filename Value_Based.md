# Value-Based Approach

In value-based methods, we learn a value function, that maps a state to the expected value of being at that state. Because we are not training a policy with this approach
we need to define our policy and specify the policy behavior.

Two types of value-based functions: **State-Value** and **Action-Value**
* In **state-value** function, we calculate the value of a state.
* In **action-value** function, we calculate the value of state-action pair hence the value of taking that action at that state.

**Bellman Equation**:
An efficient method for calculating the expected value at each state. This equation is equivalent to the *sum of immediate reward + the discounted value of the state that follows*.
