I analyzed this dataset via Google Cloud's BigQuery feature. At there, there are free datasets from Kaggle.

"""
SELECT primary_type, location_description, count(*)
FROM
  `bigquery-public-data.chicago_crime.crime`
group by primary_type, location_description
order by count(*) DESC;
"""
