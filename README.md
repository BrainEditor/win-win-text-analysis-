# Parsing the Jargon of China's Newly Assertive Foreign Policy: "Win-Win" Text Analysis

Critical Chinese foreign policy documents often contrast China's search for "win-win" cooperation against Western state's "zero-sum" games.

The term win-win sounds good, but what does it **actually** mean in Party discourse?
Where does the Party pursue win-win cooperation, and what policy areas are most often framed as win-wins? 

## Motivation and Findings

While the term might seem like empty jargon, answering these questions gives us a better understanding of China's foreign policy under Xi. In particular, we can better understand Beijing's public diplomacy strategy abroad. 

Beijing's increasingly assertive foreign policy aims to develop comprhensive economic and security partnerships by pursuing "win-win" policies via the Belt and Road initiative. State media contrasts these relationships with alleged U.S. unilaterailsm to cultivate soft power, undercutting U.S. public dimploacy and image abroad. 

However, I find that Beijing is reticent to highlight security cooperation and primarily focuses on economic initatives in public-facing propoganda. Though China's partnerships may one day be truly comprehensive, for now its public diplmocay is focused on economic development, and state media downplays military activity abroad in the pages of the People's Daily. This is surprising, since top leaders and authoritative whitepapers have recently called for the PLA to provide public security goods and deepend military partnerships with other nations. However, Beijing may be wary of publicly promoting security-focused foreign policies, lest they appear too assertive and threatening abroad, which could jepordize positive perceptions of China as a helpful, developing peer. 


## Methods 
This combines qualitative research of authoritative policy documents and white papers with a text scraping analysis of People's Daily headlines to get a better sense of how, where, and when win-win rhetoric is used domestically to describe China's foreign policy. Using OriProbe's archive of every People's Daily article published in the last 70 years, I visualize usage of the term "win-win" in headlines over time. Then, leveraging the archive's article tag themes, I visualize which countries are most associated with "win-win" rhetoric, and what policy areas the term is most often applied to. 

This is my first text scraping project, and the code has room for improvement. Currently, the function takes two arguments - the first webpage from OriProbe being scrape, and the total number of pages to be scraped. It would be better, though, if the function itself scraped the final page number and used that to determine how many pages need to be scraped. I plan to continue working on this in the future as I continue to use this tool. 

## Supporting Documents: Research Paper and Policy Memo

In addition to the R code and knitted PDF, I've also included a long-form paper that contextualizes my findings and explores some of their implications in detail. In addition, there's a practice poliy memo written for an imagined State Department decision maker. This was an excercise in using research to make a data-driven policy recommendation, and doesn't neccessarily reflect my opinion of what the State Department should actually do.
