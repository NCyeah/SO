# A brief introduction to SO

The proposed Python file contains a Simulation-Optimization (SO) model which is developed to address the Stochastic Job-Shop Scheduling Problem (SFJSSP) of the photolithography work area. The photolithography work area is known as the bottleneck within the front-end fab of the semiconductor industry. Semiconductor industry is among the most capital-intensive businesses whose operational excellence is of vital importance. To elevate the performance of the whole semiconductor manufacturing system, developing a competent schedule for its bottleneck is essential. However, the re-entrant product flows, high uncertainties in operations times, and rapidly changing products and technologies within the photolithography, make it difficult to develop an schedule for the whole semiconductor fab. Hoeever, SO, as one of the hybrid methods in the era of industry 4.0 has proven its applicability in addressing complex production scheduling problems such as the SFJSSP of the photolithography work area. Our SO model encompasses a simulation model of the photolithography work area, along with a tailored Genetic Algorithm (GA). The GA incorporates a range of interconnected functions that collaborate to optimize the initially formulated schedule plan, generated by the simulation model, in each iteration of the GA.

The code consists of multiple functions representing different components of our SO model. Each function's purpose is briefly explained through comments within the code. Additionally, we have uploaded the necessary CSV files utilized by the first two functions, namely Operation_Dict and SetUpTime_Dict. These codes and accompanying CSV files are specifically related to problem id 1 in section 6.2.2 of the study.
