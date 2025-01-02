# failure-to-replicate-the-superiority-effect-in-crowding
The dataset failing to replicate the findings in Cicchini et al. 2022 (Nature Communications)

The csv file includes cleaned "error" variable, along with raw data (participantid, condition, block, reliabilityT, reliabilityF, theta, resp, rt, flankerMinusTarget). The variables represent:
- participantid : unique identifier for the participants
- condition: flanked (vertical_2-flanker) or unflanked (vertical_0-flanker)
- block: block number
- reliabilityT: reliability of the target, 0 if rounded, 1 if elongated
- reliabilityF: reliability of the flankers, 0 if rounded, 1 if elongated
- theta: actual target orientation (deg), where 0 is vertically oriented
- resp: reported target orientation (deg), where 0 is vertically oriented
- rt: reaction time
- flankerMinusTarget: the acute angle between the orientations of the target and flankers 
- error: resp-target (acute angle), minimally preprocessed as described in Cicchini et al. 2022 (exclude trials where rt<0.5 or >3 secs)
