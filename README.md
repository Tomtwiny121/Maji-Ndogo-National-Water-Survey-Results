# Maji-Ndogo-National-Water-Survey-Results
## For each of these user stories, we have to think about what data the user will need to answer that question.
So let's apply the what.
1. I want to see the key points of the survey results so I understand the overall status of water access in Maji Ndogo.
• We should summarise population-related access to water on a national and provincial level.
• A lot of people in Maji Ndogo live in rural and urban areas, so we should summarise their results and the challenges they face separately.
2. I want to know how many people are affected by water access challenges in Maji Ndogo and what those challenges are.
• We need to communicate the number of sources, and also the amount of people affected by these sources.
• Perhaps we should also consider making the less important sources like tap_in_homes less visible since we're not upgrading those.
3. I want to know how much money we will need to complete the upgrades, and where that money needs to be spent.
• This one will need a bit of work from us. There is some financial data in our data model called infrastructure_cost, but we will need
to do some calculations to include this type of data.
• Pres. Naledi will need to see this data at a national, provincial, and rural/urban level, and even per improvement type.
4. I want to understand this data on a national level and a provincial level.
• We have to take this into account, as well as at a rural/urban split.
Then how will we visualise that data? We may change this as we go, but let's start with a set of visualisations, and we'll add more, or remove some
as we go along:
1. I want to see the key points of the survey results so I understand the overall status of water access in Maji Ndogo.
• We can split the page into rural vs. urban, and then show the population of Maji Ndogo, and highlight key metrics.
2. I want to know how many people are affected by water access challenges in Maji Ndogo and what those challenges are.
• Here we show the distribution of source types in rural vs. urban populations
• A sorted visual of the number of source types.
3. I want to know how much money we will need to complete the upgrades, and where that money needs to be spent.
• We need to show a single number representing the data nationally, and per province.
• We should also break down costs in various ways:
– per province
– rural/urban
– source type
4. I want to understand this data on a national level and a provincial level.
• If we build the report well, we can drill down into different categories.

After all the above questions have been answered, 
We will need to show the following data:
1. Total people served for each water source type in a province.
2. Number of water sources, their type, and whether it is rural or urban.
3. Show the relevant stats for towns in that province.
4. Add relevant provincial data. Queues, gender compositions and crime, broken taps by town, etc., in provinces where it is relevant.
5. Summary of improvements and costs.

<img width="805" alt="Screenshot 2024-01-22 042738" src="https://github.com/Tomtwiny121/Maji-Ndogo-National-Water-Survey-Results/assets/128513453/558f3a3d-9a6d-4b78-84d1-7a751dcdda21">


