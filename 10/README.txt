1) this folder has a neighbor.ipynb file which uses cowin_vaccine_data_districtwise.csv and neighbor-districts.json
   when you run the ipynb file it should create a new json file with the said modification and will be named neighbor-districts-modified.json.

2) this folder has edge-generator-sh.ipynb file which uses the neighbor-districts-modified.json from the previous question , run the ipynb file and you should get 
   edge-graph.csv.

3) this folder has a case_generator_sh.ipynb file which uses neighbor-districts-modified.json , districts.csv, cowin_vaccine_data_districtwise.csv, when you run the ipynb file you should get
   three csv files named cases-week.csv , cases-month.csv and cases-overall.csv.

4) this folder has a peaks-generator-sh.ipynb file which uses neighbor-districts-modified.json, districts.csv, distkeytodisrtname.csv(i have made this as a helper file which maps districtid to district names),
   when you run the ipynb file you should get three csv files named peaks_district.csv , peaks_months.csv and peaks_overall.csv.

5) this folder has a vaccinated-count-generator-district-overall-sh.ipynb file which uses cowin_vaccine_data_districtwise.csv, helper.csv(which this code use for the distinct disrtrict names), 
   after running this ipynb code you should get vaccinated-count-district-overall.csv i've replaced the inf's with NaN which might not show in the csv file.
   this folder has another ipynb file named vaccinated-count-generator-state-overall-sh.ipynb which uses cowin_vaccine_data_districtwise.csv and upon running ,
   it should give vaccinated-count-state-overall.csv

6) this folder has vaccination-population-ratio-generator-sh.ipynb file which uses cowin_vaccine_data_districtwise.csv and DDW_PCA0000_2011_Indiastatedist.xlsx, upon running the code you should get
   three files csv files namely vaccination-population-ratio-districts.csv , vaccination-population-ratio-states.csv and vaccination-population-ratio-overall.csv.

7) this folder has vaccination-population-ratio-generator-sh.ipynb file which uses cowin_vaccine_data_districtwise.csv and DDW_PCA0000_2011_Indiastatedist.xlsx, upon running the code you should get
   three namely vaccination-population-ratio-districts.csv , vaccination-population-ratio-districts.csv and vaccination-population-ratio-overall.csv

8) this folder has vaccinated-ratio-generator-sh.ipynb file which uses cowin_vaccine_data_districtwise.csv and DDW_PCA0000_2011_Indiastatedist.xlsx, upon running the code you should get
   three files namely vaccinated-dose-ratio-state.csv , vaccinated-dose-ratio-district.csv and vaccinated-dose-ratio-overall.csv

9) this folder has complete-vaccination-generator-sh.ipynb file which uses cowin_vaccine_data_districtwise.csv and DDW_PCA0000_2011_Indiastatedist.xlsx, upon running the code you should get
   complete-vaccination.csv

10) this folder has readme.txt which tells how to use the code and has a assign.sh which runs the entire assgnment