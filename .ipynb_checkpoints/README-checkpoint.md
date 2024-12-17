# NeurIPS_Visualization
A small visualization project of fetching and visualizing NeurIPS submission from OpenReview. 
1. Fetch the all submitted notes from OpenReview API
2. Clean the data, e.g., `LLM` -> `large language model`. 
3. Visualize the trend of keywords change in Tableau.

## Tools
- openreview-py
- matplotlib
- Tableau extention, Bar Race by Inovista

## Visualization Result

![NeurIPS_Keywords_2024](result/NeurIPS_Keywords_2024.png)
![NeurIPS_Keywords_2024](result/NeurIPS_Keywords.gif)

## Reference

- [OpenReview API - How to Get All Submissions](https://docs.openreview.net/how-to-guides/data-retrieval-and-modification/how-to-get-all-submissions)
- [fedebotu - ICLR2023-OpenReviewData](https://github.com/fedebotu/ICLR2023-OpenReviewData/tree/main)
- [Inovista Bar Race Chart for Tableau](https://www.inovista.com/animatorFiles/demoProjects/BarRaceTableau.html)