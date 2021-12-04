# GeneralizedAdvantageEstimateCalculator
Calculating advantages, especially when many agents are considered at the same time, can be confusing.
Here is the correct way to calculate the target values (how valuable the state is) of the next update for critic network. In order to find the GAE / advantage, subtract the new values by the old values.
