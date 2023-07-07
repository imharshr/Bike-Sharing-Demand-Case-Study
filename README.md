# Bike Sharing Demand Case Study
> A bike-sharing system is a popular service that provides bikes for shared use on a short-term basis. Users can borrow bikes from designated docks, typically controlled by a computer system, and return them to any dock within the same network. These systems have gained traction as a convenient and eco-friendly transportation option.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Problem Statement

BoomBikes, a leading bike-sharing provider in the US, has experienced significant revenue declines during the ongoing COVID-19 pandemic. In order to sustain and accelerate their revenue once the lockdown measures are lifted and the economy rebounds, BoomBikes aims to develop a comprehensive understanding of the future demand for shared bikes. This understanding will enable them to effectively cater to customers' needs, differentiate themselves from competitors, and generate substantial profits.

To achieve this, BoomBikes has engaged a consulting company to identify the key factors that influence the demand for shared bikes in the American market. They seek answers to two critical questions: which variables are significant in predicting bike demand, and how well these variables describe the fluctuations in demand. To gather insights, BoomBikes has collected a large dataset on daily bike demands across the American market, incorporating factors such as meteorological surveys and people's preferences.

By addressing these questions and analyzing the dataset, BoomBikes aims to enhance their strategic decision-making, optimize their operations, and position themselves as a market leader in the post-quarantine period.

### Business Objective

The objective is to develop a demand model for shared bikes, utilizing the available independent variables. This model will enable the management to gain insights into the variations in demand based on different features. By understanding these demand patterns, the management can strategically adjust the business strategy to align with demand levels and exceed customer expectations. Additionally, the model will provide valuable insights into the demand dynamics of new markets, allowing the management to make informed decisions and effectively penetrate these markets. Ultimately, this objective aims to optimize operations, enhance customer satisfaction, and drive business growth.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### Equation of our best fitted line is:

 $Count = 0.59  \times  const + 0.25  \times  yr + -0.19  \times  windspeed + -0.26  \times  season\_spring + -0.04  \times  season\_summer + -0.11  \times  season\_winter + -0.1  \times  mnth\_Jan + -0.01  \times  mnth\_Jul + 0.1  \times  mnth\_Oct + 0.08  \times  mnth\_Sep + 0.01  \times  weekday\_Saturday + -0.05  \times  weekday\_Sunday + -0.32  \times  weathersit\_light\_rain\_snow + -0.09  \times  weathersit\_misty$

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- matplotlib, sns
- sklearn
- statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->