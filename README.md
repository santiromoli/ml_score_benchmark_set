# Benchmark set from "Assessing the robustness and scalability of machine learning methods to accelerate ultra-large high-throughput docking campaigns" study.

Molecular docking scores of the 10M molecule library docked with PLANTS and AutoDock Vina in 10 protein target systems are provided in two separate zip files.

Each zip files contains one csv file with the following columns: SMILES,fa7,abl1,adrb2,esr1_ant,fabp4,pa2ga,pnph,prgr,ptn1,urok.

The first column indicates the SMILES of each molecule of the 10M library. Each of the following columns corresponds to the docking scores for the corresponding target (name of the column- see Table 2 from paper).

As their names suggest, E10M_plants_docking.csv contains PLANTS docking scores, and E10M_vina_docking.csv contains AutoDock Vina scores.



