# SEC_fit
test model to predict coelution profiles to detect new interactions

PLAN: 
Develop a pipeline able to aligns SEC profiles to intensities from Metabolites across SEC fractions
1) generate a SEC profile (intesity/volume) 
2) generate algoritm to compare to the SEC profile, generate 2 differnt approaches
3) test the algorith with mock samples
  3.1 generate mock sec profiles to detect (Normal dist, poison dist and more n=2000 different curves generated automatically) 
4) evaluate quality of filtering with mock profiles
5) introduce errors in mock profiles and see if can reasing again (loop for errors and testing) 
6) generate metabolic intensity profiles and test with them. 
7) evaluate the whole process and report. 
