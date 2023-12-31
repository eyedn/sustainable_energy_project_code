# Topic Proposed
## Description
### What are you planning to do? What’s the problem you want to solve?

As the world leaves COVID-19 behind as an afterthought, a lingering crisis is, once again, brought to the forefront of global policy: the energy crisis. Worldwide, gas prices have skyrocketed due to international events such as the war in Ukraine and rising tensions in the Middle East, where countries source most of their oil. In the US alone, gas increased, on average, $1-$2, with highs of $7 in California. How can data science help alleviate these issues and combat the energy crisis? While data science does not explicitly create policy, data scientists guide policymakers in making decisions that will ease and possibly reverse the detrimental repercussions of overreliance on fossil fuels. As a group, we want to put ourselves in the roles of these data scientists and look at statistics and datasets on global energy use to see if we can make meaningful conclusions that could solve the relevant issues surrounding the energy crisis. For example, we can predict renewable energy usage or carbon emission by country to determine if those countries will meet quotas, or we can identify countries and regions with room for improvement or aid in their infrastructure to support transitions to renewable energy.

### What’s the dataset you want to use and how do you get this dataset?

The dataset that we want to use is “Global Data on Sustainable Energy (2000-2020)” and is found on Kaggle at: https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy/data 
This thorough dataset comprises 176 countries around the world and records energy-related statistics recorded over a 20 year period for each country. 

### Does it belong to supervised or unsupervised learning?

Supervised learning

### What are the features you plan to use, and what are the values to be predicted? (supervised case)

From a preliminary skim of the data, some of the values that we want to predict, or the outcomes and labels are: “Electricity from renewables”, “Value CO2 Emissions”, “Low-Carbon Electricity (% Electricity), and “Electricity from Fossil Fuels.” Some features that we plan to use are “Year”, “GDP Growth”, and “Primary Energy Consumption per Capita.”

## Motivation
#### Why do you believe this topic is worth trying? Is it an interesting topic to you? Or is it meaningful to society?

Sustainable energy is undeniably pivotal in today's global context. As the world grapples with the pressing challenges of climate change, dwindling non-renewable resources, and increasing energy demand, shifting towards sustainable energy solutions becomes paramount. Not only does it offer environmental benefits by reducing carbon footprints, but it also promises economic advantages and energy security. For society, embracing sustainable energy means safeguarding the planet for future generations, promoting technological advancements, and fostering a more resilient global community. Hence, the topic is both intriguing and of paramount significance.

### What other tools do you plan to use? (e.g. ChatGPT, GPT4) Why do you need them? How are those tools / libraries relevant to your project?

We plan to utilize ChatGPT as a knowledge resource, complementing platforms like Stack Overflow for coding assistance. ChatGPT's expansive knowledge base and conversational capabilities can offer real-time guidance, while Stack Overflow provides community-driven solutions to specific coding challenges. Together, they enhance the depth and breadth of support available for our project.

### What is the estimated amount of work you have in mind? (e.g. how to split work, and why you believe you and your teammates can handle the workload)

Because this is a comprehensive dataset rich with features and possibilities, each of our group members has decided that we will create and address individual problems, each with their own predictors and outcome labels, to solve. Thus, each group member will be responsible for going through the entire data science life cycle concerning their problem, making it a fair split as each person has a unique problem to work on, their features to preprocess, and their outcomes to visualize. The problems we will work on are:

1. What will be the % renewable energy in total energy consumption in 2025 for a majority of countries? Which countries will have the highest? Lowest?
- **File:** `renewable_energy_prediction.ipynb`

2. What factors relate to electricity usage determine a country’s CO2 Emissions?
- **File:** `CO2E_based_off_energy_consumption.ipynb`

3. What are the most import renewable energy related features in predicting economic output? How can we reduce economic uncertainty of renewable energy through modeling?
- **File:** `renewable_energy_economic_factors.ipynb`

4. How can we identify if a country is trending toward High CO2 emissions and what factors heavily influence this behavior?
- **File:** `CO2E_Classification_Regression.ipynb`
