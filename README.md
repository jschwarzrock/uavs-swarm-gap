# Solving task allocation problem in multi Unmanned Aerial Vehicles systems using Swarm intelligence

This project provides a simulation for the task allocation problem among UAVs. 
It was implemented in NetLogo (version 5.3.1).

It has four different task allocation algorithms:
- Swarm-GAP
- Allocation Loop (AL)
- Sorting and Allocation Loop (SAL)
- Limit and Allocation Loop (LAL)


Publication
-------------
 - Schwarzrock, J., Zacarias, I., Bazzan, A. L., de Araujo Fernandes, R. Q., Moreira, L. H., and de Freitas, E. P. (2018). Solving task allocation problem in multi unmanned aerial vehicles systems using swarm intelligence. Engineering Applications of Artificial Intelligence, 72, 10-20. https://doi.org/10.1016/j.engappai.2018.03.008


How to use
---------------------------------------
 - "run-n-times-all" button run all scenarios 
 - The "report.nls" file has the functions to run the scenarios and print the report.
 - The parameters of the scenarios are into the "input.nls" file.
 - The scenarios used in the article are available,  but you can also create new scenarios.
 - The other buttons ("setup", "go", and "run-n-times-all") allow quick tests.


Create a new random scenario
---------------------------------------
 - The button "create_new_random_setup" in the swarm-gap.nlogo file allows the user to create new random scenarios.
 - You can configure the parameters into the create_new_random_setup function (in base.nls file): the area size, how many UAVs, and how many tasks.
 - It will create the scenario, and next, the user will have to put it into the input.nls file.
 - Change the init_tasks function (base.nls) if you include scenarios with different numbers of tasks. 



