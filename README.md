I analyzed this dataset via Google Cloud's BigQuery feature. At there, there are free datasets from Kaggle with this query.

"""
SELECT primary_type, location_description, count(*)
FROM
  `bigquery-public-data.chicago_crime.crime`
group by primary_type, location_description
order by count(*) DESC;
"""

In the CSV file that I attached, you can see the results.

At the top side, "THEFT" as a primary_type and "STREET" as location_description data is located. This means, in Chicago "theft on the street" is from 2001 to present day is the most committed crime.
You can see the whole ordering with downloading the .CSV file.
