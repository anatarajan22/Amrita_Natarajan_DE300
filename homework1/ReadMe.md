Task 1: The expected outputs should be tables summarizing where data is null, often sorted by ‘Carrier’, ‘Manufacturer’, or ‘Manufacture Year.’ The idea behind this was to visualize the data in terms of what looks similar in other categories aside from missing information. For Carrier, Carrier Name, Airline ID, and Number of Seats, imputation of a constant was applied while for Manufacture Year the median was imputed and for Capacity in Pounds the KNN method was implemented to use surrounding data points to approximate the missing ones. This includes KNN graphs to ensure imputed data closely resembles existing data, and for the medians barcharts to visualize where the median would fall before calculating it. 

Task 2: For Data Standardization, expected outputs would be tables of value counts for different manufacturers, models, aircraft_status, and operating status, especially for the first two in distinguishing between different carriers and manufacturers to better standardize the discrepancies. 

Task 3: Information was generated from the cleaned data set to determine the new amount of data. 

Task 4: The outputs in this section include the skew for Number of Seats and Capacity in pounds, followed by histograms for both and then the BOX COX adjusted histograms for both to allow comparison. 

Task 5: The output in this section is the value counts for each size (SMALL, MEDIUM, LARGE, XLARGE) and then barcharts representing the proportion of values (outcomes) in operating status and aircraft status at each given quantile. 
