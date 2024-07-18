# CASE STUDY

As a data engineer at a travel agency, you have been tasked with integrating data from a public REST API for countries information. This data will be used to recommend travel destinations to our customers based on some different factors like language, continents, regions, currency and many more

- Extract the world country data from this API https://restcountries.com/v3.1/all
- Extract the below fields/attributes/columns
  - Country name
  - Independence
  - United Nation members
  - startOfWeek
  - Official country name
  - Common native name
  - Currency Code e.g USD, EUR
  - Currency name
  - Currency symbol
  - Country code ( idd ) . e.g Germany country code is +49
    - you need to concatenate idd root and idd suffix from the response
  - Capital
  - Region
  - Sub region
  - Languages
  - Area
  - Population
  - Continents
- Do the required transformation
- Load to your preferred Database
- Use your creativity to draw out some insight out of the data ( REALLY IMPORTANT )
- Use the data extracted to answer the below questions
  - How many countries speaks French
  - How many countries speaks english
  - How many country have more than 1 official language 
  - How many country official currency is Euro
  - How many country is from West europe
  - How many country has not yet gain independence
  - How many distinct continent and how many country from each
  - How many country whose start of the week is not Monday
  - How many countries are not a United Nation member
  - How many countries are United Nation member
  - Least 2 countries with the lowest population for each continents
  - Top 2 countries with the largest Area for each continent
  - Top 5 countries with the largest Area
  - Top 5 countries with the lowest Area

# OPTIONAL
- Present the above questions in any Visualization tool

# PROJECT REQUIREMENTS
- Dedicated git repository needs to be created for the project
- Decent ReadMe should be included in the Git repository as means of Documentation 
- Have an architecture flow as part of the ReadMe 
  - This allows people to understand the ETL/ELT from a first look.
- Visible collaboration among team should be balanced reasonably 
  - Meaning, all members must contribute
 
# GRADING METRICS
- Code best practices
- Choice of tools
- Document the thougbiht process and the reason for architectural design and choice of tools
- How easy to run the code submitted

# MEANS OF SUBMISSION
Share the github repositorty containing the solution to the Hackathon case study, the link will be shared before the end of the Hackathon.




