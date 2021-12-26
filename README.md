# notsosmart-contract


## Problem description

1. an entity generates gems 
2. gems area created over time each with a numerical id that's generated with some unknown logic
3. each gem goes through a limited set of known mutations over a period of time at unknown intervals
4. the entity provides a rate limited API for querying gems. it takes gem id as a required parameter
5. knowing all the gem ids, their mutations, and when each mutation happened is valuable to a set of people (value A)

Goal: Motivate (and reward) people to contribute to value A.

Question: how, if at all, could using smart contracts help this goal?
