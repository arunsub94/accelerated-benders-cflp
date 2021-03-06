# accelerated-benders-cflp
An accelerated Bender's decomposition approach to solve a two-stage stochastic model of a formulate a capacitated facility location problem with stochasticity in demand, supply and manufacturing capacities. 

Supply Chain is a well-researched area when it comes to application of Stochastic Programming to model and solve problems due to the inherently uncertain nature of demand, prices and costs. Stochastic modelling algorithms like Benders Decomposition are commonly used to solve Supply Chain network problems. Due to the problem size and large number of scenarios, convergence takes quite some time with these algorithms.   

Several methods to accelerate convergence have been proposed. In this paper, we will seek to emulate an Accelerated Benders Decomposition as discussed by Santoso et al. (2015). We formulate a capacitated facility location problem with stochasticity in demand, supply and manufacturing capacitites. We will then implement Cut Strengthening, Valid Inequalities & Trust Region methods to accelerate convergence, compare performance against Vanilla Benders & Level Methods and discuss the results. 
Index Terms—Supply Chain, Stochastic Programming, Accelerated Benders Decomposition

This was submitted as a research project for the University of Toronto course MIE 1612: Stochastic Programming offered by Prof. Merve Bodur. All code presented here is my work, please do not reproduce or copy without my permission. 
