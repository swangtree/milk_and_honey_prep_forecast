# Introduction
*Made by Samuel Wang [(github.com/swangtree)](https://github.com/swangtree) for Milk and Honey cafe*

To clean data run `data_preprocess.ipynb`

# Front end:
Need: data visualizations for most popular orders, most popular times of year, effects of weather, etc

Would be nice to be able to say on front page the amount of ingredients to prep for boba based on weather data, day of year, if there's a special, etc.

# Back end:
SQL database w/ orders, weather, school day/week/semester, etc.

Would be nice for database to automatically be updated from google sheets in live time or on refresh

## To do:
- [x] Data clean
    - [x] Explore raw data forms
    - [x] Identify data quality issues (missing values, inconsistencies)
    - [x] Standardize order names and ingredients
    - [x] Clean and format dates/times
    - [x] Handle outliers and anomalies
    - [x] Document data cleaning process

- [ ] Data exploration
    - [ ] Basic statistical analysis
    - [ ] Time series analysis of order patterns
    - [ ] Weather correlation analysis
    - [ ] Seasonal trends investigation
    - [ ] Customer behavior patterns
    - [ ] Popular combinations analysis
    - [ ] Create visualization prototypes

- [ ] Database creation
    - [ ] Sketch database designs
    - [ ] Define entity relationships
    - [ ] Create database schema
    - [ ] Set up PostgreSQL/MySQL database
    - [ ] Create tables and relationships
    - [ ] Implement data validation rules
    - [ ] Set up automated Google Sheets sync
    - [ ] Create backup procedures

- [ ] Frontend Development
    - [ ] Design wireframes
    - [ ] Create responsive dashboard layout
    - [ ] Implement data visualizations
        - [ ] Daily/weekly/monthly trends
        - [ ] Popular items charts
        - [ ] Weather impact visualization
        - [ ] Inventory prediction model
    - [ ] Build ingredient prep calculator
    - [ ] Add user authentication
    - [ ] Create admin interface

- [ ] Backend Development
    - [ ] Set up API endpoints
    - [ ] Implement data processing logic
    - [ ] Create caching system
    - [ ] Set up weather data integration
    - [ ] Implement real-time updates
    - [ ] Create documentation
    
- [ ] Testing and Deployment
    - [ ] Write unit tests
    - [ ] Perform integration testing
    - [ ] Load testing
    - [ ] Security audit
    - [ ] Deploy to production
    - [ ] Monitor performance
    - [ ] Create user guides