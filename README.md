# Communicate Data Findings for Ford Gobike

### Which dataset you chose
- Ford GoBike System Data

The dataset has (2383421 rows, 18 columns) . Each row represents a bike ride / rental in the period of June 2017 to December 2018. The dataset contains different data type. Station names, 'user_type', 'member_gender' belong to the String type. To integer data belongs the 'member_birth_year' and the trips duration, which is also implied by the 'start_time' and 'end_time'. also the start and end stations coordinates are also included as numeric The dataset contains "ride-related" and anonymized data only, and includes the following dimensions and metrics:

- Trip Duration (seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
- Member Year of Birth
- Member Gender

### Main findings from the exploratory data analysis , and how you chose the results to put in your explanatory analysis.

segment the age values into age groups . Segments of ten years should work. 
start with 15 to 24 years, etc. till 95 to 100 year.  
should be adequate.
the most of the rides 84% were done by users of the subscriber type. 
Male users account for the most rides 74%, whereas female users account for 24%. 
Most users are from 25 to 34 years old. 
Unusual are some users with ages far above 100 years.
Female users used the service far less than male users 
Female users are generally younger than male users. 
The shows The relative distribution of age, that the values for age are denser distributed than for males.


```python

```
