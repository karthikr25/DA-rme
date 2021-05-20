# DA-rme

First run the glassdoor_scrapper and Web_scraping_jobs files. This will scrap the data from glassdoor and indeed job sites respectively and convert them to csv format. Since we have already extraceted the job entries from the web sites you may skip this step. Then we have cleaned the data extracted from these sites. Run data_cleaning and job_data_processing_eda files to clean glassdoor and indeed data respectively. The cleaned data is then stored in seperate csv files. This step has also been done and the cleaned data has been added as a part of our code and thus you may skip this step as well. The data_eda file and job_data_processing_eda files contain our exploratory data analysis step for glassdoor and indeed data respectively.  Before running the models download all requirements in the requirements.txt file. After this step you may run the models. The salary_modelling_master file contains the implementation of our classification models which is tf-idf and mixed input network model. Their accuracy has been compared. Since tf-idf model performed better the same has been used for final api. 
