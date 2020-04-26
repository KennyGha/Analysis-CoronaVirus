# Analysis-CoronaVirus

TODO :  Text Mining from Tweet datasets - Key words extraction , Sentiment Analysis by Countries Level
        then compare the result with the Confirmed Rate
        Find the correction between Text and Confirmed Rate

        Study Andrew Ng New-Course Corona Virus and seeking input for this model
        
        
Goal :

Due to the current crisis that Corona Virus spread over the world. Here the goal of this analysis is to find out demographic distribution and current status across nations

First part of the analysis will be in individual level in term of age, country and gender

Second part will analysis from World Health Organization data in country level

* Find out current trend
* Calculating Recovered and Death rate

Tools

    Spark have used for data aggregation
    AWS S3 have been used for file storage purpose and as Data Lake
    Airflow will be used for data refresh scheduling

Data Update Behaviour

    Data will be refreshed in full rather than delta due to data source nature

Step

Step 1 : Gather individual level information from varies datasets for some countries in Kaggle and consolidate them into DB schema (Section - Dataset Schema). This schema has general information such as Age, Confirmed infected Date, Gender and Present location,etcs. You may find detail in section Dataset Schema.

(*Provide user flexibility whether to download updated data from Original datasource or Download it from S3)

Step 2: Aggregate step 1 resource and analysis demographic information

Step 3: Gather World Health Organisation (WHO) data in country level

Step 4: Calculating Ratios for analysis

Step 5: Gather additional data from Oxford - UK government for time series event

Step 6: Combin WHO data with step 5 and check whether those actions effectiveness
Source Link

novel-corona-virus-2019-dataset https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset

covid19-in-india https://www.kaggle.com/sudalairajkumar/covid19-in-india

coronavirusdataset https://www.kaggle.com/kimjihoo/coronavirusdataset

covid19-in-italy https://www.kaggle.com/sudalairajkumar/covid19-in-italy

corona-virus-brazil https://www.kaggle.com/unanimad/corona-virus-brazil

covid19-in-usa https://www.kaggle.com/sudalairajkumar/covid19-in-usa

covid19-cases-switzerland https://www.kaggle.com/daenuprobst/covid19-cases-switzerland

indonesia-coronavirus-cases https://www.kaggle.com/ardisragen/indonesia-coronavirus-cases

Novel Corona Virus 2019 Dataset https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset/tasks
