# failure-to-replicate-the-superiority-effect-in-crowding


## Attribution and Citation
This dataset accompanies the study entitled "Failure to replicate the superiority effect in crowding." by Ozkirli, A., Pascucci, D., & Herzog, M.H. (2025). 
If you use this dataset, please cite the article properly.

## variables
The csv file includes cleaned "error" variable, along with raw data (participantid, condition, block, reliabilityT, reliabilityF, theta, resp, rt, flankerMinusTarget). The variables represent:
- participantid : unique identifier for the participants
- condition: flanked (vertical_2-flanker) or unflanked (vertical_0-flanker)
- block: block number
- reliabilityT: reliability of the target, 0 if rounded, 1 if elongated
- reliabilityF: reliability of the flankers, 0 if rounded, 1 if elongated, NaN in unflanked conditions
- theta: actual target orientation (deg), where 0 is vertically oriented
- resp: reported target orientation (deg), where 0 is vertically oriented
- rt: reaction time
- flankerMinusTarget: the acute angle between the orientations of the target and flankers 
- error: resp-target (acute angle), minimally preprocessed as described in Cicchini et al. 2022 (exclude trials where rt<0.5 or >3 secs)
