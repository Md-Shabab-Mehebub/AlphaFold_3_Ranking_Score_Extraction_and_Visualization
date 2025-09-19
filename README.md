# AlphaFold_3_Ranking_Score_Extraction_and_Visualization

This notebook is designed to extract and visualize ranking scores (0.8 × ipTM + 0.2 × pTM + 0.5 × disorder − 100 × has_clash) from AlphaFold 3 biomolecular structure prediction results. It processes batch JSON summary files from all subfolders in your specified Google Drive path, extracts the 'ranking_score', and saves the collected data into a CSV file. Finally, it generates a scatter plot to visualize the distribution of these ranking scores. The scatter plot is inspired by the paper of Homma et al. (2023). 

The entire notebook is written with the help of Google Gemini.

[Google Colab Link](https://colab.research.google.com/github/Md-Shabab-Mehebub/AlphaFold_3_Ranking_Score_Extraction_and_Visualization/blob/main/AlphaFold3_ranking_score.ipynb)
