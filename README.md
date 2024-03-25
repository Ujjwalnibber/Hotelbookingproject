**Problem Statement**

 Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was 
 likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions!
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, 
the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.
Explore and analyze the data to discover important factors that govern the bookings.

**Project Summary**

In this EDA project we shall be exploring data to discover important factors that govern booking.We shall look at all the factors analyze them and pen down our observations. Exploratory Data Analysis (EDA), 
also known as Data Exploration, is a step in the Data Analysis Process, where a number of techniques are used to better understand the dataset being used.There are some main component of EDA,these are:

Knowing your variables
Cleaning your dataset
Studying/Understanding relationship between variables
I have started by first importing relevant libraries and then mounting data set. Once I have succesfully done ,then I started studying and understanding my data set like knowing shape,what each variable represents,
what kind of values are present in column,what kind of datatype is preswent in columns.

As a data analyst one spends 60%-70% of time cleaning data, this steps is most cruical. We shall make relevant changes to dataset in this step. I had done all the changes in dataset to copy of data(df_hotel) and 
not original dataset( hotel_data) as a precautionary measure. I have sarted by first removing duplicate rows, followed by finding if there are any null values and if they are there then handling them.Once done
handling null value ,I have made some changes by converting some columns into relevant data types.Further I felt some columns can be clubbed to have better understanding and some can be dropped for the same reason.
Last thing done by me was handling outliers in dataset.Once I have done cleaning , I proceeded further to start EDA.
The first thing I like to do when analyzing my variables is visualizing it through a correlation matrix because its the fastest way to develop a general understanding of all of my variables,followed by Univariate and bivariate analysis.Visualization is one of key factor that helps us undersatnding relationships,making conclusion or understanding trends.I have drawn all conclusions with help of different types of charts like scatter plot,bar charts , pie charts. In Univariate analysis indiviual column/variable has been picked up and analysis has been made like which hotels city or resort are preferred, which hotel has high cancellation rate. In Bivariate analysis two columns have been picked up and their effect on each other is seen and coclusion is drawn how they are related.Various observation like the busiest month of year,type of room preferred by guest are observed and conclusion is made how to make best use of these observation in order to have better revenue. Such analysis help us to find various factors that helps revenue to go up, like which agent is bringing more business,which kind of hotel is preferred. The companies can use such conclusions and make better revenue hence solving the purpose of doing EDA.

We have conclusions about various factors affecting booking like month of year,room type.To know more conclusion kindly refer last segment of the project.

**Conclusion**

There are two types of Hotel : Resort and City

City Hotel is preferred over Resort Hotel

72.48% hotels are not cancelled

2016 is year with most booking

61.07% of daily revenue is earned by city hotel and 38.93% by resort hotel

96.14% guests are not repeated while only 3.86% guests are repeated.

August is the busiest month of the year.

Approximately 75% customer are transient type.

BB is most preferred meal type.

TA/TO is highest distribution channel.

Agent 9 has made most booking.

City Hotel have higher waiting time and higher ADR.

As number of people increases adr increases telling both are postively related.

Total stay on an average is less than 4 days for both the hotel types.
As number of days of stay increases adr decreases.
