# DataPreprocessing
Some Data Preprocessing Exercises (cleaning, blending, manipulation)

1. datablending using pandas
    - *file*s: datablending.ipynb and wits_en_trade_summary_allcountries_allyears.zip
    - *goal*: combine all world trade summaries per country from path to one csv file using pandas
    - *process*: 
      - read each file from path by line. 
      - append columns 0 to 16 to rowlist. (includes metadata and years 2006-2015 only... 10 year span. extend as needed.)
      - append rowlist to finallist.
      - iterate. when done proceed to next step.
      - convert finallist to pandas dataframe.
      - save dataframe to csv
      - as needed: melting process to convert from wide to long using pandas.melt() **i needed this for proper tableau input format**
