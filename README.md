## Dynamic Segmentation 
- This process is to conduct dynamic segmentation on the tables in RIM, the result of which will be a mashup table.

- The total number of input tables is 33, in the context of LRS they are treated as events.

- 31 events are going to be considered as line features, the rest 2 (LEAVE_REENTER, SEGMENT_DESCRIPTION) will be point features.

- The 31 events will be injected into the LineOnLine processer as normal procedure for dynseg.

- The rest 2 events will need to create point features based on their attributes and certain rules, these geographic features will be used to further segment the result of the previous step. 

- Key attributes of the 2 events will be appended using FeatureMerger after correct coordinates have been extracted and assigned to measure columns.

:+1:
