# Homework Assignment Module 12 - NoSQL

## Description

`NoSQL_setup_starter.ipynb` contains the importing and cleanup of the `establishments` collection to MongoDB.

`NoSQL_analysis_starter.ipynb` contains various analyses of the `establishments` collection: documents where hygiene scroe is equal to 20, documents where local authority is in London and are rated 4* or higher, documents where the stores are located within a 2.22km-sided box centered on the store location of the document we added in the setup, and the count of documents where the hygiene score is 0, grouped by local authority.

## Notes

Question 3 of the analysis returned zero results. I originally thought this might have been my fault, so I included an extra cell of using pure Python to double check the results, which held out. If I was supposed to have a result, then either my database was flawed, or the directions were not clear on what "within 0.01 degree on either side of the latitude and longitude" meant.

### Sources

No code was copied/reused from external sources
