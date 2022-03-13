# cs50-finalproject

This is my final project for CS50x 2022.

I want to use all of the elements from the CS50 course, so my aim for this project is to build a web application with a backend running on Flask / Python and with the frontend running on HTML, CSS, and JavaScript, possibly using Bootstrap too.

I will be basing this project on the Solita Dev Academy pre-assignment for 2022, a repository for which can be found at solita/dev-academy-2022-exercise. The aim of the exercise is to build a functional web application that stores and displays data from a number of farms and is received in the form of CSV files.

The final application will include the following features, as taken from Solita's README file:
## Backend
- CSV parsing and validation
- Endpoints to fetch data from farms with different granularities (by month, by metric)
- Aggregate calculation endpoints, endpoint which returns monthly averages, min/max and other statistical analysis
- Add tests
- Input and output validation
## Frontend
- Show data in table format
- Add filtering options
- Add tests (fex. React testing library)
- Show data in graphs
- Nice to have
- Endpoints to store new farms and new data
- Add User management
- Running backend in Docker
- Running backend in Cloud
- Add a map which shows the location of the farms and which can be interacted with (you can decide where the farms are)
- Add E2E tests
- Add UI for adding data to farms and creating new farms
- Add User login for data manipulation
## Validation rules
- Accept only temperature,rainfall and PH data. Other metrics should be discarded
- Discard invalid values with next rules
- pH is a decimal value between 0 - 14
- Temperature is a celsius value between -50 and 100
- Rainfall is a positive number between 0 and 500
- Data may be missing from certain dates
