"Data associated files for:"			
"Clark TD, Raby GD, Roche DG, Binning SA, Speers-Roesch B, Jutfelt F, Sundin J (in prep) Ocean acidification does not impair the behaviour of coral reef fishes"			
"Clements JC, Sundin J, Clark TD, Jutfelt F. Meta-analysis reveals an extreme "decline effect" in the impacts of ocean acidification on fish behavior."


"Data script files for:"
"Yilin Bai u7457233"			

					
##################			
# DATA files			
##################			

			
### clark_paper_data.csv ###			
			
columnHeading		description	
-------------		-----------	
study			Code for each individual study
Authors			Authors of each paper	
Year (online)		Year the final paper was made available onlinegroups
Year (print)		Year the final paper was included in a journal volume/issue
Title			Title of each paper
Journal			Journal the paper was published in
Pub year IF		The journal impact factor for the year the paper was published; obtained from InCites Journal Citation Reports
2017 IF			The journal impact factor for 2017 (i.e., most recent journal impact factor); obtained from InCites Journal Citation Reports
Average n               Average sample size for the study; average of indiviudal sample sizes for the contol and experimental groups
Effect type             The type of effect concluded by the study regarding the effect of OA on behaviour; strong, weak, or no effect (see Supplementary Methods for details)
Climate (FishBase)      Climatic region for each species; obtained from FishBase
Env cue/stimulus?       Whether or not the experiment included a cue or stimulus in the experiment (olfactory, visual, auditory, or physical)
Cue/stimulus type       The type of cue or stimulus used
Behavioural metric      The specific measure of behaviour tested
Life stage              Life stage of the fish tested


*** Data used to Provides supplementary information to clark.et al(2020) data and is used for merging with clark.et al(2020) data.		
			
			
			
### OA_activitydat_20190302.csv ###			
			
columnHeading		description	
-------------		-----------	
loc			Location, and year, where the data were collected. AIMS = Australian Institute of Marine Science; LIRS = Lizard Island Research Station
species			Species name: acantho = Acanthochromis; Ambon = Pomacentrus amboinensis; Chromis = Chromis atripectoralis; Humbug = Dascyllus aruanus; Lemon = Pomacentrus moluccensis	
treatment		Elevated CO2 [CO2] (850-1,050 µátm) or control [Control] (400 - 450 µátm) groups
animal_id		Fish identity
sl			Standard length of the fish in mm
size			Size grouping of the fish, separated at 15 mm standard length into 'big' or 'small'
activity		Number of seconds the fish was active per minute, averaged across the duration of the trial
comment			Comment with notes on the origin of the data
			
*** Data used to provide fish activity information of Clark. et al. (2020) is provided for calculating mean and variance and merging with the data of Clark. et al. (2020)
			
			
			
			
### ocean_meta_data.csv	###		
			
columnHeading		description	
-------------		-----------	
study			Code for each individual study
Authors			Authors of each paper	
Year (online)		Year the final paper was made available onlinegroups
Year (print)		Year the final paper was included in a journal volume/issue
Title			Title of each paper
Journal			Journal the paper was published in
Pub year IF		The journal impact factor for the year the paper was published; obtained from InCites Journal Citation Reports
2017 IF			The journal impact factor for 2017 (i.e., most recent journal impact factor); obtained from InCites Journal Citation Reports
Average n               Average sample size for the study; average of indiviudal sample sizes for the contol and experimental groups
Effect type             The type of effect concluded by the study regarding the effect of OA on behaviour; strong, weak, or no effect (see Supplementary Methods for details)
Climate (FishBase)      Climatic region for each species; obtained from FishBase
Env cue/stimulus?       Whether or not the experiment included a cue or stimulus in the experiment (olfactory, visual, auditory, or physical)
Cue/stimulus type       The type of cue or stimulus used
Behavioural metric      The specific measure of behaviour tested
Life stage              Life stage of the fish tested
Species                 The species used in each individual experiment
ctrl.n                  Sample size of the control group
ctrl.mean               Mean of the control group
ctrl.sd                 The standard deviation of the control group, calculated from ctrl.vartype
oa.n                    Sample size of the experimental group
oa.mean                 Mean of the experimental group
oa.sd                   The standard deviation of the experimental group, calculated from ctrl.vartype


*** Data used to combine with the Clark. et al. (2020) data			
			
			
			
### meta-data_ocean_meta.csv ###			
			
*** Data used to explain the meaning of each column in the other three CSV files	
			

			
##################			
# SCRIPT files			
##################			
						
			
			
			
### Assignment_2.Rmd ###			
			
Annotated R script to examine the effects of elevated pH related to the activity for both control and treatment groups and do the meta-analyses	
			
			
			
