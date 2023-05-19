# Owkin data challenge 2023

3-day Data challenge, hosted by Owkin, at Mines Paris PSL.

Scored 2nd place submission on the private academic LB (Private LB = 0.6167).

Link to the competition overview and data : https://challengedata.ens.fr/participants/challenges/98/

Team name : c_est_la_baseline

## References

- Maximilian Ilse, Jakub M. Tomczak, Max Welling, "Attention-based Deep Multiple Instance Learning", https://arxiv.org/abs/1802.04712
- MIL review https://mars-tin.github.io/archives/reading/multiple_instance/
- "Multiple Instance Learning: A Survey of Problem Characteristics and Applications" https://arxiv.org/pdf/1612.03365.pdf
- "Multiple instance classification: Review, taxonomy and comparative study" https://www.sciencedirect.com/science/article/pii/S0004370213000581

## Notes

- The architecture is the result of multiple iterations of architecture tests. Compared to most teams which overfitted to the public test set, our model achieves poorer score on the public LB, but much better generalization score on the private test set (strong discrepancies).
- This repo is work in progress : it hasn't been cleaned since the competition.
