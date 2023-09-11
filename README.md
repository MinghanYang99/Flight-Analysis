# Flight-Analysis
Overview:

This project aims to optimize the work allocation for an airline's flight crew, ensuring an equitable distribution of workload using a Genetic Algorithm (GA). By considering various factors like flight periods, departure/arrival times, and aircraft types, we achieved a significant increase in workload calculation efficiency and optimized work schedules.

Objective:

Efficiently distribute workload among flight crew members.
Compare the efficiency of Genetic Algorithm with other optimization methods, such as Random Algorithms.
Visually present the effectiveness and fairness of the optimized workload.

Methodology:

Data Collection:
Flight Details: Used flight periods, departure/arrival times, and aircraft types.

Genetic Algorithm:

Fitness Function: Based on the data, the workload for each crew member was computed.
Selection: Selected chromosomes from the population for the next generation.
Crossover: Combined two parents to form a new offspring (or children).
Mutation: Introduced slight random modifications in the chromosome's genes to ensure genetic diversity.

Visualization:

Histogram and KDE curve: To visualize and compare the distribution of workload before and after optimization.
Lorenz Curve: To evaluate the fairness of the workload distribution.

Results:

Achieved a 67% efficiency increase in workload calculation.
Optimized work schedules by 31.33% compared to Random Algorithms.
Enhanced client assessment of fairness and effectiveness by 82%.

Tools & Libraries Used:

Genetic Algorithm and Random Method
Libraries such as NumPy, Panda, Random for data cleaning and data processing
Libraries such as Matplotlib and Seaborn for visualization.
