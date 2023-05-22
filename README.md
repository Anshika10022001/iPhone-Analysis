<img align="center" alt="Coding" width="1000" height="300"
src="https://www.digitaltrends.com/wp-content/uploads/2022/09/iphone-14-pro.jpeg?resize=1502%2C845&p=1">

# iPhone Analysis
## Project Description
A Web Scrapping and Power BI Project of iPhone Data which depicts all of the iPhone information in a dashboard form.

## Outline of Problem
To empower consumers to make more informed decisions about which iPhone model to purchase based on their individual needs and preferences, a solution has 
to be provided to give detailed insights into the prices, features, and user ratings of various iPhone models.

## Analysis Framework
- Scraped data from Flipkart: The project involved using the Beautiful Soup library in Python to extract data on various iPhone models available on the e-commerce platform Flipkart.
- Data rectification and assessment: Once the data was scraped, it was rectified and assessed in Power BI(Power Query) to ensure its accuracy and consistency. This involved removing duplicates, columns rectification, removing noise values, fixing errors, and verifying the information against other sources.
- Dataset Before: The dataset has several columns with combined values in a single column. For example, the "product name" column includes the product name, RAM and the color name within parentheses. Similarly, the "description" column contains lengthy text that includes information about ROM, display, camera, and other specifications. Additionally, the "ratings" column combines ratings and reviews. Furthermore, many columns have incorrect data types assigned to them.

![PART9](https://github.com/Anshika10022001/iPhone-Analysis/assets/128470731/60607ace-0b2e-43b5-aca3-141e70e13ef2)

- Dataset After: The changes were made and the columns were made suitable for analysis as shown below

![PART10](https://github.com/Anshika10022001/iPhone-Analysis/assets/128470731/35cf0171-290c-488c-8f84-e5631e0856e1)

- Dashboard creation: The final output of the project was a dashboard that presented the data in an easily digestible format. The dashboard provided insights on the price and features of different iPhone models, as well as user ratings and reviews.
- Price analysis: The dashboard allowed for a comprehensive analysis of the prices of various iPhone models available on Flipkart. This included a comparison of prices across different models and variants, as well as a historical price analysis to identify trends and patterns.

![prices prod](https://github.com/Anshika10022001/iPhone-Analysis/assets/128470731/49499f07-4e6f-4b28-be1b-40cfc2c25a47)

- Number of colours available: The following visual would help the customers too see the variety of colours available for thr top iPhone models.

![colours var](https://github.com/Anshika10022001/iPhone-Analysis/assets/128470731/f7f8fede-ceb1-4b5c-9923-c63b2806ef11)

- User rating and review analysis: In addition to price and feature analysis, the dashboard also included insights on user ratings and reviews of different iPhone models. This provided valuable feedback from other customers and helped users make a more informed purchasing decision.

![Ratings prod](https://github.com/Anshika10022001/iPhone-Analysis/assets/128470731/090dd7ec-f133-42cf-8008-82ce0b60eea5)

- Feature analysis: The dashboard also provided insights on the features of different iPhone models, including details such as camera specifications, display quality, and storage capacity. This allowed users to compare different models and make an informed purchasing decision.
- Slicers: Added interactive slicers for front camera, RAM and rear camera so that users can easily filter out the dispalyed data on the dashboard according to their preferences.
- Data visualization: To make the dashboard more visually appealing and easier to understand, the data was presented in various charts, graphs, and tables. This included price trends over time, feature comparisons, and user ratings and reviews.

![iPhone Dashboard](https://user-images.githubusercontent.com/128470731/235846722-f0afb980-1a93-4c3c-bbd2-a20b603bc248.png)

## Lessons Learned

- Always plan ahead: Planning ahead and creating a roadmap of the different activities that need to be completed can help keep the project on track and ensure that all the necessary steps are completed in a timely and efficient manner.

- Data cleaning is essential: Cleaning and preparing the data for analysis is a critical step in any data project, as it ensures that the insights are based on accurate and reliable data.

- The importance of visualization: Creating visualizations of the data can help communicate insights to stakeholders and make them more engaging and understandable.

- The power of automation: Using tools and scripts to automate repetitive or time-consuming tasks can save a significant amount of time and effort, allowing more focus on the actual analysis and insights.

- Continuous learning: Technology and tools are constantly evolving, and keeping up to date with the latest developments can help improve the efficiency and effectiveness of future projects.

## Tech Stack

**Python:** Beautiful Soup Library, Web Scrapping Tecniques, DataFrames

**Microsoft PowerBI:** Data Cleaning, Power Query, Dashboarding, Visualizations

## Limitations/Challenges
- While the project overall was relatively straightforward, I did encounter a notable challenge during the process. 
- Specifically, I had limited knowledge and experience with web scraping techniques using Beautiful Soup.
- As a result, I had to invest a considerable amount of time into learning how to effectively extract data from websites. 
- I dedicated several hours to watching tutorials on platforms like YouTube in order to grasp the necessary concepts and acquire the skills needed for successful web scraping. 
- Despite the initial hurdle, this experience proved to be a valuable learning opportunity, enabling me to acquire a new skill set that greatly contributed to the project's success.

## Future Scope
- Empowering consumers: By providing detailed insights into the prices, features, and user ratings of various iPhone models, this project can empower consumers to make more informed decisions about which model to purchase based on their individual needs and preferences.
- Saving time and money: With so many iPhone models and variants available on the market, it can be overwhelming for consumers to choose the right one. This project can help users save time and money by presenting the information in a clear and concise format, making it easier for them to compare and select the best option for their budget and requirements.
- Staying up-to-date: This project can also help users stay up-to-date with the latest iPhone models and features, ensuring that they are aware of all the options available to them. This can be particularly useful for those who are looking to upgrade their current device or switch to an iPhone for the first time.
- Making educated purchasing decisions: By providing comprehensive insights into the prices, features, and user ratings of various iPhone models, this project can help users make educated purchasing decisions that they can feel confident about. This can help them avoid buyer's remorse or regret over choosing a model that doesn't meet their needs.

