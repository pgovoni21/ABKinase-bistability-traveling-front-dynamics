# Bistability &amp; Traveling Front Dynamics in the Cell Cycle Regulatory Protein, Aurora B Kinase

## MSc Thesis in Biophysics & Biochemistry 

**Author:** Me, Patrick Govoni <br>
**Supervisor:** Prof. Lendert Gelens <br>
**Affiliation:** Department of Cellular and Molecular Medicine 
**Group:** Dynamics in Biological Systems <br>
**Academic Year:** 2020-2021 <br>

Mass-action model taken from: <br>
Zaytsev, Anatoly V., et al. "Bistability of a coupled Aurora B kinase-phosphatase system in cell division." elife 5 (2016): e10644.

### This collection of Jupyter Notebook files walk through the exploration of kinase-phosphatase dynamics concerning Aurora B kinase as described in my master's thesis, mirroring the theoretical/simulation sections of the report by:

- comparing activation & inactivation (positive & negative) feedback loops and the bistability that results from their balance in the reaction network (4.1)
- using both a fully defined mass-action model as well as a simpler phenomenological model (4.2)
- combining diffusion with bistable reaction kinetics to produce traveling front behavior (6.1)
- relating the model to figures in Zaytsev's paper, finding simulated traveling front behavior only relevant on a much larger scale than observed in vivo (6.3)
- finding traveling front behavior relevant to the centromeric localization force by lowering diffusion, creating an interesting stalling behavior (6.4)
- switching to the phenomenological model to find kinase valleys between centromere + chromosome arms to cause the stalling (6.5)
- describing the stalling via geometric analysis as a transient approach to an energetic equilibrium, or Maxwell point (6.6)
- moving back to the mass-action model to explain phosphatase as well as kinase dynamics (6.7.1)
- as well as the effects of fixing phosphatase and of an altered binding site profile on the system (6.7.2)

Note: Several simulations in the report take a significant amount of time to run, as noted in the relevant cells. Due to Github file size limits and repository size recommendations, the associated data files have not been uploaded. Feel free to reach out to me if you would like to look at the data without taking the time to run those cells!
