# Dark Souls Data Analysis Project


<div align="center">
  <kbd>
    <img src="https://i.imgur.com/a2tOcTD.png" />
  </kbd>
</div>

## Description

This code above loads the Dark Souls armor stats data set  from [0xYUANTI's DarkTools Dataset](https://github.com/0xYUANTI/DarkTools/blob/master/doc/darksouls-armor-stats-0.csv) and builds a visualization analyzing the defense stats of each of the following armor types: 'physical', 'magic', 'fire', 'lightning', 'bleed', 'poison', 'curse'. The code then generates a box and whisker plot for the subset using matplotlib. The box and whisker plot visualizes the distribution of values for each column, showing the median, quartiles, and outliers for each distribution. 

### Insights

- From the plot, we can see that physical defense has the largest distribution, followed by magic and fire defenses. Poison and curse resistance have the smallest distributions, with most of the values being concentrated around the lower end of the displayed range. Overall, the box and whisker plot provides a clear visualization of the distribution of values for each column of interest in the Dark Souls armor stats data set.

### Built with

- Visual Studio Code
- Python
- Pandas
- matplotlib
- ChatGPT

### Acknowledgements

Thanks to Tangerine for the inspiration and 0xYUANTI for the dataset.

### License

This project is licensed under the [MIT License](LICENSE.md).
