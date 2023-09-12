# Telling Stories with Data Portfolio - Clarissa Clifton
This is a repository to store and showcase work done during my Telling Stories with Data class at CMU

Link to live site --> https://cjclifto.github.io/tswd_portfolio/

## Who is Clarissa?
My name is Clarissa (she/her). I am a Dual MS student at Carnegie Mellon studying Biomedical Engineering and Engineering & Technology Innovation Management. I am passionate about designing diagnostics devices, particularly for applications in rural areas or areas of the world without easy access to medical clinics. Outside of my career path, I love doing art - I always have my hands in some sort of creative project! 

## What I hope to learn from Telling Stories with Data
I already have a serious interest in data visualization prior to this class. Data viz scratches the itch in my brain where my engineering and arty sides meet. During this semester, I'm hoping to gain some formal techniques for data visualizaton and proper frameworks for making good design decisions. I have an adjacent love for technical writing, which I feel is closely related to data visualization. In technical writing, the key is to communicate technical information at a high acuity to the layperson. To me, data visualization accomplishes a very similar task! Any information I have is useless if I can't effectively communicate it my audience. I'm hoping to learn best practices for this effective communication!

Once I graduate, I plan to work in the startup world on disease diagnostics platforms. I'm extremely passionate about this field, and I love startup environments for the interdisciplinary nature of their work, mass amounts of opportunity to creatively problem solve, and the challenge of bringing a new technology to the communities it can have the most positive impact on.

## Portfolio
### Visualizing Government Debt
The visualization below is from the Organisation for Economic Co-operation and Development (OECD) from the [General Government Debt page](https://data.oecd.org/gga/general-government-debt.htm). This visualization shows data from 2017, with the lowest and highest debt-to-GDP ratios highlighted (Estonia and Japan, respectively). The United States is also highlighted to give an easy context clue for American audiences. 

<iframe src="https://data.oecd.org/chart/7biI" width="750" height="563" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7biI" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2017</a></iframe>

The following visualization shows many countries' debt-to-GDP ratios from 1995-2021. Many countries have experienced a consistent rise in government debt since the mid-1990s, with a spike during 2020 - or, the onset of the COVID-19 pandemic. However, all countries besides Latvia, Brazil, and New Zealand show a decrease from this spike post-pandemic.

<div class="flourish-embed flourish-chart" data-src="visualisation/14987756"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

This final visualization shows government debt in 2017 on a world map. I chose to limit my data set to one year to play with the map visualization - I believed it would be a bit overwhelming for a viewer to be met with an automatic animation of government debt across a world map over ~30 years, so I limited the data set to government debt-to-GDP ratios in 2017 alone, matching the first OECD chart shown previously. 

I chose to represent the data in a map because the data is debt comparisons across geographic locations - a map seemed intuitive for this. I chose to scale the interactive countries in red, with deeper red indicating a higher debt-to-GDP ratio. I decided to use this color scheme to capitalize on red's conventional association with "bad" or "danger" (this is, assuming my audience also agrees that a higher debt-to-GDP ratio is bad). For clarity, I chose to not have static data call-outs, as I felt this would be distracting for the audience. I thought it would be distracting for an audience to subconsciously be attempting to imagine the borders of countries with missing data, so I also chose to fill in countries missing from the data set with gray to "fill out" the map and ease the subconscious strain on the audience. To polish the message of my visualization, I summarized the key takeway in the title/subtitle: Japan is indicated to have the highest government debt of all countries shown. 

<div class="flourish-embed flourish-map" data-src="visualisation/14988072"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

***
_Thank you for taking the time to check out my work!_
