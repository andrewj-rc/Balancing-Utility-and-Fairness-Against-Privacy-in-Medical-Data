This repositiry contains the raw data form the experiments performed for the paper: 

'Understanding Effects of Mitigation on De-identified Data' 

This was presented for the conference: IEA/AIE 2021 (The 34th International Conference on Industrial, Engineering & Other Applications of Applied Intelligent Systems)

The raw data is a .csv file containing the experimental results:

All tests were preformed by taking the mean of 10 random sets.  Due to the necessitiy on have examples in each privileged and unprivilged group with both positive and negative out comes specific permissable random seeds were selected to produce this result. These were the values used fo rthe random splits using Sci-kit learn's train/test split. [40146, 20613, 8530, 42664,  2585,  8930, 29868, 22414, 7658, 2022]

The data for figures 2 and 3: are contained in 'figures_2_3_real_world_data.csv'

The data for figures 4(a), 4(b), and 4(c): are contained in 'figures_4_synthetic results.csv'

The data for figures 5(a) and 5(b) sue the same data as figures 2 and 3 but these results were compared on a classification threshold represented here:

class_thresh_arr = [0.01, 0.01989899, 0.02979798, 0.03969697, 0.04959596,
	       0.05949495, 0.06939394, 0.07929293, 0.08919192, 0.09909091,
	       0.1089899 , 0.11888889, 0.12878788, 0.13868687, 0.14858586,
	       0.15848485, 0.16838384, 0.17828283, 0.18818182, 0.19808081,
	       0.2079798 , 0.21787879, 0.22777778, 0.23767677, 0.24757576,
	       0.25747475, 0.26737374, 0.27727273, 0.28717172, 0.29707071,
	       0.3069697 , 0.31686869, 0.32676768, 0.33666667, 0.34656566,
	       0.35646465, 0.36636364, 0.37626263, 0.38616162, 0.39606061,
	       0.4059596 , 0.41585859, 0.42575758, 0.43565657, 0.44555556,
	       0.45545455, 0.46535354, 0.47525253, 0.48515152, 0.49505051,
	       0.50494949, 0.51484848, 0.52474747, 0.53464646, 0.54454545,
	       0.55444444, 0.56434343, 0.57424242, 0.58414141, 0.5940404 ,
	       0.60393939, 0.61383838, 0.62373737, 0.63363636, 0.64353535,
	       0.65343434, 0.66333333, 0.67323232, 0.68313131, 0.6930303 ,
	       0.70292929, 0.71282828, 0.72272727, 0.73262626, 0.74252525,
	       0.75242424, 0.76232323, 0.77222222, 0.78212121, 0.7920202 ,
	       0.80191919, 0.81181818, 0.82171717, 0.83161616, 0.84151515,
	       0.85141414, 0.86131313, 0.87121212, 0.88111111, 0.8910101 ,
	       0.90090909, 0.91080808, 0.92070707, 0.93060606, 0.94050505,
	       0.95040404, 0.96030303, 0.97020202, 0.98010101, 0.99]
