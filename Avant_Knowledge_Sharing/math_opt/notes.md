# Preparation Notes for Mathematical Optimiztion / Mixed-Integer Programming Knowledge Sharing

### [MIP Podcast](https://www.youtube.com/watch?v=9GU384msb6g&feature=youtu.be) with Dr. Edward Rothberg, CEO and Co-founder of Gurobi
- Goal of optimization
  - Maximize/mimize some goals/objectives subject of a set of constraints, which often come from the fact that activities need to be planned to compete for resources (budgets, machines, workers, etc).
  - **Reason** to use math. opt. is that often times the number of potential/feasible solutions can be astronomical, such that it is prohibited to use brute-force or naive method to find the optimal solution.
- Drives for adoptions of optimization/MIPs.
  - More data from businesses and increased computational powers.
- Examples of industries where optimization/MIPs are used.
  - Supply chain planning, in which all sorts of plans for producing and delivering certain products are computed, including facility allocation, scheduling, etc. 
  - [Electricity market](https://en.wikipedia.org/wiki/Electricity_market). Matching buyers and sellers to balance power consumptions and productions.
    - [Unit Commitment Problem](https://en.wikipedia.org/wiki/Unit_commitment_problem_in_electrical_power_production)
    - Security-constrained unit commitment model.
  - Sports scheduling
    - Create schedules of the season to minimize travels subject to stadium availablities and other constraints.
- Machine learning + optimization
  - Use machine learning and optimzation **in conjunction**. For example, retail shopping centers make product replacement and discount/on-sale decisions to maximize revenue. Use machine learning to predict customer's response to certain actions, and then use optimization to plan sales strategies.
  - Use optimization to solve machine learning problems, such as the best sub-set regression (See [Best Subset, Forward Stepwise, or Lasso? Analysis and Recommendations Based on Extensive Comparisons](https://www.stat.cmu.edu/~ryantibs/papers/bestsubset.pdf))
- Challenges for data scientists to use optimization
  - Recognizing the optimization problem.
  - A little bit of exposure to optimization, add optimization to the data science toolbox.


### References
- [Data Science Central Podcast - MIP: Briging Decisions to Data Science](https://www.youtube.com/watch?v=9GU384msb6g&feature=youtu.be)
