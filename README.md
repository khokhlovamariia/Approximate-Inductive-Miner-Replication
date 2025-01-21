# Approximate Inductive Miner Replication
This repository contains the implementation, analysis, and documentation for the replication of the research paper: [An Approximate Inductive Miner](https://ieeexplore.ieee.org/document/10271971).

Authors: 
* Akgül Sükriye Aybüke
* Marampea Eleni
* Khokhlova Mariia
* Djedovic Mustafa
* Saborosch Philipp

# Results
![](https://github.com/khokhlovamariia/Approximate-Inductive-Miner-Replication/blob/main/results/fitness_comparison_barplot.png)
![](https://github.com/khokhlovamariia/Approximate-Inductive-Miner-Replication/blob/main/results/precision_comparison_barplot.png)
![](https://github.com/khokhlovamariia/Approximate-Inductive-Miner-Replication/blob/main/results/size_comparison_barplot.png)

# Usage
## Repo structure
* data/: Contains the input event logs in a compressed .zip archive.
* src/: Contains the source code for AIM and evaluating process models.
* results/: Stores the generated results, such as evaluation metrics and visualizations.

## Generating Results
After running the main script:
* Processed results (evaluation metrics like precision, fitness, and model size) are saved in the results/ folder.
* Visualizations (difference plots, bar charts) are also saved in results/.
* Event logs are extracted to data/. 


# Acknowledgement of sources
1. van Dongen, Boudewijn (2012): BPI Challenge 2012. Version 1. 4TU.ResearchData. dataset. https://doi.org/10.4121/uuid:3926db30-f712-4394-aebc-75976070e91f
2. Ward Steeman (2013): BPI Challenge 2013, incidents. Version 1. 4TU.ResearchData. dataset. https://doi.org/10.4121/uuid:500573e6-accc-4b0c-9576-aa5468b10cee
3. Ward Steeman (2013): BPI Challenge 2013, closed problems. Version 1. 4TU.ResearchData. dataset. https://doi.org/10.4121/uuid:c2c3b154-ab26-4b31-a0e8-8f2350ddac11
4. van Dongen, B.F. (Boudewijn) (2015): BPI Challenge 2015. Version 1. 4TU.ResearchData. collection. https://doi.org/10.4121/uuid:31a308ef-c844-48da-948c-305d167a0ec1
5. van Dongen, Boudewijn (2017): BPI Challenge 2017. Version 1. 4TU.ResearchData. dataset. https://doi.org/10.4121/uuid:5f3067df-f10b-45da-b98b-86ae4c7a310b
6. van Dongen, Boudewijn (2019): BPI Challenge 2019. Version 1. 4TU.ResearchData. dataset. https://doi.org/10.4121/uuid:d06aff4b-79f0-45e6-8ec8-e19730c248f1
7. van Dongen, Boudewijn (2020): BPI Challenge 2020. Version 1. 4TU.ResearchData. collection. https://doi.org/10.4121/uuid:52fb97d4-4588-43c9-9d04-3604d4613b51
8. de Leoni, M. (Massimiliano); Mannhardt, Felix (2015): Road Traffic Fine Management Process. Version 1. 4TU.ResearchData. dataset. https://doi.org/10.4121/uuid:270fd440-1057-4fb9-89a9-b699b47990f5
9. Mannhardt, Felix (2016): Sepsis Cases - Event Log. Version 1. 4TU.ResearchData. dataset. https://doi.org/10.4121/uuid:915d2bfb-7e84-49ad-a286-dc35f063a460
