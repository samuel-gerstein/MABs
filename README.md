# MABs
Multi-Arm Bandits (MABs) with i.i.d, non-stationary, and federated bandit examples.

The paper (results.pdf) describes the first two parts of the experiment.
The presentation (Federated MAB.pptx) describes the federated bandit experiment. 

Projects: 
1. 10-armed Testbed (I.I.D.)
2. Applying MABs to non-I.I.D. ad optimization simulation.
3. Applying MABs to the daily change in cryptocurrency price for the top 100 cryptocurrencies. This problem is non-stationary, non-I.I.D., and extremely volatile.
4. Built a federated MAB framework based off of the Federated Averaging algorithm proposed in Communication-Efficient Learning of Deep Networks from Decentralized Data (McMahan et al.). This was then applied to the ad optimization simulation, where the server should not know the exact clicks of its users.
