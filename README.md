# Crime-SQL-Project
Exploring Chicago_Crime Dataset With SQL

"""
SELECT primary_type, location_description, count(*)
FROM
  `bigquery-public-data.chicago_crime.crime`
group by primary_type, location_description
order by count(*) DESC;
"""
