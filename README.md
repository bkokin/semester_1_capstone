# AI CAPSTONE TEAM 4

### Navigating Repository:
* Exploratory work: contains exploratory data analysis from all members
* Images: visualization of graphs derived from the analysis
* Capstone 1: finalized notebook with the analysis
* README: includes project overview, analysis, and recommendations


## Project Overview

Computing Vision, endeavors to establish its presence in the realm of filmmaking. Tasked with guiding Computer Vision, our project aims to harness the power of exploratory data analysis and statistical methods to unravel the dynamics behind successful movies and translate these revelations into actionable insights.


### Business Understanding

Computing Vision recognizes the thriving landscape of original content creation and has set its sights on establishing a new movie studio. However, the organization's limited experience in the film industry necessitates an informed approach. To bolster their presence in the market successfully, thorough analysis of data is required. Our objective is to delve into diverse sets of available data to discern patterns, trends, and relationships. Subsequently, we will distill these findings into strategic directives, facilitating Computing Vision's decision-making process regarding optimal film types to pursue. 

#### Key Business Questions:
 1. What genre movies should be pursued to maximize return on production investment?
 2. What genre movies should be pursued to achieve the highest overall profitability?
 3. What is the ideal production budget to balance investment and revenue for the chosen genre? 


### Data Understanding and Analysis

#### Understanding sources of data
* [IMDB](https://www.imdb.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)
* PDF Link to PPT Here 

 1.Internet Movie Database (IMDB)
  -The IMDB houses an expansive repository of titles, encompassing films, TV series, video games, and streaming content. The SQL dataset encompasses facets ranging from directors and writers to ratings and movie specifics, including runtime and actors. 
  
 2.The Movie Database (TMDB)
  -The TMDB encapsulates an array of essentials such as the genres, titles, release dates, popularity indicies, vote counts and language.
  
 3.The Numbers Movie Budgets Database
  -The database introduces financial dimensions and essential information encompassing movie titles, release dates, production budgets, domestic gross, and worldwide gross. 
  
#### Data Analysis Process

 1. Collection: The process commences with the collection of diverse data sources including CSV files and SQL database.
 2. Cleaning: Eradicate inconsistencies, address missing values and ensures data uniformity.
 3. Processing: As we progress, we leverage Python's built-in functions and specialized packages to process the refined data.
 4. Analysis: Employing visualization packages such as Matplotlib and Seaborn, we craft vivid representations of our recommendations. 


#### Top Genres for Profit Over Production Budget (POPB)
![top_POPB](https://raw.githubusercontent.com/ml-disciple/semester_1_capstone/main/images/top_POPB.svg)

#### Production Budget by Genre
![median_POPB](https://raw.githubusercontent.com/ml-disciple/semester_1_capstone/main/images/PB_distribution.svg)

#### Top Combined Genres Profit 
![top_profitting_genre](https://github.com/ml-disciple/semester_1_capstone/blob/main/images/ProfitBillions.svg)


## Statistical Communication

1. Obtaining and analyzing correlation between worldwide profit and production budget
    * The correlation between worldwide profit and production budget yielded a result of 68%. This is considered a strong positive correlation indicating that as the production budget increases, so does the profit.
    
2. Obtaining and interpreting the confidence interval of the top genres 
    * A confidence interval for the production budget of top movie genres was computed with a confidence level of 95%. The confidence interval resulted in bounds of $149,880,980.81 and $168,523,019.19.
    
3. Interpretation of Confidence Interval
    * The confidence interval indicates that we can be 95% confident that the true mean of the top profiting movie genres is contained within the range of $149,880,980.81 and $168,523,019.19.

## Conclusion

**Our data-driven analysis has yielded three key recommendations that will steer Computer Vision's new movie studio toward successful and informed decision-making:**

1. Maximizing Return on Production:
  * Recommendation: Consider producing movies in the Horror & Thriller genres.
  * Rationale: These genres have yielded substantial returns on production investments.

2. Achieving Overall Best Profitability:
  * Recommendation: Prioritize the creation of movies in the Action & Adventure genres.
  * Rationale: Exhibits the potential to generate the highest overall profits.

3. Optimal Production Budget Strategy: 
  * Recommendation: Maintain production budgets within the range of $149,880,980.81 to $168,523,019.19. 
  * Rationale: The budget range balances investment in quality production with ensuring favorable returns. 


#### Summary

In summary, our endeavor has strategically positioned Computing Vision for a successful entry into the competitive film industry. We have unraveled key patterns and preferences that pave the way for informed decision-making. The culmination of our efforts is encapsulated in three actionable recommendations: focusing on Horror & Thriller genres to maximize returns on production investment, prioritizing Action & Adventure genres for overall best profitability, and adhering to a production budget range of $149,880,980.81 to $168,523,019.19. With these insights in hand, Computing Vision is well-prepared to embark on a successful journey and thrive in the market. 


#### Presentation Slide 
<object data="/Presentation.pdf" type="application/pdf" width="100%"> </object>






