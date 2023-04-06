# ga-bb
Multi-shop Idle Capacity Scheduling Method Based on Genetic Algorithm and Branch and Bound

XIE Zhi-qiang, XIA Ying-chun
School of Computer Science and Technology, Harbin University of Science and Technology, Harbin 150080

Abstract：Personalized products have variable BOM structures and complex processing parameters, making it difficult for a single workshop to meet such a wide range of processing parameters, and requiring cooperation with external workshops to expand capabilities of processing. Since each workshop has different loads and different idle periods, a hybrid scheduling method based on genetic algorithm (GA) and branch and bound (BB) is proposed to improve the utilization of the idle periods. Firstly, a dynamic rescheduling mechanism based on a hybrid optimization strategy is designed to transform the dynamic production process into a series of static scheduling problems that are continuous in time. Then, a constraint programming model with the objective of minimizing the total tardiness is established; Finally, GA and BB method are used to optimize the two phases of the scheduling process, that is, GA is used to generate a pre-scheduling scheme at each event moment, and the scheme is divided into the dispatched part, the to-be-dispatched part and the adjustable part, and the BB method is used to optimize the adjustable part during the execution period of the dispatched part. Google OR-Tools is used to verify the correctness of the proposed model. The simulation experiments show that the hybrid method obtains improvements on each instance compared to the single method, verifying that the proposed method is effective and feasible.

Key words： personalized product    multi-shop    idle capacity    tree constraint    dynamic scheduling

Cite

XIE Zhi-qiang, XIA Ying-chun. Multi-shop Idle Capacity Scheduling Method Based on Genetic Algorithm and Branch and Bound. Journal of Mechanical Engineering, 2022, 58(22): 462-472. DOI: 10.3901/JME.2022.22.462

谢志强, 夏迎春. 基于遗传算法和分枝定界的多车间空闲产能调度方法[J]. 机械工程学报, 2022, 58(22): 462-472. DOI: 10.3901/JME.2022.22.462
