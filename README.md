# Fantasy Football Rankings Projections Using Advanced Metrics
Zach Brazil, Richard Charles, Adam Kiehl

## Directories
`Data`: Contains data frames, both scraped and generated.  
- masterDF[2018-2020].csv and masterDF[2021].csv scraped data frames from pro-football-reference.com  
- averages.csv generated by Averages.Rmd for prediction  
- predFull.csv full results generated by Testing.Rmd for use in paper  
`Deliverables`: Contains project deliverables to be submitted for grading  
- finalPresentation.Rmd along with exported .pdf file  
- finalPaper.Rmd along with exported .pdf file  
`Models`: Contains trained models saved as .rds files for use in testing  
- passydsModel.rds, passtdModel.rds, intModel.rds, and flModel.rds generated by Passing.Rmd  
- recModel.rds, recYdsModel.rds, recTDModel.rds, and recFLModel.rds generated by Receiving.Rmd  
- rushYdsModel.rds, rushTDModel.rds, and rushFLModel.rds generated by Rushing.Rmd  
`Plots`: Contains saved plots for presentation and paper  
`Scripts`: Contains the scripts for data collection and analysis  
- Averages.Rmd calculates player expected game stats for prediction  
- Passing.Rmd generates and validates models for passing stats  
- Receiving.Rmd generates and validates models for receiving stats  
- Rushing.Rmd generates and validates models for rushing stats  
- Scraping.Rmd scrapes initial data frames from pro-football-reference.com  
- Testing.Rmd predicts expected fantasy performances and tests against 2021 data  
`Tables`: Contains saved tables for presentation and paper  

## Project Flow
1. Scrape data from pro-football-reference.com using Scraping.Rmd  
2. Select 2018-2020 data as training set  
3. Fit and train models on training data in Passing.Rmd, Receiving.Rmd, and Rushing.Rmd  
4. Calculate expected game performance with Averages.Rmd  
5. Predict expected fantasy performance with saved models and test against 2021 data  
6. Report results in finalPresentation.Rmd and finalPaper.Rmd  
