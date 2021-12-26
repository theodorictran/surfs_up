# Surfs_Up Weather Analysis
## Overview
Interested in opening a surfing and ice cream shop in Oahu, Hawaii, W. Avy enlisted me to conduct some weather analyis to determine if the shop idea will be sustainable. Specifically, I was tasked to gather June and December temperatures. To do so, I used two SQL queries to gather temperature data filtered by months and created respective dataframes from the results. With the generated dataframes, I generated summary statistics to determine if the business will be sustainable all year-round.

## Results
Below is a summary of June's temperatures:

<img width="131" alt="june_summary" src="https://user-images.githubusercontent.com/91519293/147421848-eefe7d2d-7092-4479-959b-43c3edf9e71f.png">

Below is a summary of December's temperatures:

<img width="132" alt="dec_summary" src="https://user-images.githubusercontent.com/91519293/147421852-277e7d32-56a0-4b1b-96fd-96a76ed13a6f.png">

Key Takeaways:
- June's average temperature is about 75 degrees while December's average temperature is 71 degrees. Being similar, low-to-mid 70's is great weather for ice cream and surfing.
- June's max temperature is 85 degrees and December's max temperature is 83 degrees.
- June's minimum temperature is 64 degrees and Decembers's minimum temperature is 56 degrees.
## Summary
With the gathered results, based on temperature information, I believe that the surfing and ice creams shop would perform well year-round. Average temperatures and max temperatures for both June and Decemeber present great conditions for both surfing and ice cream. Observed lowest temperatures for June and December aren't too great for ice cream, but it is possible that the recorded lows are late in the night. This analysis only covered weather temperatures. To be more diligent, I suggest performing an additional analysis on June and Decemeber precipitation trends. I would modify my current queries to get precipitation data instead of temperatures, while maintaining the same filters for months of June and December. Having the same summary statistics for both temperatures and precipitation will provide a clearer picture to make a busines decision from.
