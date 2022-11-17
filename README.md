## Heatmap : Behavior x CFOS Density

PTSD laboratory study analysis using fake data.

This project was completed to give an example of the type of work conducted in the lab. 

1. Objective (Act Phase) 

To visualize the extent to which behavior and brain region are related through the use of a heatmap containing the correlation between behavioral and brain region cfos density data.

2. Prepare Phase

Behavior data and brain cfos density data is usually imported from the shared drive on the vpn. Located here: 

Fake data was created for this project. This data is mirrors the columns and ranges of the original data.

Behavior data contains three behavioral test observations: Acoustic startle response, open field maze, and elevated plus maze. Cfos density is separated by brain region: PFC, hippocampus, thalamus, dorsal raphae.

3. Process Phase

Inspect each attribute for anomalies. 

4. Analyze Phase

Calculate z-scores for behavior and brain region density were collected.

Use z-scores to calculate pearson correlation r, p-value, and n. Pare down the values to only the comparisons we need. 

5. Share Phase

Melt the r and p-values into columns. Add a column for p-value significance stars. Save data frame (results table).

Use ggplot2 to plot heat map with significance stars and pearson r correlation color label. Save plot (heatmap). 

6. Act Phase

For all significant behavioral effects, add an additional plot to visualize group differences.

For all significant brain regions, recommend investigating mechanism behind density shift. Try to translate toward behavioral effects.



