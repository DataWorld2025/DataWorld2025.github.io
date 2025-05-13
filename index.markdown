---
layout: page
title: "San Francisco Businesses over years"
description: "Exploring drug-related crimes using Bokeh, Matplotlib, and interactive maps."
---

<!-- Import Recoleta Font -->
<style>
    @import url('https://fonts.googleapis.com/css2?family=Recoleta:wght@400;700&display=swap');

    body {
        font-family: 'Recoleta', sans-serif;
        line-height: 1.7;
        color: #333;
        background-color: #fafafa;
        padding: 40px 20px;
        max-width: 800px;
        margin: auto;
    }

    h1, h2, h3 {
        font-weight: 700;
        color: #222;
        margin-bottom: 15px;
    }

    p {
        font-size: 17px;
        margin-bottom: 20px;
    }

    .code-block {
        background-color: #282c34;
        color: #fff;
        padding: 15px;
        border-radius: 6px;
        font-family: 'Courier New', monospace;
    }

    iframe {
        margin-top: 20px;
        border-radius: 10px;
        border: 1px solid #ddd;
        box-shadow: 3px 3px 12px rgba(0, 0, 0, 0.1);
        width: 100%;
        min-width: 700px; /* Ensures a minimum width of 700px */
        height: 700px; /* Adjust height as needed */
    }

    .highlight {
        background: #f4f4f4;
        padding: 15px;
        border-left: 5px solid #4682B4;
        border-radius: 5px;
        overflow-x: auto;
    }
</style>

---
<figure>
  <img src="{{ site.baseurl }}/assets/macy.png" alt="Businesses closures Over the Years">
  <figcaption>Macy's leaving San Francisco</figcaption>
</figure>

---
## **Business Development Over the Years**
**Over the past twenty years, San Francisco has been a thriving environment for both small and large businesses, driven by its diverse, affluent, and highly educated population. This demographic created a strong demand for unique, high-quality goods and services. The city boasted walkable neighborhoods, a vibrant tourism industry, and a supportive government. However, in recent years, a noticeable shift has occurred. Business closures are now outpacing new openings, and the number of active businesses has been steadily declining. At the same time, crime rates of vandalism and theft have risen to higher levels. Could this be a main factor contributing to the decline of businesses in San Francisco?**

To answer the above question, we will use San Francisco crime and economic data, focusing on the years from 2001 to the present for the economy, and the last 7 years for crime data. In the chart below, we can see that at the beginning in 2001, 40,000 companies were registered in the San Francisco area. Since then, the number of businesses has grown by approximately 5% per year. However, the chart also shows that starting in 2013, alongside new openings, the number of closures became more significant each year.

<figure>
    <img src="{{ site.baseurl }}/assets/AllOverYears.png" alt="Business Over the Years">
    <figcaption>Business numbers in San Francisco over the years</figcaption>
</figure>
---
In 2018, the number of closures hit a record high, with 15% of businesses shutting down. The following year continued this trend. Even with the impact of COVID-19 in 2020, the closure rate was not as high as in 2018. The period from 2013 to the present is particularly interesting to analyze due to the noticeable shifts in the data, so our analysis will focus on this timeframe.

<figure>
    <img src="{{ site.baseurl }}/assets/closure.png" alt="Business Over the Years">
    <figcaption>Percentage of closures out of all active businesses in given year</figcaption>
</figure>
---
The interactive map represents the number of closures in each of San Francisco's districts from 2013 to 2022. The darker the color, the higher the number of closures. One might falsely assume that businesses should thrive closer to the city center, but the map visualizes the opposite. The southern, central, and northern districts were among the three most affected. The visible markers represent fifty known brands that closed down during this period, which are only a small portion of the larger numbers. By hovering over a marker, viewers can see the brand name and the year it closed. This helps visualize that even well-known brands, with greater financial resources and top locations, chose to close their doors.

<figure>
    <iframe src="{{ site.baseurl }}/assets/intermaptest.html" width="50%" height="700px"></iframe>
    <figcaption>Interactive Map of closed businesses in San Francisco by district from 2018 to 2024.</figcaption>
</figure>
---
Since 2012, many major retailers like Macy's and Nordstrom have closed their downtown locations. In October 2023, Starbucks decided to close seven stores. When companies like that shut down multiple city center locations, it is often not simply due to underperformance, it may signal deeper structural issues.

<div style="display: flex; justify-content: space-between; gap: 20px;">
    <figure style="flex: 1; text-align: center;">
        <img src="{{ site.baseurl }}/assets/vice2.png" style="width:100%; height:auto;">
        <figcaption>Starbucks closing seven cafes in Downtown San Francisco</figcaption>
    </figure>
    <figure style="flex: 1; text-align: center;">
        <img src="{{ site.baseurl }}/assets/nord.png" style="width:100%; height:auto;">
        <figcaption>Nordstrom closing down in 2021 in San Francisco downtown</figcaption>
    </figure>
</div>
---
In recent years, a growing number of business owners in San Francisco have raised concerns about public safety, citing issues such as theft, vandalism, drug activity, and homelessness near their establishments. These concerns have become a key factor in decisions to reduce operations, relocate, or shut down entirely.

Retailers including Walgreens, Whole Foods, and Starbucks have referenced employee safety and deteriorating street conditions as part of the rationale behind closing downtown locations. Small business owners echo similar worries, reporting increased incidents that make it difficult to retain staff and attract customers.

The San Francisco Chamber of Commerce and other local business groups have urged city officials to address what they describe as a “crisis of confidence” in public safety, warning that without more visible enforcement and support services, the city’s commercial core could face long-term damage.

A 2022 survey by the San Francisco Office of Small Business found that 39% of businesses had experienced public safety concerns due to street behavior, 34% had experienced graffiti or vandalism, and 20% had experienced shoplifting or retail crime.

<figure>
    <img src="{{ site.baseurl }}/assets/lock2.png" style="width: 100%; height: auto;">
    <figcaption>Fridges locked because of high number of shoplifting incidents</figcaption>
</figure>


---

In San Francisco, there have been several instances where protests turned into vandalism and looting, including the George Floyd protests in May 2020 and the protests against the killing of Stephon Clark in March 2018. These events led to significant looting and vandalism, particularly in areas like Union Square, where retail stores were targeted. High-end stores, including those in luxury shopping districts, were looted, windows were smashed, and merchandise was stolen. The police were forced to use crowd control tactics, and several businesses reported major losses as a result.

<figure>
    <img src="{{ site.baseurl }}/assets/Valentino1.png" alt="Business Over the Years">
    <figcaption>Valentino covering windows to prevent break-ins during protests</figcaption>
</figure>

---
In November 2021, looting of the Louis Vuitton store in San Francisco's Union Square is widely considered an example of organized retail crime. The incident involved multiple suspects who coordinated to ransack the store, leading to significant property damage and theft of high-value merchandise. This event was part of a larger wave of coordinated thefts across the Bay Area, including similar incidents at Burberry, Bloomingdale’s, and other luxury retailers in Union Square.

<figure>
    <img src="{{ site.baseurl }}/assets/loot1.png" style="width: 100%; height: auto;">
    <figcaption>Looting at San Francisco Louis Vuitton store</figcaption>
</figure>

---
In the chart below, we can see the number of crimes related to business safety, such as vandalism, theft, robbery, and burglary, over a 9-year period in areas where the most closures occurred. These crimes appear to be correlated with the business closures, gradually increasing from 2013 and peaking in 2018. The most frequent crime is theft, which can seriously affect many businesses.

In 2014, Proposition 47 was established. This initiative lowered the threshold for felony theft, which previously included thefts over $400. After the passage of Proposition 47, shoplifting of items valued at $950 or less became a misdemeanor offense. This could have altered the perception of the risk of getting caught, potentially contributing to the high number of theft-related crimes.

<figure>
    <img src="{{ site.baseurl }}/assets/CrimesBusinesss.png" alt="Business Over the Years">
    <figcaption>Crime numbers which may affect businesses of Central, Southern, and Northern districts.</figcaption>
</figure>

---

Even thought the rise of crime correlates with closures in SF, data shows that many big retailers have been closing stores in major cities across the United States in recent years. This trend has been particularly noticeable in cities like  New York, and Chicago, among others. The closures of large retail chains in urban areas are often driven by a mix of factors, including the rise of e-commerce, changing consumer behaviors, rising operational costs, and in some cases, safety concerns[5].


---

##  **Conclusions**
This analysis highlights the correlation between the rise in crime and the closure of businesses in San Francisco. The data and the stories behind them strongly suggest that crime is a significant factor in the decline of businesses. Crime not only directly impacts businesses through the high costs of lost inventory or damaged property, but it also creates an atmosphere of fear that discourages potential customers. This, in turn, may lead individuals to choose safer areas to spend their time and money, further exacerbating the challenges faced by businesses in these affected areas. However, the closures of major retailers suggest that there may be other factors at play, warranting further investigation.


---

Sources:  
[1]Eater SF, 2023. Starbucks closing seven downtown San Francisco stores. Eater SF. Available at: https://sf.eater.com/2023/10/3/23902134/starbucks-closing-downtown-san-francisco [Accessed 13 May 2025].
[2] Castleman, T. (2023) 'Whole Foods closes San Francisco flagship store after a year, citing employee safety', Los Angeles Times, 11 April. Available at: https://www.latimes.com/california/story/2023-04-11/whole-foods-san-francisco-store-closes-employee-safety (Accessed: 13 May 2025).
[3] an Francisco Office of Small Business (2022) 2022 Small Business Survey on Economic Recovery. Available at: https://media.api.sf.gov/documents/2022_SBC_Small_Business_Survey_1.pdf (Accessed: 13 May 2025).
[4] California Secretary of State, 2014. Proposition 47: The Safe Neighborhoods and Schools Act. [online] Available at: https://www.sos.ca.gov/elections/ballot-measures/official-voter-information-guide/2014-general-election-propositions/proposition-47/ [Accessed 13 May 2025].
[5] https://massmarketretailers.com/store-closures-reach-highest-level-since-2020-2