HOW TO RUN:
(this assignment has these dependancies which are pandas, numpy ,openpyxl,so make sure they are installed)
put the folder assignment1 on desktop
open assign1.sh file,in the file there will be 9 cd commands each having [putYourComputersName] as a part,  replace them with your computers name and remove the brackets , then save and close it
now open a terminal while in the assignment1 folder then type ./assign1
(now if it shows permission denied then type  chmod +x assign1(this will make the file executable)
then type ./assign1 in the terminal and it should run)
this command will run all the files and the csv's will be saved in their respective folders
(i've put each question in separate folders and all the required files is also in their respective folders so no clutter is formed)
i've also included scripts in each folder ,so to run the files in any any specific folder cd into that folder and run the script file by typing the name of the script file after ./ in terminal,
the resultant csv's will be saved in the current folder
 



CONTENTS:
1) this folder has a neighbor.sh file which runs the neighbor.py file which uses cowin_vaccine_data_districtwise.csv and neighbor-districts.json
   when you run the sh file it should create a new json file with the said modification and will be named neighbor-districts-modified.json.

2) this folder has a edge-generator.sh file which runs the edge-generator.py file which uses the neighbor-districts-modified.json from the previous question , run the sh file and you should get 
   edge-graph.csv.

3) this folder has a case_generator.sh which runs case_generator.py file which uses neighbor-districts-modified.json , districts.csv, cowin_vaccine_data_districtwise.csv, when you run the sh file you should get three csv files named cases-week.csv , cases-month.csv and cases-overall.csv.

4) this folder has a peaks-generator.sh which runs peaks-generator.py file which uses neighbor-districts-modified.json, districts.csv, distkeytodisrtname.csv(i have made this as a helper file which maps districtid to district names),when you run the sh file you should get three csv files named peaks_district.csv , peaks_months.csv and peaks_overall.csv.

5) this folder has a vaccinated-count-generator.sh file whic runs vaccinated-count-generator-district.py file which uses cowin_vaccine_data_districtwise.csv, helper.csv(which this code use for the distinct disrtrict names) and vaccinated-count-generator-state-overall-sh.ipynb which uses cowin_vaccine_data_districtwise.csv,after running the sh file you should get six csv's named vaccinated-count-district-overall.csv (i've replaced the inf's with NaN which might not show in the csv file), vaccinated-count-district-weekly.csv, vaccinated-count-district-monthly.csv,vaccinated-count-state.csv,vaccinated-count-state-monthly.csv,vaccinated-count-state-weekly.csv.
   
6) this folder has a vaccination-population-ratio-generator.sh file whic runs the vaccination-population-ratio-generator.py file which uses cowin_vaccine_data_districtwise.csv and DDW_PCA0000_2011_Indiastatedist.xlsx, upon running the sh file you should get three files csv files namely vaccination-population-ratio-districts.csv , vaccination-population-ratio-states.csv and vaccination-population-ratio-overall.csv.

7) this folder has a vaccine-type-ratio-generator.sh file which runs the vaccine-type-ratio-generator.py file which uses cowin_vaccine_data_districtwise.csv and DDW_PCA0000_2011_Indiastatedist.xlsx, upon running the sh file you should get three csv's namely vaccine-type-ratio-generator-districts.csv , vaccine-type-ratio-generator-states.csv and vaccine-type-ratio-overall.csv

8) this folder has a vaccinated-ratio-generator.sh file which runs the vaccinated-ratio-generator.py file which uses cowin_vaccine_data_districtwise.csv and DDW_PCA0000_2011_Indiastatedist.xlsx, upon running the sh file you should get three csv's files namely vaccinated-dose-ratio-state.csv , vaccinated-dose-ratio-district.csv and vaccinated-dose-ratio-overall.csv

9) this folder has a complete-vaccination-generator.sh file which runs the complete-vaccination-generator.py file which uses cowin_vaccine_data_districtwise.csv and DDW_PCA0000_2011_Indiastatedist.xlsx, upon running the sh file you should get complete-vaccination.csv




















































