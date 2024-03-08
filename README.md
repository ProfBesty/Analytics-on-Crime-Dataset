![image](https://github.com/ProfBesty/Analytics-on-Crime-Dataset/assets/147350441/ef749e70-b8a2-4306-825c-60bbe5b256a3)

In our world today, crime is a big problem, and it's getting worse. This makes it hard for police officers everywhere to do their job. To make things better, they need to use new technologies and look at data more closely. This story talks about how looking at crime data can help police do a better job in a big city.

Interact with the final dashboard here:

- [Smart Crime Report](https://github.com/ProfBesty/Analytics-on-Crime-Dataset/assets/147350441/79549796-985d-47f1-b2f9-88b6feb12631)


View Students' Project Gallery


<h1>Problem Statement</h1>

The big-city police department I work with is facing more and more crime, and they want to find better ways to stop it before it happens. They asked our company, Datafied Technologies, for help using data analysis to learn about crime patterns, where crime might happen a lot, and how to stop it from happening. As a junior data analyst at Datafied Technologies, my job is to:

- Figure out crime patterns and trends using data.
- Find out where crime might happen a lot using data.
- Make plans for stopping crime better using what we learn from the data.

<h1>Data Sourcing</h1>

The data we have comes from the police and covers crime from March 2013 to 2023. It's considered very reliable and follows strict rules set by the Home Office. This makes sure the information is fair and meets professional standards for statistics.

(![Imageeee](https://github.com/ProfBesty/Analytics-on-Crime-Dataset/assets/147350441/cf5ccc1d-f96c-4f77-acc5-5d7f78bf685f)

The regions under study include all areas in England and Wales:

- East Midlands Region
-Eastern Region
- London Region
- North East Region
- North West Region
- South East Region
- South West Region
- Wales
- West Midlands Region
- Yorkshire and the Humber

These regions encompass all police forces and community safety partnerships (CPS).

<h3>Data source</h3>


- [Crime Records](https://docs.google.com/spreadsheets/d/1mCdPRU2TMxb9Z_g_iDUT373bE_mB7GPEA7mKWHYMiTc/edit?usp=sharing)
- [Location Data](https://docs.google.com/spreadsheets/d/1DXLOKdN-O6a4rYjn1c2tKtNt5dIe9_op1TH1smUXitM/edit?usp=sharing)


<h1>Project Objective</h1>
The project's successful implementation will enable the police department to make informed decisions, resulting in significant enhancements in crime prevention and law enforcement effectiveness. This not only revolutionizes conventional policing techniques but also highlights the importance of proactive, data-driven strategies in tackling the changing dynamics of crime in urban settings.

<h1>Data Transformation and Cleaning</h1>
By eliminating duplicates, filtering rows and columns, rectifying inconsistencies, and validating data format, the dataset underwent a comprehensive cleaning process, ensuring its readiness for analysis and visualization tasks.

**Dataset Before Cleaning**
![Data before cleaning](https://github.com/ProfBesty/Analytics-on-Crime-Dataset/assets/147350441/6825eff0-48e8-49c4-a9b7-1fdff1a3a4e0)

**Dataset After Cleaning**
![Data after cleaning](https://github.com/ProfBesty/Analytics-on-Crime-Dataset/assets/147350441/7916cc9f-121f-4247-b1ec-6de0d0ffef5e)

<h1>DATA MODELING</h1>
I Identified dimensions for analysis breakdown and this led to the creation of new tables. 
These tables include the 
- Offence dimension
- Date dimension and 
- Location dimension.

The Star Schema data model was adopted in this instance
![image](https://github.com/ProfBesty/Analytics-on-Crime-Dataset/assets/147350441/d6fb9f55-4283-49c5-a57e-5a348b939ee8)



