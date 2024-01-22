# Maji-Ndogo-National-Water-Survey-Results
## Summary of Maji Ndogo National Water Survey Results:

## The Maji Ndogo National Water Survey was conducted to assess and analyze the water infrastructure, usage, and quality in the region. The survey aimed to provide valuable insights into water availability, consumption patterns, and the overall state of water resources in Maji Ndogo.

## Key Highlights:

## Water Infrastructure: The survey examined the existing water infrastructure, including distribution networks, sources, and storage facilities. It assessed the coverage and accessibility of water supply systems across different areas.

## Water Usage Patterns: Detailed analysis was conducted on water consumption patterns, considering factors such as residential, agricultural, and industrial usage. The survey aimed to understand the demand for water in various sectors.

## Quality Assessment: Water quality parameters were thoroughly evaluated, encompassing factors like chemical composition, contaminants, and bacteriological safety. The survey aimed to identify areas with potential water quality issues.

## Community Feedback: Stakeholder engagement and community feedback played a crucial role in the survey. Input from residents, local authorities, and water management organizations helped to gain a holistic perspective on water-related challenges and opportunities.

## Recommendations: Based on the survey results, recommendations were provided for improving water infrastructure, enhancing water quality, and implementing sustainable water management practices. These recommendations aimed to address current challenges and support the long-term development of Maji Ndogo's water resources.

## The Maji Ndogo National Water Survey Results serve as a foundation for informed decision-making, enabling authorities, policymakers, and water management agencies to implement targeted interventions and initiatives for sustainable water development and management in the region.
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


<img width="826" alt="Screenshot " src="https://github.com/Tomtwiny121/Maji-Ndogo-National-Water-Survey-Results/assets/128513453/f39d0bdf-c62b-4609-9407-970a508745e4">


